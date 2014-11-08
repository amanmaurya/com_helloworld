Joomla komponenta: Helloworld

LINK: http://docs.joomla.org/J3.x:Developing_a_MVC_Component/Adding_a_view_to_the_site_part

V0.0.2

1. Kreirani fajlovi
		helloworld.xml
		site/helloworld.php
		site/index.html
		site/controller.php
		site/views/index.html
		site/views/helloworld/index.html
		site/views/helloworld/view.html.php
		site/views/helloworld/tmpl/index.html
		site/views/helloworld/tmpl/default.php
		admin/index.html
		admin/helloworld.php
		admin/sql/index.html
		admin/sql/updates/index.html
		admin/sql/updates/mysql/index.html
		admin/sql/updates/mysql/0.0.1.sql

2. Autori komponenti svoj kod razdvajaju u tri dijela
		- modeli 
		- kontroleri  
		- prikazi

3. Rezultat
		- Vidjeti poruku spremljenu u varijabli $this->msg