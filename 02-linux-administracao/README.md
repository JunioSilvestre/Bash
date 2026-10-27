# 02-linux-administracao — Administração de Sistemas Linux

Automação do ciclo de vida de servidores Linux, pacotes, usuários, serviços e permissões avançadas.

## 📂 Subáreas
- [`usuarios-e-grupos/`](./usuarios-e-grupos) — **Ferramentas:** `useradd, usermod, groupadd, chage, passwd` — Provisionamento e auditoria de contas de usuários, grupos e políticas de expiração de senhas.
- [`permissoes-e-acl/`](./permissoes-e-acl) — **Ferramentas:** `chmod, chown, setfacl, getfacl, umask` — Configuração de permissões POSIX padrão e Access Control Lists (ACLs) detalhadas.
- [`systemd/`](./systemd) — **Ferramentas:** `systemctl, journalctl, systemd-analyze` — Criação de service units personalizadas, timers, sockets e diagnóstico de boot.
- [`pacotes-e-atualizacoes/`](./pacotes-e-atualizacoes) — **Ferramentas:** `apt, apt-get, dpkg, unattended-upgrades` — Gerenciamento automatizado de repositórios, atualizações de segurança e inventário de pacotes.

## 📌 Guia de Execução
- Scripts nesta pasta devem seguir a convenção de shebang `#!/usr/bin/env bash`.
- Utilize funções reutilizáveis e evite efeitos colaterais fora do escopo principal.
