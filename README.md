Configuración sitio web
----

Para futuras referencias se documenta el proceso que se siguió con el cliente "Electromar", proyecto referido por la gerencia.


Creación de cuenta en gmail
-----

Se creó una cuenta en Gmail para almacenar todas las comunicaciones e identificaciones relacionadas al proyecto.



Creación de cuenta en Github
----

Se creó cuenta en Github para almacenar el repositorio del proyecto en GIT.

Se decidió no utilizar gh-pages para tener más flexibilidad en la creación de las páginas.


Creación de repositorio en Github
-----

Se creó el repositorio "electromar-hugo" para almacenar el contenido del proyecto.


Instalación de applicación Netlify
----

Se configuró el repositorio para que manejara la aplicación "Netlify".

Desde netlifycms.org se hizo el deploy con el template "Kaldi".  

Con esto se generó el proyecto en el repositorio con las siguientes características:
* Integración con identity en netlify
* Utilización de hugo como generador estático
* Implementación de plantilla Kaldi
* Instalación de aplicación netlifycms en el directorio /admin
* Utilización de certificados digitales para proveer un sitio seguro


Configuración de DNSs
-----

Se realizaron las adaptaciones para hacer que el dominio electromarpanana.com apuntara a los servidores de nombres de Netlify.

En especial se configuraron estos name servers:

* dns1.p07.nsone.net
* dns2.p07.nsone.net
* dns3.p07.nsone.net
* dns4.p07.nsone.net

En la consola del registrante se cambiaron los servidores de dominio.

El proceso tomó unas horas para propagarse.

Dentro de netlify, se configuraron los dominios siguiendo las instrucciones para delegar el dominio.

Búsqueda de materiales
---

Se buscaron los materiales actualizados del sitio en el [archivo de internet](https://archive.org/), utilizando la herramienta [archivarix](https://en.archivarix.com/) para descargar el contenido completo del sitio.


Cambios en plantilla
-----

Utilizando el contenido descargado se procedió a modificar la plantilla para proveer las páginas del sitio.

En particular se crearon las páginas de:
* Home
* Products
* About us
* Contact

En cada una de ellas se utilizaron algunos textos del sitio y otros se modificaron para proveer mejor información.

Se utilizaron imagenes ubicadas en internet.  Es necesario que el cliente provea fotografías adecuadas.
