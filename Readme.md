Análisis del problema

Problema:
“La empresa de seguros TK-U, ubicada en la ciudad Jedha, realiza cientos de cotizaciones para sus posibles clientes/asegurados. El inconveniente es que las cotizaciones se realizan de forma manual, lo que hace que las personas pierdan mucho tiempo y que se generen como máximo 50 cotizaciones al día.

Esto causa atraso para la entrega de las cotizaciones y posiblemente están perdiendo posibles clientes. Realice un Cotizador automático para la empresa de seguros TK-U, se requiere que usted complete los siguientes requisitos, le proveen un programa base en el cual debe de completar los requerimientos.”

Analice los requerimientos y en sus propias palabras explique cuál es el problema y qué casos se están considerando:

En este caso debemos realizar una serie de preguntas al usuario para saber qué tipo de operaciones debemos realizar dependiendo de las respuestas que nos dé.

En primer lugar, debemos conocer los datos del usuario para luego sí en caso la respuesta es la esperada debemos de realizar las siguiente pregunta, una vez respondida la primera pregunta como positiva debemos considerar la segunda pregunta si la segunda pregunta también es positiva tenemos de realizar el procedimiento, en caso contrario no se realiza, finalmente realizamos la tercera pregunta de ser positiva continuamos con el procedimiento sí es negativa no lo realizamos. 

Al finalizar debemos tomar en cuenta cada una de las respuestas obtenidas y agregarlas a la respuesta final.

Más específicamente el problema necesita que establezcamos un precio de cotización y dependiendo de la edad del cónyuge sí existe y del mismo usuario o si tiene hijos o no; cosa que conoceremos a través de las preguntas el precio de la cotización irá aumentando.
Debemos tomar en cuenta que esperamos string e número como inputs dependiendo del caso, pero esperamos como output un número.
