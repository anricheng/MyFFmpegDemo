#build-ios-ffmpeg.sh
1. 使用该脚本有一个限制条件，就是该脚本要放在ffmpeg所在的目录，即与ffmpeg目录并列。
2. ffmpeg 源码目录名必须是ffmpeg，不能是ffmpeg...,例如：ffmpeg-4.0.2这样是不行的。
3. 如果你之前编译过ffmpeg，那么在 ffmpeg 目录下就会有config.h这个文件，在编译时会报`Out of tree builds are impossible with config.h in source dir.`错误，解决办法是将ffmpeg目录中用config.h文件删除掉。

