# 11. ZeroTworu/anet

**URL:** [https://github.com/ZeroTworu/anet](https://github.com/ZeroTworu/anet)
**Stars:** 363
**Language:** Rust
**Description:** 一个简单的Rust VPN客户端/服务器。

---
## Detailed Description

ANet — 这是一款旨在为亲密用户群体构建私密、安全信息空间的工具。它致力于在传统通信方式受阻时，搭建起数字桥梁。ANet并非一项服务，而是一种连接彼此信任用户的技术。

核心特性：
*   **隐私性：** 采用ChaCha20Poly1305 / X25519实现完整的端到端加密。
*   **稳定性：** 在高丢包率和不稳定连接的网络环境中也能稳定运行。
*   **伪装性：** 传输层流量与随机噪声无异（高熵UDP流），难以被识别。
*   **跨平台：** 提供适用于Linux、Windows和Android的客户端。

## Tech Stack

主要编程语言：Rust；协议：ASTP (ANet Secure Transport Protocol)；加密算法：ChaCha20Poly1305 / X25519；模块：anet-server, anet-client-cli, anet-client-gui, anet-mobile, anet-common, anet-keygen；构建工具：cargo。

## Use Cases

1. 组织私人、安全的通信空间；2. 在网络受限或审查环境下建立连接；3. 保护个人隐私和数据安全；4. 提供跨平台VPN解决方案。

## Screenshot

![Screenshot](./images/11_ZeroTworu_anet.webp)
