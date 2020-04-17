# 快乐二级域名分发系统
> 大部分源代码来自[原仓库](https://github.com/klsf/kldns)，目前该系统自用，不提供支持，如需使用请自行摸索或使用原代码

## 支持部署等问题请去[原仓库](https://github.com/klsf/kldns)请求帮助

## 改版本代码没有改动，改动的在[4.0分支](https://github.com/HSDComputerTeam/kldns/tree/4.0)

## 此系统有哪些特点
* 目前支持的域名解析平台有
    *  dnspod
    *  cloudxns
    *  aliyun
    *  dnscom
    *  dnsla
    *  cloudxns
    *  DnsDun
* 多用户、多域名、多平台同时存在
* 界面简单、舒适，操作简单
## 3.1.0 (20190803)
* 1、增加解析网站内容关键词检测
* 2、增加对dnsdun.com解析平台的支持
* 2、修复已知的一些问题
## 3.0.1 (20190419)
* 1、程序框架由ThinkPHP 改为Laravel 5.8
* 2、增加对cloudxns平台的支持
* 3、增加用户组功能
* 4、更新一些平台的接口

## 安装说明
* 1、程序的框架是Laravel 5.8，因此需要环境满足以下要求：
    * PHP >= 7.1.3
    * PHP OpenSSL 扩展
    * PHP PDO 扩展
    * PHP Mbstring 扩展
    * PHP Tokenizer 扩展
    * PHP XML 扩展
    * PHP Ctype 扩展
    * PHP JSON 扩展
    * PHP BCMath 扩展
* 2、环境必须支持伪静态

* Apache 伪静态配置
    * 确保 Apache 启用了 mod_rewrite 模块以支持 .htaccess 解析。
* Nginx 伪静态配置

        location / {
            try_files $uri $uri/ /index.php?$query_string;
        }

## 有问题反馈
请尽量找[原作者](https://github.com/klsf/kldns)  
（原仓库readme里面已经写了停止更新维护，能否得到支持还是要看原作者）
