[![Build Status](https://travis-ci.org/womakerscode/networking.svg?branch=master)](https://travis-ci.org/womakerscode/networking)
![Dependecies](https://david-dm.org/womakerscode/networking.svg)

# Novo Site: WoMakersCode

![alt_text](https://user-images.githubusercontent.com/2198735/34808410-fa314386-f675-11e7-9dbf-3dd9b06534d8.png)

Desenvolvimento de um novo site do **[WoMakersCode](womakerscode.org/)**. Com intuito de deixá-lo mais intuitivo e mais colaborativo para todas as pessoas.

## Recursos Utilizados no Desenvolvimento do Projeto: 💻

- Visual Studio Code
- Node.js - [DOWNLOAD](https://nodejs.org/pt-br)
- Jekyll - [Docs](https://jekyllrb.com/)
- HTML, CSS & JavaScript
- Boostrap 3/4 - [DOWNLOAD](https://getbootstrap.com/)
- Node Static Page Generator - [DOWNLOAD](https://github.com/Chalarangelo/node-static-page-generator)

## Como Faço para executar o projeto?! 🚀

É bem simples. Depois de baixar o **Node.js** em sua máquina basta seguir os passos abaixo:

1) Faça um fork desse projeto.

2) Após isso, execute o comando **dentro da pasta src**: 

```
> npm install
```

Pois ele irá instalar todas as dependências necessárias para a execução do projeto. Observem que ele irá criar uma pasta chamada **node_modules**

3) Depois, bastam executar o comando abaixo **dentro da pasta src**:

```
> npm run start
```

E vòilá! O projeto será executado na porta **http://127.0.0.1:8080/**. Conforme podem ver na imagem de exemplo abaixo:

![alt_text](https://i.imgsafe.org/51/5167d436cd.png)

Caso deseja criar um novo arquivo .html, basta criar um arquivo dentro da pasta **pages/** um arquivo .md. Por exemplo:

```
pages/teste.md

```

Daí basta começar a criar a página no formato **Markdown** ou **Jekyll**. Depois que concluir a página, basta executar o seguinte comando no prompt de comando:

```
> npm rum build:pages
```

Este comando irá criar uma espécie de 'transpiler' do que você criou no arquivo **teste.md** e criará um arquivo **teste.html** na pasta: build/..

Com isso, basta começar a fazer as alterações necessárias que o projeto automaticamente irá alterar em tempo real para você!

Após isso, execute o comando para visualizar as mudanças realizadas **dentro da pasta src**:

```
> npm run start
```

Caso tenham dúvidas com respeito ao tópico acima, não se hesite em abrir uma **[ISSUE](https://github.com/WoMakersCode/networking/issues)**

## Observações Finais: ⭐️

Esse projeto foi baseado no **[Node Static Page Generator](https://github.com/Chalarangelo/node-static-page-generator)**. Caso alguém deseja contribuir com o projeto (criando uma nova página), recomendo que dêem uma olhada no **[README.md](https://github.com/WoMakersCode/networking/blob/master/README.md)** do projeto, para que possa entender como funciona o código. 
Procurei fazer algumas modificações na arquitetura do projeto original, visando justamente a melhoria e qualidade na entrega do código.
Dúvidas, não hesite em contatar-nos, abrindo uma **[ISSUE](https://github.com/WoMakersCode/networking/issues)** que estaremos tirando todas as dúvidas inerente ao projeto desenvolvido aqui! 😃

## Desejam Propor Melhorias no Código? Façam Pull Request!!! 🔥

Caso desejam que eu implemente algo no código, abram uma [**ISSUE**](https://github.com/WoMakersCode/networking/issues) nesse repositório. Assim, todos poderão colaborar para o melhor desenvolvimento desse projeto. E sintam-se à vontade em fazer Pull Requests!! ❤️ ❤️ ❤️️
