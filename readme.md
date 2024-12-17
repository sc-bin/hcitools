说明
======
bluez自带的`hcitools`工具不支持一些蓝牙模块，这份源码增加了一些蓝牙模块的支持

使用
======
1.clone
------
```
git clone https://github.com/sc-bin/hcitools.git
cd hcitools
```

2.编译
------
过程中会冒出很多警告，只要能编译成功就不管了（
```
make
```

3.安装到本机
```
make install
```