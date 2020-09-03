# NLP-with-Python-and-Alteryx

Lo que se hizo en este proyecto fue tomar todos los comentarios de personas que aparentemente fueron ex trabajadores de Santander y que decidieron escribir una pequeña reseña de lo que fue su trabajo en el banco.
Para este proyecto se utilizaron algoritmos de Machine Learning como lo son las herramientas del Procesamiento del Lenguaje Natural (NLP), específicamente se utilizaron
las técnicas de LDA (Latent Dirichlet Allocation) y el NMF (Nonnegative matrix factorization). 
Es así como se llegó al siguiente resultado.


Luego del análisis de 698 comentarios de personas sobre su experiencia de trabajo y paso por Santander, podemos concluir lo siguiente:

![](images/image.png)




Ahora bien, expliquemos un poco que fue lo que se hizo...

Desafío

Desafío 1: "Primero, probar las funcionalidades de Alteryx y poder utilizarlo para generar un flujo de trabajo mediante un ejemplo práctico. Y segundo, testear la integración que tienen con otros programas en este caso Python" 
Desafío 2 (desafío personal) : "Entrenar un algoritmo de machine learning dentro de alteryx con el objetivo que funcione, arroje resultados y podamos obtener la data para ver resultados"

Resumen del proyecto

1) Se tomaron 700 comentarios de referencias, reviews, comentarios de personas que trabajaron en Santander y que decidieron escribir una reseña en 2 portales de trabajo.
( https://cl.indeed.com/cmp/Grupo-Santander/reviews y https://cl.indeed.com/cmp/Santander/reviews)
Trabajar en Santander: 59 evaluaciones | Indeed.com
59 evaluaciones de empleados de Santander sobre la cultura de la empresa, los salarios, los beneficios, el equilibrio entre el trabajo y la vida personal, la seguridad, la gestión y más en Santander.
cl.indeed.com

Trabajar en Grupo Santander: 609 evaluaciones | Indeed.com
609 evaluaciones de empleados de Grupo Santander sobre la cultura de la empresa, los salarios, los beneficios, el equilibrio entre el trabajo y la vida personal, la seguridad, la gestión y más en Grupo Santander.
cl.indeed.com

2) Se procesó la información mediante un app que proporciona cierta interfaz de procesamiento para hacer un webscrapping de los comentarios. (Parsehub) 
El flujo de la app está más o menos de esta forma.



3) Se tomó el procesamiento de la data en alteryx para hacer una unión, limpiar campos, filtrar datos, eliminar data que no sirve, etc etc. El flujo fue algo así: 



4) Por último, se trabajó dentro del ambiente de alteryx con Python botando un archivo para un tablero en Tableau.

Alteryx






Tableau

