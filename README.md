# WhatAV
windows pc端杀毒软件识别（需要tasklist 命令执行的结果）
也许提权或者上传其他利用程序之前，你想通过tasklist来判断目标服务器安装了什么杀毒软件，好进行针对性免杀。我从网络上收集了一些杀毒软件的名称及其进程名还有官网地址（一共104款国内外杀毒软件，344个进程名），写出python脚本方便日后查询。  
# 截图  
![截图1](./Capture/1.PNG)  
![截图2](./Capture/3.PNG)

python3 whatAV.py -f tasklist.txt