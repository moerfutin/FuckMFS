# FuckMFS

去他妈的取证

是一个 Xposed 模块 
  
最近出现了公共场合查手机的事情、收集到多个名为 MFSocket 的取证软件客户端。
  
模块对所有收集到的程序适配 (

## MFSocket 类型 / 版本

目前有三种不同类型的 MFSocket 应用  
  
一 : com.Android.MFSocket  
  
图标为旧版Android默认应用图标 默认安卓签名  
  
[查看所有版本](./mfsocket/0)  
  
最新版本为 1.1 即某人最近被查手机安装的应用 (虽然没有混淆、看起来很假、但是确实是从被查的手机里提取出来的)  

二 : com.Android.MFSocket / com.android.mfsocket  
  
图标为放大镜、有meiya的签名

[查看所有版本](./mfsocket/1)  

早期版本包名为 com.Android.MFSocket 后期为 com.android.mfsocket  
  
有混淆 比第一版提取了更多数据 : 日历、通话记录等等  还会读取 Telegram的聊天记录

三 : com.Android.MFSocket  
  
图标为小电脑  
  
[所有版本](./mfsocket/2)  
  
有混淆 比第二种多了四个二进制程序、貌似还能root手机  

## 更新

06 / 23 : 增加联系人与SIM卡号随机生成、短信返回通知类、图片音频视频信息随机生成、应用列表返回国内白名单应用。  
06 / 23 : 更新国内应用白名单列表
06 / 26 : 更新对其他版本的适配 请更新

## 感谢

柊 ゆり子 : https://github.com/Hiiragi-Yuriko  
   
应用变量 : https://github.com/kingsollyu/AppEnv  

## 开源协议

MIT License

## 使用

下载安装已编译的 [FuckMFS.apk](./FuckMFS.apk?raw=true) 并在Xposed安装器启用即可  
  
提示 : 如果Android版本高无法使用原生Xposed，可以使用基于Magisk的Xposed框架EDXposed

## 假的

已经被辟谣了
  
说实话，我叫李田所，是一名二十四岁的学生，不小心在新疆追尾了官员的黑色高级车，被抓进了集中营，所以萌生了传播谣言的想法。
  
我通过境外法轮功势力的帮助，伪造了一个APK内文件创建时间为几年前的间谍软件。  
  
他们承诺让法轮功学员在网上发表被查手机的事，还帮忙伪造了一张 警务稽查通 上面显示查询手机并查到了VPN字段未通过检查的照片。  

后来在推特上因发送有关64事件30周年，香港送终等有关推文被约谈。在民警同志的引导下，认识到了问题的严重性。且在此声明热爱祖国，热爱人民，热爱中国共产党。  
  
最后，身正不怕影子斜，怕查手机的只有那些违法翻墙，整天浏览境外反动网站的人。

## 太极

他们的管理和我有个人恩怨，您可以Fork一份，修改 PackageName 重新打包，并向太极提交申请，这样就可以在太极使用了。

## 最后

还是物理隔离安全 (

## 交流

[Telegram 群组](https://t.me/joinchat/M5LsLE86uw8vGFqEBNi4NA)
