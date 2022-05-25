# LeadScoring-Machine-Learning
## Puntuación de clientes potenciales basado en ML

¿Cómo es el proceso de captación de clientes en las empresas?

Por lo general, las grandes empresas utilizan un modelo comercial inbound multifase donde se identigican 4 etapas:
 * Marketing online y ofline
 * Generación de leads
 * Gestión de leads
 * Venta


¿Cuáles son los principales problemas a los que se enfrentan?

En muchos casos el número de leads excede la capacidad de los canales comerciales, especialmente los medianos, saturando el canal, generando quejas a los comerciales y obteniendo menos resultados de los posibles. Esto se traduce en bajos ingresos para la empresa.


**Propuesta de mejora**

Proyecto del ámbito de marketing digital, con aplicación de modelos de ML que facilitan la identificación de clientes (Leads) con mayor potencial comercial.

<img width="599" alt="Proceso que genera Lead Scoring" src= "https://github.com/jorgeariasm/LeadScoring---Machine-Learning/blob/main/predictive_lead_scoring.png">

Entre las principales etapas del proyecto destacan:

  * Monitorización del Customer Journey
  * Modelización predictiva
  * Segmentación de clientes

Esta aproximación de Machine Learning en Scikit-learn, está más enfocada al uso optimizado de los algoritmos, frente al análisis pormenorizado en búsqueda de insights 
de negocio. Haciendo uso de una metodología híbrida entre las más reconocidas CRISP-DM y SEMMA, se ejecutan las etapas secuencialmente, desde la importación de los datos
y su tratamiento, hasta la modelización y evaluación de los algoritmos utilizados, todo esto gracias a un framework estructurado y replicable en múltiples proyectos, que
permite la ejecución de los mísmos de forma muy eficaz.

En las carpetas del proyecto se encuentran:

  * **01_Documentos:** contiene archivo .yml con la configuración del entorno de trabajo y plantillas en excell para seguimiento de transformaciones realizadas en fase de desarrollo
     y procesos ejecutados en fase de producción.
  * **02_Datos:** conjunto de datos para el desarrollo y separación de los mismos entre originales, vaidación y trabajo.
  * **03_Notebooks:** cuadernos .ipynb con las 10 etapas de desarrollo de este proyecto.
  * **04_Modelos:** archivos en formato .pickle de entrenamiento y de ejecución de los modelos.
  * **05_Resultados:** archivos en formato .pickle con las variables finales elegidas para la modelización.


Como valor añadido, se realiza una segmentación mediante modelos no supervisados,  que permitirá entender mejor qué tipo de leads está capturando la empresa y 
nos permite darle recomendaciones de consultoría
