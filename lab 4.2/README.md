Laboratorio 4.2: Página web estilizada con CSS

Laboratorio de la Semana 4 del curso de Front End (Columbia Central University). El proyecto es una página sobre fotografía: explica los tres controles de la exposición y tres ideas de composición.

Autor: Carolina Del Valle Faría 

Archivos
lab 4.2/
├── index.html    Contenido de la página (HTML semántico)
├── styles.css    Estilos de la página (CSS)
└── README.md     Este archivo
Cómo verlo
Descarga o clona el repositorio.
Abre la carpeta lab 4.2.
Haz doble clic en index.html para abrirlo en el navegador.

Las tipografías se cargan desde Google Fonts, así que se necesita conexión a internet para verlas. Sin conexión, la página usa tipografías de respaldo.

Requisitos de la tarea y dónde se cumplen
Requisito	Dónde está
Estructura semántica	index.html usa header, nav, main, section, article, aside y footer. Los datos de cada tarjeta van en una lista de definición (dl).
CSS con selectores y propiedades	styles.css define colores, tipografías, tamaños, márgenes y espaciados. Los colores y las fuentes están guardados en variables dentro de :root.
Selectores de elemento, clase e ID	Elemento: body, h1, p, a. Clase: .tarjeta, .boton, .etiqueta, .rejilla, .seccion. ID: #encabezado, #portada, #dato-del-dia, #pie.
Modelo de caja	#dato-del-dia y .tarjeta combinan padding, border, margin y border-radius. Se usa box-sizing: border-box en todos los elementos y margin: 0 auto para centrar las secciones.
Diseño responsivo	Etiqueta viewport en el HTML. La rejilla usa repeat(auto-fit, minmax(16rem, 1fr)) y hay dos @media: uno hasta 520 px (encabezado y tarjetas en una columna) y otro desde 800 px (portada en dos columnas).