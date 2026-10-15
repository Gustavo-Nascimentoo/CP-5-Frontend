<h1 align="center">CP5 - Front end</h1>

<p align="center">
  Atividades do CP5 de Front end, feitas com HTML, CSS, Bootstrap e Tailwind.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap">
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS">
</p>

---

## Sumário

- [Sobre](#sobre)
- [Estrutura](#estrutura)
- [Como abrir](#como-abrir)
- [Projetos](#projetos)
  - [Bootstrap - Sabor Caseiro](#1-bootstrap---sabor-caseiro)
  - [Tailwind - Força Total](#2-tailwind---força-total)
  - [Revisão - Mc Donalds Core](#3-revisão---mc-donalds-core)
  - [Vibe Coding - NEXUS](#4-vibe-coding---nexus)
- [Tecnologias](#tecnologias)

---

## Sobre

Repositório com os quatro projetos do CP5. Não há JavaScript próprio em nenhum deles.

## Estrutura

```
CP5 - Front end/
├── bootstrap/
│   └── index.html
├── tailwind/
│   └── index.html
├── revisao/
│   ├── index.html
│   └── css/
│       └── style.css
└── Vibe Coding/
    ├── Prompts.txt
    └── Nexus - Landing page - Organizado/
        ├── index.html
        └── css/
            └── styles.css
```

## Como abrir

Não precisa instalar nada. Clone o repositório e abra o `index.html` de cada pasta no navegador.

```bash
git clone <url-do-repositorio>
```

> O Bootstrap, o Tailwind, as fontes do Google e algumas imagens vêm de links externos, então é preciso estar conectado à internet.

## Projetos

### 1. Bootstrap - Sabor Caseiro

Página de uma loja de comida caseira feita com os componentes do Bootstrap 5.3.

- Navbar escura com três links e o botão "Comprar agora"
- Modal de pedido aberto pelo botão da navbar
- Seção inicial com título, texto e imagem
- Carrossel de depoimentos
- FAQ com accordion
- Footer simples com fundo escuro
- Fonte: Fredoka

### 2. Tailwind - Força Total

Página de uma academia feita com classes utilitárias do Tailwind CSS 4.

- Navbar escura com três links
- Seção inicial com título e botão de aula experimental
- Seção "Como funciona" com 4 etapas em grid
- Galeria de fotos em grid de 3 colunas
- Depoimento e footer
- Fonte: monospace (`font-mono`)

### 3. Revisão - Mc Donalds Core

Site de uma lanchonete feito só com HTML e CSS próprios, usando `grid` e `flex`.

- Menu, banner, cardápio, sobre nós, depoimentos, contato com formulário e footer
- Layout responsivo com `@media` (850px e 500px)
- Paleta em azul e cinza, definida com variáveis CSS
- Fonte: `fantasy`

| Variável | Cor |
|---|---|
| `--azul-escuro` | `#1e3a5f` |
| `--azul` | `#2f6fbd` |
| `--azul-claro` | `#dbe7f5` |
| `--cinza-escuro` | `#3d4450` |
| `--cinza` | `#e6e8ec` |
| `--branco` | `#ffffff` |

### 4. Vibe Coding - NEXUS

Landing page de periféricos de computador (mouses e teclados), baseada no site da Nike e criada com ajuda do ChatGPT. Os prompts usados estão em [`Vibe Coding/Prompts.txt`](./Vibe%20Coding/Prompts.txt).

**Prompt inicial (resumo):** landing page inspirada na Nike, com tema de periféricos, cores principais preto e branco, detalhes em vermelho, verde e azul (ideia de RGB), um LED RGB simples em alguma parte do site, só HTML e CSS. Depois, pedi para separar o HTML e o CSS e organizar os arquivos.

**O que a página tem**

- Barra de aviso, navegação fixa com busca e botão de sacola
- Banner principal "Seu setup. Suas regras."
- Categorias de mouses e teclados
- Quatro produtos em destaque: Phantom Wireless, Pulse Mechanical, Core Precision e Strike Compact
- Seção "RGB Mode" com uma barra de LED
- Três benefícios: precisão, conforto e personalidade
- Footer

**Paleta**

| Uso | Cor |
|---|---|
| Preto | `#0a0a0a` |
| Branco | `#ffffff` |
| Vermelho | `#ff3434` |
| Verde | `#39e66b` |
| Azul | `#3985ff` |

**Fonte:** Arial, Helvetica, sans-serif.

**Limitações**

- Não há JavaScript. A busca, a sacola e os botões "Adicionar" ainda não funcionam.
- As imagens vêm de links externos (Unsplash).

## Tecnologias

- HTML5
- CSS3 (variáveis, flexbox, grid, media queries)
- Bootstrap 5.3
- Tailwind CSS 4
- Google Fonts (Fredoka)
