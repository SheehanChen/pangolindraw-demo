# pangolindraw-demo

>以下模型均下载自3D warehouse网站。


pangolin 是Opengl的一个轻量级封装，SLAM中常用它来进行可视化操作，这次为了简图需要绘制三维线框模型来解决导入普通模型导致的加载速度过慢的问题，我通过解析导出的obj文件通过自动生成代码的脚本设计了以下线框模型，下面是这个我们绘制的图像的效果。
![img](https://github.com/mephisto-c/pangolindraw-demo/blob/master/Screenshot%20from%202019-08-13%2008-41-15.png)

使用的开发工具是spyder
脚本链接：



使用 OpenGL 绘制三维线框所需要的程序包 (demo).

## 编译

```bash
mkdir build && cd build
cmake ..
make
```

注意过程中是否有错误产生。

## 运行

生成的可执行文件将会被放置在`./bin`文件夹下。也可以直接运行脚本：

```bash
sh ./runDemo.sh
```

来运行。
