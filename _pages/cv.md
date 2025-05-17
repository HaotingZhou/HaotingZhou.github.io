---
layout: archive
#title: ""
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

# [Renyuan Liu](https://ryannnice.github.io)
+86 14784206312 | rliu@e.gzhu.edu.cn  

---
## Education

- **[Guangzhou University](https://english.gzhu.edu.cn/)**
  B.Eng. in Computer Science (Information Security); **GPA: 90.13/100.00; Ranking: Top 10%**  
  Sept. 2022 - Jun. 2026 (Expected)  
  **Curriculum:** Machine Learning 100\*, Data Structure and Algorithm Laboratory 99\*, Operating System 98\* (Course Project 95\*), Programming Practice 98\*, Data Structure and Algorithm 97\*, Programming Laboratory I 95\*, Computer Network (Course Project 95\*), Principles of Computer Composition, Higher Mathematics, Discrete Mathematics, Linear Algebra, Probability and Mathematical Statistics (\*: rank 1st in all students of the course).

- **[The University of Hong Kong](https://www.hku.hk/)/[University of Macau](https://www.um.edu.mo/)** (Summer Camp)  
  Nov. 2023  
  **GPA: 97.50/100.00** (Interdisciplinary Programme)  
  **Honor:** Commendation Letter for Outstanding Performance in the Winning Team

---

## Publications

- **R. Liu** and Q. Fu, [Attention-Driven LPLC2 Neural Ensemble Model for Multi-Target Looming Detection and Localization](https://arxiv.org/abs/2504.04477). *Accepted at International Joint Conference on Neural Networks (IJCNN 2025, acceptance rate ≈ 38%)*.

- G. Gao, **R. Liu**, M. Wang and Q. Fu, [A Computationally Efficient Neuronal Model for Collision Detection With Contrast Polarity-Specific Feed-Forward Inhibition](https://www.mdpi.com/2313-7673/9/11/650). *Biomimetics, vol. 9, no. 11, p. 650, 2024.*

- J. Huang, Z. Qin, M. Wang, **R Liu**, and Q. Fu, [A biohybrid collision-detection visual neural model coordinating self-and-lateral inhibitions](https://ryannnice.github.io//assets/A%20biohybrid%20collision-detection%20visual%20neural%20model%20coordinating%20self-and-lateral%20inhibitions.pdf). Accepted at *The 14th International Conference on Biomimetic and Biohybrid Systems (Living Machines 2025)*.

---

## Honors and Awards

- **Honorable Mention**, Mathematical Contest in Modeling (MCM)  
  Jan. 2025

- **National First Prize (Top 5%)**, Asia and Pacific Mathematical Contest in Modeling (APMCM)  
  Nov. 2024

- **Provincial First Prize & Innovation Silver Award (Top 2 out of 1,167 Teams)**, "Greater Bay Area Cup" Guangdong-Hong Kong-Macao Financial Mathematics Modeling Competition  
  Nov. 2024

- **The Third-Class Scholarship (Top 12%)**, *Guangzhou University*  
  Nov. 2024

- **The First-Class Scholarship (Top 5%)**, *Guangzhou University*  
  Nov. 2023

---

## Research Experience

*Machine Life and Intelligence Research Centre, Guangzhou University.*  
Advisor: [Prof. Qinbing Fu](https://scholar.google.com/citations?user=YIte1M8AAAAJ&hl=zh-CN)

- **Real-time Visual Processing Systems Development of Micro-Mobile Robot**  
  Mar. 2023- Present
  - Reading and giving reports of research articles during research seminars on a weekly basis.
  - Deployed visual neural network models inspired by insect neurons onto the [STM32-based micro-robot *Colias*](https://link.springer.com/chapter/10.1007/978-3-319-96728-8_17), achieving real-time collision perception and avoidance. Optimized model memory usage to fit within the **62 KByte** SRAM capacity of [*Colias*](https://link.springer.com/chapter/10.1007/978-3-319-96728-8_17); developed and refined algorithms to enable real-time execution under extreme computational constraints (processing time **< 33 ms** on the STM32F427 chip); performed debugging, tuning, and conducted both offline and online experiments.
  - [**A poster** illustrating the fly-inspired closed-loop visual-perception and motion-control system](https://ryannnice.github.io/assets/TAROS_2025_Poster_100.pdf) for the micro robot [*Colias*](https://link.springer.com/chapter/10.1007/978-3-319-96728-8_17) is submitted to **Towards Autonomous Robotic Systems (TAROS 2025)**.
  - Selected code can be accessed below:  
  [Fly Visuomotor-Inspired Attention-LPLC2 Model **(independently, 2k lines of code in C)**](https://github.com/Ryannnice/mLPLC2_Colias_Robot);  
  [Locust Vision-Inspired Optimized-LGMD Model **(independently, 1k lines of code in C)**](https://github.com/Ryannnice/Optimized-LGMD).
		
		
		
- **Attention-Driven LPLC2 Neural Ensemble Model for Multi-Target Looming Detection and Localization**, paper accepted at *IJCNN 2025*, *first author*.  
  Jul. 2024 - Nov. 2024  
  - Conducted full-cycle research on modeling the lobula plate/lobula columnar type 2 (LPLC2) neural ensemble in the fruit fly *Drosophila*, known for its ultra-selectivity to looming stimuli.
  - Developed the multi-attention LPLC2 (mLPLC2) neural network model inspired by the visual system of the fly by leveraging a bottom-up attention mechanism driven by motion-sensitive neural pathways
([independently, 3k lines of code in C/C++](https://github.com/Ryannnice/Offline_Multi-Attention_LPLC2_Model)).

- **A Computationally Efficient Neuronal Model for Collision Detection with Contrast Polarity-Specific Feed-Forward Inhibition**, article published at *Biomimetics*, *second author*.  
  Mar. 2024 - Jul. 2024  
  - Participated in the entire research on modeling the optimized locust lobula giant movement detector neuron with detailed feed-forward inhibition (oLGMD) to enhance processing speed and the robustness towards translating movement.
  - Implemented oLGMD model into the embedded system of [*Colias*](https://link.springer.com/chapter/10.1007/978-3-319-96728-8_17) ([independently, 1k lines of code in C](https://github.com/Ryannnice/Supplementary_Materials_FFI_ON_OFF/tree/main)), and conducted closed-loop arena comparative experiments to evaluate performance of oLGMD, achieving the highest success ratio of collision avoidance at 97.51% while nearly halving the processing time compared with previous LGMD models; conducted all online experiments of this paper, analyzing the results using real-world data collected by the *Colias* robot; designed criteria to assess time efficiency and collision selectivity.
   - Led the initial writing of the introduction and experimentation sections; participated in revising the submitted paper.

- **Bio-Inspired LGMD Collision Detection Model Leveraging Optical Flow and Learning-Based Optimization, *Provincial Key*** *College Students’ Innovative Entrepreneurial Training Plan Program*.  
  Mar. 2023 - Present  
  - Developed neuromorphic binocular models for collision prediction which combines directional and depth motion cues; optimized directional-selective neuron parameters using a genetic algorithm; collected a stereo RGB-D dataset capturing diverse indoor-outdoor collision scenarios to support model training and evaluation; conducted online robotic experiments with the [*Colias*](https://link.springer.com/chapter/10.1007/978-3-319-96728-8_17) and [*TurtleBot*](https://www.turtlebot.com/turtlebot3/) robots.
  - Designed detailed figures illustrating the models and experiments; drafted manuscript introductions, and contributed to manuscript revisions. [**Two manuscripts of the above works are under review**](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5245992).

---


## Skills

- **Language:** IELTS 6.5 (R8.0, L6.5, W6.0, S5.5), CET-6 564
- **Programming Skills:** C/C++, Python, Matlab
- **Others:** LaTeX, Keil, Webots, Linux, Git, Markdown, MS Office/Visio, Adobe Photoshop/Premiere Pro

Hobbies: Movie, Music, Photography, Basketball, Jogging, Badminton, Hiking.
