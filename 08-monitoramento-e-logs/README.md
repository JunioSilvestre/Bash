# 08-monitoramento-e-logs — Monitoramento, Logs e Troubleshooting

Scripts para parsing de logs, coleta de métricas do sistema e envio de alertas.

## 📂 Subáreas
- [`metricas/`](./metricas) — **Ferramentas:** `vmstat, iostat, sar, free, uptime` — Coleta periódica de telemetria de CPU, memória, I/O e carga do sistema.
- [`logs/`](./logs) — **Ferramentas:** `grep, awk, sed, journalctl, logrotate` — Filtragem avançada, extração de relatórios e rotação automatizada de logs.
- [`alertas/`](./alertas) — **Ferramentas:** `curl, mailx, webhook (Slack/Discord/Telegram)` — Notificação imediata em caso de falhas ou limites de recursos atingidos.
- [`troubleshooting/`](./troubleshooting) — **Ferramentas:** `dmesg, strace, lsof, ss` — Scripts de diagnóstico rápido para incidentes e análise de chamadas de sistema.

## 📌 Guia de Execução
- Scripts nesta pasta devem seguir a convenção de shebang `#!/usr/bin/env bash`.
- Utilize funções reutilizáveis e evite efeitos colaterais fora do escopo principal.
