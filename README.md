# CSGOserver
这是几个用来在CentOS上装CSGO服务端的玩意儿
仅限于CentOS的root用户操作
## 忘了说，这是一个满十服

### 首先要把三个脚本弄到/home里去，注意路径别错了
为什么是/home呢，因为/home里基本不会有啥东西，所以脚本里都是按照/home里跑的<br/>
我本来想弄一个脚本里去，突然想到了本来下载的东西就多，万一以后想更新什么的，跑起来耗的流量不少啊，毕竟阿里云1G要1块钱</br>
### 然后运行那个start.sh就慢慢等吧
### 插件是从X社区搞来的，所以跑起来会看到他们的广告
### 至于更新，会自动更新的，自动更新出问题了，，不知道，不管我的事
## gl hf
## cyka blyat
### 我觉得不能这样啥都不说啊，真有小白看不明白怎么办呢
首先执行<code>cd /home</code>这条命令，然后执行下面三条：
<code><br/>wget https://raw.githubusercontent.com/ech0l1u/CSGOserver/master/startInstall.sh
<br/>
wget https://raw.githubusercontent.com/ech0l1u/CSGOserver/master/serverInstall.sh
<br/>
https://raw.githubusercontent.com/ech0l1u/CSGOserver/master/run.sh</code>
<br/>再然后执行<code>sh startInstall.sh</code>这条命令就行了
