这边对于一些贼tm新的新手来一期对熟知之人讲来没卵用的东西，那么我们开始吧:
1.如何在termux上面装个nodejs呢？
答:首先我们需要一个termux，打开
安装: apt update ，也可能需要 apt upgrade ，但是这个东西大部分人都不需要，
等待安装之后呢，我们输入: apt install nodejs 安装nodejs，apt这个指令的作用我就不多说了，
大家可以去一些平台或网站学习学习。安装完后，我们可以检查一下 node -v 来检查当前nodejs的版本。
这样，nodejs的基本配置就安装完成了.
2.nodejs有那些功能呢？
答:这个我也不想说，你们自行去help一下吧，这边我讲一下必要的功能，
当你安装完nodejs之后，输入 node 进入执行环境，这里就可以使用一些js基本的命令啦
输入 console.log('test') 检查一下是否能使用这些功能。
执行你所拥有的js文件的话，最好是输入 node FilePath 但是有一点，你的路径前面
不应该是'/storage/emulated/0/'，而应该只有'/sdcard/'，不然会报错的.
