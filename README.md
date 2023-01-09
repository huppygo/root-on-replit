## root脚本命令列表：
> 6条命令行按顺序依次输入
```bash
wget https://cdn.discordapp.com/attachments/853535040250970113/878590395611775016/yt.zip
```
```bash
unzip yt.zip && rm yt.zip
```
```bash
unzip root.zip && rm root.zip
```
```bash
tar -xvf root.tar.xz && rm root.tar.xz
```
```bash
./dist/proot -S . /bin/bash
```
```bash
su
```

## 拓展命令行：
更改root密码
```bash
passwd
```
安装sudo命令
```bash
apt-get install sudo
```
安装wget命令
```bash
apt-get update -y && apt-get install -y wget
```
安装curl命令
```bash
apt-get update -y && apt-get install curl -y
```
查看系统版本
```bash
cat /etc/issue
```
