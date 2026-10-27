# backup-e-restauracao

> Criação de cópias de segurança incrementais, validação de integridade e criptografia.

## 🛠️ Ferramentas & Utilitários
- `rsync, tar, sha256sum, gpg`

## 📋 Boas Práticas
- Utilize `set -euo pipefail` para garantir interrupção segura em caso de erros.
- Documente flags e opções aceitas usando funções de ajuda (`--help`).
- Valide permissões de execução (`chmod +x script.sh`) antes de rodar.
- Verifique a sintaxe com `shellcheck script.sh` antes de comitar.
