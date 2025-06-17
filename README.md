# Popular App Genres: iOS vs Android

Este proyecto analiza los géneros de aplicaciones más comunes y populares en las tiendas App Store (iOS) y Google Play (Android). Se trabajó con datos públicos y se utilizó Python en un Jupyter Notebook para llevar a cabo limpieza, exploración y análisis de los datos.

## Archivos

- `popular_app_genres.ipynb`: Notebook principal con el análisis completo.

## Herramientas utilizadas

- Python (Jupyter Notebook)
- Librerías: `csv`, `matplotlib`, `pprint` y manejo básico de listas y diccionarios

## Limpieza de datos

Se realizó un proceso de limpieza para:
- Remover aplicaciones duplicadas
- Filtrar únicamente apps en inglés
- Conservar solo aplicaciones gratuitas

## Análisis

Se analizaron las variables `prime_genre` (iOS), `Category` y `Genres` (Android) para identificar:

- Los géneros más frecuentes en cada plataforma
- El número promedio de usuarios por género, basado en:
  - `rating_count_tot` en iOS como proxy de popularidad
  - `Installs` en Android como medida directa

## Hallazgos clave

### App Store (iOS)

Géneros con mayor promedio de calificaciones:
- Social Networking (~45,499)
- Music (~28,842)
- Reference (~22,411)

### Google Play (Android)

Géneros con mayor promedio de instalaciones:
- Communication (~38.5 millones)
- Video Players (~24.7 millones)
- Social (~23.3 millones)
- Photography (~17.8 millones)
- Productivity (~16.8 millones)

## Recomendación

Para una empresa que desea desarrollar apps gratuitas y monetizarlas con anuncios, se recomienda:

- En iOS: apps de redes sociales, música o referencia
- En Android: apps de comunicación, reproductores de video o productividad

## Autor

Jorge Guadarrama Gamboa  
Contacto: [jorge.guadarrama.gamboa@gmail.com]
