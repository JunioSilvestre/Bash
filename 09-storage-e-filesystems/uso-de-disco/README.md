# uso-de-disco

> Auditoria de ocupação de storage, identificação de arquivos gigantes e alertas de espaço.

## 🛠️ Ferramentas & Utilitários
- `df, du, ncdu, find`

## 📋 Boas Práticas
- Utilize `set -euo pipefail` para garantir interrupção segura em caso de erros.
- Documente flags e opções aceitas usando funções de ajuda (`--help`).
- Valide permissões de execução (`chmod +x script.sh`) antes de rodar.
- Verifique a sintaxe com `shellcheck script.sh` antes de comitar.
