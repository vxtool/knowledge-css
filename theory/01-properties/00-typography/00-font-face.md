@font-face
========

@font-face permite que autores especifiquem fontes online para exibir texto em suas páginas web. Permitindo autores a proporcionar suas próprias fontes, @font-face elimina a necessidade de depender do limitado número de fontes que os usuários tem instalado em seus computadores.

~~~

@font-face {
  font-family: 'FontAwesome';
  src: url('fonts/fontawesome.eot?v=4.2.0');
  src: url('fonts/fontawesome.eot?#iefix&v=4.2.0') format('embedded-opentype'), url('fonts/fontawesome.woff?v=4.2.0') format('woff'), url('fonts/fontawesome.ttf?v=4.2.0') format('truetype'), url('fonts/fontawesome.svg?v=4.2.0#fontawesomeregular') format('svg');
  font-weight: normal;
  font-style: normal;
}

~~~