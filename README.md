Ejemplos de CSS: display y position

Ejemplos prácticos en HTML y CSS para aprender cómo se comportan los elementos de una página con las propiedades display y position. Fueron creados como material de apoyo para una clase dirigida a desarrolladores junior.

Contenido del repositorio
├── proyecto-display/
│   ├── index.html
│   └── styles.css
└── proyecto-position/
    ├── index.html
    └── styles.css
proyecto-display

Muestra los tres comportamientos básicos de display. Todas las cajas tienen los mismos estilos (width, height, margin y padding), y lo único que cambia en cada sección es el valor de display, así que las diferencias se ven a simple vista.

Sección	Qué muestra
0. Sin clase de display	Un div ya es block por defecto
1. display: block	Cada caja ocupa su propia línea y respeta su tamaño
2. display: inline	Las cajas fluyen dentro del texto e ignoran el ancho y el alto
3. display: inline-block	Las cajas quedan en la línea, pero respetan su tamaño
Resumen	Tabla comparativa de los tres valores
proyecto-position

Muestra cómo position permite cambiar dónde se ubica un elemento y respecto a qué. En cada ejemplo, la caja roja es la que se mueve.

Sección	Qué muestra
1. position: static	El valor por defecto: top y left no tienen efecto
2. position: relative	El elemento se corre desde su propio lugar y deja su hueco
3. position: absolute	El elemento sale del flujo y se ubica dentro del contenedor más cercano con position
4. relative + absolute	Casos reales: una insignia en una tarjeta y el botón de cerrar de una ventana
5. z-index	Qué elemento queda arriba cuando se superponen
6. Inline con absolute	Un span que pasa a respetar el ancho y el alto
7. position: fixed	Un botón que queda fijo en la ventana al hacer scroll
8. position: sticky	Títulos que se pegan al borde al hacer scroll
9. display + position	Un menú desplegable que combina las dos propiedades
Resumen	Tabla comparativa de los cinco valores
Cómo usarlos

No necesitan instalación. Descarga o clona el repositorio y abre el archivo index.html de cada carpeta en el navegador.

Para aprovecharlos mejor:

Abre el styles.css en un editor, cambia un valor, guarda y recarga la página para ver el efecto.
Usa las herramientas de desarrollo del navegador (clic derecho → Inspeccionar) para ver qué estilos tiene cada elemento.
En proyecto-position, haz scroll por la página y dentro de la caja de la sección 8, y pasa el mouse sobre el botón del menú de la sección 9.
Conceptos clave
display decide cómo se comporta un elemento: si ocupa su propia línea o si se acomoda entre el texto.
position decide dónde se ubica un elemento y cuál es su referencia: su propio lugar, un contenedor o la ventana.
Las dos propiedades son independientes y se pueden combinar en un mismo elemento.
Para seguir aprendiendo
MDN: display
MDN: position
Autoría

El código de este repositorio fue generado con inteligencia artificial por Claude, asistente de IA de Anthropic, adaptado y revisado por Virginia Morrone para su uso en clase.
