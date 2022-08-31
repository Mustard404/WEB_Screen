## WEB_SCREEN   
    
### 功能    
-   区分IPv4、IPv6资产，并能根据端口信息进行URL拼接；     
-   获取WEB Title；      
-   对IP、端口进行拼接，并尝试Http及Https请求截图；      
### 使用    
####    环境准备    
1.根据本地环境的chrome版本和操作系统下载相关驱动。    
https://registry.npmmirror.com/binary.html?path=chromedriver/       
-   Windows系统下载完成后，按照目录添加环境变量。参考（https://blog.csdn.net/u011202097/article/details/122168656）； 
-   Linux可以直接复制到/usr/local/bin/目录下；  
2.安装相关依赖，pip3 install requirements.txt；   
####    使用
1.打开target.xlsx，并填好id、IP、PORT几项信息；   
2.执行python3 main.py运行程序；
3.URL、Title信息会更新至表格内，Web截图保存到web_screen目录下；   