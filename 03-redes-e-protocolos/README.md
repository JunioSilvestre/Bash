# 03-redes-e-protocolos — Redes, Conectividade e Protocolos

Diagnósticos de tráfego, resolução DNS, regras de firewall e comunicação remota via SSH.

## 📂 Subáreas
- [`diagnostico/`](./diagnostico) — **Ferramentas:** `ip, ss, traceroute, ping, tcpdump, nc` — Análise de interfaces, rotas de rede, portas abertas e inspeção de pacotes.
- [`dns-e-dhcp/`](./dns-e-dhcp) — **Ferramentas:** `dig, nslookup, host, resolvectl` — Consultas e validações de registros DNS, servidores autoritativos e cache local.
- [`firewall-e-vpn/`](./firewall-e-vpn) — **Ferramentas:** `iptables, nftables, ufw, wireguard-tools` — Automação de políticas de firewall, liberação de portas e gerenciamento de VPNs.
- [`ssh-e-scp/`](./ssh-e-scp) — **Ferramentas:** `ssh, scp, sftp, ssh-keygen, ssh-copy-id` — Automação com chaves SSH, túneis, cópias seguras e execução em múltiplos hosts.

## 📌 Guia de Execução
- Scripts nesta pasta devem seguir a convenção de shebang `#!/usr/bin/env bash`.
- Utilize funções reutilizáveis e evite efeitos colaterais fora do escopo principal.
