[![GitHub license](https://img.shields.io/github/license/JhoncSilva/Proffy?style=flat-square)](https://github.com/JhoncSilva/Proffy/blob/master/LICENSE)
![GitHub last commit](https://img.shields.io/github/last-commit/JhoncSilva/Proffy?style=flat-square)

<h1 align="center" size="20">Proffy</h1>
<p align="center"> Projeto da Next Level Week #2 na trilha omnistack, pela <a target="_blank" href="rocketseat.com.br">rocketseat</a>.


<p align="center">
 <a href="#descrição">Descrição</a> •
 <a href="#status-do-projeto">Status</a> • 
 <a href="#tecnologias-utilizadas">Tecnologias</a> • 
 <a href="#dependências">Dependências</a> •
 <a href="#como-rodar">Como rodar</a> •
 <a href="#licença">Licença</a>
</p>


# Descrição 
Proffy é uma plataforma de **estudos**, onde professores e alunos se conectam por web e mobile.

Os professores se registram no servidor (atualmente só pela web) informando a matéria que ensinam, número para contato, dias disponíveis etc, e os alunos podem filtrar por esses parâmetros para encontrar o profissional que se encaixa no seu gosto.

# Status do projeto

- [x] Dias 1 ao 5

- [ ] Desafios

Todo o conteúdo da semana já está feito, começarei a fazer os desafios e atualizar o repositório.

# Tecnologias utilizadas

- React 

- React native

- Typescript

- NodeJS

- Yarn

- Expo

# Dependências

É necessário instalar o <a href="https://nodejs.org/en/">Node</a> e o <a href="https://yarnpkg.com/getting-started/install">Yarn</a> para o servidor web. E para mobile o <a href="https://expo.io/learn">Expo</a>.

Também é interessante ter um editor como o <a href="https://code.visualstudio.com/">VS Code<a/>.

# Como rodar 

Primeiro é necessário clonar o repositório:
```
https://github.com/JhoncSilva/Proffy.git
```

Depois, rodar a API
```Bash
cd Proffy/server

yarn install

yarn start
```
Após isso, você pode iniciar o servidor web:
```Bash
cd Proffy/web

yarn install 

yarn start

# a página deverá abrir automáticamente, porém se não, acesse http://localhost:3000/
```
E para iniciar o servidor mobile:
```Bash
cd Proffy/mobile

yarn install

yarn start

# no final será aberta uma página para o servidor mobile no navegador, com o QR code para acesso no celular
```
Para acessar a aplicação pelo celular, instale o expo <a href="https://play.google.com/store/apps/details?id=host.exp.exponent&hl=pt_BR">(Android)</a> <a href="https://apps.apple.com/br/app/expo-client/id982107779">(IPhone)</a>, e escaneie o QR code, ou use um emulador no computador.

# Licença
Este projeto esta sobre a <a href="https://github.com/JhoncSilva/Proffy/blob/master/LICENSE">licença MIT</a>.
