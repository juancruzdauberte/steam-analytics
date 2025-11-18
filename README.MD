# Análisis de Datos juegos de PC en Steam

Este repositorio contiene un análisis exploratorio de datos (EDA) del dataset "Top PC Games: Metacritic vs Steam Popularity". El objetivo principal es limpiar, analizar y visualizar los datos para descubrir patrones y relaciones de la opinión de los usuarios de Steam y la popularidad de los juegos de PC.

**Dataset original en Kaggle:** [Top PC Games: Metacritic vs Steam Popularity](https://www.kaggle.com/datasets/alyahmedts13/top-pc-games-metacritic-vs-steam-popularity)

---

## 🎯 Objetivos del Análisis

Este proyecto busca responder preguntas clave sobre el éxito y la recepción de los videojuegos, tales como:

- **Limpieza de Datos:** ¿Cómo manejar valores nulos (`NaN`) y convertir columnas de texto (como `precio` o `puntuación`) a formatos numéricos para el análisis?
- **Ranking de Juegos:** ¿Cuáles son los juegos "Top 5" según diferentes métricas (tiempo de juego, puntuación, total de reseñas)?
- **Análisis de Reseñas:** ¿Cuál es la verdadera recepción de un juego? Se normalizarán las reseñas positivas y negativas para crear un **porcentaje de aprobación** y así comparar juegos con diferentes volúmenes de reseñas de manera justa.
- **Correlación:** ¿Existe alguna relación entre el precio de un juego y la cantidad de reseñas negativas que recibe?
- **Visualización:** Crear gráficos de barras, histogramas, gráficos de tortas y gráficos de dispersión para comunicar los hallazgos de forma efectiva.
- **Segmentación:** Agrupar los juegos por `editor` o `revelador` (desarrollador) para ver quién domina el mercado.

---

## 🛠️ Tecnologías Utilizadas

- **Python:** Lenguaje principal para el análisis.
- **Pandas:** Para la manipulación y limpieza de datos.
- **NumPy:** Para operaciones numéricas y manejo de valores `NaN`.
- **Matplotlib / Seaborn:** Para la visualización de datos.
- **Jupyter Notebook:** Como entorno de trabajo interactivo para el análisis.

---

## 📖 Diccionario de Datos

El dataset (`.csv`) contiene las siguientes columnas:

- `appid`: ID de aplicación de Steam único para cada juego.
- `name`: Título oficial del juego en Steam.
- `developer`: Desarrollador o estudio responsable del juego.
- `publisher`: Compañía que publicó el juego en Steam.
- `score_rank`: Puntuación de clasificación de SteamSpy (si está disponible).
- `positive`: Número de reseñas positivas de usuarios.
- `negative`: Número de reseñas negativas de usuarios.
- `userscore`: Valor de la puntuación del usuario de SteamSpy (0 si no está disponible).
- `owners`: Rango estimado de propiedad (ej., “1,000,000 .. 2,000,000”).
- `average_forever: Tiempo total de juego promedio (en minutos).
- `average_2weeks`: Tiempo promedio de juego (en minutos) durante las últimas dos semanas.
- `median_forever`: Tiempo total de juego medio (en minutos).
- `median_2weeks`: Tiempo medio de juego (en minutos) durante las últimas dos semanas.
- `price`: Precio actual del juego en centavos (ej., 999 = $9.99).
- `initialprice`: Precio original del juego antes de descuentos (en centavos).
- `discount`: Porcentaje de descuento actual (0–100).
- `ccu`: Número actual de jugadores simultáneos (CCU).

---

## ✍️ Autor

- **Juan Cruz Dauberte** - [Juan Cruz Dauberte](https://www.linkedin.com/in/juancruzdauberte/)
