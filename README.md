# Freelancer

* **Unidad:** _Maquetado web con HTML & CSS_
* **Autora:** _Tatiana Tudela Hernández_

***

## Contenido del repositorio

1. Archivo `index.html`.

2. Carpeta **ccs** que contiene el archivo `main.css`.

3. Carpeta **docs** que contiene el archivo `fullpage.png` en la que se muestra la apariencia que deberá tener la pagina web a diseñar con HTML y CSS.

4. Carpeta **assets** que a su vez contiene la carpeta **images** cuyo contenido esta conformado por la imagen `profile.png` y la carpeta **portfolio** con otras imagenes adicionales que se utilizaron en el diseño de la página: `cabin.png`, `cake.png`, `circus.png`, `game.png`, `safe.png` y`submarine.png`.

5. Archivo `README.txt`. 

## Explicación de los archivos `index.html`** y `main.css`.

El archivo HTML esta conformado por las siguientes partes:

* **Encabezado delimitado por la etiqueta `<header>`:**
	En el archivo CSS se fijó el encabezado con un fondo color `#2C3E50` y en el que se muestra el texto "START BOOTSTRAP" etiquetado como `<div class="logo">` y nombres de opciones de menú de color blanco, etiquetadas en lista `<li></li>` , pero que al apuntar con el mouse cambian a color `#18BC9C`. 

* **Bajo el encabezado se dividió el diseño en las siguientes secciones (delimitados por la etiqueta `<section>`):**

  - Sección "contenedor inicio" (presentación de la página web mediante una imagen central y fondo turquesa).
	En el archivo CSS se se posicionó la imagen `profile.png` etiquetada como `<img src="assets/images/profile.png" alt="">`. Así mismo, se utilizó el color de fondo `#18BC9C` y se aplicó el color blanco en el título (etiquetado como: `<span class="nombreb">`**) y texto (etiquetado como: `<span class="detalle">`. Entre ambas etiquetas se muestra una estrella entre dos líneas con etiqueta: `<span class="icono fa fa-star"></span>` sobre la cual se trabajó este estilo de línea un poco compleja de estructurara en el css(Fuente de donde se investigo este diseño de línea - estrella - línea: `https://stackoverflow.com/questions/46761721/how-to-make-a-section-of-hr-transparent`. Es importante hacer notar que esta etiqueta se repite en las siguientes secciones, con la única diferencia que se intercalan los colores de su presentación entre secciones.

  - Sección "contenedor portafolio" (se muestran seis imagenes sobre un fondo blanco).
	En el archivo CSS se posicionaron las imagenes: `cabin.png`, `cake.png`, `circus.png`, `game.png`, `safe.png` y `submarine.png` de la carpeta **portfolio**, mediante: `display: inline-block`, etiquetadas mediante `<div class="imagen"><img src="assets/images/portfolio/nombre de la imagen.png"></div>`. El texto, las líneas y el ícono de estrella entre estas, se presenta en color `#2C3E50`.

  - Sección "contenedor about" (se muestran el título y parrafos descriotivos del sitio web en dos columnas, con fondo turquesa).
	En el archivo CSS se muestra el texto, las líneas y el ícono de estrella entre estas,  en color blanco y fondo `#18BC9C`, los párrafos se posicionan mediante `display: inline-block` y el boton "Download" etiquetado como `<a class="boton" href="#"><i class="fa fa-download"></i> Download Theme</a>`, continen un icono de descarga, texto y borde con el mismo estilo, pero al apuntar con el mouse este boton cambia y se presenta con un fondo blanco y texto color `#18BC9C`.

  - Sección "contenedor contact" (se muestra un formulario para llenar los datos del usuario y el botón "SEND").
	En el archivo CSS se muestra el texto, las líneas y el ícono de estrella entre estas, se presenta en color `#2C3E50`. En la estructura del formulario se utilizó las etiquetas `form`, `input`, `button`, de la siguiente forma:
		`<form action="">`
			`<label for="nombre">Nombre</label>`
			`<input type="text" id=nombre>`
			`<br>`
			`<label for="correo">Email Addressl</label>`
			`<input type="email" id="correo">`
			`<br>`
			`<label for="telefono">Phone Number</label>`
			`<input type="number" id="telefono">`
			`<br>`
			`<label for="mensaje">Message</label>`
			`<textarea id="mensaje"></textarea>`
			`<button>Send</button>`
		`</form>`
	El boton "SEND" cambia su estilo al apuntar con el mouse, oscureciendose mediante el color: `#128F76`.

* **Pie de página web delimitado por la etiqueta `<footer>`:**
	En el archivo CSS se aplicó un fondo color: `#212529` y texto blanco presentado en tres columnas y en la parte central se muestran los iconos de `font-awesome`, con estilo: `border-radius: 50%`, color blanco, posicionados mediante `display: inline-block`. Finalmente, en la parte inferior se muestra centrado el texto "Copyright © Your Website 2017".