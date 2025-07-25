# A Multi-Scene Flow Intelligence Detection System Based on Raspberry Pi

English | [简体中文](README_CN.md) | 

**_2022.7~2022.8_** 

_Team Project of 3 members_ 

<div align=center> <img src="https://github.com/anOrangeCat1/projects_sustech/assets/99580008/9e0a970d-5965-4909-8ed8-4957eac7f6c0" width="40%" height="40%"/> <img src="https://github.com/anOrangeCat1/projects_sustech/assets/99580008/472ea16d-5e3b-4d1a-b92e-a9349f10acc9" width="43%" height="43%"/> </div>

**Discription of project**: This project focuses on solving multi-class object detection challenges, improving system architecture, reducing data processing loads, and speeding up data computation and transmission. The intelligent detection system utilizes a Raspberry Pi 4B equipped with a camera, employs the YOLOv5 framework for model training, and builds an OpenCV-based image object detection framework for various scenarios, including nucleic acid testing. The identified data is uploaded to a cloud server, further processed via a PC interface, and presented with visualization on a web page for real-time access by users.

**Individual contribution**: I have completed the deployment of YOLOv5 on a Raspberry Pi, using a simplified lightweight version(YOLOv5_lite), achieving approximately 4 frames per second (fps) and enabling real-time detection. It can detect various objects in multiple scenarios. Finally, the system provides a count of objects within the frame.

The results of objects detection using YOLOv5 running on Raspberry Pi were attached as below:

<div align=center>
   <img src="https://github.com/anOrangeCat1/projects_sustech/assets/99580008/82e2e889-efb9-43dc-afb5-36bb37547b04" width="40%" height="40%"/>
  <img src="https://github.com/anOrangeCat1/projects_sustech/assets/99580008/c44e9772-a360-4377-b259-c1f1a149c495" width="40%" height="40%"/>
  <img src="https://github.com/anOrangeCat1/projects_sustech/assets/99580008/a1fdee4f-d108-4c5b-9a0e-b5d759230a1e" width="40%" height="40%"/>
 
</div>

**video link:**

youtube: https://www.youtube.com/watch?v=WhOx_mLZSFg

bilibili: https://www.bilibili.com/video/BV1qC4y157nN

With the advancement of artificial intelligence technology and deep learning object detection algorithms, in response to the demand for building smart cities today, 
this project focused on multi-category traffic flow measurement. It improved the system architecture, reduced data processing load, and accelerated data computation and transmission.
This intelligent detection system used a Raspberry Pi 4B with a camera, using the YOLOv5 framework, building an OpenCV image object detection architecture for various scenarios 
such as nucleic acid testing, and uploaded relevant data to a cloud server. Further processing of recognition data is carried out on the PC, and the visualized results are displayed on a web page for real-time access by users.

I was responsable for the part of intelligent detection using YOLOv5 and my teammates built remote control and TCP construction.

**Below are the relevant files:**
|file_name|content&function|
|------|------|
|_Frame_IR.py_|**code for the hardware component**|
|_Frame_final.py_|**The final project code, including both hardware and software components, can accomplish infrared remote control, target detection, and upload relevant data to the cloud.**|
|_design_report.pdf_|**Final Project Design Report**|
|_final_pre.pdf_|**Final Project PPT**|










