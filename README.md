# SoftwareBank
github增强使用方法 https://greasyfork.org/zh-CN/scripts/412245/discussions/79355#comment-192045
Node安装教程: https://zhuanlan.zhihu.com/p/442215189
如何使用gitlfs: 
 执行exe文件,安装成功之后
命令行输入 git lfs install
出现 Git LFS initialzed 代表成功
这样就算完事了
然后去有大文件的本地仓库下,执行cmd命令:
如果要追踪指定文件,比如 test.png,则输入命令 git lfs track "test.png"
如果要追踪指定类型的文件,比如exe类型的,则输入 git lfs track "*.exe"
执行完以上命令之后,就可以在github 客户端里正常commit和push了

具体参考 https://blog.csdn.net/DinnerHowe/article/details/79398178
