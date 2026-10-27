# 10-funcoes-e-bibliotecas — Funções, Bibliotecas e Modularização

Padrões de engenharia para scripts Bash: bibliotecas reutilizáveis, parsing de argumentos e tratamento de exceções.

## 📂 Subáreas
- [`funcoes/`](./funcoes) — **Ferramentas:** `source, return, local, declare` — Definição de funções modulares, encapsulamento de escopo e retorno de status.
- [`logging/`](./logging) — **Ferramentas:** `logger, ANSI colors, timestamps` — Formatadores de saída padrão (INFO, WARN, ERROR) com suporte a Syslog.
- [`argumentos-e-opcoes/`](./argumentos-e-opcoes) — **Ferramentas:** `getopts, $1, shift` — Parsing profissional de opções curtas (-a) e longas (--verbose) com validação de entrada.
- [`tratamento-de-erros/`](./tratamento-de-erros) — **Ferramentas:** `trap, set -euo pipefail, ERR` — Interceptação de sinais, limpeza de arquivos temporários e interrupção imediata em falhas.

## 📌 Guia de Execução
- Scripts nesta pasta devem seguir a convenção de shebang `#!/usr/bin/env bash`.
- Utilize funções reutilizáveis e evite efeitos colaterais fora do escopo principal.
