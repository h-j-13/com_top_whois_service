顶级域WHOIS探测程序
============
![](https://img.shields.io/badge/Python-2.7-blue.svg)
![](https://img.shields.io/badge/WHOIS-domain-brightgreen.svg)
![](https://img.shields.io/badge/TLD-com-red.svg)       
com 一级WHOIS数据探测程序

###  Requirement
Python v 2.7.12+
python依赖环境见```requirement.txt```        

要求数据库有相应结构          
依赖 -  ```Whois Support``` 库         
数据存放 - ```com_top_server_data``` 库          
详细库表结构见库内           

### Quick Start & Install
* Clone
clone代码到需要部署的虚拟机上
需要确保此虚拟机能正确的**访问网络**及**249数据库**

* Before run
修改 ```Setting/setting.json``` 中
```json
"whoisData": {
    ...
    "whoisTable": "domain_whois_com_top_srv_11",
    "whowasTable": "domain_whois_com_top_srv_11",
    "domainTable": "domain_whois_com_top_srv_11"
```
*并检查其他参数是否正确*

* run
```nohup python ../main.py```

* note
运行过程中会自动生成名为```running.log.*```的日志文件
自动保留最近三天，可用于Debug 或直接删除

### License
GPL

### About

@`13
HITwh-DNS lab

2017年06月27日







