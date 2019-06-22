# FuckMFS

去他妈的取证

是一个 Xposed 模块 
  
最近出现了公共场合查手机的事情、收集到一个名为 MFSocket 的取证软件客户端。 副本 : [MFSocket.apk](MFSocket.apk?raw=true)
  
功能 : 阻止读取联系人短信媒体文件和应用信息等并随机设备和网络信息。

## 更新

06 / 23 : 增加联系人与SIM卡号随机生成、短信返回通知类、图片音频视频信息随机生成、应用列表返回国内白名单应用。  
06 / 23 : 更新国内应用白名单列表

## 感谢

应用变量 : https://github.com/kingsollyu/AppEnv

## 开源协议

MIT License

## 使用

下载安装已编译的 [FuckMFS.apk](./FuckMFS.apk?raw=true) 并在Xposed安装器启用即可  
  
提示 : 如果Android版本高无法使用原生Xposed，可以使用基于Magisk的Xposed框架EDXposed

## 非Android手机

不能用

## 虚拟框架

VirtualXposed与太极不能用。因为adb不会把取证软件装到vxp和太极里。

## 最后

还是物理隔离安全 (