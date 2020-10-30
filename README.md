# WiFiDemo

说明：根据官方的demo整理成Andorid Studio中可编译的项目。

[**WiFiDirectDemo**](https://android.googlesource.com/platform/development/+/master/samples/WiFiDirectDemo/)

测试用例：

1. 两个手机连接WLAN热点：如`Fiture(2.4G/5G)`，在同一个网络下。

   运行结果：两个手机能正常通信，收正常收发图片。

2. 一个手机连接WLAN热点：如`Fiture-Slim(5G)`，另一个手机连接`Fiture（2.4G/5G）`。

   运行结果：两个手机能正常通信，收正常收发图片。

>Group Owner IP -192.168.49.1

3. AP隔离场景：一个手机连接4G网络虚拟的`人个热点`，一个手机连接`Fiture（2.4G/5G）`。

   运行结果：两个手机能正常通信，收正常收发图片。

  > Group Owner IP -192.168.49.1

4. 开发板的测试场景（同上述三种测试场景）



运行截图：

![wifidirect](screen/wifidirect.png)