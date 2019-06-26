# FuckMFS

去他妈的取证

是一个 Xposed 模块 
  
最近出现了公共场合查手机的事情、收集到一个名为 MFSocket 的取证软件客户端。
  
功能 : 阻止读取联系人短信媒体文件和应用信息等并随机设备和网络信息。

## MFSocket 类型 / 版本

目前有三种不同类型的 MFSocket 应用  
  
1. com.Android.MFSocket  
  
图标为旧版Android默认应用图标 默认安卓签名  
  
[查看所有版本](./mfsocket/0)  
  
最新版本为 1.1 即某人最近被查手机安装的应用 (虽然没有混淆、看起来很假、但是确实是从被查的手机里提取出来的)  

2. com.Android.MFSocket / com.android.mfsocket  
  
图标为放大镜、有meiya的签名

[查看所有版本](./mfsocket/1)  

早期版本包名为 com.Android.MFSocket 后期为 com.android.mfsocket  
  
有混淆 比第一版提取了更多数据 : 日历、通话记录等等  还会读取 Telegram的聊天记录

3. com.Android.MFSocket  
  
图标为小电脑  
  
[所有版本](./mfsocket/2)  
  
有混淆 比第二种多了四个二进制程序、貌似还能root手机  

## 更新

06 / 23 : 增加联系人与SIM卡号随机生成、短信返回通知类、图片音频视频信息随机生成、应用列表返回国内白名单应用。  
06 / 23 : 更新国内应用白名单列表
06 / 26 : 更新对其他版本的适配 请更新

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

兼容VirtualXposed。如果你能让取证机器的adb把取证软件装到vxp里。

## 太极

可笑 原来太极是白名单 还得给他某个死妈初中生他们发申请才能提示兼容 就不能给个 默认支持 的选项嘛 真是奇妙深刻 爱支持不支持 这么进步怎么买不起两台手机了 军训粪蛆有什么救的必要吗 就算本夜蝶的亲姐姐东风谷早苗碰到这种奇妙深刻的事也要心肺停止的罢 完美华丽 

## 最后

还是物理隔离安全 (
