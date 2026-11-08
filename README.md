### Práctica 4 de CSS 2: MOVILIDAD ERASMUS ###

## ESTRUCTURA:

- indexParteA.hmtl
- styles (carpeta)
    - estilos.css
- README.md

## PARTE A:

En esta parte maquetaremos la cabezera y pie de página.

# Primera parte: Configuracion del layaout

    - Eliminamos margenes y rellenos
    - Configuramos el body como contenedor flex en dirección columna
    - Al contenedor principal le asignamos un flex de 1 para asegurar que el pie de pagina siempre este al final

# Segunda parte: Maquetación de cabezera

    - Separamos el logo del navegador
    - Alineamos verticalmente ambos elementos
    - Espaciamos los enlaces sin usar márgenes manuales
    - Le añadimos el borde amnarillo

# Tercera parte: Maquetación del pie de página

    - Distanciamos el texto legal de la lista de enlaces
    - Organizamos la lista horizontalmente

## PARTE B: 

En esta parte maquetaremos el formulario y el cuadro de ayuda con CSS Grid y enfoque móvil primero.

# Primera parte: Bloques del formulario y campos

    - Diseñamos cada bloque como una tarjeta con fondo blanco, borde fino, esquinas redondeadas y separación de 1,5 rem
    - Colocamos el título sobre el borde en azul oscuro, negrita y a 1,2 rem
    - Apilamos la etiqueta en negrita, el control y el texto de ayuda separados 0,25 rem
    - Ajustamos el ancho mínimo a 0 en los campos para evitar que controles como el de fecha desborden su columna

# Segunda parte: Distribución de los bloques en rejilla

    - Colocamos todos los campos en una sola columna separados 1 rem
    - Creamos una rejilla de 6 columnas iguales con 1 rem entre filas y 1,5 rem entre columnas
    - Repartimos los campos de Datos personales y Datos académicos indicando cuántas columnas ocupan con span
    - Colocamos los campos de Preferencias de destino y Motivación mediante zonas con nombre

# Tercera parte: Teléfono, opciones y botonera

    - Ponemos prefijo y número en línea con Grid en el teléfono
    - Creamos columnas automáticas de mínimo 8 rem en las opciones
    - Diseñamos cada opción como una rejilla de dos columnas centrada en vertical
    - En móvil apilamos el pie de la carta y los botones

# Cuarta parte: Estructura general y cuadro de ayuda

    - Maquetamos la tarjeta lateral de ayuda y sus pasos numerados utilizando Grid
    - En móvil colocamos el cuadro de ayuda debajo del formulario y lo situamos en una columna a la derecha