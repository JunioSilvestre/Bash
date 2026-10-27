# ssh-e-scp

> Automação com chaves SSH, túneis, cópias seguras e execução em múltiplos hosts.

## 🛠️ Ferramentas & Utilitários
- `ssh, scp, sftp, ssh-keygen, ssh-copy-id`

## 📋 Boas Práticas
- Utilize `set -euo pipefail` para garantir interrupção segura em caso de erros.
- Documente flags e opções aceitas usando funções de ajuda (`--help`).
- Valide permissões de execução (`chmod +x script.sh`) antes de rodar.
- Verifique a sintaxe com `shellcheck script.sh` antes de comitar.
