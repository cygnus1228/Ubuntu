# MarsLUL视频
```https://www.bilibili.com/video/BV1t54y1R7F3```
[跳转](https://www.bilibili.com/video/BV1t54y1R7F3)
# VirtualBox官网下载
```https://www.virtualbox.org/wiki/Downloads```
[跳转](https://www.virtualbox.org/wiki/Downloads)
# Ubuntu下载
```https://cn.ubuntu.com/desktop```
[跳转](https://cn.ubuntu.com/desktop)
# Ubuntu镜像源替换
```https://mirrors.tuna.tsinghua.edu.cn/help/ubuntu/```
[跳转](https://mirrors.tuna.tsinghua.edu.cn/help/ubuntu/)
## ubuntu-20.04百度云
```
链接：https://pan.baidu.com/s/1Re8pyPzFPQKXbqT2p3HRYA 
提取码：9o77 
备用秒传链接：77fc715a283e41d0ad33d6418a9ba128#447f275659e9840ecd754d5bd9a9a157#2785017856#ubuntu-20.04.1-desktop-amd64.iso
```
[百度云](https://pan.baidu.com/s/1Re8pyPzFPQKXbqT2p3HRYA)
[安装秒传链接插件](https://www.userscript.zone/search?q=%E7%A7%92%E4%BC%A0%E9%93%BE%E6%8E%A5)
# VirtualBox所需代码
###### 复制文件
```sudo cp /etc/apt/sources.list /etc/apt/sources_backup.list```
###### 打开文件
```sudo nano /etc/apt/sources.list```
###### 更新软件源
```sudo apt update```
###### 安装软件
```sudo apt install curl git openssh-server net-tools```
# MarsWang42 git
[Mars](https://github.com/MarsWang42/My-Vim-Conf)
## 安装 zsh
```
sudo apt install -y zsh
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```
## 失败后
```
git clone git://github.com/robbyrussell/oh-my-zsh.git ~/.oh-my-zsh
cp ~/.oh-my-zsh/templates/zshrc.zsh-template ~/.zshrc
```
## 下载他的仓库
```git clone https://github.com/MarsWang42/My-Vim-Conf.git```
## 进入仓库文件夹
```cd My-Vim-Conf```
## 设置他的系统
```
chmod +x ./setup.sh ./tmux.sh
./setup.sh
```
## 按照提示并完成所有软件的安装
```source ~/.zshrc```
