![Design preview for the NFT preview card component coding challenge](assets/design/desktop-preview.jpg)

# NFT preview card component solution

Esse projeto foi desenvolvido de um desafio do [Frontend Mentor Challenge](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). 

O desafio foi construir esse cartão de visualização e deixá-lo o mais próximo possível do design original.

Esta é uma solução para o desafio do Frontend Mentor, onde ajuda a melhorar as habilidades praticas com o código, através da criação de projetos realistas.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Os usuários devem ser capazes de:

- Visualizar o layout ideal depedendo do tamanho da tela do dispositivo
- Vizualizar os elementos interativos.

### Screenshot

![Screenshot Finished project](assets\design\screenshot-solution.jpg)

### Links

- Live Site URL: [NFT preview card component](https://filipesilvait.github.io/nft-preview-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

Aprendi mais sobre flexbox, estilizar com border-shadow, usar o hover e sobrepor uma imagem.

```css
.img-overlay {
    position: absolute;
    left: 0;
    top: 0;
    height: 100%;
    width: 100%;
    background-color: hsl(178, 100%, 50%, 0.5);
    display: none;
}
```
```css
.img-overlay img {
    position: absolute;
    width: 50px;
    left: 50%;
    top: 50%;
    transform: translate(-50%, -50%);
}
```

### Continued development

Vou continuar aprendendo mais sobre HTML semântico. Aprender e praticar com CSS, flexbox, styles, positions e decorations.

## Author

- LinkedIn [Filipe Silva](https://www.linkedin.com/in/filipesilvait/)
- Twitter - [@filipesilvait](https://twitter.com/filipesilvait)
