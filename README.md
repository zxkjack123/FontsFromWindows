# FontsFromWindows

常用的中文字体

字体从Windows 10当中提取。可用于Mac/Linux安装。

## Mac安装步骤如下：

**若安装过同名的字体，请删除并清空缓存后再行安装。**

* 首先下载好所需的字体
* 在mac使用快捷键`command+space空格`，搜索并打开字体册
* 点击菜单`文件->添加字体`，选择所下载的字体文件，打开即可自动安装
* 安装完字体后，相关应用需要重启才能找到新安装的字体

## Ubuntu安装步骤如下：

**Ubuntu安装方法见[参考](https://blog.csdn.net/zfy_220/article/details/125994811)**

* 拷贝字体到/usr/share/fonts/truetype/windows-font 目录下
* 安装字体：
```
#更改文件夹权限
sudo chmod -R 777  /usr/share/fonts/truetype/windows-font
cd /usr/share/fonts/truetype/windows-font
 
# 如果提示 mkfontscale: command not found
# 在Ubuntu下运行如下命令
# sudo apt-get install ttf-mscorefonts-installer
# 在cent os下运行如下命令
# yum install mkfontscale 
sudo mkfontscale
sudo mkfontdir
 
# 如果提示 fc-cache: command not found
# 在Ubuntu下运行如下命令
# sudo apt-get install fontconfig
# 在cent os下运行如下命令
# yum install fontconfig
sudo fc-cache -fv
```

**sudo mkfontscale 安装时有个细节需注意，会弹框让选择OK，需要先按Tab建选中OK，在Enter就可以了**

* 重启系统：sudo reboot

# 字体下载

| 字体网盘链接 | 网盘提取码 | 直接下载 |
| :------: | :------: | :------: |
| [仿宋](https://pan.baidu.com/s/1U7CUmTcB1Fd0Hueiek9A0Q) | uuph | [点击下载](https://github.com/Orient-ZY/FontsFromWindows/raw/master/fonts/%E4%BB%BF%E5%AE%8B_%E5%B8%B8%E8%A7%84.ttf) |
| [黑体](https://pan.baidu.com/s/12roGUveIM9n5yCxKziQmrQ) | 87et | [点击下载](https://github.com/Orient-ZY/FontsFromWindows/raw/master/fonts/%E9%BB%91%E4%BD%93_%E5%B8%B8%E8%A7%84.ttf) |
| [楷体](https://pan.baidu.com/s/1B7RumiYUsw30EEMJn70Kwg) | dfjk | [点击下载](https://github.com/Orient-ZY/FontsFromWindows/raw/master/fonts/%E6%A5%B7%E4%BD%93_%E5%B8%B8%E8%A7%84.ttf) |
| [宋体](https://pan.baidu.com/s/1AslV3-3hytlKsv_EBKcqPA) | sv3j | [点击下载](https://github.com/Orient-ZY/FontsFromWindows/raw/master/fonts/%E5%AE%8B%E4%BD%93_%E5%B8%B8%E8%A7%84.ttc) |
| [楷体_GB2312](https://pan.baidu.com/s/1IDDVuOBLcNlNlWbNOFldWg) | zhbx | [点击下载](https://github.com/Orient-ZY/FontsFromWindows/raw/master/fonts/Mac%E6%A5%B7%E4%BD%93GB2312.ttf) |
| [仿宋_GB2312](https://pan.baidu.com/s/1U9X7JPQcfXv7pFZ-rps_PQ) | eq9t | [点击下载](https://github.com/Orient-ZY/FontsFromWindows/raw/master/fonts/Mac%E4%BB%BF%E5%AE%8BGB2312.ttf) |
| [方正小标宋简体](https://pan.baidu.com/s/1NX2uBqJWHTdVAkbFqiSO7A) | t47a | [点击下载](https://github.com/Orient-ZY/FontsFromWindows/raw/master/fonts/Mac%E6%96%B9%E6%AD%A3%E5%B0%8F%E6%A0%87%E5%AE%8B%E7%AE%80%E4%BD%93.ttf) |
| [方正小标宋GBK](https://pan.baidu.com/s/1tE6fEARIhdt6IBVhkcqhHQ) | 1xfb | [点击下载](https://github.com/Orient-ZY/FontsFromWindows/raw/master/fonts/Mac%E6%96%B9%E6%AD%A3%E5%B0%8F%E6%A0%87%E5%AE%8BGBK.ttf) |
| [华文中宋](https://pan.baidu.com/s/16lm9NS1WS85xA25v-EifOQ) | gp9v | [点击下载](https://github.com/Orient-ZY/FontsFromWindows/raw/master/fonts/%E5%8D%8E%E6%96%87%E4%B8%AD%E5%AE%8B.TTF) |
| [华文宋体](https://pan.baidu.com/s/1iE4ncP8_YgmhjXk7BWX8uA) | q37f | [点击下载](https://github.com/Orient-ZY/FontsFromWindows/raw/master/fonts/%E5%8D%8E%E6%96%87%E5%AE%8B%E4%BD%93.TTF) |
| [华文楷体](https://pan.baidu.com/s/1d7bMDbvi4P4CIBgrvlZTMw) | 4fgn | [点击下载](https://github.com/Orient-ZY/FontsFromWindows/raw/master/fonts/%E5%8D%8E%E6%96%87%E6%A5%B7%E4%BD%93.TTF) |
| [华文行楷](https://pan.baidu.com/s/1ya3M6gVBh1lmrrwjGOlXZg) | scs5 | [点击下载](https://github.com/Orient-ZY/FontsFromWindows/raw/master/fonts/%E5%8D%8E%E6%96%87%E8%A1%8C%E6%A5%B7.TTF) |
| [华文仿宋](https://pan.baidu.com/s/1OwucFc--rVluVOWqD7vrrA) | jehn | [点击下载](https://github.com/Orient-ZY/FontsFromWindows/raw/master/fonts/%E5%8D%8E%E6%96%87%E4%BB%BF%E5%AE%8B.TTF) |
