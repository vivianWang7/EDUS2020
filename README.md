本系统运用了python、postgresql数据库、js\css\html语言，完成一个简易的学生成绩管理系统，实现了增删改查以及用户登录的功能。
操作：
1.打开postgresql后台，待启动成功后，开始后续工作；
2.用vs code打开此文件夹，在vs code里下载sqltools和sqltools postgresql，然后建立一个名为postgres@localhost的connection name，用户名和数据库都为postgres，密码为空，save并connect now，运行grade0123后再建立第二个连接，名为examdbo@localhost，数据库名为examdb，用户名为examdbo，test无误后save，connect now；
3.打开cmd，敲入所在文件夹，输入命令行py server.py，回车后等待端口号8080提示，打开Google，输入网址localhost:8080，即可跳转至该系统。