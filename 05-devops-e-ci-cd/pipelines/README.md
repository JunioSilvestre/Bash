# pipelines

> Orquestração de etapas de build e entrega através de scripts reutilizáveis.

## 🛠️ Ferramentas & Utilitários
- `make, env, jq, yq`

## 📋 Boas Práticas
- Utilize `set -euo pipefail` para garantir interrupção segura em caso de erros.
- Documente flags e opções aceitas usando funções de ajuda (`--help`).
- Valide permissões de execução (`chmod +x script.sh`) antes de rodar.
- Verifique a sintaxe com `shellcheck script.sh` antes de comitar.
