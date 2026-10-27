# 05-devops-e-ci-cd — DevOps, Git e CI/CD

Integração de scripts Shell em pipelines modernos de entrega contínua e automação de repositórios.

## 📂 Subáreas
- [`git/`](./git) — **Ferramentas:** `git, git-hooks` — Ganchos (pre-commit, post-receive) e automação de fluxos de versionamento.
- [`github-actions/`](./github-actions) — **Ferramentas:** `actions/runner, gh-cli` — Execução de scripts Bash em steps de GitHub Actions e interação via gh CLI.
- [`gitlab-ci/`](./gitlab-ci) — **Ferramentas:** `gitlab-runner, curl, jq` — Scripts para jobs de build, teste e deploy em pipelines do GitLab CI/CD.
- [`pipelines/`](./pipelines) — **Ferramentas:** `make, env, jq, yq` — Orquestração de etapas de build e entrega através de scripts reutilizáveis.

## 📌 Guia de Execução
- Scripts nesta pasta devem seguir a convenção de shebang `#!/usr/bin/env bash`.
- Utilize funções reutilizáveis e evite efeitos colaterais fora do escopo principal.
