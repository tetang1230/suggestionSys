suggestionSys
=============
还是一样,沉淀总结,多谢好友永杰！

c hash index search


如何使用

1 需安装libevent-2.0.19（看清版本号）
  注意我安装的时候分别制定了includedir和libdir（./configure --includedir=XXX  --libdir=XXX）不然使用运行示例程序,会报错！

2 发布程序
  ./control.sh make
  ./control.sh build
  ./control.sh start
  
3 测试下
  http://localhost:8080/?word=%E4%B8%80
