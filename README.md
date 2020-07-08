# Aprendizado MEAN

## O que é o MEAN?

A MEAN Stack é uma solução completa para desenvolvimento de Single Page Applications (SPA) na plataforma Node.js utilizando AngularJS para views dinâmicas, Express para construção de APIs REST de alto nível e MongoDB para persistência. A combinação desse quarteto resulta na "onipresença" da linguagem JavaScript em todas as camadas da aplicação.

Aprenda nesse workshop como essas três tecnologias combinam-se entre si e pratique criando uma aplicação do início ao fim. Principais tópicos:​

**Visão geral da Stack** – Projeto de exemplo, organização e escopo.

**Express** – Configuração e seus principais middlewares. Criação das rotas da aplicação. Dados voláteis disponibilizados pela API criada. Uso de Generators para ajudar na programação assíncrona.

**Angular 1.x** – Data binding, rotas, diretivas, controllers, módulos. Nesta etapa, dados voláteis serão utilizados para exercitar os conceitos.

**Angular 1.x/Express** – Integração do cliente Angular com o backend através de serviços especializados do Angular como $http e $resource

**MongoDB** – Introdução ao MongoDB: busca, inclusão, alteração e atualização através do seu cliente em linha de comando.

**Express/MongoDB** – Integração do back-end como MongoDB através do Mongoose, ferramenta ODM especializada na criação de esquemas.

**Outras ferramentas** – Karma Test Runner e Protractor​


| Syntax      | Description |
| ----------- | ----------- |
| **MongoDB**       | MongoDB é um software de banco de dados orientado a documentos livre, de código aberto e multiplataforma, escrito na linguagem C++. Classificado como um programa de banco de dados NoSQL, o MongoDB usa documentos semelhantes a JSON com esquemas.       |
| **Express**       | O Express.js, ou simplesmente o Express, é uma estrutura de aplicativo da Web para o Node.js, lançada como software livre e de código aberto sob a Licença MIT. Ele foi projetado para criar aplicativos da Web e APIs. Foi chamado de estrutura de servidor padrão de fato para o Node.js.        |
| **AngularJS**     | AngularJS é um framework JavaScript código aberto, mantido pelo Google, que auxilia na execução de single-page applications.        |
| **Node.js**       | Node.js é um interpretador de JavaScript assíncrono com código aberto orientado a eventos, criado por Ryan Dahl em 2009, focado em migrar a programação do Javascript do cliente (frontend) para os servidores, criando aplicações de alta escalabilidade (como um servidor web)[1], manipulando milhares de conexões/eventos simultâneas em tempo real numa única máquina física.        |


Iniciando um projeto

```
npm init -y
```


Instalando dependências do projeto

```
npm install http-server --save
npm install angular-br-filters --save
npm install angular-i18n --save
npm install angular-input-masks --save
npm install angular-ui-mask --save
npm install chosen-js --save
npm install acorn --save
npm install highcharts --save
npm install highcharts-ng --save
npm install iframe-resizer --save
npm install ng-file-upload --save
npm install ng-table --save
npm install ui-select --save
npm install moment --save
npm install bufferutil --save
npm install utf-8-validate --save
npm install puppeteer --save
```