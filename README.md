<p align="center"><strong>DevRadar Omnistack#10 - Rocketseat </strong></p>
<p align="center">
  <a aria-label="Versão do Node" href="https://github.com/nodejs/node/blob/master/doc/changelogs/CHANGELOG_V12.md#12.14.1">
    <img src="https://img.shields.io/badge/node.js@lts-12.14.1-informational?logo=Node.JS"></img>
  </a>
  <a aria-label="Versão do React" href="https://github.com/facebook/react/blob/master/CHANGELOG.md#16120-november-14-2019">
    <img src="https://img.shields.io/badge/react-16.12.0-informational?logo=react"></img>
  </a>
  <a aria-label="Versão do Expo" href="https://www.npmjs.com/package/expo-cli/v/3.11.5">
    <img src="https://img.shields.io/badge/expo--CLI-3.11.5-informational?logo=expo"></img>
  </a>
</p>

Projeto de uma Aplicação chamada Dev Radar, desenvolvido durante a semana Omnistack10 da Rocketseat, onde foi criado uma aplicação desde o Backend em Node.JS,
o Frontend em ReactJS e o Mobile em React Native.
A aplicação consiste em cadastrar Devs utilizando mongodb como banco de dados e para listar ou buscar devs no aplicativo, 
utilizamos API Rest.

## Instalando
Configure o MongoDB e modifique a url de conexão com o seus dados dentro do arquivo `index.js`. 

Instale todas as dependências e rode o servidor da aplicação
```bash
cd backend
yarn install
yarn dev
```
**Frontend**: execute os comandos:
```bash
cd frontend
yarn install
yarn start
```

**Mobile**: Configure a URL do seu servidor no arquivo localizado em: `src/services/api.js`, após execute:
```bash
yarn global add install expo-cli
cd mobile
yarn install
yarn start

