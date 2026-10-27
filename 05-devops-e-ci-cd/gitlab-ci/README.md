# gitlab-ci

> Scripts para jobs de build, teste e deploy em pipelines do GitLab CI/CD.

## 🛠️ Ferramentas & Utilitários
- `gitlab-runner, curl, jq`

## 📋 Boas Práticas
- Utilize `set -euo pipefail` para garantir interrupção segura em caso de erros.
- Documente flags e opções aceitas usando funções de ajuda (`--help`).
- Valide permissões de execução (`chmod +x script.sh`) antes de rodar.
- Verifique a sintaxe com `shellcheck script.sh` antes de comitar.
