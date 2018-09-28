# WeChatPlugin-iOS

微信小助手-iOS版 v2.1.0

## 您的打赏是作者研发的动力!

### 功能
- [x] 自动抢红包
- [x] 抢自己的红包
- [x] 支持后台抢红包
- [x] 防止多人同时抢红包
- [x] 群聊过滤
- [x] 关键词过滤
- [x] 增加各种模拟真实用户抢红包功能,防止腾讯微信的封杀
- [x] 支持剪刀石头布以及掷骰子的游戏作弊
- [x] 修改微信运动步数,分为固定设置步数与范围随机步数
- [x] 修改地理位置,异国交友不是梦!
- [x] 消息防撤回
- [x] 可查看累计抢红包总额
- [x] 抢到红包后的本地推送新增红包金额提醒

### 截图

设置界面：

<img src="https://upload-images.jianshu.io/upload_images/12555132-3191426e071ca47c.jpg" height="400" hspace="20" style="display: inline-block"><img src="https://upload-images.jianshu.io/upload_images/12555132-6d924084be157503.jpg" height="400" hspace="20" style="display: inline-block"><img src="https://upload-images.jianshu.io/upload_images/12555132-15b180b209ebe98b.jpg" height="400" hspace="20" style="display: inline-block">

---

#### 0. 准备

* [ios-app-signer](https://github.com/DanTheMan827/ios-app-signer)  (重签名)
* Xcode 或者 PP助手 (安装ipa)
* iOS 证书(可用Xcode生成临时开发证书，然而只能用7天)
* APP文件(可直接下载下面百度云的app文件)


#### 1. 生成临时证书(~~若有证书忽略该步骤~~)
使用 Xcode 创建一个 iOS 的 Project，选择方框1 的开发者，并用真机运行(~~使证书导入到 iPhone~~)。
![Xcode.png](https://upload-images.jianshu.io/upload_images/12555132-ca47f9a309deae55.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

#### 2. 生成注入的app文件

* 可直接通过百度云下载

链接:https://pan.baidu.com/s/1nak9GOQyJYyagJXLGurpzw  密码:wj1w(微信版本 6.7.3-同步微信更新)


#### 3. 使用`iOS App Signer.app` 进行重签名

![iOS App Signer.app.png](https://upload-images.jianshu.io/upload_images/12555132-448e262a0e326a18.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

* `Input File` 选择上面的app文件。
* `Signing Certificate` 选择第一步中的开发者账号(方框3)
* `Provisioning Profile` 选择第一步中的`bundle id`(方框2)

点击start获得重签名的`ipa`文件。

#### 4. 使用 Xcode 安装 ipa

打开Xcode-Window-Devices，将重签名的ipa文件拖到方框中，或者点击`+`添加ipa，即可完成。

![Device.png](https://upload-images.jianshu.io/upload_images/12555132-1526958db3b5b050.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

#### 5. iOS权限设置

打开`设置-通用-描述文件与设备管理`，信任证列表中的开发者应用。

### 免责声明
本项目不可使用于商业和个人其他意图。若使用不当，均由个人承担。


---

#### 听说你想请我喝下午茶？😏

<img src="https://upload-images.jianshu.io/upload_images/12555132-327b709186bcf8a2.jpg" height="250" hspace="50"/>&nbsp;&nbsp;&nbsp;<img src="https://upload-images.jianshu.io/upload_images/12555132-739d47f06701dc93.jpg" height="250" hspace="50"  />

