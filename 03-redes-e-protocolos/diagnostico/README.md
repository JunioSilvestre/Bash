# diagnostico

> Análise de interfaces, rotas de rede, portas abertas e inspeção de pacotes.

## 🛠️ Ferramentas & Utilitários
- `ip, ss, traceroute, ping, tcpdump, nc`

## 📋 Boas Práticas
- Utilize `set -euo pipefail` para garantir interrupção segura em caso de erros.
- Documente flags e opções aceitas usando funções de ajuda (`--help`).
- Valide permissões de execução (`chmod +x script.sh`) antes de rodar.
- Verifique a sintaxe com `shellcheck script.sh` antes de comitar.
