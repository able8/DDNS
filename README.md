# DDNS-noip

针对 Linux 操作系统的动态域名解析（Dynamic DNS）方案
 

## 快速安装

1. 下载脚本
    
```
  wget https://raw.githubusercontent.com/able8/DDNS/master/noipddns.sh
  chmod +x noipddns.sh
```


2. 替换配置信息
     * 修改noipddns.sh脚本里的 noip 账号 密码 和 域名


3. 添加contab定时更新任务

```
    */5 * * * * /home/xxx/noipddns.sh
```

