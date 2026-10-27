# 01-automacao — Automação Operacional em Bash

Scripts para automatizar rotinas administrativas, operações com arquivos, processos e agendamento de tarefas.

## 📂 Subáreas
- [`arquivos-e-diretorios/`](./arquivos-e-diretorios) — **Ferramentas:** `find, xargs, rsync, tar, gzip, stat` — Manipulação, busca, compressão e gerenciamento seguro de arquivos e diretórios.
- [`processos-e-servicos/`](./processos-e-servicos) — **Ferramentas:** `pgrep, pkill, systemctl, ps, kill, nohup` — Monitoramento de processos em execução, controle de sinais e gerenciamento de serviços.
- [`tarefas-agendadas/`](./tarefas-agendadas) — **Ferramentas:** `cron, crontab, at, systemd-timers` — Agendamento periódico e pontual de execuções via Cron e Systemd Timers.
- [`backup-e-restauracao/`](./backup-e-restauracao) — **Ferramentas:** `rsync, tar, sha256sum, gpg` — Criação de cópias de segurança incrementais, validação de integridade e criptografia.

## 📌 Guia de Execução
- Scripts nesta pasta devem seguir a convenção de shebang `#!/usr/bin/env bash`.
- Utilize funções reutilizáveis e evite efeitos colaterais fora do escopo principal.
