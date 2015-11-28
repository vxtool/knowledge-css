Pseudo-classes
========

Existem vários tipos de pseudo-classes. Podemos separá-las em dois grandes grupos:Estruturais e Dinâmicas. Existem outras pseudo-classes que não se encaixam nestes dois grupos principais, que controlam a interface do usuário, elementos de URLs e etc.

### Pseudo-classes Dinâmicas

As pseudo-classes dinâmicas controlam os estados dos elementos. Abaixo, vão alguns deles:

`:hover` – quando passamos o mouse em cima do elemento.

`:active` – quando ativamos o elemento. Por exemplo, quando clicamos em um link e não soltamos o botão do mouse. Nesse momento, estamos ativando a ação do elemento. Esse estado é ativado também quando navegamos pelos links pelo teclado utilizando o TAB. Este estado não há em todos os elementos.

`:visited` – quando o link é visitado.

`:focus` – quando um elemento recebe foco. Muito utilizado em campos de texto. Quando clicamos em cima um campo de texto para escrever, o elemento está ganhando foco.

### Pseudo-classes Estruturais

As pseudo-classes estruturais servem para selecionarmos um elemento da estrutura do código. Existem várias, por exemplo:

`:first-child` – seleciona o primeiro filho de um outro elemento. <br>
`:last-child` – seleciona o último filho de um elemento. <br>
`:root` – representa um elemento que é a raiz do documento. No HTML 4, é sempre a tag HTML. <br>
`:nth-child()` – permite que selecionemos qualquer elemento no meio de um grupo de elementos. Por exemplo, você pode selecionar linhas de uma tabela. Assim, podemos fazer uma tabela zebrada, sem a ajuda de javascript. Há variações dessa pseudo-classe para podermos pegar os elementos de baixo para cima (`:nth-last-child`) e assim por diante. Testei aqui e isso não funcionou no meu FF3 (mac). <br>
`:lang()` – seleciona elementos que tem o atributo lang com um valor específico. ( [exemplo](http://tableless.com.br/wp-content/uploads/2009/03/lang.html) )


### Pseudo-classes Estruturais - target

O seletor target do CSS3 nos permite aplicar uma formatação ao elemento que é alvo ativo de um link. ( [exemplo](http://www.uxdesign.blog.br/curso-html5-css3/target.html) )

~~~
div:target { z-index: 1000; }
~~~

### Pseudo-classes Estruturais - atributo

No CSS3 também é possível formatarmos elementos que possuam um atributo específico. 

~~~
a[title] {color: red;} 
a[href="index.html"] {color: red;} 
img[alt*="web"] {border: 5px solid red;} 
a[href$=".pdf"] {background: url(pdf.png)}
~~~