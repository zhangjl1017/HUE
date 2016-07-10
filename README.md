<<<<<<< HEAD
#HUE
安装
- lsb_release -a 查看系统版本
- sudo apt-get install git  安装git
- git clone https://github.com/cloudera/hue.git 这里一定要git下载源代码，原因是自己在github上下载的代码不一定完整也没有下载检测，git会检测代码下载的完整度的。所以安装的时候问题少。（在这里吃了亏，搞了好几天）
- sudo apt-get install ant gcc g++ libkrb5-dev libmysqlclient-dev libssl-dev libsasl2-dev libsasl2-modules-gssapi-mit libsqlite3-dev libtidy-0.99-0 libxml2-dev libxslt-dev make libldap2-dev maven python-dev python-setuptools libgmp3-dev  安装依赖
- cd hue
- make apps   编译（大概三个小时左右）


./build/env/bin/hue runserver
  启动自己的界面

安装教程链接
=======
#HUE
安装
- lsb_release -a 查看系统版本
- sudo apt-get install git  安装git
- git clone https://github.com/cloudera/hue.git 这里一定要git下载源代码，原因是自己在github上下载的代码不一定完整也没有下载检测，git会检测代码下载的完整度的。所以安装的时候问题少。（在这里吃了亏，搞了好几天）
- sudo apt-get install ant gcc g++ libkrb5-dev libmysqlclient-dev libssl-dev libsasl2-dev libsasl2-modules-gssapi-mit libsqlite3-dev libtidy-0.99-0 libxml2-dev libxslt-dev make libldap2-dev maven python-dev python-setuptools libgmp3-dev  安装依赖
- cd hue
- make apps   编译（大概三个小时左右）


./build/env/bin/hue runserver
  启动自己的界面

安装教程链接
>>>>>>> e1fbc3c1eb0df575e2f21314fa07f8558a6dc1da
http://gethue.com/how-to-build-hue-on-ubuntu-14-04-trusty/


http://blog.csdn.net/nsrainbow/article/details/43677077
http://shiyanjun.cn/archives/1002.html
http://gethue.com/a-new-spark-web-ui-spark-app/     //hue_spark