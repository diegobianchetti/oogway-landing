# oogway-landing

Site de landing do portfólio Oogway — hospedado no GitHub Pages em
<https://oogway.com.br/>.

## Conceito

Uma **journey** em vez de um flyer: hero com OOGWAY em escala grande, trajetória
de experiência em linguagem qualitativa, mapa da trilha em SVG interativo (com a
tartaruga Oogway percorrendo a linha) e quatro nós navegáveis —
**Infra Linux → Containers → Automação → Alocação** — onde o último nó é a
conversa (e-mail, GitHub, Torre.ai).

## Stack

- HTML/CSS/JS puro — arquivo único (`index.html`), sem framework, sem build
- Tipografia: Inter + JetBrains Mono (Google Fonts)
- Tema dark com gradientes verdes (`#1D9E75` / `#3ECB9C`), glow pulsante e
  animações CSS/JS (`prefers-reduced-motion` respeitado)
- Google Analytics 4 (`G-ERD8TZ65C7`)

## Estrutura

- `index.html` — página completa: hero, trajetória, mapa da trilha, nós 01–04 e
  conversão; links para os 9 repositórios públicos do portfólio
- `favicon.svg` — ícone da tartaruga Oogway
- `CNAME` — domínio personalizado (`oogway.com.br`)

## Convenções

- Commits em português
- Nenhum dado real de cliente; snippets de código sempre genéricos/fictícios
- Experiência em anos sempre em linguagem qualitativa, nunca como número