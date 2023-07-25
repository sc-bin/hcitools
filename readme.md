说明
======
系统使用apt自动安装的`hcitools`不支持板子上的蓝牙模块，需要用修改过的源码重新编译，安装这一份才能用

使用这份源码
======
1.下载到本地
------
```
git clone https://github.com/sc-bin/hcitools.git
```

2.进去编译
------
过程中会冒出很多警告，只要能编译成功就不管了（
```
cd hcitools
make
```

3.安装到本开发板
```
make install
```