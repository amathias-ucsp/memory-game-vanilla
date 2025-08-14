# 🧠 Jogo da Memória (Vanilla JS)

Jogo da memória **4x4** feito em **um único arquivo `index.html`** (HTML + CSS + JS puro).  
Recursos: cronômetro, contador de jogadas, **melhor tempo** com `localStorage`, animações e layout responsivo.

- **Demo (GitHub Pages):** https://amathias-ucsp.github.io/memory-game-vanilla/  
- **Tecnologias:** HTML, CSS, JavaScript (sem dependências)  
- **Status:** ✅ Concluído (melhorias sugeridas abaixo)

## 🎯 Objetivo
Criar um jogo simples, apresentável e publicável em GitHub Pages para compor o meu **Portfólio Digital**, demonstrando domínio de HTML/CSS/JS, boas práticas de README e versionamento.

## ✨ Funcionalidades
- Tabuleiro 4×4 com cartas embaralhadas
- Contador de jogadas e cronômetro em tempo real
- Registro do **melhor tempo** no navegador (localStorage)
- Botão “Novo Jogo”
- Acessível via teclado (foco nos elementos) e cores com bom contraste

## 🧩 Como rodar
```bash
# opção 1: abrir direto
abra o arquivo index.html no navegador

# opção 2: usar um servidor local (ex. Python)
python -m http.server 8000
# depois acesse via browser http://localhost:8000
```

## 🚀 Publicação no GitHub Pages

Suba o index.html na raiz do repositório.
Settings → Pages → Deploy from a branch → main / root.
A URL sai em About → Website.

## 🧠 O que eu aprendi

Organização de um projeto estático pronto para GitHub Pages (sem bundlers).
Estado e regras de jogo com JavaScript puro (bloqueio de cliques, dupla seleção, comparação, reset).
Persistência simples com localStorage (best time).
Acessibilidade básica e responsividade.
Escrita de README orientado a portfólio.

## 📌 Especificações Técnicas

Desenvolver um jogo da memória 4x4 em um único arquivo index.html (HTML, CSS e JavaScript puro), com embaralhamento de cartas, contador de jogadas, cronômetro e registro de melhor tempo utilizando localStorage.
O projeto foi pensado para ser simples, responsivo e pronto para publicação no GitHub Pages.

Tecnologias utilizadas:

HTML5
CSS3
JavaScript (ES6+)

## O que aprendi:

Manipulação do DOM: criação e atualização dinâmica dos elementos de jogo.
Controle de Estado no JavaScript puro: armazenamento e atualização de variáveis de jogo como jogadas, cartas viradas e pares encontrados.
Persistência Local: uso do localStorage para guardar e exibir o melhor tempo alcançado pelo jogador.
Lógica de Jogo: embaralhamento aleatório (algoritmo de Fisher–Yates), verificação de pares e bloqueio temporário de cliques.
Responsividade e Estilo: uso de CSS moderno (flex, grid, gradients) para um visual agradável e adaptado a diferentes telas.

