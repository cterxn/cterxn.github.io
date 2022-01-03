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


## 贡献说明：

**永远不要直接对termuxcn目录进行更改！将新deb包直接提交至仓库根目录**



## 计划新建立一个名为TCUR（全名：cterxn/TCUR）的仓库

允许所有人提交，只要是deb包即可提交，本人不进行任何测试，但偶尔可能会抽测/使用。所有这样的deb包名称中应带上*TCUR*
