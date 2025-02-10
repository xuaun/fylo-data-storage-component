# Frontend Mentor - Fylo data storage component solution

## Languages
This first section is in English. 

[Versão em português logo abaixo.](#portuguese)

## Context

This is a solution to the [Fylo data storage component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-data-storage-component-1dZPRbV5n). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

> Your challenge is to build out this data storage component and get it looking as close to the design as possible.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

#### Desktop

<p align="center">
  <img src="./src/design/desktop-screenshot.png" alt="Desktop Screenshot live page" title="Desktop Screenshot live page" width="600px" />
</p>

#### Mobile

<p align="center">
  <img src="./src/design/mobile-screenshot.png" alt="Mobile Screenshot live page" title="Mobile Screenshot live page" width="300px" />
</p>

### Links

- Solution URL: [GitHub Repository](https://github.com/xuaun/fylo-data-storage-component) and [my Frontend Mentor solution page](https://www.frontendmentor.io/solutions/responsive-fylo-data-storage-component-TAEMujbyUi)
- Live Site URL: [Live Page](https://xuaun.github.io/fylo-data-storage-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Media Query + clamp()

### What I learned

In this project I was able to use flexbox, grid, variable, and media query concepts in CSS, as well as using a ready-made Figma design to create this component. I also used `rem` for measurements, `clamp()` to help with responsiveness, and BEM methodology for naming classes.

```css
.storage__progression {
  background-color: var(--background-progression-bar);
  width: clamp(26.2rem, -0.664rem + 71.636vw, 45.9rem);
  height: 2rem;
  border-radius: 1rem;
  margin-bottom: 0.8rem;
  display: flex;
  align-items: center;
}

.storage__usage {
  border-radius: 0.8rem;
  width: clamp(19.3rem, -0.609rem + 53.091vw, 33.9rem);
  height: 1.4rem;
  margin: 0.3rem;
  background: var(--gradient-background);
  background: var(--gradient-1-moz);
  background: var(--gradient-1-webkit);
  background: var(--gradient-1);
  filter: var(--gradient-a-filter);
  position: relative;
}
```

## Author

- Website - [João Víctor de Araujo Lima's Portfolio](https://xuaun.github.io/)
- Frontend Mentor - [@xuaun](https://www.frontendmentor.io/profile/xuaun)


____
<br>

# <p id="portuguese">Frontend Mentor - Solução do projeto de Componente de armazenamento de dados Fylo</p>

## Contexto

Esta é uma solução para o [desafio de componente de armazenamento de dados Fylo no Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Os desafios do Frontend Mentor ajudam você a melhorar suas habilidades de codificação construindo projetos realistas.

> Seu desafio é criar esse componente de armazenamento de dados e fazer com que ele tenha a aparência mais próxima possível do design.

## Lista de conteúdos

- [Visão Geral](#visão-geral)
  - [Desafio](#desafio)
  - [Prints](#prints)
  - [Links](#links-pt)
- [Meu processo](#meu-processo)
  - [Tecnologias utilizadas](#tecnologias-utilizadas)
  - [O que eu aprendi](#o-que-eu-aprendi)
- [Autor](#autor)

## Visão Geral

### Desafio

Os usuários devem ser capazes de:

- Visualizar o layout ideal dependendo do tamanho da tela do dispositivo

### Prints

#### Computador

<p align="center">
  <img src="./src/design/desktop-screenshot.png" alt="Print da tela no Desktop" title="Print da tela no Desktop" width="600px" />
</p>

#### Celular

<p align="center">
  <img src="./src/design/mobile-screenshot.png" alt="Print da tela no Celular" title="Print da tela no Celular" width="300px" />
</p>

### <p id="links-pt">Links</p>

- Link da solução: [Repositório no GitHub](https://github.com/xuaun/fylo-data-storage-component) e a [página da minha solução no Frontend Mentor](https://www.frontendmentor.io/solutions/responsive-fylo-data-storage-component-TAEMujbyUi)
- Site com a solução: [Página do projeto no ar](https://xuaun.github.io/fylo-data-storage-component/)

## Meu processo

### Tecnologias utilizadas

- HTML5
- CSS
- Flexbox
- CSS Grid
- Media Query + calmp()

### O que eu aprendi

Neste projeto eu pude utilizar conceitos de flexbox e grid, de variáveis e de media query no CSS, além de usar um design pronto do Figma para a elaboração deste componente. Eu também usei `rem` para medidas, `clamp()` para ajudar na responsividade e metodologia BEM para nomear classes.

Eu aprendi a fazer uma barra de progresso com valores fixos usando css.

```css
.storage__progression {
  background-color: var(--background-progression-bar);
  width: clamp(26.2rem, -0.664rem + 71.636vw, 45.9rem);
  height: 2rem;
  border-radius: 1rem;
  margin-bottom: 0.8rem;
  display: flex;
  align-items: center;
}

.storage__usage {
  border-radius: 0.8rem;
  width: clamp(19.3rem, -0.609rem + 53.091vw, 33.9rem);
  height: 1.4rem;
  margin: 0.3rem;
  background: var(--gradient-background);
  background: var(--gradient-1-moz);
  background: var(--gradient-1-webkit);
  background: var(--gradient-1);
  filter: var(--gradient-a-filter);
  position: relative;
}
```

## Autor

- Website - [Portfólio - João Víctor de Araujo Lima](https://xuaun.github.io/)
- Frontend Mentor - [@xuaun](https://www.frontendmentor.io/profile/xuaun)

