# auditoria

> Coleta e análise de eventos de segurança e proteção contra ataques de força bruta.

## 🛠️ Ferramentas & Utilitários
- `auditd, aureport, ausearch, fail2ban`

## 📋 Boas Práticas
- Utilize `set -euo pipefail` para garantir interrupção segura em caso de erros.
- Documente flags e opções aceitas usando funções de ajuda (`--help`).
- Valide permissões de execução (`chmod +x script.sh`) antes de rodar.
- Verifique a sintaxe com `shellcheck script.sh` antes de comitar.
