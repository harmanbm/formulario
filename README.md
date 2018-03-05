# formulario
Aquí puedes probar el Formulario(minimify):https://rawgit.com/harmanbm/formulario/minimified/inicio.html


## Descripción del proyecto
He usado lenguajes css, html y javascript para hacer el proyecto de formulario.

He mirado ejemplo del profesor y también he visto códigos en la pagina de https://www.w3schools.com para completar el proyecto.

    Hay:
    4 paginas HTML: inicio.html         -> Donde se explica sobre el examen y como acceder a la pagina de instrucciones.
                    instrucciones.html  -> Se explica brevemente los tipos y también explica como responder.
                    examen.html         -> Aquí se muestra todas las preguntas del fichero xml.
                    answer.html         -> En esta pagina están todas las respuestas correctas.
                    
    1 fichero javascript: js.js
    
    6 ficheros css: d.css,m.css         -> Aplican a las paginas inicio.html y examen.html
                    infod.css,infom.css -> Aplican a las paginas instrucciones.html
                    ansd.css,ansm.css   -> Aplican a las paginas answer.html
                    
    1 fichero xml: quiz.xml -> Aquí esta el fichero que tiene todas las preguntas, y de donde vamos a leer las preguntas en examen.html.
    1 fichero dtd: quiz.dtd -> Ayuda a corregir el fichero quiz.xml.

## Explicación sobre el formulario
Consiste en 10 preguntas.
Es obligatorio responder a todas.

## Después de responder
Al hacer clic en corregir, te muestra el resultado.
Hay una opción de ver las respuestas correctas.
Hay otra opción para ver los resultados en detalles donde las notas se muestran dependiendo del numero de la pregunta.

## La pagina “answer”:
Solamente he creado para mostrar las respuestas correctas para alguien que quiere saber-las.(También para el profesor)
No depende del xml. (Pero se puede hacer).
