# website_receiver
这是项目application的移动端文件。 
该项目包含了application_sender，和website_receiver，中间通过MQTT通信协议进行联调。 
低UX，这是因为这并不是最终版，而是最初发行的实验版本。
其中在发送端，用户可以在文本框中输入内容，或者点击现成的内容。 接收端会以弹幕的形式轮播这些内容。 
receiver端存在触发机制，特定的内容‘nice’, 'love', 'happy'可以触发对应的特效，有烟花、爱心和干杯，类似送礼物特效，遗憾的是最终版本源文件消失。所以只能上传之前带有bug的版本。
