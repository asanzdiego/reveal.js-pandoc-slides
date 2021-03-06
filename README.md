# Instructions

## English

### Samples

- [HTML](http://asanzdiego.github.io/reveal.js-pandoc-slides/doc/export/readme.html)
- [HTML Reveal Slides](http://asanzdiego.github.io/reveal.js-pandoc-slides/doc/export/readme-reveal-slides.html)
- [PDF Reveal Slides](http://asanzdiego.github.io/reveal.js-pandoc-slides/doc/export/readme-reveal-slides.pdf)
- [HTML Reveal Slides Alternativo](http://asanzdiego.github.io/reveal.js-pandoc-slides/doc/export/readme-reveal-slides-alternative.html)
- [PDF Reveal Slides Alternativo](http://asanzdiego.github.io/reveal.js-pandoc-slides/doc/export/readme-reveal-slides-alternative.pdf)

### Dependencies

- [Pandoc](http://johnmacfarlane.net/pandoc/) (needs to be installed)
- [Phantom.js](http://phantomjs.org) (needs to be installed)
- [Reveal.js](http://lab.hakim.se/reveal-js/#/) (downloaded automaticaly)

### Creation

- First **copy the doc folder and rename it as you like**. This is not necessary but
  helps you organize your documents.

- **Create the md files** that you want to generate. The md files are
  [Markdown](http://en.wikipedia.org/wiki/Markdown) files which are nothing more
  than plain text files with extension md, and a lightweight markup (we should
  know it but it is very simple).

- Once created the md files, we can **generate html, html-slides y pdf-beamer with a script**.

### Build

- To **convert all md files of all the folders**
  go to the root folder and execute:

~~~
   ./build.sh
~~~

- To **convert all md files of one folder**
  go to the root folder and execute:

~~~
   ./build.sh [folder_name]
~~~

## Español

### Ejemplos

- [HTML](http://asanzdiego.github.io/reveal.js-pandoc-slides/doc/export/leeme.html)
- [HTML Reveal Slides](http://asanzdiego.github.io/reveal.js-pandoc-slides/doc/export/leeme-reveal-slides.html)
- [PDF Reveal Slides](http://asanzdiego.github.io/reveal.js-pandoc-slides/doc/export/leeme-reveal-slides.pdf)
- [HTML Reveal Slides Alternativo](http://asanzdiego.github.io/reveal.js-pandoc-slides/doc/export/leeme-reveal-slides-alternative.html)
- [PDF Reveal Slides Alternativo](http://asanzdiego.github.io/reveal.js-pandoc-slides/doc/export/leeme-reveal-slides-alternative.pdf)

### Dependencias

- [Pandoc](http://johnmacfarlane.net/pandoc/) (necesita ser instalado)
- [Phantom.js](http://phantomjs.org) (necesita ser instalado)
- [Reveal.js](http://lab.hakim.se/reveal-js/#/) (descargado automaticamente)

### Creación

- Primero **copia la carpeta doc y renombrala a tu gusto**. Esto no es necesario pero
  te ayuda a organizar tus documentos.

- **Crea los ficheros md** que quieras generar. Los ficheros md son ficheros
  [Markdown](http://es.wikipedia.org/wiki/Markdown), que no son nada más que
  ficheros de texto plano, con extensión md, y con un marcado ligero (que hay
  que conocer pero que es muy sencillo).

- Una vez creado los md, puedes **generar html, html-slides y pdf-beamer con un script**.

### Generación

- Para **convertir todos los ficheros md de todas las carpetas**
  hay que posicionarse en la carpeta raiz, y ejecutar:

~~~
   ./build.sh
~~~

- Para **convertir todos los ficheros md de una carpeta**
  hay que posicionarse en la carpeta raiz, y ejecutar:

~~~
   ./build.sh [nombre_de_carpeta]
~~~
