## Highway_violation_detection

## 高速公路违章检测

随着交通需求的不断增长，高速公路快速发展，带动和促进了社会进步与经济发展，产生巨大的经济效益和社会效益，但是由于某些驾驶员安全意识淡薄、法规意识差、驾驶经验不足使得交通事故频发，造成高速公路通行能力下降，经济损失和资源浪费。

我国近年来建成的高速公路交通监控系统大多是在特定路段安装固定的监控摄像头，仍需要人工观看视频录像的方式进行，劳动强度大、工作效率低且容易发生异常事件发现不及时和漏判现象，难以实现预定的功能，影响高速公路监控效果，实时性差。而且目前在高速公路交通环境下，难把城市道路中的交通信息采集技术移植到高速公路环境中来，原因在于高速公路特殊的环境背景不利于硬件设备的安装，很难在大范围的道路上实时采集交通信息。若发生交通堵塞、交通事故或者出现极端气候时，传统方法更是无法实时监测。

采用UAV实时进行高速公路信息采集技术，能有效克服极端情况和环境的影响，在广阔的范围内采集交通信息，对高速公路实现实时监控。UAV可实现较大范围内的交通视频图像采集，结合视频图像处理技术，可为交通规划、交通仿真、交通控制、交通安全、交通拥堵等研究提供一种新颖的处理方法，可和传统的交通信息采集技术相结合，极大丰富和发展传统的交通信息采集方法。

UAV可装载各类传感器和摄像机，通过航拍的方式可采集高速公路中的视频图像，利用高性能，低功耗的机载嵌入式平台经过一系列的深度学习与图像处理技术能获取并检测该区域的多种交通信息。UAV技术还可以定性的检测一些违章交通事件，具体的交通违章事件包括：车辆违章轧实线，违章变道，违法占用应急车道等等。

本项目目前已实现车辆违章轧实线的功能，具体代码请移步"push_lane_detection"文件夹

![图1](https://img-blog.csdnimg.cn/2019033121524313.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3UwMTA3MTIwMTI=,size_16,color_FFFFFF,t_70)


![无违章](https://img-blog.csdnimg.cn/20190331215146313.png)


![图2](https://img-blog.csdnimg.cn/20190331215217233.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3UwMTA3MTIwMTI=,size_16,color_FFFFFF,t_70)

![违章轧线](https://img-blog.csdnimg.cn/20190331215157407.png)

![图3](https://img-blog.csdnimg.cn/20190331215229313.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3UwMTA3MTIwMTI=,size_16,color_FFFFFF,t_70)

![无违章](https://img-blog.csdnimg.cn/20190331215134288.png)

TODO: 车辆违章变道，违法占用应急车道

