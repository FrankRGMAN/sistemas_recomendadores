# Sistemas Recomendadores de Películas

Este proyecto implementa tres tipos de sistemas de recomendación usando el dataset MovieLens + TMDB (~45,000 películas):

## 1. Recomendador simple (estilo IMDb Top 250)
Calcula una puntuación ponderada usando:
- Calificación promedio (R)
- Número de votos (v)
- Promedio global (C)
- Umbral mínimo de votos (m)

## 2. Recomendador basado en contenido (TF‑IDF)
Compara películas según la similitud de sus sinopsis usando:
- TF‑IDF
- Similitud coseno

## 3. Recomendador basado en metadatos
Usa información más rica:
- Actores principales
- Director
- Palabras clave
- Géneros

Crea una “sopa de metadatos” y la vectoriza con CountVectorizer.

## Estructura del proyecto
sistemas_recomendadores/ │ ├── data/ │   ├── movies_metadata.csv │   ├── credits.csv │   └── keywords.csv │ ├── notebooks/ │   └── recomendadores_peliculas.ipynb │ └── README.md


## Requisitos

pandas numpy scikit-learn


## Ejecución

1. Activar entorno virtual  
2. Abrir Jupyter Notebook  
3. Ejecutar el notebook celda por celda  