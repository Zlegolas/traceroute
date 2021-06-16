# traceroute
记录教育网IPv6网络的tracer路径

Windows版本

1. 在CMD里使用ipconfig，查看是否有IPv6地址，不是本地链接IPv6，没有的话无法运行。
   类似： 2001:250:4802:6:212:343:da:1
   图 查看是否有IPv6地址：

![d34175a46ea7e6c2623fef3b2b1e423](https://user-images.githubusercontent.com/32036515/122180408-faafdb80-ceba-11eb-8c1e-87f2a05e27f9.png)

2. 关闭360等杀毒软件（一定要关闭呀！）；
   下载文件后将所有文件解压至同一个文件夹；
   运行tracer.exe，运行完会自动结束(大约三个小时)

注：config.json文件是配置文件，不用管；若出现需输入服务器地址，即为config文件未成功解压
![Snipaste_2021-06-16_15-57-03](https://user-images.githubusercontent.com/32036515/122180996-845fa900-cebb-11eb-9c9a-f4d3d60fba45.png)

注：出现闪退，一般是杀毒程序将文件部分删除，需重新下载，若仍出现，按如下操作：

所在文件夹的位置，按着shift，右键打开powershell，把exe程序拖进去，enter一下，看下运行情况，并截图反馈
