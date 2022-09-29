# sillyGirl-VH
旧版傻妞文件 新版目前还不太完善 特意备份下旧版本

一键安装：

```ssh
s=sillyGirl-VH;a=arm64;if [[ $(uname -a | grep "x86_64") != "" ]];then a=amd64;fi ;if [ ! -d $s ];then mkdir $s;fi ;cd $s;wget https://git.songw.top/https://github.com/songwqs/${s}/releases/download/1659883049662/${s}_linux_$a -O $s && chmod 777 $s;pkill -9 $s;$(pwd)/$s
```
