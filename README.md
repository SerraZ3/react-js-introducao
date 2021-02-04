[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/SerraZ3/react-js-introducao">
    <img src="./img/react.png" alt="Logo" width="300">
  </a>

  <h2 align="center">Introdução ReactJs</h2>

  <p align="center">
    Projeto desenvolvido para aulas
    
    
  </p>
</p>

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Sumário</summary>
  <ol>
    <li>
        <a href="#sobre-o-reactjs">Sobre o ReactJs</a>
        <ul>
            <li><a href="#o-que-é">O que é</a></li>
            <li><a href="#origem">Origem</a></li>
        </ul>
    </li>
    <li>
        <a href="#como-começar">Como começar</a>
        <ul>
            <li><a href="#pré-requisito">Pré-requisitos</a></li>
            <li><a href="#instalação">Instalação</a></li>
        </ul>
    </li>
    <li>
        <a href="#criando-um-projeto-do-zero">Criando um projeto do ZERO</a>
        <ul>
            <li><a href="#criando-projeto">Criando projeto</a></li>
            <li><a href="#estrutura-de-arquivos">Estrutura de arquivos</a></li>
            <li><a href="#hello-world">Hello World</a></li>
        </ul>
    </li>
    <li>
        <a href="#entendendo-o-que-é-um-component">Entendendo o que é um component</a>
        <ul>
            <li><a href="#criando-compenent">Criando component</a></li>
            <li><a href="#o-que-é-props">O que é props?</a></li>
            <li><a href="#trabalhando-com-props">Trabalhando com props</a></li>
            <li><a href="#o-que-é-state">O que é state?</a></li>
            <li><a href="#trabalhando-com-state">Trabalhando com state</a></li>
            <li><a href="#ciclo-de-vida-de-um-compenent">Ciclo de vida de um component</a></li>
        </ul>
    </li>
    <li><a href="#contribuidores">Contribuidores</a></li>
  </ol>
</details>

## Sobre o Reactjs

### O que é?

O ReactJs é uma biblioteca JavaScript declarativa, eficiente e flexível para a criação de interfaces de usuário (UI)" segundo os criadores.

Desde de seu surgimento vem ganhando popularidade e sua comunidade vem crescendo cada vez mais.

### Origem

Ela foi criado pelo Facebook em 2011 para projetos internos e em 2013 foi aberto para a comunidade. Ela foi desenvolvida para a criação de sites web de forma rápida, escalável e simples. Em seguida ela foi adaptada para aplicações mobile com o surgimento do React-Native, que a partir de um código JavaScript é possível criar uma aplicativo para Android e IOS.

---

## Como começar

### Pré-requisitos

Para começar a aprender é necessário saber algumas linguagens e usar algumas ferramentas para facilitar o aprendizado.

Linguagens:

- Javascript
- JSX (Entender como funciona)
- HTML e CSS (é necessário pois todo o JS será convertido em HTML, CSS e JS no final)

Ferramentas:

- NPM (Node Package Manager, Gerenciador de Pacotes Node)

### Instalação

O ReactJs utiliza o `npm` como gerenciador de pacotes. Com ele é possivel instalar o Reactjs e outros pacotes posteriormente.

Para nosso tutorial utilizaremos as seguintes versões do `node` e `npm`

- node: v14.15.1^
- npm: v6.14.1^

Além disso é necessário instalarmos o `create-react-app` para podermos criar nosso projetinho

### Instalando o create-react-app

Instalando create-react-app com npm:

Para instalar com o npm basta rodar o seguinte comando

```sh
npm install create-react-app -g
```

O que esse comando está fazendo? `npm` é o gerenciador, `install` é o comando do `npm` que diz "Hey, quero instalar um pacote", `create-react-app` é o nome do pacote que quero instalar e `-g` significar "global", ou seja, está dizendo "hey, instalar o pacote X de forma global para que eu sempre possa usar ele"

---

### Criando um projeto do zero

Existem duas formas para criar um projeto em ReactJs.

A primeira forma é usando o `create-react-app` que instalamos anteriormente.

A segunda é usando o `npx`. Ele usa os pacotes do `npm` sem precisar baixá-los. Para usar o `npx` é necessário que a versão do `npm` seja maior que `v5.2`.

Para verificar se o `npx` está instalado na sua máquina rode o seguinte comando:

```sh
npx -v
# Comentário
# saida deve ser a versão do seu npx
# exemplo: 6.14.8
```

Criando projeto com create-react-app:

Rode o seguinte comando para criar seu projetinho

```sh
create-react-app nome-projeto
```

Em `nome-projeto` você deve por o nome que será o seu projeto

Criando projeto com npx:

Esse comando diferente do anterior, ele não instala as configurações do `create-react-app` na sua máquina, ele busca no banco de dados do `npm` e roda direto na sua máquina

```sh
npx create-react-app nome-projeto
```

---

## Contribuidores

- [Henrique Serra](https://github.com/SerraZ3)

[contributors-shield]: https://img.shields.io/github/contributors/SerraZ3/react-js-introducao.svg?style=for-the-badge
[contributors-url]: https://github.com/SerraZ3/react-js-introducao/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/SerraZ3/react-js-introducao.svg?style=for-the-badge
[forks-url]: https://github.com/SerraZ3/react-js-introducao/network/members
[stars-shield]: https://img.shields.io/github/stars/SerraZ3/react-js-introducao.svg?style=for-the-badge
[stars-url]: https://github.com/SerraZ3/react-js-introducao/stargazers
[issues-shield]: https://img.shields.io/github/issues/SerraZ3/react-js-introducao.svg?style=for-the-badge
[issues-url]: https://github.com/SerraZ3/react-js-introducao/issues
[license-shield]: https://img.shields.io/github/license/SerraZ3/react-js-introducao.svg?style=for-the-badge
[license-url]: https://github.com/SerraZ3/react-js-introducao/blob/main/LICENSE
