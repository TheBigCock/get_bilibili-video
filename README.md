# get_bilibili-video
爬取bilibili视频


##提示：
在运行视频与音频合并的程序时，可能会出现ffmpeg指令无效的提示，此时，你需要从官网中下载对应的ffmpeg并在配置相应的系统环境
下载地址： https://github.com/BtbN/FFmpeg-Builds/releases   选择第一个即可
###系统环境的配置：
你需要在 此电脑--属性--高级系统设置--环境变量中添加系统环境变量:  变量名 FFMPEG_HOME  变量值：你按照ffmpeg的绝对路径。
接着，在系统变量的path中添加%FFMPEG_HOME%以及%FFMPEG_HOME%\bin（直接添加时这两个即可）
配置好系统环境之后，你可以才cmd中输入ffmpeg -version 对安装进行验证，如果输出对应的版本信息，则说明按照成功。

安装成功之后，再次运行程序即可，如果安装成功之后运行程序仍有错误，此时你关闭编译器重启即可。
