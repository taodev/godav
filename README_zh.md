# godav

一个安全的WebDAV服务器，具备加密存储和云集成功能。

## 功能特点

- 基于golang.org/x/net/webdav的标准WebDAV实现
- 安全的用户名/密码用户认证
- 所有通信采用HTTPS加密
- AES-256-GCM文件存储加密
- 支持远程云存储挂载（阿里云盘、百度网盘）
- 本地和云存储中的文件均采用加密形式存储

## 安装

```bash
go install github.com/taodev/godav@latest
```

## 配置

1. 创建配置文件（config.yaml）
2. 配置SSL证书
3. 设置用户账户和加密密钥
4. 配置云存储连接

## 使用方法

```bash
godav --config config.yaml
```

## 文档

完整文档位于`docs`目录中。

## 语言

- [English](README.md)
- [中文](README_zh.md)