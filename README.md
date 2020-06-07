# homebrew
安装homebrew的时候，在终端输入
```shell
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
提示：
```shell
curl: (7) Failed to connect to raw.githubusercontent.com port 443: Operation
```

解决方法:
```shell
进入如下网站后进行下载，或者直接clone本项目中的homebrew.rb 来进行相应的安装
https://raw.githubusercontent.com/Homebrew/install/master/install
```
把这个网页保存名为brew_install.rb的文件，保存的位置你随便，只要自己能找到。

在终端输入curl
```shell
$ curl
```
出现
```shell
curl: try 'curl --help' or 'curl --manual' for more information
```

然后在终端进入存放这个文件的目录，然后终端输入
```shell
ruby brew_install.rb
```
接下来 安装操作一步步进行安装即可
