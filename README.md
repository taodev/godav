# godav

A secure WebDAV server with encrypted storage and cloud integration capabilities.

## Features

- Standards-compliant WebDAV implementation using golang.org/x/net/webdav
- Secure user authentication with username/password protection
- HTTPS encryption for all communications
- AES-256-GCM encryption for file storage
- Remote cloud storage mounting (Aliyun Drive, Baidu Netdisk)
- Encrypted file storage for both local and cloud storage

## Installation

```bash
go install github.com/taodev/godav@latest
```

## Configuration

1. Create a configuration file (config.yaml)
2. Configure SSL certificates
3. Set up user accounts and encryption keys
4. Configure cloud storage connections

## Usage

```bash
godav --config config.yaml
```

## Documentation

Full documentation is available in the `docs` directory.

## Language

- [English](README.md)
- [中文](README_zh.md)