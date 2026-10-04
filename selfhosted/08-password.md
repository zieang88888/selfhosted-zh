# 08 · 密码管理与密钥保管

> 把密码、密钥从浏览器自带和商业密码库里拿回来。替代 1Password / LastPass。

## 密码管理器（自托管服务端）

- [Vaultwarden](https://github.com/dani-garcia/vaultwarden) — Bitwarden 兼容的轻量第三方服务端，Rust 写的，自托管首选｜AGPL-3.0
- [Bitwarden](https://bitwarden.com) — 流行的跨平台密码管理器，官方提供自托管方案｜GPL-3.0
- [KeePassXC](https://keepassxc.org) — 跨平台开源 KeePass 桌面客户端｜GPL-3.0
- [KeePass](https://keepass.info) — Windows 老牌密码保险箱，本地数据库｜GPL
- [KeeWeb](https://keeweb.info) — 网页/桌面都能用的 KeePass 兼容客户端｜MIT
- [Padloc](https://padloc.app) — 现代、简洁的团队密码管理器，可自托管｜GPL-3.0
- [Teampass](https://www.teampass.net) — 面向团队的密码与敏感信息管理｜GPL-3.0
- [Passit](https://passit.io) — 自托管、端到端加密的密码管理器｜AGPL-3.0
- [Buttercup](https://buttercup.pw) — 跨平台密码库，本地/云同步｜GPL-3.0
- [pass (标准 Unix 密码管理器)](https://www.passwordstore.org) — GPG 加密的命令行密码管理｜GPL-2.0
- [Psono](https://psono.com) — 团队级自托管密码管理器，共享文件夹｜GPL-3.0
- [Passbolt](https://www.passbolt.com) — 面向团队的开源密码管理器，主打共享密码｜AGPL-3.0
- [Padlock](https://padlock.io) — 跨平台、可自建同步的轻量密码保险箱｜GPL-3.0

## 开发者 / 运维密钥管理

- [HashiCorp Vault](https://www.vaultproject.io) — 业界标准的密钥/证书/动态凭据管理｜MPL-2.0
- [Infisical](https://infisical.com) — 开源端到端加密的应用密钥与配置管理｜MIT
- [Sealed Secrets](https://github.com/bitnami-labs/sealed-secrets) — Kubernetes 中可安全提交到 Git 的加密 Secret｜Apache-2.0
- [External Secrets Operator](https://external-secrets.io) — 把外部密钥源同步进 Kubernetes Secret｜Apache-2.0
- [OpenBao](https://openbao.org) — Linux 基金会托管的开源秘密管理（Vault 的社区分叉）｜MPL-2.0
- [sops](https://github.com/getsops/sops) — 对配置文件/Secret 进行加密的 CLI 工具｜MPL-2.0
- [Chamber](https://github.com/segmentio/chamber) — 基于云 KMS 的环境变量/Secret 管理｜MIT
