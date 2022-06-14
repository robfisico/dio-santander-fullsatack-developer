#Anotações Bootcamp Santander Fullsatack Developer

##HTML

Utilizando o VScode por exemplo, o primeiro passo é criar um arquivo index.html

Para iniciar uma página começamos com <!DOCTYPE html>

Na tag **<head>** colocamos os metadados para o documento. Como idioma e titulo na aba do navegador.

A seguir, usamos a tag <html> </html> para dar início a raiz de um documento HTML

A inserção da tag <meta charset = “utf-8” /> possibilita a utilização de caracteres especais do PT-BR

A tag <title> </title> define o que aparecerá na aba do navegador

**</head>**

Após o *head*, iniciamos o <body> que é o corpo do documento.

Dentro do <body> chamamos a tag <header>cabeçalho</header>. Nele podemos chamar o elemento <h1></h1> que é cabeçalho de maior grau/relevância da seção.

Após o header podemos usar o elemento *section*, que representa uma seção genérica do documento e aceita a criação de cabeçalhos de grau *h1* a *h6*.

É possível utilizar a tag <p> </p> para introduzir um parágrafo.

Utilizando o elemento <a> com o atributo href, nós colocamos um hiperlink para uma pagina desejada. quando há necessidade de abrir uma nova aba clicando no hiperlink, também se utiliza target=”_blank”. 

Exemplo: *<p>Lorem ipsum dolor sit amet, <a href="[https://www.linkedin.com/in/robfisico/](https://www.linkedin.com/in/robfisico/)" target="_blank">consectetur adipiscing</a> elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation <a [href="mailto:robfisico@gmail.com](mailto:href=%22mailto:robfisico@gmail.com)">ullamco</a> Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>*

No exemplo acima o parágrafo foi iniciado, depois utilzado o elemento a com o atributo href, especificando a abertura em outra aba com target=”_blank” e na sequencia foi utilizado outro elemento <a> com o atributo href=”mailto: exemplo@mail.com

O elemento <article> representa uma composição completa ou independente em uma página

Dentro do <article></article> também é possível fazer uso de cabeçalhos <header> e elementos h1 a h6.

Após terminar a section </section> pode ser adicionado o elemento <footer>rodapé</foother>.

Por fim, após o rodapé fechamos os elementos </body> e </html>, para indicar sua finalização.

Conseguimos utilizar imagens nas páginas, para isso usamos o elemento <img> (não precisar fechar tag </img>). Este elemento possui apenas dois atributos:

<img src=”img/avatar.jpg”> carrega a imagem a partir de seu endereço. Enquanto <img alt=”Descrição da imagem”>. Recurso útil quando a foto não é carregada e para leitores de tela.

Sites úteis: unsplash (algumas imagens sem direitos autorais); tinypng (retirar metadados e reduzir tamanho).

Os elementos listas servem para agrupar coleção de itens. Podem ser ol, ul ou li.

<ul> ordem os itens não é importante. item 1, item 2…

<ol> ordem importante. 1° item 1, 2° item2…

<li> representa um item da lista