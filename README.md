# Aria2一键完美配置魔改版 for Colab （Final）

目前形势高风险脚本，上传仅为小白存档学习使用，其余风险自行解决。

小白能力有限，不能对症下药，所以脚本之后基本停止优化，不能用也正常。

感谢源项目作者提供脚本。


源作者地址：

Aria2 一键安装管理脚本 增强版：https://github.com/P3TERX/aria2.sh

OneClickRun：https://github.com/biplobsd/OneClickRun


# 主要功能

调用源作者大佬一键安装Aria2和ngrok内网穿透脚本，优化安装过程，真一键全自动安装。

使用源作者大佬Aria2完美配置方案。

受未知原因限制，脚本无法重启，无法实现自动上传，已添加手动上传方式，全部下载完成执行第二个方框里的代码即可（上传下载目录下所有文件）


# 预览

![Preview](https://github.com/hmglife/aria2-colab/raw/master/Preview.png)

![Speed Preview](https://github.com/hmglife/aria2-colab/raw/master/Speed%20Preview.png)


# 使用方法

1、下载笔记本到本地，上传到Colab后，先配置以下内容：

Rclone Config ，配置教程推荐参考这篇：https://p3terx.com/archives/rclone-installation-and-configuration-tutorial.html

本身有配置好的Config文件的输入直链即可，配置建议在外网linux环境下操作。win下也很方便，不过需要将cmd代理。一次配置，永久使用，建议长期保存便于使用其他如goindex的项目。

2、配置完成并上传到可直链下载的位置后（可以直接fork上传你的配置文件到仓库或者用GoIndex等目录直链永久使用）输入到笔记本对应位置，一键执行即可！

3、手动上传脚本三项内容：源文件位置（已默认为下载目录），rclone里盘的ID，目标盘的目录（建议目录名无特殊符号且简单防止出错）。


# PS

GoIndex项目推荐GoIndex-theme-acrou，配置见项目地址：https://github.com/Aicirou/goindex-theme-acrou

ngrok免费token可能不稳定，建议免费注册使用自己的token。token获取地址：https://dashboard.ngrok.com/auth

测速和检测上传功能种子推荐：https://releases.ubuntu.com/20.04/ubuntu-20.04.1-desktop-amd64.iso.torrent

Colab实例理论只能用12小时，之后会删除实例，所以不建议下慢种。启动后浏览器Colab面板不要关，理论上不会掉线。
