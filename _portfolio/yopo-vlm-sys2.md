---
title: "yopo-vlm-sys2: VLM Semantic Safety Layer for Off-Road Navigation"
excerpt: "An open-source System-2 that lets a depth-only off-road planner avoid semantic hazards (water / mud / sand) via VLM-based trajectory veto. <br/> [Main repo](https://github.com/PerryNotFound/yopo-vlm-sys2)"
collection: portfolio
---

A System-2 semantic safety layer for the YOPO-Rally off-road planner. YOPO plans
from depth images at 10 Hz but cannot see *semantic* hazards — water, mud, sand.
This project adds low-frequency scene understanding with **Qwen3-VL-4B** and injects
it into the planner via **semantic veto on trajectory candidates**: hazard zones
reported by the VLM are projected onto candidate trajectories (cost → +inf), while
geometric obstacles remain handled by YOPO's learned depth cost.

Key properties:

- Fully asynchronous — never blocks the 10 Hz planner / 20 Hz MPC
- 2 s soft-timeout fallback to pure YOPO; failed VLM inferences are skipped silently
- Motor-level active recovery when all candidates are vetoed
- Validated in closed loop in a Unity simulator with randomized puddles

Repositories:

- [yopo-vlm-sys2](https://github.com/PerryNotFound/yopo-vlm-sys2) — VLM semantic layer (main repo)
- [YOPO-Rally-vlm](https://github.com/PerryNotFound/YOPO-Rally-vlm) — planner/MPC fork with the veto interface
- [YOPO-Sim-Project-vlm](https://github.com/PerryNotFound/YOPO-Sim-Project-vlm) — Unity simulator fork
