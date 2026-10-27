# argumentos-e-opcoes

> Parsing profissional de opções curtas (-a) e longas (--verbose) com validação de entrada.

## 🛠️ Ferramentas & Utilitários
- `getopts, $1, shift`

## 📋 Boas Práticas
- Utilize `set -euo pipefail` para garantir interrupção segura em caso de erros.
- Documente flags e opções aceitas usando funções de ajuda (`--help`).
- Valide permissões de execução (`chmod +x script.sh`) antes de rodar.
- Verifique a sintaxe com `shellcheck script.sh` antes de comitar.
