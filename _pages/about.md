---
permalink: /
title: "Jisong Yu - 俞锦松"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<!-- 仅当前页面生效的字体缩小样式 -->
<style>
/* 定位页面内容区域，避免影响侧边栏等其他模块 */
.page__content {
  font-size: 14px; /* 正文基础字体（默认通常16px，缩小2px） */
  line-height: 1.6; /* 保持行高，避免字体缩小后拥挤 */
}

/* 缩小各级标题字体（按比例调整，保持层级感） */
.page__content h1 { /* 页面大标题（如姓名） */
  font-size: 2em; /* 默认约2.4em，缩小后更协调 */
}
.page__content h2 { /* 模块标题（如Research Interests） */
  font-size: 1.5em; /* 默认约1.9em，适配正文大小 */
}
.page__content h3 { /* 子模块标题（如Project Experience） */
  font-size: 1.2em; /* 默认约1.5em，避免过粗过大 */
}
.page__content h4 { /* 项目标题（如1. Underwater Inspection Robot） */
  font-size: 1.1em; /* 默认约1.2em，突出项目但不突兀 */
}

/* 确保列表文字与正文一致 */
.page__content ul, 
.page__content ol {
  font-size: 14px;
}
</style>

I am a current master’s student in Control Engineering at Tianjin University, with a core research focus on the field of robotics and artificial intelligence.

I am pursuing my master’s degree under the supervision of Prof. Bailin Tian, and I belong to the TJU-AIR-LAB, which is part of the School of Electrical Engineering and Automation at Tianjin University. My research centers on the fundamental theories and engineering applications of robotic systems. Through close collaboration with academic mentors and industrial partners, I explore practical pathways for technology implementation. Key experiences include: participating in the core research on end-to-end trajectory planning for UAVs and exploring the integration of VLA technology with UAV trajectory planning; joining the Shanghai Abyss Science and Technology Center during my undergraduate studies, where I conducted research on underwater robot structural design and inspection algorithms under the guidance of Prof. Zhe Jiang and Mr. Gaosheng Luo; advancing research related to USV trajectory planning and underwater target recognition with Prof. Bowen Xing; founding the university’s robotic competition team, independently developing a quadruped robot, and winning a national-level award in the ROBOCON Competition; participating in the structural R&D of nursing robots at Shanghai Deyin Technology Co., Ltd.; overseeing the R&D project management of wheeled humanoid robots at Shanghai Zhiyuan Xinchuang Technology; and serving as a co-founder of the team in the Entrepreneurship Summer Camp at the Shenzhen Institute of Advanced Technology (guided by Prof. Zexiang Li), where I completed the end-to-end process of an underwater robot—from user market research to prototype development.

---

### Research Interests

My research focuses on developing next-generation robotic systems capable of operating efficiently and adapting to diverse tasks in complex real-world environments. It centers on the deep integration of robotics and artificial intelligence, exploring practical pathways from theoretical algorithms to engineering implementation.

In previous research, I have explored various topics in robotics and AI, including robotic trajectory planning, structural design of underwater robots, development of inspection algorithms, and target recognition for unmanned surface vehicles (USVs). I have also gained hands-on experience with a range of robotic platforms, including unmanned aerial vehicles (UAVs), underwater robots, quadruped robots, nursing robots, and wheeled humanoid robots. My past research focused on "adaptability of robots to complex tasks," such as improving the trajectory accuracy of unmanned systems through algorithm optimization and enhancing the environmental adaptability of robots through structural design.

Currently, my research focuses on technological breakthroughs in end-to-end trajectory planning for UAVs, with a particular emphasis on the transformation and application of robotic systems in scientific research and industrial scenarios. Specific research interests include:

- Optimization of end-to-end trajectory planning algorithms for UAVs
- Integration of VLA technology with robotic trajectory planning
- Task allocation and communication for multi-UAV systems
- Design and control of underwater/ground unmanned robotic systems

---

### Project Experience

#### **1. Underwater Inspection Robot: R&D of Magnetic Adsorption & Panoramic Vision System**

**Collaborative Institution**: Shanghai Abyssal Science and Technology Center | **Time**: Dec 2023 – Dec 2024  
To address the pain points of underwater inspection for metal structures—robots being easily dislodged by water currents and blurred vision in turbid environments—I led core R&D work: designing the layout of magnetic adsorption units to improve attachment stability, developing a 360° panoramic image stitching algorithm to optimize visual perception, and integrating the vision and hardware systems under the ROS framework to support field testing of the robot prototype and the implementation of inspection tasks.

**Achievements**: Patent: CN222728123U

#### **2. Underwater Robot Multi-Sensor Fusion Perception for Low-Light/Turbid Waters**

**Collaborative Institution**: Shanghai Ocean University (Advisor: Prof. Bowen Xing) | **Time**: Oct 2023 – Mar 2024  
To solve the problems of optical camera failure and insufficient recognition accuracy of single sonar in low-light/turbid waters during marine observation, I proposed an acoustic-optical fusion perception framework. By combining optical images with P360 sonar data (2° horizontal beamwidth), I realized accurate target recognition and size measurement through algorithm alignment, enhancing the robot’s perception capability in complex waters.

**Achievements**: Patent: CN202311353714

#### **3. Quadruped Robot R&D & Competition: Building a Team from Scratch to Win National Award**

**Role**: Founder/Captain | **Institution**: Shanghai Ocean University Robotics Team | **Time**: Oct 2023 – Jul 2024  
To overcome the challenges of stable locomotion and environmental navigation of quadruped robots on complex terrain, I led the establishment of a 12-member team and directed core R&D: developing a ROS-based trot gait control framework to optimize motion stability, building a visual navigation system integrating YOLOv8-seg segmentation, stereo vision, and ORB-SLAM3, while coordinating the entire process of team R&D, debugging, and competition preparation.

**Achievements**: Github：xxx | Award: National Third Place in National University Robot Competition (ROBOCON)

<!-- 
This is the front page of a website that is powered by the [Academic Pages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the repository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. Incidentally, these same features make it a great template for anyone that needs to show off a professional template!

 You can fork [this template](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and Markdown files, add your own PDFs and other content, and have your own site for free, with no ads!

A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured Markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various Markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your Markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the Markdown files! You can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

For those users that need more advanced functionality, the template also supports the following popular tools:
- [MathJax](https://www.mathjax.org/) for mathematical equations
- [Mermaid](https://mermaid.js.org/) for diagraming
- [Plotly](https://plotly.com/javascript/) for plotting

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](https://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
注释内容 -->

