gluno
======

gluno ＝ glooko + bluno

－－－－－－－－－

项目简介：

通过一个简单的电路，连接bayer counter TS血糖仪和bluno，并将血糖仪中的数据通过bluno的蓝牙或usb串口发送出来。

血糖仪接收的信号必须是经过反向电路处理后的ttl电平信号。

血糖仪发送的信号是标准的ttl信号，bluno可以直接识别。

－－－－－－－－－

目录结构：

bayerBluno/ 烧写进bluno的arduino源码

gluno.pdf 导出为pdf的fritzing连线图

gluno.fzz fritzing连线图

Inverter_(Transistor).png 三极管反向电路原理图

MeterInterface.pdf Bayer血糖仪官方文档，含接口引脚，数据格式等介绍。
=======
glooko + bluno

sent diabetes data to mobile phone with bluetooth by bluno.
