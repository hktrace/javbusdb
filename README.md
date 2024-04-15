# javbusdb
收集影视元数据，并规范本地文件（夹）的格式，收集演员头像，为emby、kodi、jellyfin、极影派等影片管理软件铺路。

copy了一份github上的文件，自己定位修改了javbus不支持的问题。

目前就修复了javbus_youma.py这个python文件的bug。

【其他开发者】运行环境：

python3.7.6 发行版是pyinstaller打包的exe

pip install requests==2.20.0（安装2.25.1报错ProxyError无法使用http代理）

pip install Pillow

pip install baidu-aip

pip install pysocks

pip install cloudscraper（目前版本暂时不需要）

pip install xlrd==1.2.0（安装2.2.1无法读取xlsx）

几个jav的py都是独立执行的，加了很多很多注释，希望能理解其中踩过的坑。

【使用方法】

打开functions_requests.py文件，搜索“这里修改成你自己的cookie”，F12抓cookie填入即可。不懂的自行谷歌或者百度找下相关教程


![Example Image](https://raw.githubusercontent.com/hktrace/javbusdb/main/20240415.jpg)
