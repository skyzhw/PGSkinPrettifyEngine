# PGSkinPrettifyEngine
品果视频美肤引擎

## 支持的效果

* 磨皮美肤，强度可调
* 肤色的白晰、粉嫩、红润程度调节

实际处理效果可参看[刊例](http://www.camera360.com/filter/index.html)，或者下载Demo进行体验。

### Change Log
2016.10.26
	增加暂停和恢复接口

2016.10.13
	降噪处理优化
	
2016.10.10
	修复内存泄露问题
	
2016.09.01
	背景虚化实际中使用较少、并且比较消耗性能，屏蔽掉后性能大幅提升

## 支持的平台
### iOS
* [Demo安装](http://www.camera360.com/filter/download.html?k=5xdNAApspj8DcVH2T9owooKC%2Bwe9h2u4jtDbHGbhWWsqaIU6nks3pw%3D%3D)
* [Demo源码](https://github.com/pinguo/PGSkinPrettifyEngineDemo-iOS)
* [API文档](README_iOS.md)
* [SDK引擎](https://github.com/pinguo/PGSkinPrettifyEngineDemo-iOS/tree/master/PGSkinPrettifyDemo-iOS/PGSkinPrettifyEngine)

### Android
* [Demo安装](http://www.camera360.com/filter/adrdownload.html?k=hylVnDMi62bhog%2BED1c819SPZ0zgYKpjT4sDY6IOLWs%3D)
* [Demo源码](https://github.com/pinguo/PGSkinPrettifyEngineDemo-Android)
* [API文档](README_Android.md)
* [SDK接入流程](Android-SDK接入.md)
* [SDK引擎](https://github.com/pinguo/PGSkinPrettifyEngineDemo-Android/tree/master/app/src/main/java/us/pinguo/pgskinprettifyengine)

## 性能测试
视频美肤引擎的处理性能测试为：从数据输入引擎开始，至引擎输出数据结束(不包括屏幕显示)。

分辨率	|iphone5 | iphone5s | iPhone6plus | iPhone6 | iPhone6s
:------- |:--------|:----- |:----- |:----- |:----- 
360p（480x360）| 4ms| 6ms| 5ms| 5ms| 4ms
480p（640x480）| 4ms| 7ms| 6ms| 6ms| 4ms
720p（1280x720）| 5ms| 7ms| 4ms| 5ms| 4ms


分辨率	|	三星s3 | MI2 | 三星SM-G9280  
:------- |:------|:----- |:----- 
360p（480x360）| 6ms| 10ms| 8ms
480p（640x480）| 6ms| 10ms| 8ms
720p（1280x720）| 6ms| 10ms| 8ms

* 增加了GetSkinPrettifyResult接口调用，获取美肤结果

分辨率	|	vivo x7 | 三星s7 | 三星note3 
:------- |:------|:----- |:----- 
480p（640x480）| 6ms| 7ms| 10ms
720p（1280x720）| 11ms| 15ms| 25ms
1080p（1920x1080）| 85ms| 60ms| 50ms

* SDK内存消耗（数据输入前后内存波动范围）

分辨率	|	vivo x7 | 三星s7 | 三星note3 
:------- |:------|:----- |:----- 
480p（640x480）| 3M-7M| 3M-11M| 3M-13M
720p（1280x720）| 3M-7M| 3M-11M| 3M-13M
1080（1920x1080）| 6M-13M| 6M-20M| 6M-21M

* CPU占用（数据输入前后CPU占用波动范围）

分辨率	|	vivo x7 | 三星s7 | 三星note3 
:------- |:------|:----- |:----- 
480p（640x480）| 3%-6%| 2%-8%| 3%-8%
720p（1280x720）| 4%-7%| 4%-8%| 7%-12%
1080p（1920x1080）| 10%-13%| 10%-20%| 10%-14%

## 联系我们

### 商务合作及授权 Authorization

联系人 Contact	|职位 Title | Mobile | QQ | E_mail 
:------- |:--------|:----- |:----- |:----- 
杨颂 Amiel Yang | 商务合作总监 Director of Business Cooperation| 18615700177 13980706252| 2851258101| yangsong@camera360.com

### 技术支持 Technical 
Email: liuzhaohui@camera360.com 

QQ: 165202938



