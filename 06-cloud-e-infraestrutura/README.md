# 06-cloud-e-infraestrutura — Cloud Providers e Infraestrutura

CLI automation para nuvens públicas e scripts de bootstrap de instâncias (user_data).

## 📂 Subáreas
- [`aws/`](./aws) — **Ferramentas:** `aws-cli, jq` — Scripts de automação para recursos AWS (EC2, S3, IAM, CloudWatch).
- [`azure/`](./azure) — **Ferramentas:** `az-cli, jq` — Automação de recursos Azure (VMs, Resource Groups, Storage Accounts).
- [`gcp/`](./gcp) — **Ferramentas:** `gcloud, gsutil` — Scripts operacionais para Google Cloud Platform (Compute Engine, GCS).
- [`provisionamento/`](./provisionamento) — **Ferramentas:** `cloud-init, user_data, curl` — Scripts de inicialização de instâncias e provisionamento base pós-boot.

## 📌 Guia de Execução
- Scripts nesta pasta devem seguir a convenção de shebang `#!/usr/bin/env bash`.
- Utilize funções reutilizáveis e evite efeitos colaterais fora do escopo principal.
