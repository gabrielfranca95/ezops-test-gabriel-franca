# Aplicação webchat com Node.js,Express, mongoose(mongodb) e socket.io
### aplicação de bate papo em tempo real.
####disponivel em: https://gabrielfranca95.github.io/webchat_comNode.js_eMongodb/

![image](https://user-images.githubusercontent.com/57453192/159144467-7b8a3e5e-8280-4128-818f-94f793871336.png)

Neste tutorial, usaremos a plataforma Node.js para criar um aplicativo de bate-papo em tempo real que envia e mostra mensagens para um destinatário instantaneamente sem nenhuma atualização de página. Usaremos o framework JavaScript Express.js e as bibliotecas Mongoose e Socket.io para conseguir isso.
Antes de começarmos, vamos dar uma olhada rápida nos conceitos básicos do Node.js
Node.js
O Node.js é framework de código aberto que executa código JavaScript fora do navegador. A vantagem mais importante de usar o Node é que podemos usar JavaScript como uma linguagem de front-end e back-end.
Como sabemos, o JavaScript foi usado principalmente para scripts do lado do cliente, nos quais os scripts eram incorporados no HTML de uma página da Web e executados no lado do cliente por um mecanismo JavaScript no navegador da Web do usuário.
O Node.js permite que os desenvolvedores usem JavaScript para escrever ferramentas de linha de comando e para scripts do lado do servidor — executando scripts do lado do servidor para produzir conteúdo dinâmico da página da Web antes que a página seja enviada ao navegador da Web do usuário.
Embora o Node seja de thread único, ainda é mais rápido ao usar funções assíncronas. Por exemplo, o Node pode processar outras coisas enquanto um arquivo está sendo lido no disco ou enquanto aguarda a conclusão de uma solicitação HTTP. O comportamento assíncrono pode ser implementado usando retornos de chamada. Além disso, o JavaScript funciona bem com bancos de dados JSON como eu executei no cardapio de delivery em um dos meus repositórios, onde você pode encontra-lo aqui mesmo no githhub e bancos de dados No-SQL. 

##Módulos NPM

O Node.js permite que os módulos das bibliotecas sejam incluídos na aplicação. Esses módulos podem ser módulos definidos pelo usuário ou de terceiros.
Módulos de terceiros podem ser instalados usando o seguinte comando:
```
npm install module_name
```
E os módulos instalados podem ser usados usando a função require() :
```
var módulo = require('module_name')
```
Em aplicativos Node, usaremos um arquivo package.json para manter as versões do módulo. Este arquivo pode ser criado por este comando:
```
npm init
```
E os pacotes devem ser instalados da seguinte forma:
```
npm install -s module_name
```
