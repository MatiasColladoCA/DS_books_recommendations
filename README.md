# DS_books_recommendations

Sobre el dataset
https://sites.google.com/eng.ucsd.edu/ucsdbookgraph/home (redirige a https://mengtingwan.github.io/data/goodreads.html)

Recopilado a finales de 2017 a partir de goodreads.com. Solo se hizo scraping de los estantes públicos de los usuarios, es decir, todos pueden verlo en la web sin iniciar sesión. Los ID de usuario y los ID de revisión son anónimos. Recopilamos estos conjuntos de datos solo para uso académico. No los redistribuya ni los use con fines comerciales.

Recopilacion de tres grupos de conjuntos de datos:

(1) metadatos de los libros
(2) interacciones usuario-libro (estantes públicos de usuarios)
(3) reseñas detalladas de libros de usuarios. Estos conjuntos de datos se pueden fusionar uniéndose en identificadores de libro/usuario/revisión.
Estadísticas Básicas del Gráfico Completo del Libro:

2.360.655 Libros (1.521.962 obras, 400.390 series de libros, 829.529 autores)
876.145 Usuarios; 228.648.342 interacciones usuario-libro en los estantes de los usuarios (incluyen 112.131.203 lecturas y 104.551.549 calificaciones)
Sobre este notebook:
Del conjunto 'Meta-Data of Books' se usó: goodreads_books.json.gzn goodreads_book_genres_initial.json.gz

Del conjunto 'Book Shelves' se usó: goodreads_interactions.csv

Configuración inicial de vinculación con repositorio de github
Analisis
Quitar información innecesaria (columnas innecesarias para el analisis buscado)
Analizar datos faltantes o erroneos
Eliminación o imputación de valores faltantes.
Graficas de visualización para comprensión de los datos
Descripción
Predicción
Prescripción
