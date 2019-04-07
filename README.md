# WoMakersCode - Portal

**[Veja um preview](https://womakerscode.github.io/networking/)**

## Instalação & Configuração

### Utilizando RubyGems:

Siga as instruções abaixo para configuração completa:

1. Se deseja executar o site na sua máquina, instale o [Ruby](https://www.ruby-lang.org/pt/documentation/installation/)
2. Faça um fork deste repositório e clone para sua máquina
3. Instale os recursos através da linha de comando: `bundle install`
4. Executando em sua máquina: `bundle exec jekyll serve`

### Incluindo o seu perfil na seção de voluntárias:

Siga as instruções abaixo para configuração completa:

1. Faça um fork deste repositório em seu GitHub
2. Navegue até a pasta `_posts` e crie um arquivo com a data atual, em formato americano, seguido do seu nome. Exemplo `2019-03-08-cynthia-zanoni.html`
3. O arquivo deve manter a seguinte estrutura:
```
---
layout: post
title:  "Cynthia Zanoni"
date:   2017-10-26 23:45:13 -0400
image: '/img/posts/cynthia-zanoni.jpg'
linkedin: http://br.linkedin.com/in/cynthiazanoni
facebook:
twitter: http://www.twitter.com/cynthiazanoni
instagram:
hasBio: yes
permalink: cynthia-zanoni
---
```
**Entendendo a configuração do perfil**

* title: campo com o seu nome
* date: data em formato americano
* image: caminho da imagem para sua foto de perfil (você terá que acessar a pasta `img` e fazer upload de uma foto sua
* linkedin, facebook, twitter, instagram: links de suas redes sociais. Caso não tenha ou não queira divulgar, deixe em branco
* hasBio: se você escrever um texto no formato de biografia, adicione um `yes` no campo. Caso não tenha escrito, deixe o campo vazio
* permalink: URL personalizada para o seu perfil, ela não pode conter nenhum caractarecer especial, como ç ou acentos

4. Após preencher o arquivo, você deverá realizar um `commit` para que sua alteração seja publicada dentro de seu GitHub. 

5. Com o `commit` feito, irá aparecer uma opção, em seu GitHub, chamada `Compare & Pull Request`. Clique e siga o passo a passo para solicitar a sua inclusão no site. O Pull Request criará uma tarefa para as administradoras da organização WoMakersCode no GitHub e elas irão avaliar a sua solicitação.

Tem dúvidas sobre versionamento e GitHub? Acesse esse [guia rápido.](https://blog.da2k.com.br/2015/02/04/git-e-github-do-clone-ao-pull-request/)

## Copyright and License

Copyright 2015-2019 WoMakersCode. Code released under the [MIT](https://github.com/womakerscode/networking/blob/gh-pages/LICENSE) license.
