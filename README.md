# Network-proxy-node-
这个网络节点的100%搭建成功 2026年最新
你如果不懂的话可以看一下YouTube上面我发的视频,如果视频有问题的话可以向LuGeekLab@outlook.com发邮件不会的话可以在视频底下评论
first you must buy a foreign vps
#首先你必须买一个国外的vps vps也就是一台虚拟的服务器
second when you have a vps,you should enter some command to connect your vps.First, press Win + R and type 'powershell'. Then, run the command 'ssh root@your_vps_ip'.
#第二当你有了vps后你要连接你的vps 同时按键盘上的win和r调出运行框在输入power shell进入后 输入ssh root@ 你买的vps里面的IP   
third you should Run the following command:&#10;bash &lt;(curl -Ls [https://raw.githubusercontent.com/MHSanaei/3x-ui/master/install.sh)&#10;&#10;If](https://raw.githubusercontent.com/MHSanaei/3x-ui/master/install.sh)&#10;&#10;If) that fails, run:&#10;x-ui restart &amp;&amp; x-ui status&#10;&#10;To restart, run:&#10;x-ui restart
#你需要输入bash <(curl -Ls https://raw.githubusercontent.com/MHSanaei/3x-ui/master/install.sh)
假如打不开x-ui的话输入x-ui restart && x-ui status
x-ui restart
下次只需要输入x-ui就可以直接进入里面的控制面板了
你输入bash <(curl -Ls https://raw.githubusercontent.com/MHSanaei/3x-ui/master/install.sh)后1应该会有密码和网址和用户名
解决的方法输入sqlite3 /etc/x-ui/x-ui.db "SELECT username, password FROM users;"账户和密码可以被找到就行了
去浏览器里面输入网址后输入 用户名和密码就可以进入x-ui的面板了
剩下的就交给视频里面的详细做法了


