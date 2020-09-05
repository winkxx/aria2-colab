# Aria2一键完美配置魔改版 for Colab

小白自用学习魔改版，感谢源项目作者提供脚本。

源作者地址：

Aria2 一键安装管理脚本 增强版：https://github.com/P3TERX/aria2.sh

OneClickRun：https://github.com/biplobsd/OneClickRun

# 主要功能

调用源作者大佬一键安装Aria2和ngrok内网穿透脚本，优化安装过程，真一键全自动安装。

使用源作者大佬Aria2完美配置方案。

优化源作者大佬开启上传GD方法，自行添加相关配置链接后安装即实现下载完成全自动上传Google Drive，完成后删除本地文件。

# 预览

![Preview](https://github.com/hmglife/aria2-colab/raw/master/Preview.png)

![Speed Preview](https://github.com/hmglife/aria2-colab/raw/master/Speed%20Preview.png)


# 使用方法

1、下载笔记本到本地，上传到Colab后，先配置以下内容：

Rclone Config 配置教程推荐参考这篇：https://p3terx.com/archives/rclone-installation-and-configuration-tutorial.html ，本身有配置好的Config文件的输入直链即可，配置建议在外网linux环境下操作。win下也很方便，不过需要将cmd代理。一次配置，永久使用，建议长期保存便于使用其他如goindex的项目。

Aria2 Config和Script Config配置推荐参考这篇：https://p3terx.com/archives/offline-download-of-onedrive-gdrive.html ，建议下载作者默认文件修改上传提供直链即可。下载地址：Aria2 Config：https://github.com/P3TERX/aria2.conf/raw/master/aria2.conf ，Script Config：https://github.com/P3TERX/aria2.conf/raw/master/script.conf

2、配置完成并上传到可直链下载的位置后（可以直接用GoIndex等目录直链永久使用）输入到笔记本对应位置，一键执行即可！

PS：GoIndex项目推荐GoIndex-theme-acrou，配置见项目地址：https://github.com/Aicirou/goindex-theme-acrou

内网穿透建议选择ngrok。免费token可能不稳定，建议免费注册使用自己的token。token获取地址：https://dashboard.ngrok.com/auth
