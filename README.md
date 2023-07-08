# bili-dl-merge
一个音频和视频合并脚本，用于哔哩哔哩安卓端的缓存视频  
需要安装termux  [termux下载](https://f-droid.org/zh_Hans/packages/com.termux/)  
# 使用方法  
配置termux环境  

    pkg install ffmpeg dialog aria2 which -y

下载bili-dl-merge  

    aria2c https://raw.githubusercontent.com/licyk/bili-dl-merge/main/bili-dl-merge.sh &&chmod +x bili-dl-merge.sh

启动bili-dl-merge  

    ./bili-dl-merge.sh

如果配置termux环境失败，可使用科学上网，或者输入  

termux-change-repo

用方向键，回车键选择，空格键勾选
