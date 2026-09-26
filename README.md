# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Links

- Solution URL: [https://github.com/rafael60507]
- Live Site URL: (https://rafael60507.github.io/desafio-order-summary/)

## My process

### Built with

- Semantic HTML5 markup
- CSS3 (Flexbox)
- Local fonts with @font-face (Red Hat Display)
- Mobile-first responsive design

### What I learned

Aprendi a usar Flexbox pra alinhar elementos tanto na horizontal quanto na vertical, combinando `flex-direction: row` e `column` em camadas diferentes do layout.

Também entendi a diferença entre o seletor `:first-child` (que olha os irmãos dentro do mesmo pai) e o combinador (que restringe a regra só a filhos diretos)

```css
main > img {
    width: 100%;
    display: block;
}
```

Outra coisa importante: quando se usa `@font-face` com pesos específicos (500, 700, 900), é preciso declarar explicitamente o `font-weight` nos elementos de texto, porque o navegador não escolhe automaticamente um peso próximo, ele simplesmente ignora a fonte se o peso não bater exatamente.

Por fim, aprendi a fazer um layout responsivo simples usando `max-width` combinado com `padding` no body, em vez de `width` fixo, o que evita que o card "estoure" a tela em dispositivos pequenos.

### AI Collaboration

Usei o Claude (Anthropic) para tirar duvidas e resolver erros, durante o desenvolvimento deste projeto.

- **Como usei**: pedi pra ele me explicar os conceitos por trás de cada parte do CSS (Flexbox, seletores, responsividade) antes de escrever o código, em vez de me dar a solução pronta. Também usei ele pra desbugar problemas reais que tive (como uma fonte que não carregava e um padrão de fundo mal posicionado).
- **O que funcionou bem**: a explicação por etapas me ajudou a entender o "porquê" de cada propriedade CSS, não só o "como". Desbugar em conjunto também me ensinou a usar ferramentas como o DevTools do navegador.
- **O que foi desafiador**: alguns bugs (principalmente relacionados a cache do navegador e carregamento de fonte) levaram várias tentativas até serem resolvidos, o que mostrou como debugging real muitas vezes não tem solução óbvia de primeira.

## Author

- [Rafael Côrtes da Silva]
- GitHub - [@rafael60507](https://github.com/rafael60507)
