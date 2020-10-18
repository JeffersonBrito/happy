<h1 align='center' >
    <img alt='Happy' src='.github/banner.png' />
        <br>Next Level Week #3<br/>
     ReactJS 
</h1>

<p align="center">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/JeffersonBrito/happy?style=flat-square">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/JeffersonBrito/happy?style=flat-square">
  <img alt="GitHub" src="https://img.shields.io/github/license/JeffersonBrito/happy?style=flat-square"> 
  <img alt="Made by Rocketseat" src="https://img.shields.io/badge/made%20by-Rocketseat-%237519C1?style=flat-square"><br/>
</p>
<p align="center">
  <a href="#bookmark-sobre">Sobre</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#rocket-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#boom-como-executar">Como Executar</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>

<p align='center'>
    <img alt='Happy' src='.github/happy.png' width='100%'>
</p>

## :bookmark: Sobre

O **Happy** é uma aplicação Web para auxiliar na localização de orfanatos pelo país.
  
Essa aplicação foi realizada durante a Next **Level Week #3**, projeto da [Rocketseat](https://rocketseat.com.br/).

## :rocket: Tecnologias

-  [Typescript](https://www.typescriptlang.org/)
-  [Node.js](https://nodejs.org/en/)
-  [ReactJS](https://reactjs.org/)
-  [React Native](http://facebook.github.io/react-native/)
-  [Expo](https://expo.io/)
-  [Express](https://expressjs.com/)
-  [axios](https://github.com/axios/axios)

## :boom: Como Executar

- ### **Pré-requisitos**

  - É **necessário** possuir o **[Node.js](https://nodejs.org/en/)** instalado no computador
  - É **necessário** possuir o **[Git](https://git-scm.com/)** instalado e configurado no computador
  - Também, é **preciso** ter um gerenciador de pacotes seja o **[NPM](https://www.npmjs.com/)** ou **[Yarn](https://yarnpkg.com/)**.
  - Por fim, é **essencial** ter o **[Expo](https://expo.io/)** instalado de forma global na máquina

1. Faça um clone do repositório:

### ⌨ Baixando o projeto
```bash
# Clone o Repositório
$ git clone https://github.com/JeffersonBrito/happy.git

# Acesse a pasta do projeto
$ cd happy
```


2. Executando a Aplicação:

### 🗄️ Configurando o modulo do servidor
```bash
# Acesse a pasta do servidor
$ cd server

# Instale as dependências
$ npm install

# Adicione as variáveis de ambiente
-> Crie um arquivo com o nome '.env'
# Salve o token no arquivo .env
-> PORT=4000

# Execute as migrations do banco de dados
$ npm run knex:migrate

# Execute o projeto
$ npm run start
```

### 🖥️ Configurando o modulo do site
```bash
# Acesse a pasta do servidor
$ cd web

# Instale as dependências
$ npm install

# Adicione as variáveis de ambiente
-> Crie um arquivo com o nome '.env'
# Crie uma conta gratuita no MapBox para pegar seu token
-> https://account.mapbox.com
# Salve o token no arquivo .env
-> REACT_APP_MAPBOX_TOKEN=TOKEN

# Execute o projeto
$ npm run start
```


## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.


## :rocket: Ajustes futuros! 
``` Exclusão de imagem e editar orfanato ```

---
<sup>Projeto desenvolvido com a tutoria de [Diego Fernandes](https://github.com/diego3g), da [Rocketseat](rocketseat.com.br).</sup>