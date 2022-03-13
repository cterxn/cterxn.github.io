# cterxn.github.io
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

**[English](https://github.com/cterxn/cterxn.github.io/blob/main/README_EN.md)**    

提交要求：体积适当，可以运行，安全

本人不担保包可使用且安全，尤其是cterxn/TCUR和cterxn/TCSR中的包

请大伙们积极访问本仓库和[项目首页](https://cterxn.github.io)以获取最新公告，资讯与更新！

使用前，请完整阅读[README.md](./README.md)!

## 如何使用cterxn/termuxcn软件源:

执行：

`
apt edit-sources
`

将下列内容加入源文件中：

`
deb [trusted=yes] https://cterxn.github.io/termuxcn termux extras
`

然后执行：

`
apt update
`

完事！

注：也可参考[UTermux博客中的换源教程末尾的换源方法](https://blog.utermux.dev/ut/changerepo.html#cterxn)，只是我习惯于`apt edit-sources`

## 贡献说明：

**永远不要直接对termuxcn目录进行更改！将新deb包直接提交至仓库根目录**



## 计划新建立一个名为TCUR（全名：cterxn/TCUR）的源

允许所有人提交，只要是deb包即可提交，本人不进行任何测试，但偶尔可能会抽测/使用。所有这样的包的名称（不是deb包名称！）中应带上*TCUR*

## 计划建立src-dir（全名：cterxn/src-dir）源

这个仓库只是一个打包为deb的文件夹的集合，文件夹里面有源码包，需要自行动手编译安装（这样安装的软件包就不归apt管了）

## 计划建立TCSR（全名：cterxn/TCSR）源

将cterxn组织的TCSR仓库中的（部分）脚本（分类）通过文件夹形式打包为deb包，安装后在/data/data/com.termux/files/usr/src/（需要预创建）。安装deb包后请自行前去使用/安装脚本。

所有包名中都将带上*TCSR*

## 征集制作deb包

希望大家帮忙制作！（希望能优先制作checkinstall和install-log，checkinstall可以更加方便的生成deb（rpm,slackware安装包等）,install-log可以捕捉编译安装软件后软件被安装到了哪里。这些工具将方便打包）

*  checkinstall （源码镜像：https://github.com/cntrump/checkinstall
（官网：http://checkinstall.izto.org/

* php 7.4 （7.3也可。官网下载页面：https://www.php.net/downloads.php

* install-log （年代久远但实用。源码位于https://nxretc.github.io/install-log-cvs.tar.bz2
（非要访问官网的话，链接：http://install-log.sourceforge.net/
……注意：官网上指向最新版本的链接已无法使用，我的版本是从*网页时光机*找来的，最后一个版本（大概）更新于2003.05.27）

* hashcat,metasploit和sqlmap （国光大佬从Git的提交记录中恢复了源码，链接：https://github.com/sqlsec/termux-sec-packages/tree/main/metasploit

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/txmu"><img src="https://avatars.githubusercontent.com/u/71213934?v=4?s=100" width="100px;" alt=""/><br /><sub><b>txmu</b></sub></a><br /><a href="#design-txmu" title="Design">🎨</a></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!