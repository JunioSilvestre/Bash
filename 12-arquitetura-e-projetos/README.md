# 12-arquitetura-e-projetos — Arquitetura e Projetos Integradores

Projetos completos de engenharia Shell que combinam múltiplos módulos em soluções robustas.

## 📂 Subáreas
- [`padroes-de-scripts/`](./padroes-de-scripts) — **Ferramentas:** `Boilerplate, Twelve-Factor CLI` — Modelos padrão estruturados com cabeçalho de metadados, help e tratamento robusto.
- [`modularizacao/`](./modularizacao) — **Ferramentas:** `Lib sourcing, dependências` — Arquitetura desacoplada dividida em arquivos de configuração, bibliotecas e executáveis.
- [`alta-disponibilidade/`](./alta-disponibilidade) — **Ferramentas:** `Keepalived, VIP, health checks` — Scripts de failover e verificação de nós em clusters de alta disponibilidade.
- [`projetos-integradores/`](./projetos-integradores) — **Ferramentas:** `Soluções Completas de Infraestrutura` — Projetos completos de auditoria de servidores, auto-remediação e provisionamento.

## 📌 Guia de Execução
- Scripts nesta pasta devem seguir a convenção de shebang `#!/usr/bin/env bash`.
- Utilize funções reutilizáveis e evite efeitos colaterais fora do escopo principal.
