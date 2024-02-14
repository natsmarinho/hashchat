<h1 align="center">Hashchat</h1> 

<p align="center">
<img src="https://img.shields.io/static/v1?label=Github&message=deploy&color=blue&style=for-the-badge&logo=github"/>
<img src="http://img.shields.io/static/v1?label=STATUS&message=CONCLUIDO&color=GREEN&style=for-the-badge"/>
</p>

> Status do Projeto: :heavy_check_mark: concluído

### Tópicos 

:small_blue_diamond: [Descrição do projeto](#descrição-do-projeto)

:small_blue_diamond: [Funcionalidades](#funcionalidades)

:small_blue_diamond: [Deploy da Aplicação](#deploy-da-aplicação-dash)

:small_blue_diamond: [Pré-requisitos](#pré-requisitos)

:small_blue_diamond: [Como rodar a aplicação](#como-rodar-a-aplicação-arrow_forward)

... 


## Descrição do projeto 

<p align="justify">
 Bate papo online feito durante intensivo de javascript da plataforma Hashtag.
</p>

## Funcionalidades

:heavy_check_mark: Envio de mensagens instantaneas 

:heavy_check_mark: Visualização da mensagem

:heavy_check_mark: Troca de mensagens entre indivíduos que estiverem na mesma rede  
 

## Layout ou Deploy da Aplicação :dash:

> Link do deploy da aplicação: https://natsmarinho.github.io/hashchat/
## Pré-requisitos

:warning: [Node](https://nodejs.org/en/download/) 

## Como rodar a aplicação :arrow_forward:

No terminal, clone o projeto: 

```
git clone https://github.com/React-Bootcamp-WoMarkersCode/certificate-generator
```

Depois inicie o node: 
```
node
```

Coloque os arquivos na branch do git:
```
npm i gh-pages --save-dev
```
Execute o deploy definida no arquivo package.json do projeto:
```
npm run deploy
```

## Casos de Uso
Bate papo entre pessoas da mesma rede, podendo ser usada em empresas para troca de mensagens comerciais, etc.

## Iniciando/Configurando banco de dados

cria um novo arquivo package.json:
```
npm init -y
```
Instale o framework Express.js no projeto: 
```
npm install express
```

Instale o socket.io para interligação:
```
npm install socket.io

\\No javascript:
const servidorHttp = http.createServer(aplicacao);
const io = require('socket.io')(servidorHttp)

io.addListener('connection', (socket) => {
    console.log('Um usuário conectou');
    socket.addListener('nova mensagem', (msg) => {
        io.emit('nova mensagem', msg)
    });
})

aplicacao.use(express.static('public'))

servidorHttp.listen(1000, '192.168.0.117');
```

Instale a build: 
```
npm run build
```
```
npm install
```
## Linguagens, dependencias e libs utilizadas :books:

- [Socket.io](https://socket.io/)
- [Express](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs)

...

## Desenvolvedores/Contribuintes :octocat:
[Hashtag treinamento](https://lp.hashtagtreinamentos.com/pg-inscricao-pbi-impressionador-perpetuo?origemurl=1233653045375544&src=vtsd_pbi_conv_01_bing&msclkid=48d2331ce84019e8cb9e56d014c87b90)

<p align="center"> Copyright :copyright: 2024 - Hashchat </p>
