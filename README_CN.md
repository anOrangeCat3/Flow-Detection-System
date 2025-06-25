# 基于树莓派的多场景流动智能检测系统

[English](README.md) | 简体中文 |

**_2022年7月 ~ 2022年8月_**

_三人团队项目_


<div align=center> <img src="https://github.com/anOrangeCat1/projects_sustech/assets/99580008/9e0a970d-5965-4909-8ed8-4957eac7f6c0" width="40%" height="40%"/> <img src="https://github.com/anOrangeCat1/projects_sustech/assets/99580008/472ea16d-5e3b-4d1a-b92e-a9349f10acc9" width="43%" height="43%"/> </div>

**项目描述**：本项目旨在解决多类别目标检测的挑战，优化系统架构，降低数据处理负载，加快数据计算与传输速度。该智能检测系统基于配备摄像头的树莓派 4B，采用 YOLOv5 框架进行模型训练，并构建了一个基于 OpenCV 的图像目标检测框架，适用于包括核酸检测在内的多种场景。检测到的数据上传至云服务器，通过 PC 端进行进一步处理，并通过网页端进行可视化展示，供用户实时访问。

**个人贡献**：本人负责将 YOLOv5 部署至树莓派，使用了简化的轻量级版本(YOLOv5_lite)，实现了约每秒 4 帧（fps）的实时检测性能，能够在多个场景中识别多类目标。最终系统可对画面中的目标数量进行统计。

以下附上在树莓派上运行 YOLOv5 进行目标检测的结果图示：

<div align=center>
   <img src="https://github.com/anOrangeCat1/projects_sustech/assets/99580008/82e2e889-efb9-43dc-afb5-36bb37547b04" width="40%" height="40%"/>
  <img src="https://github.com/anOrangeCat1/projects_sustech/assets/99580008/c44e9772-a360-4377-b259-c1f1a149c495" width="40%" height="40%"/>
  <img src="https://github.com/anOrangeCat1/projects_sustech/assets/99580008/a1fdee4f-d108-4c5b-9a0e-b5d759230a1e" width="40%" height="40%"/>
</div>

**视频链接:**

youtube: https://www.youtube.com/watch?v=WhOx_mLZSFg

bilibili: https://www.bilibili.com/video/BV1qC4y157nN

随着人工智能技术和深度学习目标检测算法的不断发展，为响应当前智慧城市建设的需求，本项目聚焦于多类别交通流量测量，优化了系统架构，降低了数据处理负载，加快了数据计算与传输速度。

本智能检测系统基于搭载摄像头的树莓派 4B，采用 YOLOv5 框架，并构建了适用于核酸检测等多种场景的 OpenCV 图像目标检测架构。系统将相关识别数据上传至云服务器，由 PC 端进行进一步处理，并通过网页展示可视化结果，供用户实时访问。

我负责使用 YOLOv5 实现智能检测模块，队友则完成了远程控制和 TCP 通信部分的搭建。

**以下是相关文件：**
|文件名|内容与功能|
|------|------|
|Frame_IR.py|硬件部分的控制代码|
|Frame_final.py|最终项目代码，集成硬件与软件部分，可实现红外遥控、目标检测并将相关数据上传至云端|
|design_report.pdf|最终项目设计报告|
|final_pre.pdf|最终项目展示PPT|