# RuoYI 4.2 (Shiro 1.4.1) Shiro-721漏洞复现环境

用于在RuoYI上复现Shiro-721漏洞(CVE-2019-12422)。

提示：本服务存在**严重漏洞**，仅用于漏洞复现用途，请勿用于生产环境。

## 启动
`docker-compose up -d`

## 版本
+ JDK 1.8 (8u65)
+ MySQL 5.7
+ Maven 3.0
+ Base Ubuntu:22.04

## 配置参数
+ apt-get: USTC mirrors
+ mvn: Aliyun mirrors
+ MySQL字符集: utf8/utf8_unicode_ci

## 服务信息
+ HTTP: 8080
+ 默认用户: admin/admin123
