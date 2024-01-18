西电 网信院 网络工程专业 网络程序设计课设

我的选择(其实就是看上这2分的bonus了)

题目1：设计一个类似于QQ的聊天系统

基本功能（必须完成）：

新用户注册、
用户登录和退出、
聊天服务、
在线用户查询

附加功能（可选）：
文件传送服务（2分的奖励）

对课设的解释说明：

Network Programs Design\Server\cmake-build-debug\net.db 中的数据库文件可以使用navicat进行查看/直接进行修改。

Server和Filetrans中执行cmake -B build命令即可生成执行文件。

执行uix文件时如出现：error while loading shared libraries: libQt5Widgets.so.5: cannot open shared object file:

通过安装libQt5Widgets即可，命令如下：sudo apt-get install libqt5widgets5 (注意软件名一定要小写)

运行Server时命令格式示例： ./proj run 8080 net.db

和Server通信时本地使用环回地址127.0.0.1
