# SSR-Bash-Python
一个SSR多用户控制管理脚本

## 操作
### 安装
```
wget -N --no-check-certificate https://raw.githubusercontent.com/lllvcs/SSR-Bash-Python/master/install.sh && bash install.sh
```

### 卸载
```
wget -N --no-check-certificate https://raw.githubusercontent.com/lllvcs/SSR-Bash-Python/master/uninstall.sh && bash uninstall.sh
```

### 自检
```
wget -N --no-check-certificate https://raw.githubusercontent.com/lllvcs/SSR-Bash-Python/master/self-check.sh && bash self-check.sh
```
## 功能
### 支持的加密
- 1.none
- 2.aes-128-cfb
- 3.aes-256-cfb
- 4.aes-128-ctr
- 5.aes-256-ctr
- 6.aes-128-gcm
- 7.aes-256-gcm
- 8.camellia-128-cfb
- 9.camellia-256-cfb
- 10.bf-cfb
- 11.des-cfb
- 12.idea-cfb
- 13.seed-cfb
- 14.rc4-md5
- 15.chacha20
- 16.chacha20-ietf
- 17.chacha20-ietf-poly1305
- 18.xchacha20-ietf-poly1305
- 19.salsa20

### 支持的协议
- 1.origin
- 2.auth_sha1_v4
- 3.auth_aes128_md5
- 4.auth_aes128_sha1
- 5.verify_deflate
- 6.auth_chain_a
- 7.auth_chain_b
- 8.auth_chain_c
- 9.auth_chain_d
- 10.auth_chain_e
- 11.auth_chain_f

### 支持的混淆
- 1.plain
- 2.http_simple
- 3.http_post
- 4.random_head
- 5.tls1.2_ticket_auth
- 6.tls1.2_ticket_fastauth

## 其他
### *Debian 9 设置自启动可能会报错，请进行如下设置*
```
vim /etc/fstab
tmpfs /run tmpfs nosuid,noexec,size=20M,nr_inodes=4096 0 0
```
