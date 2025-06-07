# Lift & Lead ; Análisis de Medallas del Campeonato Europeo de Halterofilia 

Este proyecto es un análisis de mercado para la apertura de centros especializados en Halterofilia

La startup ficticia L i f t & L e a d está explorando la posibilidad de abrir centros de entrenamiento
especializados en halterofilia. Con el creciente interés en el CrossFit, que incorpora técnicas
de este deporte, los fundadores creen que es un buen momento para invertir en centros
dedicados exclusivamente a la halterofilia.


El objetivo de este caso práctico es validar la hipótesis de que el auge del CrossFit está
aumentando el interés por la halterofilia en Europa, realizando un estudio de las medallas obtenidas 
en el Campeonato Europeo de Halterofilia


Los datos han sido obtenidos mediante web scraping, a través de la web de Wikipedia.


## **Herramientas** 

El análisis de datos se ha realizado utilizando Python y las siguientes librerías:
- Pandas: Para manipulación y análisis de datos.
- Numpy: Para operaciones numéricas y manejo de arrays.
- Plotly: Para visualización interactiva de datos.
- Requests: Para realizar solicitudes HTTP durante el web scraping.
- html5lib: Para parsear HTML.
- BeautifulSoup (de bs4): Para extraer datos de documentos HTML.
- re: Para trabajar con expresiones regulares.
- FuzzyWuzzy: Para realizar coincidencias de cadenas difusas y limpieza de datos.


## Habilidades y técnicas usadas

Para llevar a cabo el análisis, se llevaron a cabo distintas funciones y acciones en las distintas etapas
del analisis , para la limpieza y manipulación de Datos se aplicaron expresiones regulares para identificar y corregir los nombres de atletas y paises, 
se llevo a cabo la creación y eliminación de distintas columnas según la evolución del análisis . 
Para ampliar la información y unificar funciónes se llevo a cabo web scrapping a través de distintas paginas en Wikipedia.  


## Conclusiones

Las conclusiones del análisis se pueden visualizar en Jupyter Notebook, donde se explican los resultados obtenidos
