# PicGo + Gitee 实现图床



图床是在线图片的个人仓库，通过图床图片链接可实现图片访问。

下文介绍PicGo + Gitee 实现个人免费图床，并在Typora（Markdown编辑器）中进行应用。



## Gitee 注册账号并创建仓库

[Gitee](https://gitee.com/)(码云)是OSCHINA.NET 推出的代码托管平台,支持 Git 和 SVN,提供免费的私有仓库托管。



### 注册账号

Gitee官网，[注册账号](https://gitee.com/signup)



### 创建仓库

点右上角“+”号选择【新建仓库】

![](https://gitee.com/kisswind/resouces/raw/master/Images/Gitee-CreateRep.png)

输入仓库参数（选择“开源”）【创建】

![](https://gitee.com/kisswind/resouces/raw/master/Images/Gitee-CreateRepSettings.png)

注意：创库地址在PicGo设置中需要。



### 创建Gitee私人令牌

![](https://gitee.com/kisswind/resouces/raw/master/Images/Gitee-GenToken.png)

注意：令牌在PicGo设置需要。



## PicGo 安装及设置

PicGo是一个用于快速上传图片并获取图片 URL 链接的工具。PicGo是一款开源软件，可直接下载[安装包](https://github.com/Molunerfinn/PicGo/releases)（建议选择最新版本，本文以2.2.2版演示），或下载[源码](https://github.com/Molunerfinn/PicGo)。



### PicGo 安装

1. 运行PicGo安装包，安装PicGo

2. 安装PicGo插件，图中安装了任意一个即可

   ![](https://gitee.com/kisswind/resouces/raw/master/Images/PicGo-GiteeInstall.png)

注意：插件安装后，退出重启PicGo应用



### PicGo 设置

【图床设置】》【gitee】或【插件设置】点击插件设置按扭选择【配置 upload - gitee】

![](https://gitee.com/kisswind/resouces/raw/master/Images/PicGo-GiteeSettings-0.png)



设置Gitee仓库参数（仓库地址及令牌）

![](https://gitee.com/kisswind/resouces/raw/master/Images/PicGo-GiteeSettings.png)

注意：仓库地址不需要包含Gitee官网段

配置完成了，就可以开始即使图床了！



### PicGo 上传图片并获取图片URL

![](https://gitee.com/kisswind/resouces/raw/master/Images/PicGo-Upload.png)

![](https://gitee.com/kisswind/resouces/raw/master/Images/PicGo-Ablumn.png)

通过图片URL您可以在您需要的任何地方加入并访问了！（注意：Gitee对访问文件大小有限制，小于1M）



## Typora 使用 PicGo 图床

[Typora](https://typora.io/) 是一款轻便、简洁、免费的Markdown编辑器，支持即时渲染。

### Typora 安装及设置

[Typora官网](https://typora.io/)下载，安装。

运行Typora，菜单【文件】》【偏好设置】进行图像的偏好设置

![](https://gitee.com/kisswind/resouces/raw/master/Images/Typora-PicGoSettings.png)



 ### Typora 图床使用

![](https://gitee.com/kisswind/resouces/raw/master/Images/Typora-PicGoUpload.png)

在编辑区正文中插入图片，选择本地图片，Typora会自动上传至 Gitee 并转换成图片URL。


## VSCode 使用 PicoGo

[VSCode](https://code.visualstudio.com/)是微软开发的一款轻量、开源且功能强大的代码编辑器，支持跨平台。

### VSCode 安装

[VsCode官网](https://code.visualstudio.com/Download)下载，安装。

运行VSCode，并安装 PicGo 插件

![](E:/Work/RefTest/Samples/Electron/resouces/Images/VsCode-PicGoInstall.png)




### VSCode 图床使用

默认 Ctrl+Alt+E 插入本地图片，插入后自动上传至 SM.SM(最大支持10M)，反应速度有点慢。
也可进入 VSCode 设置进行 PicGo 图床设置。

SM.SM 图床图片：
![VsCode-PicGoInstall](https://i.loli.net/2021/07/31/B359athbSJ1jT8i.png)

