# **Análisis de Tráfico Web - Business Inteligence**

## **Introducción**
Este proyecto busca identificar los factores que impulsan la conversión de usuarios y sugiere estrategias de optimización. Denominamos conversión a concretar una acción deseada por el negocio, mientras que la tasa de conversión mide la efectividad de que el objetivo del sitio web se cumpla. 

El dataset provee la siguiente información:

- **Page Views**: La cantidad de páginas visitadas en una sesión.
- **Session Duration**: La duración en minutos de la sesión.
- **Bounce Rate**: La cantidad de usuarios que salieron del sitio web viendo una única página.
- **Traffic Source**: La fuente de origen del usuario.
- **Time on Page**: El tiempo que estuvo un usuario en una página específica.
- **Previous Visits**: La cantidad de visitas previas hechas por el mismo usuario.
- **Conversion Rate**: El porcentaje de usuarios que completaron una acción deseada.

---

## **Contenido**
1. [Análisis Exploratorio de Datos (EDA)](#Análisis-exploratorio-de-Datos-(EDA))
2. [Modelo Predictivo (Machine Learning)](#Modelo-Predictivo-(Machine-Learning))
3. [Insights](#Insights)
4. [Recomendaciones de Business Inteligence](#Recomendaciones-de-Business-Inteligence)
5. [Conclusión](#Conclusión)

---

## **Análisis Exploratorio de Datos (EDA)**
- Hice distintos scatterplots para comparar distintas variables con Conversion Rate con el fin de comprender el comportamiento de los usuarios que completan las acciones deseadas.

![Session Duration](session_duration.png)
Podemos ver aquí que más de 6 minutos por sesión no significa una mayor conversión

![Time on Page](time_on_page.png)
Podemos notar que más de 7 minutos en una página no signiica una mayor conversión

- Busque comprender las distintas fuentes de tráfico con un boxplot. Tenemos tráfico orgánico, pago, social, directo y referido. Se pudo ver que estas 5 fuentes son igual de eficientes al convertir.
  
- Analicé el comportamiento de los usuarios basandome en las visitas previas. Se encontraron patrones de comportamiento para los usuarios que mas frecuentan el sitio web. Aquellos con mayor cantidad de visitas, se supone que ya conocen el sitio web y saben lo que quieren porque sus sesiones son mas cortas. Por otro lado, el siguiente gráfico permite ver que más de 5 visitas previas casi aseguran una conversión

![Previous Visits](previous_visits_conversion.png)

---

## **Modelo Predictivo (Machine Learning)**


---

## **Insights**

---

## **Recomendaciones de Business Inteligence**


---

## **Conclusión**

   ![Dashboard 4](productos.png)
