# tratamento-de-erros

> Interceptação de sinais, limpeza de arquivos temporários e interrupção imediata em falhas.

## 🛠️ Ferramentas & Utilitários
- `trap, set -euo pipefail, ERR`

## 📋 Boas Práticas
- Utilize `set -euo pipefail` para garantir interrupção segura em caso de erros.
- Documente flags e opções aceitas usando funções de ajuda (`--help`).
- Valide permissões de execução (`chmod +x script.sh`) antes de rodar.
- Verifique a sintaxe com `shellcheck script.sh` antes de comitar.
