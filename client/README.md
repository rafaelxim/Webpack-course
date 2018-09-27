Não esqueçam de entrar dentro da pasta `client` e executar o comando `npm install` antes de utilizar o projeto.

Para ativar a compilação em tempo real, dentro de `client`, execute o comando `npm run watch`.


Aprendemos neste capítulo 1 :

O papel do webpack
Instalação através do npm
Configuração do webpack.config.js
Como executar webpack através de um npm script
O conceito de entry e output
O papel de um loader
Instalação e configuração de um loader


Tentamos utilizar o parametro -p na definição de do script build-dev dentro de package.json, porém o uglifyjs não suporta o recente ECMA, para contornar, utilizamos o babili plugin webpack

Um loader trabalha em cada arquivo, já um plugin trabalha no bundle já criado.

Fazendo com que a variavel de ambiente do node funcione no windows


Neste capítulo 2 vimos:

O efeito do parâmetro -p para o build de produção.
A incompatibilidade do uglify com código que não sejam escritos em ECMASCRIPT 5.
babili como plugin que ajuda no processo de minificação.
pegadinhas na atribuição de variáveis de ambiente.
o módulos cross-env para garantir compatibilidade do nosso npm script entre diferentes sistemas operacionais.


Neste capítulo 3 vimos:

O papel do Webpack Dev Server e suas vantagens como live reloading
Como instalar o Webpack Dev Server através do npm
A criação de um script para executar o servidor
A importância da propriedade publicPath.