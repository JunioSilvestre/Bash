# lvm-e-particoes

> Automação de redimensionamento e criação de volumes lógicos LVM.

## 🛠️ Ferramentas & Utilitários
- `fdisk, parted, pvcreate, vgextend, lvextend`

## 📋 Boas Práticas
- Utilize `set -euo pipefail` para garantir interrupção segura em caso de erros.
- Documente flags e opções aceitas usando funções de ajuda (`--help`).
- Valide permissões de execução (`chmod +x script.sh`) antes de rodar.
- Verifique a sintaxe com `shellcheck script.sh` antes de comitar.
