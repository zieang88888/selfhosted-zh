# 14 · 备份与恢复

> "没备份的服务不算自托管"。增量、加密、异地、可恢复。替代商业备份盘。

## 通用加密增量备份

- [Restic](https://restic.net) — 现代、加密、去重的命令行备份工具，目标后端丰富｜BSD-2-Clause
- [BorgBackup](https://www.borgbackup.org) — 高效去重、加密的备份程序｜BSD-3-Clause
- [Kopia](https://kopia.io) — 加密、压缩、去重的备份工具｜Apache-2.0
- [Duplicati](https://www.duplicati.com) — 带 Web UI 的加密增量备份客户端｜MIT
- [Duplicity](https://duplicity.us) — 加密的增量备份（基于 librsync）｜GPL-2.0
- [Duplicacy](https://duplicacy.com) — 跨平台去重备份工具（部分商业）｜商业
- [resticprofile](https://github.com/creativeprojects/resticprofile) — Restic 的调度/配置管理器｜MIT
- [Borgmatic](https://torsion.org/borgmatic/) — BorgBackup 的简单配置与自动调度包装器｜GPL-3.0
- [Vorta](https://vorta.borgbase.com) — BorgBackup 的跨图形界面客户端｜GPL-3.0
- [BackupPC](https://backuppc.github.io/backuppc/) — 基于 rsync/tar 的企业级 pull 备份服务器｜GPL-3.0

## 企业 / 网络备份

- [UrBackup](https://www.urbackup.org) — 开源镜像+文件备份，服务端+客户端｜AGPL-3.0
- [Bacula](https://www.bacula.org) — 企业级网络备份解决方案｜AGPL-3.0
- [Bareos](https://www.bareos.com) — Bacula 的社区分叉备份方案｜AGPL-3.0
- [Amanda](https://www.amanda.org) — 成熟的开源自动网络备份｜BSD-3-Clause
- [Proxmox Backup Server](https://www.proxmox.com) — 专为 Proxmox VE 设计的虚拟机备份｜GPL-3.0

## 系统 / 文件快照

- [Timeshift](https://github.com/linuxmint/timeshift) — 系统快照与还原（类 Windows 还原点）｜GPL-3.0
- [BackInTime](https://backintime.readthedocs.org) — Linux 简单的定时快照备份｜GPL-2.0
- [Déjà Dup](https://wiki.gnome.org/Apps/DejaDup) — GNOME 官方简易备份工具｜GPL-3.0
- [rsnapshot](https://www.rsnapshot.org) — 基于 rsync 的增量快照备份｜GPL-2.0
- [LuckyBackup](https://luckybackup.sourceforge.net) — Qt 写的备份/同步工具｜GPL-3.0
- [Syncthing](https://syncthing.net) — 设备间双向同步，可做近实时"备份"｜MPL-2.0
- [rclone](https://rclone.org) — 命令行把数据搬到任意云存储做异地备份｜MIT
