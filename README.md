# 快乐二级域名分发系统 （kldns v3.1.0）

## 有哪些特点
* 目前支持的域名解析平台有
    *  dnspod（腾讯云）
    *  aliyun（阿里云）
    *  dnscom
    *  dnsla
    *  cloudxns
    *  DnsDun
* 多用户、多域名、多平台同时存在
* 界面简单、舒适，操作简单

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

## 更新日志
[点此此处](https://github.com/HSDComputerTeam/kldns/blob/3.0/CHANGELONG.md)

## 有问题反馈
1、如果你需要程序支持其他域名解析平台，且该平台有api接口，可以联系我，我尽量添加！
2、在使用中有任何问题，欢迎反馈给我，可以用以下联系方式跟我交流

> fork from [https://github.com/klsf/kldns](https://github.com/klsf/kldns)

> 原作者：

> Github:https://github.com/klsf/kldns

> 邮件(815856515#qq.com, 把#换成@)

> QQ: 815856515

> QQ交流群：[383286818](http://shang.qq.com/wpa/qunwpa?idkey=5c50f31eb84481f05bbbeca6a0759a2e9763118f04dce5c6ca2e23652cb2a58b")
