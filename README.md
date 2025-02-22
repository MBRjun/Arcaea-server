# Arcaea-server
一个微型的Arcaea本地服务器  A small local server for Arcaea

## 简介 Introduction
这是基于Python以及Flask的微型本地Arcaea服务器，可以模拟游戏的主要功能。这可能是我第一次写这种大程序，若有不妥之处，敬请谅解。  

本程序主要用于学习研究，不得用于任何商业行为，否则后果自负，这不是强制要求，只是一个提醒与警告。  

This is a small local Arcaea server based on Python and Flask, which can simulate the main functions of the game. This may be the first time I have written such a large program. Please understand if there is something wrong with it.  

This procedure is mainly used for study and research, and shall not be used for any commercial activities, otherwise the consequences will be borne by oneself. This is not a mandatory requirement, just a reminder and warning.

> 虽然看起来很蠢，但是可以用！
> It looks stupid, but it works!

## 特性 Features
有以下 We have：
- 登录、注册 Login and registration
- 多设备登录 Multi device login
- 成绩上传 Score upload
- PTT
- 世界排名 Global rank
- 排名 Rank
- 好友系统 Friends
- 数据同步 Data synchronization
- 爬梯 Climbing steps
- 自定义世界模式 Customizable World Mode
- 自定义歌曲下载 Customizable songs download
- 单曲和曲包购买（没啥用） Single songs and song packs purchase(useless)
- 奖励系统 Present system
- 兑换码系统 Redeem code system
- 角色系统 Character system
- 全剧情解锁 Unlock all the stories
- 后台查询 Background search
- 后台自定义信息 Customize some things in the background
- 成绩校验 Score check
- 下载校验 Download check
- 服务器日志 Server log

没有以下 We don't have：
- 服务器安全性保证 Server security assurance

可能有问题 There may be problems：
- Recent 30
- 一些歌曲的解锁 Some songs' unlocking
- 同设备多共存登录 Multiple app logins on the same device

## 说明 Statement
只是很有趣，用处探索中。  
It is just so interesting. What it can do is under exploration.


## 下载 Download
[这里 Here](https://github.com/Lost-MSth/Arcaea-server/releases)

[Arcaea](https://konmai.cn/#arcaea)

## 更新日志 Update log
只保留最新版本 Only keep the latest version.

> 提醒：更新时请注意保留原先的数据库，以防数据丢失。
>
> Tips: When updating, please keep the original database in case of data loss. 

### Version 2.5
- 适用于Arcaea 3.6.2版本 For Arcaea 3.6.2
- 更新了歌曲数据库 Update the song database.
- 新增世界排名 Add global rank.
- 新增世界模式的奖励获取 Add reward acquisition of new world mode.
- 完善角色系统，包括： Improve the character system, including
  - 角色升级 Level up
  - 角色觉醒 Upcapping
  - 角色核心 Character cores
  - 世界模式下的数值计算 Numerical calculation in world mode
  - 某些场景下的角色解锁 Character unlocking in some cases

- 新增了一些设置选项和后台功能 Add some setting options and background functions.
- 正在构建API接口 Building API interface.
- 打算重新写后台界面 Plan to rewrite the background interface.
- 修复了一些Bug Fix some bugs.
  - 登录时获取信息的并行计算导致的数据库锁错误 Database lock error caused by parallel computing of getting information during login

> 提醒：由于时间仓促，本版本可能存在较多问题与漏洞，请谨慎使用  
> Tips: Due to lack of time, this version may have many bugs, please use it with caution.

## 运行环境与依赖 Running environment and requirements
- Windows/Linux/Mac OS/Android
- Python 3
- Flask module
- Charles, IDA, proxy app... (optional)

<!--
## 环境搭建 Environment construction
[中文](https://github.com/Lost-MSth/Arcaea-server/wiki/%E7%8E%AF%E5%A2%83%E6%90%AD%E5%BB%BA)  
[English](https://github.com/Lost-MSth/Arcaea-server/wiki/Environment-construction)

## 使用说明 Instruction for use
[中文](https://github.com/Lost-MSth/Arcaea-server/wiki/%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E)  
[English](https://github.com/Lost-MSth/Arcaea-server/wiki/Instruction-for-use)
-->

## 注意 Attentions
[中文](https://github.com/Lost-MSth/Arcaea-server/wiki/%E6%B3%A8%E6%84%8F)  
[English](https://github.com/Lost-MSth/Arcaea-server/wiki/Attentions)


## 鸣谢 Thanks
歌曲数据库来自 Using song database from
[BotArcAPI releases](https://github.com/TheSnowfield/BotArcAPI/releases)  

网站图标来自 Using favicon from [black fate - てんてん - pixiv](https://www.pixiv.net/artworks/82374369)

## 联系方式 Contact
如有必要，可以联系本人 Contact me if necessary  
邮箱 Email：th84292@foxmail.com

## 支持一下 Support me
生活不易。 Life is not easy.  
[支付宝 Alipay](https://github.com/Lost-MSth/Arcaea-server/blob/master/pic/Alipay.jpg)  
[微信 WeChat](https://github.com/Lost-MSth/Arcaea-server/blob/master/pic/WeChat.png)

## 使用许可 Use license
[MIT](LICENSE) © Lost
