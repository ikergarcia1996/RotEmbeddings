
# Evaluación de word embedding y métodos de generación de meta-embeddings

## ¿Que hay en este repositorio?
Este repositorio almacena el código y resultados del proyecto de fin de grado desarrollado por el alumno Iker García Ferrero. En concreto contiene:

  - Suite para la evaluación de word embeddings y generación de meta embeddings.
		 Permite la evaluación de word embeddings en la tarea del cálculo de la similitud entre palabras. Además incluye las siguientes funciones para la generación de mejores word embeddings: 
	 
	 1. Aplicación de diferentes tipos de normalizaciones (L1, L2, centrado de variables, PPA...)
	 2. Combinación de word embeddings (Aplicación en cascada y Media de las similitudes)
	 3. Generación de meta embeddings (Concatenación, Reducción de dimensionalidad, Media, Retrofitting, Alineación  de espacios vectoriales + Media). Para realizar el retrofitting es necesario el software de faruqui et al. Disponible en la siguiente dirección: https://github.com/mfaruqui/retrofitting. Para el uso de la alineación de espacios vectoriales y posterior media es necesario el software de "Artetxe et al.", disponible en la siguiente dirección: https://github.com/artetxem/vecmap.

- Resultados completos de todas las pruebas realizadas durante el proyecto
- **RotEmbeddings**. Meta-embeddings generados usando el método del alineamiento de espacios vectoriales + Media. Estos word embeddings combinan el conocimiento de WordNet, Common Crawl y PPDB, y obtienen un rendimiento al nivel del estado del arte actual. Se pueden usar como representación del significado de palabras o como punto de partida de diferentes algoritmos de aprendizaje automático. 

    ![Comparativa entre RotEmbeddings y otros word embeddings](https://raw.githubusercontent.com/ikergarcia1996/RotEmbeddings/master/Resultados%20completos/---%20Resultados%20en%20otros%20formatos%20%28ods,%20xlsx...%29%20---/Comparativa.jpg)
    
    
## Descarga de RotEmbeddings
El rendimiento de cada versión puede comprobarse aquí: [Rendimiento RotEmbeddings](https://github.com/ikergarcia1996/RotEmbeddings/tree/master/Resultados%20completos/RotEmbeddings)

- RotEmbeddings: ** Subiendo archivo, se añadirá el enlace en breve **
- RotEmbeddings + PPA: ** Subiendo archivo, se añadirá el enlace en breve **

# Autor

```
Iker García Ferrero
```

# Director del proyecto
```
German Rigau i Claramunt
```

# Documentación

En enlace a la memoria del proyecto se añadirá en breves. 
