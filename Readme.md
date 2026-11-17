# Bangyu Hong

陕西科技大学人工智能专业本科生，关注机器人视觉、移动机器人导航与嵌入式视觉部署。项目经历涉及 ROS / ROS 2、STM32 底盘控制，以及 RK3588、RA8P1 平台上的目标检测。

## 研究兴趣

- 机器人学习与具身智能
- 计算机视觉与多模态学习
- 自主导航与移动操作
- 视觉语言动作模型（VLA）

## 项目经历

### 1. 基于 RK3588 的智能物料拾取机器人

**ROS 2 · RK3588 · STM32F407 · Nav2 · RKNN**

面向室内球体拾取，将目标检测、深度定位、导航调度与机械臂抓取组织为分阶段任务。本人主导导航与任务控制、视觉感知、多传感器状态估计和底盘控制，参与机械臂接口开发与整机联调。

[项目介绍、演示视频与源码](https://github.com/Bangyu-Hong/rockchip)

### 2. RoboCup ROS 1 环境建图机器人

**ROS 1 · Gmapping · STM32F407 · RPLIDAR · RViz**

使用二维激光雷达、轮式里程计和 TF 构建室内栅格地图。工程包含底盘串口驱动、Gmapping 参数、建图启动文件及地图保存流程。

[项目介绍、场地视频与源码](https://github.com/Bangyu-Hong/robocup-autonomous-rescue)

### 3. 基于 RA8P1 的麦穗计数与环境监测系统

**RA8P1 · Ethos-U55 · YOLOX-Tiny · INT8 · 嵌入式视觉**

针对密集麦穗检测，采用重叠分块推理、坐标恢复与全局 NMS 去重，并在 RA8P1 上组织图像采集、模型推理和结果显示。本人主要负责麦穗检测模型优化与移动底盘搭建。

[项目介绍、答辩材料与源码](https://github.com/Bangyu-Hong/ra8p1-wheat-inspection)

## 技术基础

| 方向 | 使用的语言与工具 |
|---|---|
| 编程 | C/C++、Python、MATLAB |
| 机器人 | ROS / ROS 2、SLAM、Nav2、Gazebo、RViz |
| 嵌入式与端侧推理 | STM32、RK3588、Jetson、RKNN、Ethos-U55 |

## 竞赛经历

- 全国人工智能算法精英赛：国家级一等奖
- 中国机器人及人工智能大赛：国家级二等奖
- 中国服务外包创新创业大赛I（智慧社区赛道）：国家级二等奖
- Robocup大赛：国家级三等奖
- 全国大学生电子设计大赛前沿信息邀请赛（瑞萨杯）：国家级三等奖
## 联系方式

GitHub：[Bangyu-Hong](https://github.com/Bangyu-Hong)
