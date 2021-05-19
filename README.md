权衡工具和编程，是最高效的渗透测试方式

我将从以下几个方面对常用渗透测试工具全部用python复现

第1章渗透测试框
1 POC脚本
2 EXP脚本

第2章 信息搜集
被动信息搜集
1 DNS解析
2 子域名挖掘
3 邮件爬取
主动信息搜集
1 基于ICMP的主机发现
2 基于TCP、UDP的主机发现
3 基于ARP的主机发现
4 端口探测
5 服务识别
6 系统识别
7 敏感目录探测
网络空间搜索引擎
1 常见搜索引擎平台
2 搜索引擎语法
3 搜索引擎API的使用

第3章 漏洞检测与防御
未授权访问漏洞
Redis未授权访问漏洞
1 漏洞利用
2 检测方法
外部实体注入漏洞
1 检测方法
SQL盲注漏洞
1 基于布尔型SQL盲注检测
2 基于时间型SQL盲注检测
SQLMap的Tamper脚本
1 Tamper脚本的编写（一）
2 Tamper脚本的编写（二）
服务器端请求伪造漏洞
1 检测方法
2 网络代理

第4章 数据加密
1 Base64编/解码
2 DES加解密
3 AES加解密
4 MD5加密

第5章 身份认证
1 社会工程学密码字典的生成
2 后台弱口令脚本
3 SSH口令脚本
4 FTP口令脚本

第6章 模糊测试
1 绕过安全狗
2 模糊测试结合WebShell
3 XSS模糊测试工具XSStrike
4 Sulley模糊测试框架

第7章 流量分析
1 流量嗅探
2 ARP毒化
3 DoS
3.1 数据链路层DoS
3.2 网络层DoS
3.3 传输层DoS
3.4 应用层DoS

第8章 Python免杀技术
1 生成shellcode
2 shellcode的加载与执行
3 常见的免杀方式

第9章 远程控制工具
1 被控端的编写
2 主控端的编写
3 远程控制工具的使用
4 Cobalt Strike的使用及拓展
