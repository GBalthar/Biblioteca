### Instruções e Boas Práticas de React

---

#### Requisitos

- Editor de texto (Visual Studio Code)
- Navegador (Chrome) para aplicar em páginas
- JavaScript
- HTML e CSS
- Node.js
- NPM

---

#### Informações

- É uma biblioteca de JavaScript
- JSX não é necessário mas é um grande facilitador da renderização do código, ele permite o uso de JavaScript dentro do HTML da página. Ele precisa de um transpilador para funcionar no navegador e deve sempre aparecer entre chaves no código.
- A pasta *public* é visível para o usuário, já a *src* contém informações privadas de código.

---

#### Criação do Projeto

- No Git Bash, usar o comando **npx create-react-app *nome do projeto*** para criar o projeto com os módulos necessários para a aplicação.
- Ainda no Git Bash, dar o comando **npm start** dentro da pasta do projeto para rodar a aplicação. Uma dica é usar o terminal do Visual Studio Code para dar esse comando.
- Depois disso, limpamos o código inicial do React para iniciar o trabalho.
  - Na pasta *public* temos o ícone da página que aparece na aba do navegador (arquivo.ico), o index.html, que mantemos como base da aplicação, imagens e manifesto do React, que podem ser excluídos.
  - Na pasta *src*, vamos deletar os arquivos App.test.js, reportWebVitals.js, logo, e setupTests.js. Esses arquivos podem ser utilizados no futuro, mas por enquanto vamos retirá-los. Depois disso, é preciso corrigir o arquivo *index.js*, que está puxando arquivos excluídos.
  - Ainda na pasta *src*, vamos criar uma pasta chamada *Components*. Dentro dessa pasta, vamos criar pastas para cada componente que vamos criar, começando pela pasta *App*.
  - No arquivo *App*, vamos remover o logo e limpar o código dentro do *return* da função *App* e ali vamos começar a programar.


---

#### Componentes

- São os recursos de JavaScript, incluindo o *App*, que são criados e inseridos no React. Eles sempre iniciam seus nomes com letra maiúscula, por boas práticas, e ficam dentro da pasta *Components* que criamos anteriormente.
- É necessário agrupar o código em um "pai". Para isso, usamos um fragmento de HTML, colocando o código dentro de um comando desta forma: <> *código* </> ou usando uma *div*.
- No final desse arquivo JavaScript, é necessário exportá-lo para o React usando a linha de código **export default *NomeDoComponente***.
- Para inserir um componente no arquivo principal (seja o *App* ou o próprio componente chamando um arquivo .*css*), nós o chamamos usando o comando **import *NomeDoComponente* from '../Caminho do Arquivo'**. E depois para usá-lo dentro do código, usamos o comando <*NomeDoComponente*/>.

---

#### Estrutura

- **Hooks** - São funções conectadas a componentes da página, que são disparadas conforme interação com os mesmos.
  - **State Hooks** - Atribuem memória aos componentes, desta forma os estados se atualizam sozinhos conforme são feitas as chamadas dentro dos componentes. Usamos esse recurso chamando a função **import {useState} from 'react';** no início do código.
  - **Effect Hooks** - Atribuem uma reação às ações realizadas nos componentes, desta forma os estados se atualizam sozinhos conforme são feitas as chamadas dentro dos componentes. Usamos esse recurso chamando a função **import {useState, useEffect} from 'react';** no início do código. *Note que esta função chama o os dois hooks*.

---

#### Ciclo de Vida

- Stateful - São componentes que guardam memória.
- Stateless - São componentes que não guardam memória.

---

#### Webpack

- Babel
- Source Map: Ajuda a debugar códigos. É muito importante usar isso.

---

#### ESLint

- Plugin para trabalhar em grupo e melhorar a qualidade do código, ela aponta erros de código.

---

#### Elementos

- Key

---

#### Para Aprender

- (Arquitetura) Flux e Redux (Biblioteca)
- Imutabilidade, Rest e Redux
- TDD e BDD com Jest
- Debugging: React Developer Tools e Redux DevTools extensões do Chrome
- Middlewares e Enhanced Stores
- ReduxJS/Toolkit
- Ler Redux Style Guide
- Ducks Pattern e High-Order-Reducers
- Component Containers
- Hooks Everywhere
- https://github.com/renatobenks/react-redux-talk
- https://pt-br.reactjs.org/docs/hooks-intro.html
- Treinar Effect Hooks

---

#### "Hacks" Aprendidos

- Introdução ao React: https://www.youtube.com/watch?v=ib67hlBpSY4&ab_channel=ProgramadorEspartano
- CSS in JS: **npm install --save styled-components** :arrow_right: Serve para estilizar os componentes com CSS dentro do React.
- Extensão de atalhos do React:
  - **nfc** - Traz o código para um componente exportável com o nome do arquivo que você acabou de criar.



---

:white_check_mark: Por hora, é só, mas a intenção é sempre atualizar esse documento com novos aprendizados, provavelmente algo foi esquecido e será lembrado no futuro. :smile: