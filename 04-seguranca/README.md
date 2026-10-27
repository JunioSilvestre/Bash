# 04-seguranca — Segurança e Hardening Linux

Auditoria de integridade, hardening de SO, gestão segura de credenciais e privilégios sudo.

## 📂 Subáreas
- [`hardening/`](./hardening) — **Ferramentas:** `sysctl, lynis, sshd_config, pam` — Aplicação de benchmarks de segurança, endurecimento do kernel e serviços expostos.
- [`auditoria/`](./auditoria) — **Ferramentas:** `auditd, aureport, ausearch, fail2ban` — Coleta e análise de eventos de segurança e proteção contra ataques de força bruta.
- [`permissoes-e-sudo/`](./permissoes-e-sudo) — **Ferramentas:** `visudo, sudoers, find (SUID/SGID)` — Configuração de privilégios mínimos, auditoria de binários SUID e regras do sudoers.
- [`secrets-e-credenciais/`](./secrets-e-credenciais) — **Ferramentas:** `pass, gpg, openssl, envsubst` — Criptografia de credenciais, geração de certificados TLS e manipulação segura de segredos.

## 📌 Guia de Execução
- Scripts nesta pasta devem seguir a convenção de shebang `#!/usr/bin/env bash`.
- Utilize funções reutilizáveis e evite efeitos colaterais fora do escopo principal.
