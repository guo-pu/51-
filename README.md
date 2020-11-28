# 51单片机蓝牙控制小车

## 介绍
 本次设计选择基于蓝牙遥控的多功能智能小车为对象。选用STC98C52RC单片机作为主控芯片,电机驱动采用L293N ,电源部分采用两节3.7V锂电池供电.采用C语言模块化编程,提高开发效率.蓝牙控制功能.用按键或遥控器来控制小车.

## 关键词
51单片机、L298N_电机驱动、蓝牙遥控


## 系统研究背景

  蓝牙属于短距离内进行无线控制和收发的通信技术，伴随着科技的飞跃性发展，也让蓝牙找到了发展的空间，它可以代替和取代落后的数字化硬件设备之间繁琐的电缆连接。在蓝牙创造的初期，没有人预料到蓝牙会有如此大的潜力和前景，而现在的发展也是完全超出了我们的预期，因为蓝牙的安全性高，制造成本低廉和所消耗的功率也是同类产品中最低的，所以被很多人使用，越来越受到了广大消费者的欢迎，基于蓝牙技术的产品也在不断的更新和投入市场。

  蓝牙技术是近年来出现的新技术是一种短距离无线通信和信息传输的新型通讯科技，它使数据线的硬件设备接收更方便快捷。它可以广泛应用于世界各地，是一个蓝牙设置一个通用的范围，频率调制技术的使用，以防止外部干扰和多一些。低成本，低功耗和小辐射，和加密设置，让蓝牙的安全性更高；应用范围广，这些特点使得蓝牙技术被广泛的应用在我们日常生活中的蓝牙也支持一对一和一对多传输的通信连接，和多个蓝牙成为微网，也有网络的特点。
  
  在现在的智能时代，小车智能控制，方便了人们的使用。在51单片机的基础下，通过蓝牙来控制小车的驾驶。

## 系统研究的意义和目的
  因为无线技术的广泛使用，我们在研究无线和有线通信技术的方法中了解到蓝牙系统的小区域性有很大的技术突破，在国际上也得到了广泛的采纳，在市场上也有很大的需求。这也使蓝牙技术的发展成为了趋势之一，蓝牙可以发送和接受语音和数据，满足了大多数人的需求，它也融合了其他相关产品的特点，也是这样技术变得更多样性。然而，蓝牙的安全性不足，而且在小区域范围内的一点对多点的通信受到了很大的限制，这些都是其本身需要改进和完善的可以使人们更方便，更简单的控制小车。实现了无线控制小车，摆脱了有线控制的不方便，更智能。
  
## 系统的功能
51单片机的基础下，通过蓝牙来控制驱动，此驱动能把5~12V的电压，一部分给小车轮子转动，一部分通过降压，稳压，最终降为5V来供给此驱动，单片机和传感器供电。

## 总结
 本设计采用的是STC89C52RC单片机，这主要是因为该单片机的稳定性比较好和执行指令的速度很快。还可以采用其它系列的单片机。电机驱动采用L293N ,稳定电压，充足地向直流电机供电和稳定控制；电源部分采用两节3.7V锂电池供电，电压稳定，电流充足，还可以循环充电，节能环保。采用C语言模块化编程,提高开发效率.蓝牙控制功能.用按键或遥控器来控制小车，简单方便经过自己不断的搜索努力以及老师的耐心指导和热情帮助，本设计已经基本完成。
 
 过这次课程设计，使我深刻地认识到学好专业知识的重要性，也理解了理论联系实际的含义，并且检验了大学两年的学习成果。虽然在这次设计中对于知识的运用和衔接还不够熟练。但是我将在以后的工作和学习中继续努力、不断完善。这两个月的设计是对过去所学知识的系统提高和扩充的过程，为今后的发展打下了良好的基础。  由于自身水平有限，设计中一定存在很多不足之处，敬请各位批评指正.
 
## 参考文献
C语言程序设计 ：清华大学出版社作者：谭浩强
51单片机C语言教程：电子工业出版社 ，作者：郭天祥

为了大家方便，我上传了手机APP在网盘：https://pan.baidu.com/s/1UNjlUhUQa25K2RNW8hjwOQ
提取码：wn7k 

## 运行
请移植main.c代码到STC89C52RC单片机
