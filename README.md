# Strawberry-Pastry
pasteleria y reposteria en nuestra pagina web te mostraremos todo lo que te ofrecemos, contando tambien que nos adaptamos a tus petisiones
5

6

Código

Culpa

<cabeza>

Crudo

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, inicial-scale=1.0"> <!--

Hace que la página sea adaptable en

<title>Pasteleria Fresas</title> <!-- Título que aparece en la pestaña del navegador


<!-- Aquí comienza el CSS (diseño visual de la página) -->

<estilo>

/* Estilo general del cuerpo de la página */

cuerpo {

}

margen: 0; /* Elimina márgenes por defecto del navegador */

familia de fuentes: Arial 12, sans-serif; /* Definir la fuente de texto */

pantalla: flexible; /* Activa el modelo flexible para dividir la pantalla en columnas */

altura: 100vh; /* Hace que ocupa el 100% de la altura visible */

/* Estilo para la parte izquierda */

.izquierda {

}

flexión: 1; /* Ocupa la mitad del ancho total */

color de fondo: #857f7f; /* Fondo rosa claro */

relleno: 40px; /* Espacio interior alrededor del texto */

pantalla: flexible; /* Usa flexbox dentro del contenedor */

dirección flexible: columna; /* Organiza el contenido en columna */

justificar-contenido: centro; /* Centra verticalmente el contenido */

/* Estilo para la parte derecha (donde va la foto) */

.derecha {

flexión: 1; /* Ocupa la otra mitad del ancho */

pantalla: flexible; /* También usa flexbox */

justificar-contenido: centro; /* Centra horizontalmente la imagen */
3

Código

Culpa

Crudo

<cabeza>

4

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, inicial-scale=1.0"> <!-- Hace que la página sea adaptable en

<title>Pasteleria Fresas</title> <!-- Título que aparece en la pestaña del navegador -->

<!-- Aquí comienza el CSS (diseño visual de la página) -->

<estilo>

/* Estilo general del cuerpo de la página */

cuerpo {

}

margen: 0; /* Elimina márgenes por defecto del navegador */

familia de fuentes: Arial 12, sans-serif; /* Definir la fuente de texto */

pantalla: flexible; /* Activa el modelo flexible para dividir la pantalla en columnas */

altura: 100vh; /* Hace que ocupa el 100% de la altura visible */

/* Estilo para la parte izquierda */

.izquierda {

flexión: 1; /* Ocupa la mitad del ancho total */

color de fondo: #857f7f; /* Fondo rosa claro */

relleno: 40px; /* Espacio interior alrededor del texto */

pantalla: flexible; /* Usa flexbox dentro del contenedor */

dirección flexible: columna; /* Organiza el contenido en columna */

justificar-contenido: centro; /* Centra verticalmente el contenido */

/* Estilo para la parte derecha (donde va la foto) */

.derecha {

flexión: 1; /* Ocupa la otra mitad del ancho */

pantalla: flexible; /* También usa flexbox */

32

justificar-contenido: centro; /* Centra horizontalmente la imagen */
Crudo

dirección flexible: columna; /* Pon el titulo arriba y la imagen abajo */

alinear elementos: centro; /* Centra verticalmente la imagen */

color de fondo: #0c3d63; /* Fondo blanco */

}

33 34 35 36 37 38 39

/* Estilo para la imagen */

imagen {

40

ancho: 300px; /* Ancho de la imagen */

altura: 300 píxeles; /* Altura de la imagen */

radio fronterizo: 50%; /* Hace la imagen circular */

ajuste de objeto: cubierta; /* Ajusta la imagen sin deformarla */

sombra de cuadro: 0 4px 8px rgba(0,0,0,0.2); /* Agrega una sombra suave */

}

46

47

/* Estilo para los títulos (h1) */

48

h1 {

49

color: #333; /* Color rosa oscuro */

50

}

51

52

/* Estilo para los párrafos */

53

pag {

54

color: #0f0e0e; /* Color gris medio */

55

altura de línea: 1,6; /* Espaciado entre líneas para mejor lectura */

56

}

57

</estilo>

58

</cabeza>

59

60

61

62

<body> <!-- Cuerpo del documento, donde está el contenido visible
Código

Culpa

color: #0f0e0e; /* Color gris medio */

altura de línea: 1,6; /* Espaciado entre líneas para mejor lectura */

}

Crudo

</estilo>

</cabeza>

<body> <!-- Cuerpo del documento, donde está el contenido visible -->

<!-- Sección izquierda: información personal -->

<div class="izquierda">

<h1>¡Hola! Somos Camila, Valeria y Yamilet de 3-M de programacion y vendemos pasteles</h1> <!--Strawberrys pasteleria

<p>

Bienvenidos a nuestra página web. Les ofrecemos muy buenos pasteles, nos adaptamos a tus gustos y creamos algo incre Esperamos que te gusten y nos compres más.

</p>

</div>

<!-- Sección derecha: imagen personal -->

<div class="derecha">

Pastelería

<p>

<img src="image.jpg" alt="Foto de los pasteles"> <!-- Imagen (debes tener un archivo llamado 'foto.jpg' en la misma

</p>

</div>

</cuerpo>

</html>
<!-- Sección izquierda: información personal -->
