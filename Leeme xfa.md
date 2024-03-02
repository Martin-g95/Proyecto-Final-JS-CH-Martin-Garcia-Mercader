----------------------------- PROYECTO FINAL CODER HOUSE DE JAVASCRIPT------------------------------

Bueno, fue un muy lindo viaje, nunca pense que podia haber llegado hasta aca, estoy muy emocionado con todo lo que logre.
Esta pagina web es un simulador de compra de objetos como si se tratase de la parte de comercio de un juego, es por eso que la interfaz deja mucho que desear jajajaj
Le puse musica, y una naranja, que es para reiniciar la pagina y empezar otra vez.
La musica puede encenderse y apagarse.
Los objetos al hacerle click, te muestran una breve descripcion de lo que vas a comprar, y cuando lo compras, el mercader te explica de donde proviene ese objeto y tiene un pequeño lore que contarte, el mejor de todos es el lore del pomo!
Mi idea como proyecto final era entregar esto mas llevar a cabo lo mismo que aca pero con el juego de mi primera entrega, ahi me di cuenta todo el trabajo y esfuerzo que conlleva programar, y el tiempo que hay que dedicarle, por eso solamente
pude entregar esta parte de lo que queria lograr, pero tengo pensado continuarlo en el futuro.

Datos a tener en cuenta de este proyecto.

En la realizacion de este trabajo, me encontre con sorpresas que me explico mi tutor luis laverde (tutorGOD 20/10, es cine *fuma) sobre javascript, como trabaja a veces dependiendo que es lo que le estas pidiendo, y me di cuenta que en mi codigo no podia ejecutarse hasta 
esperar los datos de la api local (que en realidad, si se ejecutaba, pero solamente despues de que le pegues solo una refrescada con el f5, si, no tiene sentido) asi que tuve que insertar casi TODO el codigo dentro de la funcion asyncrona de la creacion de los objetos
(funcion que dependia de la otra funcion asyncrona de obtener los datos de la API) y fue la unica forma que encontre de solucionar
ese problema con mi codigo, en realidad, habia otra forma, pero practicamente tenia que haber modificado toda la logica del flujo del codigo para que funcione, y ya no tenia el tiempo para hacerlo, porque estas cosas hasta pueden llevar dias, tiempo que lamentablemente no poseo.

Renderizado de los objetos.

Tuve que modificar mis funciones de renderizado de los objetos (Los poderisisimos forEach) para que no se rendericen si en el otro lado o el otro localStorage poseian los mismos objetos, esto era para evitar que al recargar la pagina se vuelvan a cargar los objetos del vendedor pero vos tambien poseas los objetos que compraste, y podrias decir: "Pero es un mercader, deberia poder reponer stock facilmente para que puedas comprar mas cantidades de los objetos! como si fuera una ecomerce de hoy en dia!" 
Ey, es la edad media, los dragones atacan aldeas, los reyes cobran monton de impuestos, hay goblins por todas partes, el mercader solo tenia 5 objetos que vender nomas, y yo solo necesitaba 5 objetos que comprar. Listo.

Si despues de comprar el ultimo objeto, esperas 10 segundos, el mercader se va a despedir de vos, señalandote que, si queres, podes apretar la naranja y eso va a causar que se genere una brecha en el espacio tiempo que va a aniquilar la linea de tiempo en la que perteneces y una version multi-dimensional de vos mismo va a volver a presentarse al mercader para volver a comprar los objetos, si, estan bien raras las naranjas en la fantasia medieval.

Un abrazo a mi profe Andres y a mi tutor Luis, mis sueños cada vez se vuelven mas reales gracias a personas como ustedes. 
ADIOS!
