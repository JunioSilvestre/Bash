# 11-testes-e-qualidade — Testes, Qualidade e Análise Estática

Garantia de qualidade, validação estática de sintaxe e testes automatizados para scripts Shell.

## 📂 Subáreas
- [`shellcheck/`](./shellcheck) — **Ferramentas:** `shellcheck` — Linter estático para detectar bugs, antipatterns e falhas de segurança no código Shell.
- [`shfmt/`](./shfmt) — **Ferramentas:** `shfmt` — Formatador automático de código para garantir consistência de indentação e estilo.
- [`bats/`](./bats) — **Ferramentas:** `bats-core` — Framework de testes automatizados unitários e de integração para Bash.
- [`debugging/`](./debugging) — **Ferramentas:** `set -x, set -v, PS4` — Técnicas de rastreamento de execução e debug interativo de scripts complexos.

## 📌 Guia de Execução
- Scripts nesta pasta devem seguir a convenção de shebang `#!/usr/bin/env bash`.
- Utilize funções reutilizáveis e evite efeitos colaterais fora do escopo principal.
