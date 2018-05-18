# Vurtl-shadowrocket
搭建教程
资源下载：shadowrocket Mac 版  https://github.com/TeeMoYan/shadowrocket.git
PS(手机版的去PP助手搜索正版应用不是越狱应用（shadowrocket）下载即可，如果提示一直输入appid账号，下载电脑版pp助手，点击修复即可。
注册链接：送25美元：冲5美元送25美元。支持支付宝，（支付宝无优惠）（PS 冲值前，选other 填写5美元。看到右方显示送25美元时再充值。

提示：支付时支付方式选paypal  在右方显示送25美元了！再充值即可！
![Image text](https://github.com/TeeMoYan/Vurtl-shadowrocket/blob/master/Screenshots/1.png)




一. 购买Vurtl服务器(冲5美元送25美元 差不多可以用一年)，需要用到终端或iterm。

1.选择国外服务器节点
![Image text](https://github.com/TeeMoYan/Vurtl-shadowrocket/blob/master/Screenshots/2.png)


2.选择选择服务器的系统类型，选了默认的centos 6 X64，后面好搭建加速
3.选择服务器的空间大小，按需求选择，我选择了第一个5刀，基本够用了。
其他选默认即可

![Image text](https://github.com/TeeMoYan/Vurtl-shadowrocket/blob/master/Screenshots/3.png)

4.购买成功 如下

![Image text](https://github.com/TeeMoYan/Vurtl-shadowrocket/blob/master/Screenshots/4.png)

5.进入后可以看到ip 密码和用户

![Image text](https://github.com/TeeMoYan/Vurtl-shadowrocket/blob/master/Screenshots/5.png)

二.搭建ss（使用终端或iterm）

输入如下命令行,来登录服务器
ssh root@12.12.12.12  （root 刚才的用户名，12.12.12.12.刚才的ip）
回车后 输入密码（刚才的密码，可以直接复制）
1.然后输入这个条命令
wget —no-check-certificate -O shadowsocks-all.sh https://raw.githubusercontent.com/teddysun/shadowsocks_install/master/shadowsocks-all.sh
成功后如下图

![Image text](https://github.com/TeeMoYan/Vurtl-shadowrocket/blob/master/Screenshots/6.png)

2.然后输入这个条命令
chmod +x shadowsocks-all.sh
如果失败，shadowsocks-all替换为上图已保存“”引号中的即可  chmod +x shadowsocks-libev-debian.sh
3.然后输入这个条命令
然后输入这条命令
./shadowsocks-all.sh 2>&1 | tee shadowsocks-all.log
如果失败，shadowsocks-all替换为上图已保存“”引号中的即可    ./shadowsocks-libev-debian.sh 2>&1 | tee shadowsocks-libev-debian.log
输入完成后，如下：服务器部署选第1个即可，然后输入密码。别忘记了


![Image text](https://github.com/TeeMoYan/Vurtl-shadowrocket/blob/master/Screenshots/7.png)

加密方式选择7，其他一路默认即可

![Image text](https://github.com/TeeMoYan/Vurtl-shadowrocket/blob/master/Screenshots/8.png)


最终成功如下，记住ip 端口 密码 和加密方式，接下来下载一个客户端就可以链接了。

![Image text](https://github.com/TeeMoYan/Vurtl-shadowrocket/blob/master/Screenshots/9.png)

最后下载 shadowrocket  客户端，资源在上面了。配置如下



![Image text](https://github.com/TeeMoYan/Vurtl-shadowrocket/blob/master/Screenshots/10.png)



想要更快速上网可以安装下锐速来加速，YouTuBe 1080P视频随便看。Vultr需先执行此脚本。分别执行以下两条命令
wget -N --no-check-certificate https://freed.ga/kernel/ruisu.sh && bash ruisu.sh
wget -N --no-check-certificate https://github.com/91yun/serverspeeder/raw/master/serverspeeder.sh && bash serverspeeder.sh
若提示：The name of network interface is not eth0, please retry after changing the name.请使用备用脚本
备用脚本 wget -N --no-check-certificate https://raw.githubusercontent.com/91yun/serverspeeder/master/serverspeeder-all.sh && bash serverspeeder-all.sh
快去体验极速科学上网吧～
