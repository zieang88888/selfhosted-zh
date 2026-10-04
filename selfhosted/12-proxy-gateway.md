# 12 · 反向代理与网关

> 统一入口、自动 HTTPS、单点登录、内网穿透。自托管的"门面与门卫"。

## 反向代理 / 负载均衡

- [Nginx](https://nginx.org) — 事实标准的 Web 服务器与反向代理｜BSD-2-Clause
- [Apache HTTP Server](https://httpd.apache.org) — 老牌万能 Web 服务器｜Apache-2.0
- [Caddy](https://caddyserver.com) — 自动 HTTPS、配置极简的现代 Web 服务器｜Apache-2.0
- [Traefik](https://traefik.io) — 为 Docker/K8s 而生的自动反向代理｜MIT
- [Nginx Proxy Manager](https://nginxproxymanager.com) — 带 Web UI 的 Nginx 反代管理，新手友好｜MIT
- [HAProxy](https://www.haproxy.org) — 高性能 TCP/HTTP 负载均衡器｜GPL-2.0
- [Envoy](https://www.envoyproxy.io) — 云原生高性能边缘/服务代理｜Apache-2.0
- [Kong](https://konghq.com) — 云原生 API 网关｜Apache-2.0
- [Tyk](https://tyk.io) — 开源 API 网关与管理平台｜MPL-2.0
- [Fabio](https://fabiolb.net) — 简单的 Go 负载均衡器｜MIT
- [Skipper](https://github.com/zalando/skipper) — Zalando 出品的 HTTP 路由器/代理｜Apache-2.0
- [Pomerium](https://www.pomerium.com) — 零信任访问代理与身份感知网关｜Apache-2.0

## 单点登录 / 身份认证

- [Authelia](https://www.authelia.com) — 开源自托管认证与 SSO 门户｜Apache-2.0
- [Authentik](https://goauthentik.io) — 现代身份提供商与 SSO 平台｜MIT
- [Keycloak](https://www.keycloak.org) — 红帽出品的企业级 IAM / SSO｜Apache-2.0
- [OAuth2 Proxy](https://oauth2-proxy.github.io/oauth2-proxy/) — 反向代理旁的 OAuth 登录中间件｜MIT
- [Casdoor](https://casdoor.org) — 面向 Web/App 的零代码 IAM/SSO 平台｜Apache-2.0
- [Ory Oathkeeper](https://www.ory.sh/oathkeeper/) — 云原生身份与访问代理｜Apache-2.0

## 组网与内网穿透

- [Headscale](https://github.com/juanfont/headscale) — 自托管 Tailscale 控制端｜BSD-3-Clause
- [WireGuard](https://www.wireguard.com) — 极简高效的现代 VPN 隧道协议｜GPL-2.0
- [NetBird](https://netbird.io) — 开源 P2P 组网/防火墙管理平台｜BSD-3-Clause
- [Nebula](https://github.com/slackhq/nebula) — Slack 出品的覆盖网/网格 VPN｜MIT
- [frp](https://github.com/fatedier/frp) — 国内流行的高性能内网穿透｜Apache-2.0
- [rathole](https://github.com/rapiz1/rathole) — Rust 写的高性能 frp 替代｜MIT
- [Chisel](https://github.com/jpillora/chisel) — 通过 HTTP 隧道的 TCP/UDP 隧道｜MIT
- [bore](https://github.com/ekzhang/bore) — 轻量的 Rust 内网穿透｜MIT
- [Cloudflare Tunnel](https://www.cloudflare.com/products/tunnel/) — 把本地服务暴露到 Cloudflare 边缘｜免费/专有服务
