# padroes-de-scripts

> Modelos padrão estruturados com cabeçalho de metadados, help e tratamento robusto.

## 🛠️ Ferramentas & Utilitários
- `Boilerplate, Twelve-Factor CLI`

## 📋 Boas Práticas
- Utilize `set -euo pipefail` para garantir interrupção segura em caso de erros.
- Documente flags e opções aceitas usando funções de ajuda (`--help`).
- Valide permissões de execução (`chmod +x script.sh`) antes de rodar.
- Verifique a sintaxe com `shellcheck script.sh` antes de comitar.
