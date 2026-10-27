# 09-storage-e-filesystems — Storage, Filesystems e Volumes

Gestão de discos, particionamento LVM, RAID por software e compartilhamentos de rede.

## 📂 Subáreas
- [`uso-de-disco/`](./uso-de-disco) — **Ferramentas:** `df, du, ncdu, find` — Auditoria de ocupação de storage, identificação de arquivos gigantes e alertas de espaço.
- [`lvm-e-particoes/`](./lvm-e-particoes) — **Ferramentas:** `fdisk, parted, pvcreate, vgextend, lvextend` — Automação de redimensionamento e criação de volumes lógicos LVM.
- [`raid/`](./raid) — **Ferramentas:** `mdadm, /proc/mdstat` — Configuração e monitoramento de integridade de arrays RAID por software.
- [`nfs-e-samba/`](./nfs-e-samba) — **Ferramentas:** `mount, exportfs, showmount, smbclient` — Montagem resiliente de volumes de rede e gestão de exports.

## 📌 Guia de Execução
- Scripts nesta pasta devem seguir a convenção de shebang `#!/usr/bin/env bash`.
- Utilize funções reutilizáveis e evite efeitos colaterais fora do escopo principal.
