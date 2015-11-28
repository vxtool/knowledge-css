Pseudo-elements
========

Pseudo-elementos servem para adicionar efeitos a um seletor ou parte dele. A seguir, veremos dois pseudo-elementos do CSS3 muito úteis: :before e :after.


###:before

O pseudo-elemento :before do CSS3 serve para adicionar alguma formatação ou conteúdo antes de um elemento.

~~~
li:before {
   content: "Livro: "; 
   color: #D35529;
}
~~~

### :after

Por sua vez, o pseudo-elemento :after do CSS3 serve para adicionar alguma formatação ou conteúdo após um elemento.

~~~
li:after {
   color: #D35529;
   font-weight: bold;
}
~~~