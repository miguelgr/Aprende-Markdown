MARKDOWN
========

> Autor: John Gruber y Aaron Swartz
>
> Fecha: 25 Marzo 2004
>
> Formato: .md


1. ¿Qué es Markdown? Una breve introducción.
2. Dingus y otras aplicaciones web.
3. GFM(Github Flavoured Markdown).
4. Markdown here! Escribe emails de impacto.
5. Markdown en tus editores: Sublime Text y Vim.
6. Multimarkdown cumple con todo.


## ¿Qué es Markdown? Una breve introducción

Markdown es un lenguaje de marcado originalmente creado por John Gruber y contribuciones de Aaron Swartz que permite escribir texto fácil de leer y escribir siguiendo una sintaxis muy simple, para convertirlo en un documento HTML o XHTML estructurado. 

¿Entonces? Mardown es:

- Un script escrito en Perl `Markdown.pl` que convierte texto a HTML.
- Una sintaxis para formatear texto plano.


Markdown se distribuye bajo licencia de código abierto BSD.
[licencia] [pl]

Sitios como Github, reddit y Stack Overflow usan markdown.


### Dingus y otras apliaciones web

* [Dingus](http://daringfireball.net/projects/markdown/dingus)

  [pl]: /http://daringfireball.net/projects/markdown/license

  [sintaxis]: http://daringfireball.net/projects/markdown/syntax
  [dingus]: http://daringfireball.net/projects/markdown/dingus


### GFM(Github Flavoured Markdown)

[GitHub Flavored Markdown](https://help.github.com/articles/github-flavored-markdown#newlines)

Github usa lo que ellos llaman GFM (Github Flavoured Markdown). Es una versión distinta a la estandar SM(Standard Markdown) en cuanto a algunas funcionalidades.

- Newlines: puedes escribir párrafos de dos lineas.
- Multiple underscores: puedes_escribir_todo_junto_si_quieres
- Syntax highlighting: coloreado para la sintaxis de muchos lenguajes de programación. 
- Mentions: puedes mencionar a un usuario utilizando el carácter @ 
- Issue Autocompletion: puedes referenciar a la url para un issue, así #70
- Tasks lists: puedes crear listas de tareas con [ ] [x] 
- Emoji autocomplete: emoticonos.
- Code: Incluir código en un bloque con número de lineas y sintaxis coloreada.

Ellos te explican más en detalle todas sus características. Pero si alguna vez has usado Github cada vez que escribes un mensaje, un issue, comentarios ... has usado GFM.

### Markdown Here! Escribe emails de impacto

Se trata de una extensión para tu navegador que te permite escribir emails alucinantes utilizando Markdown. Disponible para múltiples navegadores: Chrome, Firefox, Safari, Thunderbird, y Postbox. Con ejecutar un atajo como Ctrl+M o clicar un botón convierte a HTML con alucinantes estilos cualquier email.

Es un proyecto de código libre en el cual puedes participar con contribuciones, reportando bugs o simplemente bendiciéndolo.

[Github](https://github.com/adam-p/markdown-here/)

[Sitio web](http://markdown-here.com/)

Además @adam-p tiene una excelente [guia](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) para que tengas a mano cada vez que tengas una duda sobre la sintaxis de markdown.

### Mardown en tus editores Sublime y Vim

1. [Marked Bonus Pack](http://support.markedapp.com/kb/how-to-tips-and-tricks/marked-bonus-pack-scripts-commands-and-bundles) from [Marked](http://markedapp.com/)(aplicación para MAC):

* Usa tus estilos personales: 
> Guarda tus archivos CSS en la ruta dónde tengas instalada la aplicación:
> `~/Library/Application Support/Marked/Custom CSS`
>
> Ve a Sublime - Preferencias (`cmd+b`)-> New Style

* Sublime Text 2 [link](http://support.markedapp.com/kb/how-to-tips-and-tricks/marked-bonus-pack-scripts-commands-and-bundles)
> Copia el fichero Marked.sublime-build en
>
> `~/Library/Application Support/Sublime Text 2/Packages/User/`.
>
> Ahora en Tools en tu menú de Sublime tendrás Marked en la lista Build Systems
> Cuando hayas seleccionado Marked como tu Build System. Ejectua:
> `Command-B`
>Esto mostrará una previsualicación de documento md en HTML y se actualizará cada vez que escribas algun cambio.

> * Marked te permite exportar un fichero `.md` a HTML, PDF, RTF.
> * Marked te pemite usar GM [aquí](http://support.markedapp.com/kb/how-to-tips-and-tricks/using-marked-with-github-flavored-markdown-and-syntax-highlighting)

2. [Markdown Preview](https://github.com/revolunet/sublimetext-markdown-preview)  (Preview en el navegador.
También puedes usar [Live Reload](https://github.com/dz0ny/LiveReload-sublimetext2)):

3. Syntax HighLighting:

Mi configuración de Sublime para escribir markdown:

Uso el tema iPlastic :) con este [gist](https://gist.github.com/CrazyApi/2354062)

También me gusta Monokai añadiendo estos diccionarios [dicts](http://www.bram.us/2013/02/08/sublime-text-markdown-syntax-highlighting/) al fichero `file.theme`


### Multimarkdown (MDD)

Si algo se te resistia con Markdown, pruebalo.

Se trata de un ligero lenguaje de marcado creado por Fletcher T. Penney y basado en Markdown. Soporta más formatos e implementa algunas funcionalidades que no añade la sintaxis orginal de Markdown.

> Estas son algunas de las funcionalidades:

* Notas de pie
* Tablas
* Citaciones y bibliografía
* Soporte para matemáticas (puedes escribir funciones y ecuaciones)
* automatic cross-referencing ability
* Tipografía para multiples lenguajes
* Atributos en las imágenes
* Captions para tus imágenes y tablas
* Definicion de listas
* Metadata (ejemplo: título, autor, fecha, etc.)



[Guía de la sintaxis](https://github.com/fletcher/MultiMarkdown/wiki/MultiMarkdown-Syntax-Guide)

Ejemplo de una tabla con MDD

|             |          Grouping           ||
First Header  | Second Header | Third Header |
 ------------ | :-----------: | -----------: |
Content       |          *Long Cell*        ||
Content       |   **Cell**    |         Cell |

New section   |     More      |         Data |
And more      |            And more          |
[Prototype table]
