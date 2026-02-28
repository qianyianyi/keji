# 科技工具箱

一个功能强大的服务器综合管理脚本，提供多种服务器管理功能。

## 🚀 功能特色

### 🔧 核心管理
- **Nginx 管理** - Web服务器配置和管理
- **PHP 管理** - PHP环境配置和优化
- **Docker 管理** - 容器化应用管理
- **MySQL 管理** - 数据库管理（基于Docker）

### 📁 文件服务
- **Cloudreve 网盘** - 自建云盘服务
- **图床服务** - 图片托管和管理
- **现代图床** - 新版图床服务
- **备份功能** - 数据备份和恢复

### 🔒 安全防护
- **SSH 防护** - Fail2ban配置
- **流量控制** - 网络流量管理
- **SSL 证书** - HTTPS证书下载

### 📊 监控工具
- **哪吒监控** - 综合服务器监控
- **个人导航站** - 个性化导航页面

### ⚡ 性能优化
- **BBR 加速** - 网络性能优化
- **系统重装** - DD系统功能

## 🛠️ 使用方法

### 快速开始
```bash
# 下载并运行脚本
curl -sL https://raw.githubusercontent.com/qianyianyi/server-management-script/main/manage.sh | bash

# 或者克隆仓库后运行
git clone https://github.com/qianyianyi/server-management-script.git
cd server-management-script
chmod +x manage.sh
./manage.sh
```

### 快捷命令
脚本会自动添加 `keji` 快捷命令到你的 `.bashrc`，重启终端后即可使用：
```bash
keji
```

## 📋 功能菜单

| 编号 | 功能 | 描述 |
|------|------|------|
| 1 | Nginx管理 | Web服务器配置 |
| 2 | PHP管理 | PHP环境管理 |
| 3 | Docker管理 | 容器管理 |
| 4 | MySQL管理 | 数据库管理 |
| 5 | SSL证书 | HTTPS证书 |
| 6 | 备份功能 | 数据备份 |
| 8 | App管理 | 应用管理 |
| 9 | BBR加速 | 网络优化 |
| 11 | Cloudreve网盘 | 自建云盘 |
| 12 | 哪吒监控 | 服务器监控 |
| 13 | 个人导航站 | 导航页面 |
| 14 | 图床 | 图片托管 |
| 15 | 现代图床 | 新版图床 |
| 16 | 现代图床Docker版 | 容器化图床 |
| 41 | SSH防护 | 安全防护 |
| 42 | 流量控制 | 网络管理 |
| 99 | Nginx整合测试版 | 测试功能 |
| 101 | DD系统 | 系统重装 |
| 209 | BBR+队列测试版 | 网络优化测试 |

## 🔧 依赖要求

- **curl** - 自动检测并安装
- **bash** - 脚本解释器
- 相应包管理器 (apt-get/yum)

## 📝 作者信息

- **作者**: 一点科技
- **YouTube**: [https://www.youtube.com/@1keji_net](https://www.youtube.com/@1keji_net)
- **Telegram**: [https://t.me/tg_1keji](https://t.me/tg_1keji)
- **网站**: [https://1keji.net](https://1keji.net)

## ⚠️ 注意事项

1. 请在测试环境中先试用
2. 部分功能需要root权限
3. 确保系统支持相应的包管理器
4. 备份重要数据后再进行操作

## 📄 许可证

MIT License
