---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

# Yucheng Zhang

**Email:** [yz90@illinois.edu](mailto:yz90@illinois.edu)<br>
[Download CV (PDF)]({{ '/files/CV.pdf' | relative_url }})

## Research Interests

Humanoid loco-manipulation and human motion, at the intersection of computer vision and robotics.

## Education

### University of Illinois Urbana-Champaign

Urbana, IL, USA<br>
**Master of Science in Computer Science** (expected July 2027)<br>
*Sep. 2025 – Present*

### University of Illinois Urbana-Champaign

Urbana, IL, USA<br>
**Bachelor of Science in Computer Engineering**<br>
*Sep. 2021 – Jun. 2025*

- **GPA:** 3.97/4.0

### Zhejiang University – University of Illinois Urbana-Champaign Institute

Zhejiang, China<br>
**Bachelor of Engineering in Electrical and Computer Engineering**<br>
*Sep. 2021 – Jun. 2025*

- **GPA:** 3.78/4.0

## Publications

<sup>†</sup> Equal contribution.

- **Yucheng Zhang**<sup>†</sup>, Sirui Xu<sup>†</sup>, Jinhong Li<sup>†</sup>, Liuyu Bian<sup>†</sup>, et al. [“InterMimicGen: Scaling Humanoid Loco-Manipulation Through Self-Evolving Motion Imitation”](https://arxiv.org/abs/2610.06850). Under review at ICLR 2027.
- Zimu Zhang<sup>†</sup>, **Yucheng Zhang**<sup>†</sup>, et al. [“HandX: Scaling Bimanual Motion and Interaction Generation”]({{ '/files/HandX.pdf' | relative_url }}). CVPR 2026.
- Sirui Xu<sup>†</sup>, Dongting Li<sup>†</sup>, **Yucheng Zhang**<sup>†</sup>, et al. [“InterAct: Advancing Large-Scale Versatile 3D Human-Object Interaction Generation”]({{ '/files/InterAct.pdf' | relative_url }}). CVPR 2025.
- Enxin Song<sup>†</sup>, Wenhao Chai<sup>†</sup>, Guanhong Wang<sup>†</sup>, **Yucheng Zhang**, et al. [“MovieChat: From Dense Token to Sparse Memory for Long Video Understanding”]({{ '/files/moviechat.pdf' | relative_url }}). CVPR 2024.

## Research Experience

### Scalable Humanoid Loco-Manipulation via Self-Evolving Motion Imitation

**Research Assistant, UIUC** | *Feb. 2026 – Present*<br>
**Advisor:** [Prof. Yu-Xiong Wang](https://yxw.web.illinois.edu/)

- Proposed InterMimicGen, a framework that scales sparse human-object motion capture into large-scale, physically executable references for dexterous humanoid loco-manipulation.
- Built an interaction-preserving retargeting pipeline that maps human-object motion to different embodiments while preserving body-object spatial relations and finger contacts.
- Worked on reinforcement learning for motion tracking and a self-evolving loop that jointly improves the motion set and policy.
- Resulting paper under review at ICLR 2027.

### Bimanual Motion and Interaction Generation

**Research Assistant, UIUC** | *Apr. 2025 – Jan. 2026*<br>
**Advisor:** [Prof. Yu-Xiong Wang](https://yxw.web.illinois.edu/)

- Proposed a unified foundation spanning data, annotation, and evaluation for bimanual hand motion.
- Organized datasets into a unified format for the annotation pipeline.
- Designed a diffusion-based generation model and a unified evaluation pipeline supporting diffusion and autoregressive models.
- Developed data conversion and interface pipelines to integrate the dataset with physics simulators.
- Resulting paper, HandX, accepted at CVPR 2026.

### Human-Object Interaction with SMPL Models

**Research Assistant, UIUC** | *Feb. 2024 – Nov. 2024*<br>
**Advisor:** [Prof. Yu-Xiong Wang](https://yxw.web.illinois.edu/)

- Proposed a method for representing human poses with a small number of markers.
- Built a data collection website on Amazon Mechanical Turk to create a dataset with 22.94 hours of human-object interaction data and detailed annotations.
- Segmented videos based on motion changes measured with Posecode, and implemented GPT-based annotation and augmentation.
- Performed penetration evaluation and motion prediction on the dataset.
- Resulting paper, InterAct, accepted at CVPR 2025.

### Long Video Understanding

**Team Leader, ZJU-UIUC Institute** | *Jul. 2023 – Dec. 2023*<br>
**Advisor:** [Prof. Gaoang Wang](https://cvnext.github.io/)

- Developed a memory management method for long video understanding with high computational and memory costs.
- Reduced memory costs by maintaining short-term memory and selectively storing long-term memory based on frame similarity.
- Built a dataset of 1,000 long videos with manually annotated summaries and question-answer pairs.
- Resulting paper, MovieChat, accepted at CVPR 2024.

## Awards and Honors

- **Gold Medal**, 46th ICPC Asia Regional Contest, Jinan Site (top 10%), 2021
- **Silver Medal**, China Collegiate Programming Contest, Weihai Site, 2021
- **Dean’s List (ZJUI)**, 2021–2022
- **Dean’s List (UIUC)**, 2023–2024

## Teaching Experience

### CS 446 / ECE 449: Machine Learning

**Teaching Assistant, UIUC** | *Fall 2026*

- Design homework assignments and exams.
- Hold weekly office hours and answer student questions on the course forum.

### CS 101: Introduction to Computing for Engineering and Science

**Teaching Assistant, UIUC** | *Fall 2025 & Spring 2026*

- Led three weekly lab sections, office hours, and review sessions.
- Reviewed quizzes, labs, and homework for quality assurance.

### MATH 285: Differential Equations

**Teaching Assistant, ZJUI** | *Spring 2025*

- Led weekly discussion sections, office hours, and review sessions.
- Graded homework and exams.

### MATH 241: Calculus III

**Teaching Assistant, ZJUI** | *Fall 2024*

- Led weekly discussion sections, office hours, and review sessions.
- Graded homework and exams.

## Industry Experience

### Apple

**Advanced Manufacturing Engineering Intern** | *Summer 2025*

- Initiated a project involving large language models.

## Projects

### Smart Cane — Senior Design

- Developed the computer vision component using YOLO for object and person detection, regression for distance and angle estimation, and traffic light color recognition.
- Implemented GPS-based navigation.
- Wrote the system in Python, with the YOLO component in C.

### Simplified Computer System

- Built a computer system in C and assembly supporting parallel program execution, instruction input and storage, and program calls.
- Implemented drivers, a real-time clock, system calls, a file system, scheduling, memory mapping, and signals.

### Traffic Light Simulation Control System

- Used YOLO to detect vehicles at intersections and adapt traffic light duration based on vehicle presence and accumulated waiting time.
- Built a server to run YOLO and traffic light control logic on FPGA, with LED indicators to visualize results.

## Skills and Tools

- **Programming:** MATLAB, C/C++, Python, SageMath
- **Frameworks and Tools:** Pandas, PyTorch, smplx, Keras, NumPy, SciPy, tqdm
