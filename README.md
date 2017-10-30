# Lyft 
 
### Descripción general: 
Este repositorio es el resultado de un ejercicio de maquetación utilizando HTML y CSS como base para diagramar y dar estilo al contenido. Esto sin considerar su funcionalidad de origen (enlaces, despegables, etc). 

El propósito del ejercicio es lograr una réplica "pixel perfect", para ello me apoyé en la extensión de Chrome "Page Ruler" para medir los píxeles utilizados en la página original, no se utilizaron las medidas exactas, sino fueron generadoras de parámetros más exactos para adaptarle a la pantalla de trabajo. Cabe señalar que en la imagen del reto no fue posible utilizarle, así como tampoco en el gif del footer. 

El formato de letra fue dado junto a las instrucciones del reto. Del mismo modo, se facilitó el gif inicial y las direcciones de los vídeos, aunque no todas estaban operativas. Los íconos fueron obtenidos desde: https://icomoon.io 
  
### ¿Cómo se elaboró la réplica? 

Para la réplica se establecieron distintas secciones, con el propósito de facilitar el proceso de maquetación. Para este caso particular se siguió una división natural dada por los distintos background. De este modo, la división quedó en un total sietesecciones: menú, imagen, cuadro de formulario, vídeo 1, vídeo 2, vídeo 3, footer. 

Teniendo presente la división, se inició la redacción del código HTML y CSS en paralelo, es decir, sección por sección. Esto permitió visualizar en manera –casi- instantánea el avance de la página; algo similar ocurrió con cada sección al permitir el inicio y finalización del proceso (ajustando colores, píxeles, font, etc.). 

Para hacer del proceso más sencillo todos los elementos fueron encapsulados en <div> con distintas clases, las que hacían referencia directa a la posición, función o elemento que acompañaban.  Por otra parte, en el CSS cada div fue ubicado haciendo uso de la guía "outline",  para establecer visualmente sus límites y moverle con mayor facilidad dentro de la página. Seguidamente, se le dio a cada elemento un heigth y un width, para determinar el espacio por ocupar en la maqueta. 

La imagen principal corresponde a un gif, proporcionado al inicio del reto, que se ubicó como background, para la sección izquierda, frente al formulario y que cubriese, además, el fondo del menú. 

El formulario fue ubicado en un cuadro con background blanco. Para la línea del formulario se utilizó un <input> al que se le borraron los bordes laterales y superior; cambiándole color al borde inferior y ajustando las medidas para alcanzar un "pixel perfect". 

Los vídeos fueron extraídos desde youtube y luego se ajustó el tamaño de la ventana, se quitó la posibilidad de visualización a pantalla completa, al igual que en los vídeos originales de la página (actual). El texto fue agregado dándoles el mismo estilo CSS a los tres bloques, aunque se les ajustaron los márgenes para ubicarles según correspondiese al original. 

Por último, para el <footer> se dividió la sección en seis nuevas secciones y los textos fueron agrupados utilizando listas "li". Las imágenes fueron agrupadas en un <div> dándoles a cada una medidas personalizadas para alcanzar una mejor visualización del logo. Los iconos fueron rodeados por un borde blanco y la línea fue generada por un "hr" al que se le dio medidas en CSS. Por último, la línea final fue extraída desde la página original del sitio. 
 
 
 
##### Este archivo es la versión 0.0.1 
##### Proyecto realizado por RoArriaza 
 
