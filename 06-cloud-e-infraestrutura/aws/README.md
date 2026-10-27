# aws

> Scripts de automação para recursos AWS (EC2, S3, IAM, CloudWatch).

## 🛠️ Ferramentas & Utilitários
- `aws-cli, jq`

## 📋 Boas Práticas
- Utilize `set -euo pipefail` para garantir interrupção segura em caso de erros.
- Documente flags e opções aceitas usando funções de ajuda (`--help`).
- Valide permissões de execução (`chmod +x script.sh`) antes de rodar.
- Verifique a sintaxe com `shellcheck script.sh` antes de comitar.
