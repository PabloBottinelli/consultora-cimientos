# Consultora Cimientos

<p align="center">
  <img src="media/capturaBanner.png" alt="Consultora Cimientos" width="100%">
</p>

Sitio web desarrollado para **Consultora Cimientos**, consultora especializada en asesoramiento jurídico e institucional para asociaciones civiles, fundaciones, instituciones educativas y organizaciones del tercer sector.

La web funciona como presentación institucional de la consultora, permitiendo comunicar sus áreas de práctica, servicios y propuesta de valor, además de facilitar el contacto de potenciales clientes.

[consultoracimientos.com.ar](https://www.consultoracimientos.com.ar/)

![Status](https://img.shields.io/badge/STATUS-EN%20PRODUCCIÓN-2EA44F)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=000)
![PHP](https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white)

## Sobre la web

La web es completamente responsive y está adaptada para escritorio, tablet y dispositivos móviles.

La navegación se adapta a dispositivos móviles mediante un menú hamburguesa implementado con JavaScript.

### Identidad visual

Además del desarrollo del sitio, diseñé el logo de **Consultora Cimientos** y preparé distintas versiones para adaptarlo a diferentes usos dentro de la web.

Se generaron variantes:

- Isotipo.
- Logo completo con texto.
- Versiones en color.
- Versiones en escala de grises.
- Variantes con y sin subtítulo.
- Adaptaciones para header, footer y favicon.

Los recursos gráficos se encuentran en formato SVG para mantener buena calidad y facilitar su uso en distintos tamaños.

### Formulario de contacto

El formulario utiliza un backend en PHP para procesar las consultas recibidas desde la web.

Incluye:

- Validación de campos obligatorios.
- Validación del formato del email.
- Procesamiento de nombre, email, asunto y mensaje.
- Envío de consultas por correo electrónico.
- Mensajes de confirmación o error luego del envío.

Las respuestas del formulario se comunican nuevamente al frontend mediante parámetros en la URL, mostrando al usuario si la consulta fue enviada correctamente.

### SEO y configuración del sitio

Se implementaron distintas optimizaciones orientadas al posicionamiento y correcta indexación de la web:

- `title` y `meta description` específicos.
- URL canónica.
- `robots.txt`.
- `sitemap.xml`.
- Textos alternativos en imágenes.
- Estructura semántica mediante encabezados y secciones.
- Redirecciones permanentes mediante `.htaccess`.

El archivo `.htaccess` también fuerza el uso de **HTTPS + www**, evita el listado de directorios y redirige `/index.html` hacia la URL principal del sitio.

## Autor

| [<img src="https://github.com/PabloBottinelli.png" width="115"><br><sub>Pablo Bottinelli</sub>](https://github.com/PabloBottinelli) |
| :---: |