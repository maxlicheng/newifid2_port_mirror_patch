# newifid2_port_mirror_patch

补丁文件，用于增加新3路由器交换机端口镜像功能

有了端口镜像功能，可以很方便的抓取局域网内想要的网络数据（方便抓包）

1.下载
```Barsh
  #在openwrt(或lede)源码根目录下，执行
  git clone https://github.com/maxlicheng/newifid2_port_mirror_patch.git
```

2.执行patch
```Barsh
  patch -p1 < port_mirror.patch
```

编译后在网络交换机中即有端口镜像功能


