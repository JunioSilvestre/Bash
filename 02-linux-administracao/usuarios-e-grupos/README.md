# usuarios-e-grupos

> Provisionamento e auditoria de contas de usuários, grupos e políticas de expiração de senhas.

## 🛠️ Ferramentas & Utilitários
- `useradd, usermod, groupadd, chage, passwd`

## 📋 Boas Práticas
- Utilize `set -euo pipefail` para garantir interrupção segura em caso de erros.
- Documente flags e opções aceitas usando funções de ajuda (`--help`).
- Valide permissões de execução (`chmod +x script.sh`) antes de rodar.
- Verifique a sintaxe com `shellcheck script.sh` antes de comitar.
