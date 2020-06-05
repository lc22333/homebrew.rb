安装Homebrew
使用官网提供的命令
在终端输入
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
报错
curl: (7) Failed to connect to raw.githubusercontent.com port 443: Connection refused
由于网络受限，导致地址无法访问
使用homebrew的安装脚本在本地安装
先在终端执行
curl
看看有没有提示
curl: try 'curl --help' or 'curl --manual' for more information
说明命令可用
终端cd到rb文件所在的位置，执行命令
curl homebrew.rb
等待安装结束提示
==> Next steps:
- Run `brew help` to get started
- Further documentation: 
    https://docs.brew.sh
