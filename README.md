# Análisis del Mercado de Google Play Store

De Literatura a Ciencia de Datos.  
Trabajo donde la estrategia, la creatividad y la analítica convergen.

---

## Contexto

Este proyecto analiza el ecosistema de Google Play Store a partir de un dataset real de aplicaciones móviles.

El objetivo es entender cómo se comportan las apps en términos de calificaciones, descargas, precios y percepción de los usuarios.

---

## Objetivo

- Analizar la distribución de aplicaciones por categoría  
- Evaluar el comportamiento de las calificaciones (ratings)  
- Explorar la relación entre tamaño, precio y calificación  
- Comparar el desempeño de apps gratuitas vs de pago  
- Analizar el sentimiento de las reseñas de usuarios  

---

## Dataset
https://drive.google.com/drive/folders/1RBobZZ0mdyHDK0Z_SuBz2e6PXhcZPCFi?usp=drive_link

- Más de **9,659 aplicaciones** después de eliminar duplicados  
- 33 categorías diferentes de aplicaciones  
- Variables clave: Rating, Reviews, Size, Installs, Price, Category, Type  

Los datos fueron limpiados para eliminar caracteres especiales y asegurar consistencia numérica en variables como Installs y Price.

---

## Metodología

1. Limpieza de datos  
   - Eliminación de duplicados  
   - Conversión de variables a formato numérico  
   - Validación de valores  

2. Análisis exploratorio  
   - Distribución por categorías  
   - Distribución de ratings  
   - Análisis de tamaño y precio  

3. Análisis comparativo  
   - Apps gratuitas vs de pago  
   - Relación entre categoría y precio  

4. Análisis de sentimiento  
   - Evaluación de polaridad en reseñas de usuarios  

---

## Hallazgos clave

- El dataset contiene 33 categorías, donde *Family*, *Game* y *Tools* concentran la mayor cantidad de aplicaciones  
- El rating promedio es de aproximadamente **4.17**, con la mayoría de apps entre 4.0 y 4.7  
- No se encontró una relación clara entre el tamaño de la app y su calificación  
- Las apps de pago tienen un rating promedio ligeramente mayor (**4.26 vs 4.17**)  
- Las apps gratuitas dominan en descargas y número de reseñas  
- Existen aplicaciones con precios extremadamente altos (hasta ~$400), muchas sin valor funcional claro  

---

## Interpretación de negocio

- Las calificaciones altas no son un diferenciador fuerte, ya que la mayoría de apps están bien valoradas  
- Las apps gratuitas maximizan alcance y visibilidad, pero presentan mayor variabilidad en la percepción del usuario  
- Las apps de pago tienen usuarios más estables, pero menor volumen  
- El mercado está concentrado en pocas categorías, lo que sugiere alta competencia  
- La estrategia de monetización debe considerar percepción de valor más que el precio absoluto  

---

## Herramientas y tecnologías

- Python (Pandas)  
- Visualización (Matplotlib, Seaborn)  
- Jupyter Notebook  

---

## Contenido del proyecto

En este repositorio encontrarás:

- **Notebook principal**  
  Contiene todo el análisis: limpieza de datos, exploración, visualizaciones y conclusiones.

- **Archivo de conclusiones (PDF)**  
  Resumen estructurado de los hallazgos más importantes.

---

## Contacto

📩 Correo: emmanuelmata111@gmail.com
