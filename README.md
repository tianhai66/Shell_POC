# Shell_POC
linux下的各种shell脚本
**所提供的工具仅供于个人学习和研究， 严禁传播者利用此工具进行非法测试。**


CVE-2021-43798_Grafana未授权任意文件读取漏洞检测POC  
POC中罗列了部分插件URL，来提高检测效率，可自行调整。

本地创建URL.txt，写入url，端口后不带反斜杠/
示例：http://192.168.0.175:3000

使用方法：
chmod +x CVE-2021-43798.sh  
./CVE-2021-43798.sh URL.txt

![图片](https://user-images.githubusercontent.com/40051714/145383195-0b6a68a9-12fb-40b7-a23f-3cbd5a0e9a57.png)


