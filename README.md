# 00003924_practica3_secci-n2
Preguntas 
# ¿Porqué cambia el posicionamiento de las cajas internas al div principal?, ¿Qué pasa si me solicitan hacer 
un cambio en el orden de los elementos pero sin tocar los archivos html y js, será que puedo lograrlo a traves de 
CSS?. 
R/Porque en Flexbox el eje principal lo define flex-direction. Si usas row/row-reverse los ítems se distribuyen a lo largo de la fila; con column/column-reverse lo hacen a lo largo de la columna. Cambiar esa propiedad altera el flujo y, por tanto, la posición de los elementos. Además, si activas flex-wrap: wrap, los ítems pueden saltar a nuevas líneas,lo que también reacomoda el layout. 

#  ¿Qué hacen estás propiedades?
R/display: flex; convierte el contenedor en un flex container.

flex-direction: row | column | row-reverse | column-reverse; establece orientación del eje principal, cambiando cómo fluyen los ítems. 

Guía de laboratorio III - Prog…

flex-wrap: wrap; permite que los ítems se ajusten a varias líneas cuando no cabe todo en una sola. 

Guía de laboratorio III - Prog…

(Si en tu práctica usaste width o flex-grow): width define el tamaño base del ítem (con flex-basis:auto por defecto); flex-grow reparte el espacio libre proporcionalmente entre los ítems.

# ¿Puedo diseñar toda mi web usando GRID?
R/ Si es posible crear la pagina utiliznado esta tecnologia 

#¿Por qué se ven cambios grandes con tan pocas líneas de CSS?
R/Porque en Grid defines columnas/filas y colocas los elementos independientemente del orden del HTml. Unas pocas declaraciones pueden reorganizar todo el layout sin tocar el marcado.
