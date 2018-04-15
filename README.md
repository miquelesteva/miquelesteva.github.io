# HowTo: Portofolio de Miquel Esteva
<br/>

* Alumno: Miquel Esteva Thomas
* Identificación: isx41536245
* Curso 2017-2018
* Ciclo: ASIX: Administració de Sistemes Informàtics en Xarxa
* Módulo 9: Implantació d'aplicacions Web

### Repositorio

	https://miquelesteva.github.io
	
	
### Instal·lación del programario

**Pandoc i Git**

	dnf -y install pandoc texlive
	dnf -y install git gitg meld
	
**Jekyll**

Instalación: 

	dnf -y install rubygems rubygems-devel ruby-devel
	dnf -y install redhat-rpm-config
	sudo gem install jekyll

Test local: 

	jelyll new foobar
	cd foobar
	bundle exec jekyll serve
	
	Browse to http://localhost:4000
	
### Página Web

Se trata de crear una página web estática para mostrar los conocimientos adquiridos durante el curso del módulo 9. 

Dicha página web consta de tres apartados: 

* Inicio: breve descripción sobre mí. 
* Sobre mí: descripción más amplia sobre mi persona. 
* Currículum Vitae
* Contacto: pie de página para contacto. 

#### Tratamiento de la página web

* Utilicé una plantilla de jekyll descargada desde jekyllthemes [spectral](http://jekyllthemes.org/themes/spectral/). 
* Utilización del css original con modificaciones a mi gusto. 
* Utilización básica de HTML para el resto de la página. 
* Utilización de FontAwesome para los iconos. 

### Estructura de directorios

	├── about.html
	├── _config.yml
	├── css
	│   ├── font-awesome.min.css
	│   ├── ie8.scss
	│   ├── ie9.scss
	│   ├── images
	│   │   ├── arrow.svg
	│   │   ├── bars.svg
	│   │   └── close.svg
	│   └── main.scss
	├── curriculum.html
	├── feed.xml
	├── fonts
	│   ├── FontAwesome.otf
	│   ├── fontawesome-webfont.eot
	│   ├── fontawesome-webfont.svg
	│   ├── fontawesome-webfont.ttf
	│   ├── fontawesome-webfont.woff
	│   └── fontawesome-webfont.woff2
	├── images
	│   ├── banner.jpg
	│   ├── leo.jpg
	│   ├── pic01.jpg
	│   ├── pic02.jpg
	│   ├── pic03.jpg
	│   ├── pic04.jpg
	│   └── pic05.jpg
	├── _includes
	│   ├── footer.html
	│   ├── header.html
	│   ├── head.html
	│   └── scripts.html
	├── index.html
	├── js
	│   ├── ie
	│   │   ├── backgroundsize.min.htc
	│   │   ├── html5shiv.js
	│   │   └── respond.min.js
	│   ├── jquery.min.js
	│   ├── jquery.scrollex.min.js
	│   ├── jquery.scrolly.min.js
	│   ├── main.js
	│   ├── skel.min.js
	│   └── util.js
	├── _layouts
	│   ├── default.html
	│   ├── landing.html
	│   └── page.html
	├── README.md
	└── _sass
	    └── libs
		├── _functions.scss
		├── _mixins.scss
		├── _skel.scss
		└── _vars.scss






