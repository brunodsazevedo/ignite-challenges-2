# **Ignite Challenges - #2**
### Desafio do curso Ignite - Rocketseat
<br>

Este repositório foi um desafio realizado pela corporação Rocketseat com intuito de firmar conhecimentos e fundamentos de componentização utilizando ReactJS

A aplicação é um sistema de serviço de streaming de séries e filmes conforme imagem ilustrada abaixo:


![2022-02-18_11-00](https://user-images.githubusercontent.com/58368716/154701419-d97d4c70-5d8b-4538-856f-b4a4d79c3edb.png)



## **Contexto do desafio**

Observando o código original, todo código HTML da aplicação estava sendo feita dentro do arquivo `App.tsx`. Por mais que no momento o código em questão esteja pequeno, é preciso avaliar a questão de novas features, ficará cada vez mais dificil dar manutenção ao código.

## **Objetivo**

O objetivo desse desafio é identificar o que pode ser componentizado no momento para deixar a aplicação com um código limpo e escalável.

Analisando o código e a aplicação, foi possível detectar os seguintes elementos a serem componentizados:

<ul>
    <li><strong>Sidebar: </strong>conteúdo que lista os botões de gênero de filmes</li>
    <li><strong>Content: </strong>conteúdo que lista os filmes de acordo com o gênero selecionado</li>
</ul>

![2022-02-18_10-58](https://user-images.githubusercontent.com/58368716/154701541-8b65d679-898f-4e27-bedd-b8e3bca51bad.png)



Foi realizado então a componentização dos elementos, possibilitando assim mais escalabilidade na aplicação e um código limpo.

## **Instalação das dependencias**
Antes de rodar a aplicação deverá ter instalado e configurado previamente o <a href="https://nodejs.org/en/">NodeJS</a> e <a href="https://yarnpkg.com/">Yarn</a>. 


Para instalar as dependências do projeto, digite a linha de comando abaixo:

`$ yarn`


## Executando a aplicação

A aplicação possui um Fake API utilizando MirageJS para listar os filmes e gêneros que serão exibidos em tela.
Execute o servidor fake para consumir a API Fake:

`$yarn server`

E logo em seguida, execute em outro terminal o comando para executar o frontent da aplicação:

`$ yarn dev`


No navegador, abra a rota http://localhost:8080 e será exibido a aplicação com a melhoria dos elementos componentizados.



https://user-images.githubusercontent.com/58368716/154701739-029843d4-1235-40fa-a4d2-fdc57aede14b.mp4




Desafio concluído com sucesso! :)
