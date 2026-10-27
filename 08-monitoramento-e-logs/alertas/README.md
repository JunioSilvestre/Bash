# alertas

> Notificação imediata em caso de falhas ou limites de recursos atingidos.

## 🛠️ Ferramentas & Utilitários
- `curl, mailx, webhook (Slack/Discord/Telegram)`

## 📋 Boas Práticas
- Utilize `set -euo pipefail` para garantir interrupção segura em caso de erros.
- Documente flags e opções aceitas usando funções de ajuda (`--help`).
- Valide permissões de execução (`chmod +x script.sh`) antes de rodar.
- Verifique a sintaxe com `shellcheck script.sh` antes de comitar.
