# Super Mario Galaxy

Landing page conceitual inspirada no universo de Super Mario Galaxy, com visual cinematográfico, efeitos de estrelas, animações suaves e uma estrutura de marketing para divulgação do filme.

## Visão geral

Este projeto é uma página estática de apresentação, desenvolvida em HTML, CSS e JavaScript, com foco em experiência visual marcante e navegação fluida. A interface simula um site oficial de lançamento com hero section, personagens, vídeos e contagem regressiva para a estreia.

## Funcionalidades

- Hero section com vídeos em camadas e botões de destaque
- Fundo estrelado animado em canvas
- Navegação flutuante para seções da página
- Letreiro animado com nomes e temática espacial
- Seção de personagens com layout editorial e efeitos visuais
- Área de trailers e informações do filme
- Countdown para a data de estreia
- Layout responsivo para desktop e mobile
- Animações com GSAP e partículas em movimento

## Stack utilizada

- HTML5
- CSS3 com variáveis e design tokens
- JavaScript vanila
- GSAP
- ScrollTrigger
- particles.js
- Assets locais de imagens e vídeos

## Estrutura do projeto

```text
.
├── index.html
├── DESIGN.md
├── css/
│   └── styles.css
├── js/
│   └── script.js
├── assets/
│   ├── images/
│   └── videos/
├── docs/
│   ├── hero-section-spec.md
│   ├── personagens-section-spec.md
│   ├── trailers-section-spec.md
│   ├── marquee-section-spec.md
│   ├── nav-section-spec.md
│   ├── estreia-section-spec.md
│   ├── starfield-section-spec.md
│   └── contador-animacao-spec.md
└── prints/
```

## Como executar

### Opção 1: abrir diretamente no navegador

Basta abrir o arquivo [index.html](./index.html) em qualquer navegador moderno.

### Opção 2: rodar um servidor local

No terminal, dentro da pasta do projeto, execute:

```bash
python -m http.server 8000
```

Depois abra no navegador:

```text
http://localhost:8000
```

## Documentação relacionada

- [DESIGN.md](./DESIGN.md): sistema de design, paleta de cores e tokens visuais
- [docs/](./docs): especificações das seções da landing page

## Observações

Este é um projeto conceitual e educacional, voltado para prática de front-end, UI/UX e animações web. Personagens, marcas e elementos da franquia Super Mario pertencem à Nintendo.

## Licença

Este projeto foi desenvolvido para fins educacionais e não tem finalidade comercial.
