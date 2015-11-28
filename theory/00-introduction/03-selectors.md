Selectors
========

Seletores são os elementos que o CSS pode formatar. São eles: Tags do HTML, classes (class) e identificadores (ID´s)


## Tags

Qualquer tag do HTML poderá ser formatada em CSS, porém, algus recursos não provocarão efeito nenhum. Por exemplo: aplicar cor em uma tag .
Para formatar tags, basta colocar o nome da tag como seletor. Exemplo:

~~~
body { 
	font-family: Verdana, Arial, Tahoma; 
	font-size: 12px; 
	background-color: #E3E3E3; 
}
~~~

## Classes

Diferente das tags, as classes não são aplicadas automaticamente no HTML. Uma vez criada, uma classe deverá ser aplicada manualmente no HTML.
A função das classes é fazer formatações específicas onde as definições de tags não são atendidas.

~~~
.recuo { 
	font-size: 10px; 
	color: #ff0000; 
}
~~~

## Identificadores

Os identificadores em CSS correspondem ao ID no HTML, ou seja, quando você criar um ID no HTML significa que ele poderá ser formatado no CSS.

~~~
#site { 
	width: 500px; 
	background-color: #ffffff; 
}
~~~