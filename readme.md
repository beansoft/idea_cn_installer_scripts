## IDEA Community 2023.1 Chinese Installer Edition Patch Files

IDEA 社区版 2023.1 中文安装包补丁源码说明

https://www.jetbrains.com.cn/idea/download/other.html

下载2023.1版本的源码 2023.1 - Sources Archive (zip)

然后用`patch`下面的文件覆盖到源码中并设置文件编码:

GBK
build/conf/nsis/desktop.ini

UTF-8
build/conf/nsis/idea.nsi

UTF-8
build/conf/nsis/idea_cn.nsi

GBK
build/conf/nsis/UninstallOldVersions.ini

UTF-8
build/src/org/jetbrains/intellij/build/IdeaCommunityProperties.kt

新建目录

build/bundle_plugins

将最新版的中文语言包下载后放入此目录 https://plugins.jetbrains.com/plugin/13710-chinese-simplified-language-pack----/versions/stable/313038

然后按照原始仓库中的说明运行脚本打包即可（Mac包只能用Mac系统打）。 Windows 如果提示找不到7z， 从7zip官网下载一个7z命令行版本改为7z.exe放进系统PATH路径里面就行了。

## 安装包下载地址
链接: https://pan.baidu.com/s/1f65r32-i2C2OdQDDzLcwjw?pwd=uqfk