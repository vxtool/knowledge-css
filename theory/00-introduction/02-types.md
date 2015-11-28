Types
========

Tipos de CSS não se refere a forma de escrever as declarações e sim o local onde ele é inserido. Se ele estiver junto ao código HTML, chamamos de CSS inline, no início da página HTML ele é incorporado e quando colocado em um arquivo externo, ele é CSS linkado.

CSS Inline
O CSS Inline é aquele que é inserido junto ao código HTML, através do atributo style. Sua aplicação é bastante questionada já que o modelo fica bastante parecido com a antiga formatação via HTML.

~~~
<p style="color: #ffff00; font-size: 11px;">
~~~

CSS Incorporado
CSS incorporado é aquele que é inserido no início do código HTML dentro da tag . o modelo incorporado é melhor que o inline, mas ainda apresenta deficiências, já que ele terá efeito apenas sobre a página e não poderá ser reaproveitado para outras páginas.

~~~
<style type="text/css"> 
p { 
	font-family: Arial, Helvetica, sans-serif; 
	font-size: 10px; 
	color: #FF0000; 
} 
</style>
~~~

CSS Linkado
CSS linkado é o modelo recomendado, pois neste modelo todo o código CSS fica em um arquivo separado, podendo ser linkado a várias páginas do site. Este é o melhor modelo para promover o reaproveitamento do código.

~~~
<link href="estilo.css" rel="stylesheet" type="text/css" media="screen">
~~~