# github-actions

> Execução de scripts Bash em steps de GitHub Actions e interação via gh CLI.

## 🛠️ Ferramentas & Utilitários
- `actions/runner, gh-cli`

## 📋 Boas Práticas
- Utilize `set -euo pipefail` para garantir interrupção segura em caso de erros.
- Documente flags e opções aceitas usando funções de ajuda (`--help`).
- Valide permissões de execução (`chmod +x script.sh`) antes de rodar.
- Verifique a sintaxe com `shellcheck script.sh` antes de comitar.
