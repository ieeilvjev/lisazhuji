# 免费获取Office 365 E5开发者订阅及无限续期教程

## 免费分享20个子账号

> **提示**：免费分享20个Office 365 E5开发者订阅子账号，包含365和5T网盘。账号后缀为`@niubi.plus`。**请在评论区留言**，附上你的昵称、邮箱和自定义前缀，密码将通过邮箱下发。**收到账号后请保持活跃**。

## 前言

Office 365 E5开发者订阅是微软为开发人员提供的官方活动，申请后可获得为期3个月的免费Office 365 E5订阅。E5计划包含25个Office 365应用的许可证，非常适合需要正版Office但预算有限的用户。

> **注意**：申请过程中可能需要准备**上网工具**。如果因已登录账号出现异常，建议使用浏览器的隐私模式（推荐Edge Chromium版）。**本教程不保证100%续期，但能显著提高续订可能性**。

## 申请步骤

1. **访问申请链接**  
   打开[微软Office 365开发者计划官网](https://developer.microsoft.com/zh-cn/office)，点击`立即加入`开始申请。  
   ![加入](https://bbtdd.com/img/402855821582621.webp)

2. **登录微软账号**  
   使用你的微软账号登录，如果没有账号，请先注册一个。

3. **注册Office 365开发人员**  
   在注册页面中，勾选第一个选项以减少广告，点击`下一步`继续。

4. **填写信息**  
   按页面要求填写相关信息，点击`加入`。

5. **申请订阅**  
   在提示页面中点击`申请一个订阅`，输入用户名和域，并记住你的`用户名@域.onmicrosoft.com`，点击`继续`。  
   ![继续](https://bbtdd.com/img/46967058989525.webp)

6. **验证手机号**  
   验证手机号时，会调用谷歌验证系统，**准备好上网工具**。  
   ![验证](https://bbtdd.com/img/1205083163693218.webp)

7. **完成申请**  
   申请完成后，你会获得25个用户许可证。现在可以使用`用户名@域.onmicrosoft.com`和设置的密码登录Office。  
   ![完成](https://bbtdd.com/img/680208024385197.webp)

## 分配账号与安装Office

E5订阅包含25个用户许可证。点击`转到订阅`或登录[Office官网](https://www.office.com/?auth=2)即可分配账号给朋友。

> **注意**：链接中一定要加上`?auth=2`，否则会进入个人版Office 365的登录界面。

点击`安装Office`可以安装Office 365。如果需要自定义安装，可以使用Office Tool Plus工具。  
![管理](https://bbtdd.com/img/98540702121.webp)  
在管理页面中，点击`用户`→`活跃用户`→`添加用户`即可分配账号。  
![添加用户](https://bbtdd.com/img/863683129782.webp)

## 设置5T网盘容量

默认OneDrive容量为1T，但可以通过设置更改为5T。

1. 点击Office 365主页的OneDrive图标。如果提示“我们目前还在设置文件”，可以先跳过此步骤。
2. 打开[OneDrive存储设置](https://admin.onedrive.com/?v=StorageSettings)，将默认存储更改为5120GB。  
   ![5T](https://bbtdd.com/img/245435555.webp)

## 无限续期与OneIndex搭建

由于E5订阅有效期为90天，需通过触发相关API来续期。推荐搭建OneIndex实现续期，并搭建私人网盘。

👉 [WildCard | 一分钟注册，轻松订阅海外线上服务](https://bbtdd.com/WildCard)

关于OneIndex搭建教程，请参考：[宝塔面板搭建OneIndex](https://blog.zwying.com/archives/29.html)。

## 自动续期脚本

如果不使用OneIndex，可以使用以下脚本通过GitHub Action实现自动调用API，保持E5订阅活跃：

- [AutoApiSecret](https://github.com/wangziyingwen/AutoApiSecret)
- [AutoApiSR](https://github.com/wangziyingwen/AutoApiSR)

这些脚本免费且无需额外设备/服务器，部署完成后无需干预。

> **提示**：使用AutoApiSecret后，若点击Action未显示运行日志，请等待几分钟。使用AutoApiSR后，需等待一两个小时查看结果。

## 小结

申请完成后，建议多使用OneIndex或自动续期脚本，确保成功续订Office 365 E5订阅。