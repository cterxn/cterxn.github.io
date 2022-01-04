# cterxn.github.io

提交要求：体积适当，可以运行，安全

本人不担保包可使用且安全，尤其是cterxn/TCUR中的包

## 如何使用cterxn/termuxn软件源:

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

注：也可参考[UTermux博客中的换源教程末尾的换源方法](https://blog.utermux.eu.org/ut/changerepo.html#cterxn)，只是我习惯于apt edit-sources

## 贡献说明：

**永远不要直接对termuxcn目录进行更改！将新deb包直接提交至仓库根目录**



## 计划新建立一个名为TCUR（全名：cterxn/TCUR）的源

允许所有人提交，只要是deb包即可提交，本人不进行任何测试，但偶尔可能会抽测/使用。所有这样的deb包名称中应带上*TCUR*

## 计划建立src-dir（全名：cterxn/src-dir）源

这个仓库只是一个打包为deb的文件夹的集合，文件夹里面有源码包，需要自行动手编译安装（这样安装的软件包就不归apt管了）

## 计划建立TCSR（全名：cterxn/TCSR）源

将cterxn组织的TCSR仓库中的（部分）脚本（分类）通过文件夹形式打包为deb包，安装后在/data/data/com.termux/files/usr/src/（需要预创建）。安装deb包后请自行前去使用/安装脚本。
