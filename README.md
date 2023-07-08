# bili-dl-merge
一个音频和视频合并脚本，用于哔哩哔哩安卓端的缓存视频  
需要安装termux  [termux下载](https://f-droid.org/zh_Hans/packages/com.termux/)  
# 使用方法  
1、配置termux环境  

    pkg install ffmpeg dialog aria2 which -y

2、下载bili-dl-merge  

    aria2c https://raw.githubusercontent.com/licyk/bili-dl-merge/main/bili-dl-merge.sh &&chmod +x bili-dl-merge.sh

如果下载失败可以使用这条命令  

    aria2c https://ghproxy.com/https://raw.githubusercontent.com/licyk/bili-dl-merge/main/bili-dl-merge.sh &&chmod +x bili-dl-merge.sh

3、启动bili-dl-merge  

    ./bili-dl-merge.sh

注:如果配置termux环境失败，可使用科学上网，或者输入  

    termux-change-repo
    
空格键勾选"Mirror group"，回车，然后用方向键选择"Mirrors in China"，空格键勾选，再回车，等待命令执行完成后再重新配置termux环境
