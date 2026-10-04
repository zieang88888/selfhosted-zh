# 06 · 监控与告警

> 指标监控、在线状态页、日志聚合、告警。替代 Datadog / New Relic / Statuspage。

## 指标与监控

- [Prometheus](https://prometheus.io) — 云原生时代事实标准的指标监控与告警系统｜Apache-2.0
- [Grafana](https://grafana.com) — 通用可视化仪表盘，接几十种数据源｜AGPL-3.0
- [Alertmanager](https://prometheus.io/docs/alerting/latest/alertmanager/) — Prometheus 的告警路由与通知组件｜Apache-2.0
- [VictoriaMetrics](https://victoriametrics.com) — 高性能、低成本的时序数据库与监控方案｜Apache-2.0
- [Thanos](https://thanos.io) — 为 Prometheus 提供长期存储与全局查询｜Apache-2.0
- [InfluxDB](https://www.influxdata.com) — 流行的时序数据库（核心开源）｜MIT
- [node_exporter](https://github.com/prometheus/node_exporter) — 采集 *nix 主机硬件/系统指标｜Apache-2.0
- [blackbox_exporter](https://github.com/prometheus/blackbox_exporter) — 通过 HTTP/TCP/ICMP 探测外部服务｜Apache-2.0
- [Netdata](https://www.netdata.cloud) — 一键安装的实时性能监控，开箱即有漂亮图表｜GPL-3.0
- [Glances](https://nicolargo.github.io/glances/) — 跨系统资源监视工具，Web/终端面板｜LGPL-3.0
- [Cockpit](https://cockpit-project.org) — 通过浏览器管理 Linux 服务器的 Web 控制台｜LGPL-2.1
- [Beszel](https://github.com/henrygd/beszel) — 轻量优雅的多主机系统状态监控面板｜MIT
- [Zabbix](https://www.zabbix.com) — 老牌企业级开源监控告警｜GPL-2.0
- [Nagios](https://www.nagios.org) — 历史悠久的主机/服务监控（核心开源）｜GPL-2.0
- [Icinga 2](https://icinga.com) — 企业级开源监控系统｜GPL-2.0
- [Checkmk](https://checkmk.com) — 开箱即用的 IT 监控，覆盖主机/云/应用｜GPL-2.0
- [Naemon](https://www.naemon.org) — Nagios 风格的监控守护进程｜GPL-2.0
- [Sensu Go](https://sensu.io) — 云原生可观察性与监控事件路由｜MIT
- [Pandora FMS](https://pandorafms.com) — 企业级可扩展监控解决方案｜GPL-2.0

## 在线状态页 / 站点监控

- [Uptime Kuma](https://github.com/louislam/uptime-kuma) — 自托管的"无宕机"状态页，秒级监控（可替代 UptimeRobot）｜MIT
- [StatPing](https://github.com/statping/statping) — 状态页与监控聚合面板｜GPL-3.0
- [Upptime](https://github.com/upptime/upptime) — 基于 GitHub Actions 的零成本状态页｜MIT
- [Cachet](https://cachethq.io) — 漂亮的开源状态页系统｜BSD-3-Clause
- [OneUptime](https://oneuptime.com) — 开源全栈可观察性，含状态页与告警｜AGPL-3.0

## 日志聚合

- [Grafana Loki](https://grafana.com/oss/loki/) — 受 Prometheus 启发的标签化日志聚合｜AGPL-3.0
- [Promtail](https://grafana.com/docs/loki/latest/send-data/promtail/) — Loki 的日志采集代理｜AGPL-3.0
- [Grafana Alloy](https://grafana.com/oss/alloy-opentelemetry-collector/) — OpenTelemetry/Prom 统一采集器｜Apache-2.0
- [Vector](https://vector.dev) — 高性能日志/指标/轨迹管道｜MPL-2.0
- [Fluent Bit](https://fluentbit.io) — 轻量高性能日志采集器｜Apache-2.0
- [Graylog](https://www.graylog.org) — 开源日志管理与分析平台｜GPL-3.0
- [Elasticsearch + Kibana](https://www.elastic.co) — 经典搜索与日志可视化栈｜Elastic-2.0

## 测速

- [Speedtest Tracker](https://github.com/henrywhitaker3/Speedtest-Tracker) — 定时跑 Ookla 测速并记录历史图表｜GPL-3.0
- [LibreSpeed](https://github.com/librespeed/speedtest) — 自托管网页网速测试｜LGPL-3.0

## Kubernetes 可视化

- [Headlamp](https://github.com/headlamp-k8s/headlamp) — 开源、可扩展的 Kubernetes Web UI｜Apache-2.0
- [Kubernetes Dashboard](https://github.com/kubernetes/dashboard) — 官方 Kubernetes Web 管理界面｜Apache-2.0
- [k9s](https://k9scli.io) — 终端里操作 Kubernetes 的超酷 CLI 面板｜Apache-2.0
- [Weave GitOps](https://www.weave.works) — Kubernetes 持续交付/可视化 GitOps 控制台｜Apache-2.0
