# Tennis Robot Introduction



## **Framework：**

### **MCU：**

1. raspberry pi：
2. K210 kit:http://www.pengzhihui.xyz/2019/09/13/k210-1/

### Recognition：

1. Feature recognition：灰度化、canny边缘检测、霍夫曼圆检测
2. ML：yoloV2或者V3

### Programming：

20210709今天还是没想明白，双目视觉or单目视觉？

1、不用UWB该如何实现定位，

定位后怎么知道捡到了呢

![image-20210709161142496](C:\Users\黄新宇\AppData\Roaming\Typora\typora-user-images\image-20210709161142496.png)

### collection:

收纳臂+滚轮滚入式

### Carframe：

CAD画一下，然后看情况制作，几个活动关节：双目摄像头需要转吗

### Moving：

方向舵机加直流减速电机  GPIO+L298N

### Power：

确定下需要几个电压等级，是否需要斩波器？5V、12V、24V
