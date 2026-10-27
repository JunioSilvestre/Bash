# raid

> Configuração e monitoramento de integridade de arrays RAID por software.

## 🛠️ Ferramentas & Utilitários
- `mdadm, /proc/mdstat`

## 📋 Boas Práticas
- Utilize `set -euo pipefail` para garantir interrupção segura em caso de erros.
- Documente flags e opções aceitas usando funções de ajuda (`--help`).
- Valide permissões de execução (`chmod +x script.sh`) antes de rodar.
- Verifique a sintaxe com `shellcheck script.sh` antes de comitar.
