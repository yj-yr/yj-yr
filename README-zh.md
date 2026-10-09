[English](README.md) | [中文](README-zh.md)

# 你好，我是杨静 👋

河北科技大学 **机械工程硕士研究生**。  
研究方向：**室内动态场景下多机器人协同路径规划**。

- 🤖 ROS 2 开发者：分布式通信、多机器人系统、Nav2、SLAM
- 🧠 目前在做多机器人避碰与跨域桥接研究
- 🛠️ 熟悉 ROS 2、Python、MATLAB、C++、Gazebo、RViz、Git/SSH
- 📫 邮箱：2590135656@qq.com

---

## 🧰 技术栈

![ROS 2](https://img.shields.io/badge/ROS%202-22314E?style=flat&logo=ros&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=flat&logo=mathworks&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

---

## 🚀 项目经历

### 多机器人协同巡逻与异常报警系统
*队长 / 技术负责人 · 2026.07 – 至今*

- 独立实现两台异构机器人的完整流程：巡逻、检测、报警、响应。
- **巡逻机器人**：自主导航到目标点、拍照、基于 OpenCV 的 HSV 红色物体检测、通过 UDP 发送报警。
- **响应机器人**：监听 UDP、解析坐标、用 Nav2 导航到异常点、触发蜂鸣器报警。
- 在 **ROS 2 Humble** 上搭建多机器人实验平台：静态 IP、SSH 远程控制、局域网组网。
- 设计**跨域桥接方案**：为每台机器人分配独立的 `ROS_DOMAIN_ID`，通过 `domain_bridge` 转发 `/tf`、`/odom` 等关键话题。
- 将双机位姿汇聚到同一 `/map` 坐标系，在 RViz 中实时同步显示。
- 目前正在研究多机器人避碰策略，分析并解决里程计累积误差、通信延迟、地图偏移等问题。

*技术栈：ROS 2、Nav2、OpenCV、Python、UDP、TF2、domain_bridge*

### 国家自然科学基金联合基金集成项目 — 智能建筑机器人系统
*子课题学生核心参与 · 2025.09 – 至今*

- 在 ROS 2 Humble 上搭建两台异构机器人的多机器人实验平台。
- 负责分布式通信、跨域桥接与多机器人协同。
- 成果：SCI 二区论文 1 篇（一作，在审）；软件著作权 1 项（二作，导师一作，在审）。

*技术栈：ROS 2、Nav2、AMCL、TEB、Gazebo、RViz*

### ROS 2 通信性能测试

- 编写脚本测量 ROS 2 中的**端到端延迟**、**吞吐量**与**话题频率**。
- 分析日志，编写脚本计算不同配置下的延迟与丢包率。

*技术栈：ROS 2、Python*

---

## 🎓 教育背景

- **河北科技大学** — 机械工程 硕士研究生，2024.09 – 至今
  - 研究方向：室内动态场景下多机器人协同路径规划
- **安徽工业大学** — 机械设计制造及其自动化 本科/学士

---

## 📄 论文与专利

- **SCI 二区论文**（第一作者）— 在审
- **软件著作权**：多机通信方向（第二作者，导师第一）— 在审
- **SCI 三区论文**（合作）— 已发表
- **实用新型专利**（参与申请）— 已受理

---

## 💼 实习经历

- **河北建工集团有限责任公司** — 实习工程师（2025.07 – 2025.12）
  - 基于 ROS 2 搭建单机器人仿真与实物导航系统（Gmapping + A\* + DWA + AMCL）。
- **上海热拓电子科技有限公司** — 来料质检员（2024.07 – 2024.09）

---

## 📫 联系方式

- 邮箱：2590135656@qq.com
- GitHub：[github.com/yj-yr](https://github.com/yj-yr)

---

*我的大部分仓库因比赛规则为私有，面试时可详细展示。*
