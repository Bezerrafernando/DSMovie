#Objetivos do projeto

#Parte 1 do Projeto

Criar o projeto e salvar no Github
Criar o layout da barra superior
Criar o layout da listagem de filmes

#Passo: preparação
Dica: extensões do VS Code
Color Highlight
Live Server

#Passo: criar projeto HTML
HTML é uma linguagem de marcação que define a estrutura do conteúdo de uma página web.

O código HTML segue uma estrutura hierárquica de elementos. Cada elemento corresponde a uma tag que deve abrir e fechar, respeitando a hierarquia.

Um site web pode conter vários arquivo HTML. Geralmente o arquivo HTML que será aberto por padrão se chama index.html.

#Passo: salvar primeira versão no Github
Caso não tenha configurado ainda seu Github

git init

git add .

git commit -m "Projeto criado"

git branch -M main

git remote add origin git@github.com:seuusuario/seurepositorio.git

git push -u origin main

#Passo: adicionar Bootstrap ao projeto
Bootstrap é um framework CSS. Ele fornece recursos que facilitam algumas tarefas na estilização das nossas páginas web.

Site oficial do Bootstrap:

https://getbootstrap.com

COMMIT: Bootstrap
Passo: fonte do Google Fonts

@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;700&display=swap');

COMMIT: Google Fonts

#Passo: Barra superior PARTE 1
Referências sobre HTML e CSS:

https://developer.mozilla.org/pt-BR/docs/Web/HTML

https://developer.mozilla.org/pt-BR/docs/Web/CSS

https://www.w3schools.com/html/

https://www.w3schools.com/css/

https://css-tricks.com/snippets/css/a-guide-to-flexbox/

@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;700&display=swap');

:root {
  --color-primary: #4d41c0;
  --bg-gray: #e8e8e8;
}

* {
    box-sizing: border-box;
    font-family: 'Open Sans', sans-serif;
}

html, body {
    background-color: var(--bg-gray);
}

a, a:hover {
  text-decoration: none;
  color: unset;
}

COMMIT: Barra superior PARTE 1

#Passo: Barra superior PARTE 2
COMMIT: Barra superior PARTE 2
Passo: Card de filme
Vamos usar imagens o The Movie Database:

https://www.themoviedb.org

COMMIT: Card de filme
#Passo: Listagem de cards
Grid System do Bootstrap:

https://getbootstrap.com/docs/5.1/layout/grid/

Breakpoints do Bootstrap:

https://getbootstrap.com/docs/5.0/layout/breakpoints/

COMMIT: Listagem de cards

Parte dois Projeto 2:

Layout do formulário
Layout das avaliações com estrelas
Polimento na listagem

Passo: Formulário PARTE 1
Passo: Formulário PARTE 2
Passo: Avaliação com estrelas
Passo: Polimento da listagem





