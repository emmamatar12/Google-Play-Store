# Google Play Store Market Analysis

De Literatura a Ciencia de Datos.  
Trabajo donde la estrategia, la creatividad y la analítica convergen.

---

## Contexto

Este proyecto analiza el ecosistema de Google Play Store utilizando datos reales de más de 9,000 aplicaciones móviles.

El objetivo es entender el comportamiento de los usuarios, el desempeño de las apps y la dinámica del mercado a través de análisis de datos y visualización.

---

## Objetivo

- Identificar patrones en las calificaciones y comportamiento de usuarios  
- Analizar diferencias entre aplicaciones gratuitas y de pago  
- Explorar la distribución por categorías y concentración del mercado  
- Extraer insights útiles para estrategia de negocio  

---

## Dataset

- Fuente: https://www.kaggle.com/  
- Registros: 9,659 apps después de limpieza  
- Variables: Category, Rating, Reviews, Size, Installs, Price, Content Rating, Genres  

Nota: Los datos crudos no se incluyen por su tamaño. Consulta la fuente.

---

## Metodología

1. Limpieza y preparación de datos  
   - Eliminación de duplicados  
   - Conversión de columnas (Installs, Price) a formato numérico  
   - Manejo de valores faltantes  

2. Análisis exploratorio  
   - Distribución por categorías  
   - Distribución de calificaciones  
   - Relación tamaño y precio  

3. Análisis comparativo  
   - Apps gratuitas vs de pago  
   - Categoría vs precio  

4. Análisis de sentimiento  
   - Comparación de polaridad en reseñas  

---

## Hallazgos clave

- El mercado está concentrado: categorías como *Family*, *Game* y *Tools* dominan en volumen  
- No se encontró una relación clara entre el tamaño de la app y su calificación  
- Las apps de pago tienen calificaciones ligeramente más altas (4.26 vs 4.17), pero mucha menor popularidad  
- Las apps gratuitas dominan en descargas, pero presentan mayor variabilidad en opiniones  
- Se identificaron apps con precios muy altos sin valor funcional claro (outliers)  

---

## Interpretación de negocio

- Las calificaciones altas no diferencian significativamente, ya que la mayoría de apps están bien valoradas  
- Las apps gratuitas maximizan alcance, pero las de pago tienden a tener usuarios más estables  
- Existe saturación en categorías principales  
- La estrategia de precio debe centrarse en el valor percibido, no solo en el costo  

---

## Herramientas y tecnologías

- Python (Pandas, NumPy, Scikit-learn)  
- Visualización (Matplotlib, Seaborn)  
- Jupyter Notebook  

---

## Contenido del proyecto

En este repositorio encontrarás:

- **/notebooks**  
  Notebook principal con todo el análisis: limpieza de datos, exploración, visualizaciones y conclusiones.


- **Archivo de conclusiones (PDF)**  
  Resumen estructurado de los hallazgos más relevantes del análisis.

- **Dataset**  
  No se incluye directamente en el repositorio por su tamaño, pero se proporciona el enlace en la sección correspondiente.

---

## Contacto

📩 Correo: emmanuelmata111@gmail.com
