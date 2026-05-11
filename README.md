# ⛓ fabric-web-demo — Hyperledger Fabric 演示项目

<p align="center">
  <img src="https://img.shields.io/badge/Go-1.x-00ADD8?logo=go&logoColor=white" />
  <img src="https://img.shields.io/badge/Hyperledger-Fabric-00B5E2?logo=hyperledger&logoColor=white" />
  <img src="https://img.shields.io/badge/license-MIT-green" />
</p>

## 📖 项目简介

基于 Hyperledger Fabric 的联盟链 Web 演示项目。展示 Fabric 网络搭建、链码（Chaincode）开发部署与 Web 前端调用全流程。

## ✨ 核心内容

- ⛓ **Fabric 网络搭建** — 多组织联盟链网络配置
- 📜 **链码开发** — Go 语言智能合约实现
- 🌐 **Web 交互** — 前端调用链码读写账本
- 🔐 **身份管理** — CA 证书与 MSP 配置

## 🏗 技术栈

| 分类 | 技术 |
|------|------|
| 区块链 | Hyperledger Fabric |
| 链码语言 | Go |
| Web 后端 | Go / Node.js |
| 前端 | HTML / JavaScript |

## 🚀 快速启动

```bash
# 启动 Fabric 网络
cd network
./start.sh

# 部署链码
./deployChaincode.sh

# 启动 Web 应用
cd web-app
go run main.go
```

## ⚠️ 注意事项

- 需要 Docker 和 Docker Compose 环境
- Fabric 二进制文件需提前下载
- 开发环境建议 8GB+ 内存

## 📄 License

MIT
