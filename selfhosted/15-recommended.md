# 15 · 新手第一次自托管，装这些就够了

> 别一上来就想全家桶。下面 12 个是"装完立刻有获得感"的入门首选，每个配一句理由。

1. [Docker](https://www.docker.com) / [Docker Compose](https://github.com/docker/compose) — 一切自托管的地基，90% 服务都用它跑，别用裸金属折腾。
2. [Nginx Proxy Manager](https://nginxproxymanager.com) — 给所有服务套统一入口 + 自动 HTTPS，图形界面点点点，新手友好。
3. [Uptime Kuma](https://github.com/louislam/uptime-kuma) — 第一个就该装的"健康管家"，哪个服务挂了立刻推送提醒。
4. [Nextcloud](https://nextcloud.com) — 你的私有网盘 + 日历 + 联系人 + 在线文档，替代 Google Drive 全家桶。
5. [Immich](https://immich.app) — 手机相册自动备份，体验最接近 Google Photos 的自托管方案。
6. [Jellyfin](https://jellyfin.org) — 把你硬盘里的电影剧集变成"自己的 Netflix"，多端秒开。
7. [Vaultwarden](https://github.com/dani-garcia/vaultwarden) — 自托管密码库，告别 1Password 订阅，Bitwarden 客户端随便用。
8. [AdGuard Home](https://adguard.com) 或 [Pi-hole](https://pi-hole.net) — 全屋去广告/DNS 过滤，路由器一设全家受益。
9. [Homepage](https://gethomepage.dev) — 浏览器打开就是你所有服务的导航首页，成就感拉满。
10. [Pingvin Share](https://github.com/stonith404/pingvin-share) — 简单好用的临时文件分享，朋友传文件不求人。
11. [Gitea](https://about.gitea.com) — 自己的私有 GitHub，代码、文档、笔记都能管起来。
12. [Restic](https://restic.net) — 最后装它，把上面所有重要数据定期加密备份——没备份等于白搭。

> 顺序建议：先 1（Docker）→ 2（反代）→ 随便挑一个业务（4/5/6）→ 再补 3（监控）和 12（备份）。
