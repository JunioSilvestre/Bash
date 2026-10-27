# 07-containers-e-kubernetes — Containers e Kubernetes

Automação do ciclo de vida de containers Docker e gerenciamento de clusters via kubectl.

## 📂 Subáreas
- [`docker/`](./docker) — **Ferramentas:** `docker, docker-compose` — Builds automatizados de imagens, gerenciamento de volumes e execução de containers.
- [`kubernetes/`](./kubernetes) — **Ferramentas:** `kubectl, helm, k9s` — Scripts operacionais de consulta a pods, deploys, rollout e coleta de manifests.
- [`manutencao/`](./manutencao) — **Ferramentas:** `docker system prune, crictl` — Limpeza de imagens órfãs, rotação de logs de containers e health checks.

## 📌 Guia de Execução
- Scripts nesta pasta devem seguir a convenção de shebang `#!/usr/bin/env bash`.
- Utilize funções reutilizáveis e evite efeitos colaterais fora do escopo principal.
