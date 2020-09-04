<h1 align="center">
    <img alt="Proffy" src=".github/logo.svg" height="100px" />
    </br>
</h1>
<h2 align="center">
   Node.js | ReactJS | React Native
</h2>

<p align="center">
<a href="https://www.linkedin.com/in/felipe-gon%C3%A7alves-33bb09187/">
    <img alt="Made by" src="https://img.shields.io/badge/made%20by-Felipe%20Gonçalves-%239871F5"></a>
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/felipesgt/proffy?style=flat-square">
  <img alt="GitHub" src="https://img.shields.io/github/license/felipesgt/proffy?style=flat-square"> 
</p>
<p align="center">
  <a href="#-sobre-o-projeto">Sobre o Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-tecnologias-usadas">Tecnologias Usadas</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-executando">Execução</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
   <a href="#-licença">Licença</a>
</p>



## 📚 Sobre o Projeto
**Proffy** é uma aplicação desenvolvida na  durante a **Next Level Week #2** da RocketSeat e que possui formato Web e Mobile, onde professores podem oferecer aulas de acordo com sua disponibilidade, custo e especialização e alunos podem vir a contratar seus serviços. 


## 🚀 Tecnologias Usadas
  Tecnologias usadas no desenvolvimento dessa aplicação

- [Node.js](https://nodejs.org/en/)
- [ReactJS](https://reactjs.org/)
- [React Native](https://reactnative.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [Expo](https://expo.io/)
- [Express](https://expressjs.com/pt-br/)
- [axios](https://github.com/axios/axios)
- [React Router DOM](https://reacttraining.com/react-router/)
- [React Navigation](https://reactnavigation.org/)


## ⚙ Executando

  ### *Requisitos*:

- [Node.js](https://nodejs.org/en/)
- [Yarn](https://classic.yarnpkg.com/)
- [Expo](https://expo.io/)

1. Clone o projeto com o Git e entre na pasta.

```bash
$ git clone https://github.com/felipesgt/proffy.git && cd proffy
```

2. Executando a Aplicação:

  ### Executando a API
```bash
  $ cd server
  # Instalando as dependências do projeto.
  $ yarn # ou npm install
  # Crie as tabelas do banco de dados.
  $ yarn knex:migrate # ou npm run knex:migrate
  # Inicie a API
  $ yarn start # ou npm start
  ```


  ### Web
  ```bash
  # Certifique-se de que a API está rodando antes de qualquer coisa.
  # Agora acesse a pasta
  $ cd web
  # Instale as dependências do projeto.
  $ yarn # ou npm install
  # Inicie a aplicação web
  $ yarn start # ou npm start
  ```

  ### Aplicação mobile
  ```bash
  # Certifique-se de que a API está rodando antes de qualquer coisa.
  # Certifique-se de que o arquivo'packages/mobile/src/services/api.ts'
  # possui o IP da sua API fornecido pelo Expo.
  # Agora acesse a pasta
  $ cd mobile
  # Instalando as dependências do projeto.
  $ yarn # ou npm install
  # Inicie a aplicação mobile
  $ yarn start # ou npm start
```


## 📜 Licença

Esse projeto está sob a licença MIT [LICENSE](LICENSE.md) 

