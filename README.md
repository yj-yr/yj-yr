# Hi, I'm Jing Yang 👋

Master's student in Mechanical Engineering at **Hebei University of Science and Technology**.
Research focus: **Multi-robot Cooperative Path Planning in Indoor Dynamic Environments**.

- 🤖 ROS 2 developer: distributed communication, multi-robot systems, Nav2, SLAM
- 🧠 Currently working on multi-robot collision avoidance and cross-domain bridging
- 🛠️ Comfortable with ROS 2, Python, MATLAB, C++, Gazebo, RViz, Git/SSH
- 📫 Reach me at: 2590135656@qq.com

---

## 🧰 Tech Stack

![ROS 2](https://img.shields.io/badge/ROS%202-22314E?style=flat&logo=ros&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=flat&logo=mathworks&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

---

## 🚀 Projects

### Multi-Robot Cooperative Patrol & Alert System
*Team Leader / Tech Lead · 2026.07 – Present*

- Designed and implemented a full pipeline for two heterogeneous robots: patrol, detect, alert, respond.
- **Patrol robot**: autonomous waypoint navigation, photo capture, HSV-based red object detection (OpenCV), UDP alert sending.
- **Response robot**: UDP listener, coordinate parsing, Nav2 navigation to abnormal point, buzzer alarm.
- Built multi-robot experiment platform on **ROS 2 Humble**: static IP, SSH remote control, LAN networking.
- Designed **cross-domain bridging**: assigned independent `ROS_DOMAIN_ID` per robot, forwarded `/tf`, `/odom`, etc. via `domain_bridge`.
- Aggregated dual-robot poses into a shared `/map` frame, visualized in RViz in real time.
- Currently researching multi-robot collision avoidance (odometry drift, communication delay, map offset).

*Stack: ROS 2, Nav2, OpenCV, Python, UDP, TF2, domain_bridge*

### NSFC Joint Fund Project — Intelligent Building Robot System
*Core Student Contributor · 2025.09 – Present*

- Building a multi-robot experiment platform on ROS 2 Humble with two heterogeneous robots.
- Working on distributed communication, cross-domain bridging, and multi-robot coordination.
- Result: 1 SCI Q2 paper (first author, under review); 1 software copyright (second author, under review).

*Stack: ROS 2, Nav2, AMCL, TEB, Gazebo, RViz*

### Communication Performance Testing for ROS 2
- Built scripts to measure **end-to-end delay**, **throughput**, and **topic frequency** in ROS 2.
- Analyzed logs and produced scripts to compute delay and packet loss under different configurations.

*Stack: ROS 2, Python*

---

## 🎓 Education

- **Hebei University of Science and Technology** — M.Eng. in Mechanical Engineering, 2024.09 – Present
  - Research: Multi-robot Cooperative Path Planning in Indoor Dynamic Environments
- **Anhui University of Technology** — B.Eng. in Mechanical Design, Manufacturing & Automation

---

## 📄 Publications & Patents

- **SCI Q2 paper** (first author) — under review
- **Software copyright** on multi-robot communication (second author, advisor first) — under review
- **SCI Q3 paper** (co-author) — published
- **Utility model patent** (co-applicant) — accepted

---

## 💼 Experience

- **Hebei Construction Group Co., Ltd.** — Intern Engineer (2025.07 – 2025.12)
  - Built single-robot simulation and real-world navigation on ROS 2 (Gmapping + A\* + DWA + AMCL).
- **Shanghai Retop Electronics Co., Ltd.** — Incoming Quality Inspector (2024.07 – 2024.09)

---

## 📊 GitHub Stats

![Jing's GitHub stats](https://github-readme-stats.vercel.app/api?username=yj-yr&show_icons=true&theme=default)

---

## 📫 Contact

- Email: 2590135656@qq.com
- GitHub: [github.com/yj-yr](https://github.com/yj-yr)

---

*Most of my repositories are private due to competition rules. Happy to walk through them during interviews.*
