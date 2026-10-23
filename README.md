# The Forbbiden Knowledge

Portfólio e laboratórios de pesquisa em segurança ofensiva, forense digital e inteligência de ameaças.

**Site no ar:** https://the-forbidden-knowledge.github.io/

## O site

Single-page application estática servida pelo GitHub Pages:

- `index.html` — shell da raiz: carrega o layout e injeta a página via JavaScript (fetch).
- `lib/theforbbidenknowledge_web/components/layouts/root.html` — layout: `<head>`, título, favicon, tema claro/escuro e o `#inner-content` onde a página entra.
- `lib/theforbbidenknowledge_web/controllers/page_html/home.html` — a página principal (conteúdo canônico).

O documento da raiz é dinâmico: o conteúdo é buscado em tempo de execução e renderizado no navegador, sem build.

## Estrutura

A árvore do projeto usa nomes ofuscados (padrão de 22 caracteres). O mapa de nomes é privado e local.

## Licença

MIT — Copyright (c) 2026 A Elite Estrangeira. Veja `LICENSE`.
