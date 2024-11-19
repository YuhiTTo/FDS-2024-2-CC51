# FDS-2024-2-CC51
  
Objetivos del proyecto 

El objetivo principal de este análisis es identificar y comprender las tendencias de los videos de YouTube en Gran Bretaña, respondiendo a preguntas como: ¿Qué características de los videos tienden a captar más atención en esta región? ¿Qué patrones pueden observarse en 
las preferencias de contenido de los usuarios británicos? Este análisis busca generar conocimiento que permita al cliente anticiparse a los cambios en el comportamiento de los usuarios y adaptar sus estrategias de marketing digital en función de las tendencias 
observadas.

Objetivos de Data Science 

Traduciendo estos objetivos comerciales en metas concretas de ciencia de datos, el proyecto de minería de datos identificará y analizará variables clave que podrían influir en la popularidad de un video. 
Variables independientes: Estas incluyen title, channel_title, category_id, publish_time, tags, comments_disabled, ratings_disabled, video_error_or_removed, description, state, lat, lon, y geometry. Cada una aporta características importantes que podrían influir en la 
interacción de los usuarios con el contenido. 

Variable dependiente (a predecir): La variable dependiente en este análisis será la popularidad de los videos, medida a través de las variables views, likes, dislikes, y comment_count. Estas métricas de interacción reflejan la respuesta del público y ayudarán a 
identificar patrones de popularidad y preferencias entre los usuarios de YouTube en Gran Bretaña. 
Se utilizará la metodología CRISP-DM (Cross Industry Standard Process for Data Mining).


- Nombre de los alumnos participantes:
  
Carlos Alejandro Molina Huatuco (U20211G139)
  
Lucero Salome Manchay Paredes (202216120)
  
José Antonio Mayhua Hinostroza (202218044)

- Breve descripcion del dataset:

Este proyecto de analítica tiene como objetivo desarrollar un análisis exhaustivo de las tendencias de videos de YouTube en siete países estratégicos, en respuesta a la necesidad de información de una destacada empresa de marketing digital. 

El conjunto de datos analiza videos de YouTube y contiene las siguientes variables: video_id (ID único del video), trending_date (fecha en que el video fue tendencia), title (título del video), channel_title (nombre del canal), category_id (ID de la categoría), 
publish_time (fecha y hora de publicación), tags (etiquetas del video), views, likes, dislikes, y comment_count (métricas de interacción como vistas, "me gusta", "no me gusta" y comentarios), thumbnail_link (enlace a la miniatura), comments_disabled y ratings_disabled 
(indicadores de si los comentarios o valoraciones están deshabilitados), video_error_or_removed (si el video fue eliminado o tiene error), description (descripción del video), y variables para análisis geográfico: state (estado asignado), lat (latitud), lon (longitud), 
y geometry (información espacial). Los tipos de datos incluyen objetos, enteros, flotantes, booleanos y fechas.


- Conclusiones

Hemos logrado extraer conocimiento valioso y generar valor a partir de los datos, permitiendo 
fundamentar y tomar decisiones basadas en la analítica de datos de YouTube para el país de Gran 
Bretaña.
-La metodología CRISP-DM ha demostrado ser una guía efectiva para el desarrollo del proyecto. A 
través de sus fases (Comprensión del Negocio, Comprensión de los Datos, Preparación de los Datos, 
Modelado, Evaluación y Despliegue), se ha asegurado una estructura clara y coherente para abordar el 
problema planteado.
-Se han identificado las categorías de videos con mayor tendencia y las que generan más interacción 
(me gusta, no me gusta, vistas y comentarios).
-Los modelos desarrollados han sido evaluados y han demostrado un buen desempeño en términos de 
precisión y exactitud, validando su capacidad para predecir y analizar las tendencias de los videos de 
YouTube en los países estudiados.

- Licencia
MIT License

Copyright (c) 2024 Lucero Salome Manchay Paredes

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
