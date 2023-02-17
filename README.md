# hk-SADPTools-mac-Chinese
海康威视 网络设备发现SADPTools macOS 中文版

1. 进入海康威视英文站：`https://www.hikvision.com/en/support/tools/hitools/cl3620e9fb51dfac31/` 下载macos版本
2. 安装后发现没有设置语言的选项（中文站下载的win版的可以修改语言）。所以猜测mac版应该也有国际化的内容。
    ![](https://typora-files.oss-cn-beijing.aliyuncs.com/file/16766122247694.jpg)

3. 进入`访达/应用程序/SADPTool.app/Contents/MacOS/`目录找到`Setup.xml`文件，把`Translator`的`Value`改为`1`
    ![](https://typora-files.oss-cn-beijing.aliyuncs.com/file/16766123328278.jpg)
4. 正常打开软件OK~
    ![](https://typora-files.oss-cn-beijing.aliyuncs.com/file/16766124231296.jpg)
