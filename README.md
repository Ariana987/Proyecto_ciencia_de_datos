<p align="center">
  <img src="imagen02.png" alt="Logo de ImageNet" width="750"/>
</p>

---

<h3 align="center">Predicción de deserción estudiantil universitaria</h3>
<h4 align="center">Machine Learning aplicado a un problema social real</h4>

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10-blue)
![ML](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-green)
![Status](https://img.shields.io/badge/Status-En%20Desarrollo-yellow)

</div>

## Descripción del Proyecto
<img src="imagen01.png" align="right" width="380" />

La **deserción estudiantil universitaria** es uno de los principales desafíos en América Latina, especialmente en ciudades como **Bogotá**.  
Este proyecto tiene como objetivo **predecir qué estudiantes presentan mayor riesgo de abandonar sus estudios**, permitiendo a las universidades **intervenir de forma temprana**.


 **Objetivo:**  
Construir un modelo de *Machine Learning* que estime la probabilidad de deserción estudiantil utilizando variables académicas, socioeconómicas y de comportamiento.

<br>


## Variables Utilizadas

- Asistencia a clases
- Notas academicas
- Nivel socioeconómico
- Edad
- Carrera universitaria
- Uso de plataformas virtuales

##  Metodología del Proyecto
El desarrollo del proyecto sigue un enfoque estándar de **Ciencia de Datos**:
<p align="center">
  <img src="imagen03.png" alt="Logo de ImageNet" width="1000"/>
</p>


## Modelos de Machine Learning Utilizados

Se entrenaron y compararon los siguientes modelos:

- **Regresión Logística** (modelo baseline)
- **Random Forest**
- **XGBoost**
> [!NOTE]
> Los modelos fueron evaluados priorizando **Recall**, dado que es más importante detectar estudiantes en riesgo que minimizar falsos positivos.


##  Resultados del Modelo

| Modelo              | Accuracy | Recall | F1-score |
|---------------------|----------|--------|----------|
| Regresión Logística | 0.72     | 0.68   | 0.70     |
| Random Forest       | 0.81     | 0.79   | 0.80     |
| XGBoost             | **0.84** | **0.83** | **0.83** |


## Impacto Social y Consideraciones Éticas

Este proyecto tiene como fin **apoyar decisiones académicas**, no penalizar estudiantes.

- Los resultados deben usarse como **herramienta de apoyo**, no como veredicto final
- Se debe garantizar la **protección de datos personales**
- El modelo busca promover **equidad e inclusión educativa**

## Posibles Soluciones

A partir del análisis de datos y las predicciones generadas por el modelo de machine learning, se pueden implementar diferentes estrategias enfocadas en reducir la deserción estudiantil.

### Apoyo Académico Personalizado
Implementar tutorías dirigidas a estudiantes con bajo rendimiento académico.


- Refuerzo en materias críticas  
- Seguimiento continuo del progreso  
- Planes de estudio personalizados  

### Acompañamiento Psicológico
Brindar apoyo emocional a estudiantes con señales de estrés, ansiedad o desmotivación.


- Sesiones con psicólogos  
- Programas de bienestar universitario  
- Prevención de burnout académico  

### Apoyo Económico
Identificar estudiantes con dificultades financieras y ofrecer soluciones.

- Becas o subsidios  
- Facilidades de pago  
- Oportunidades laborales dentro de la universidad  

## Proyecto de apoyo
<a href="https://herramientas.datos.gov.co/usos/modelo-de-prediccion-de-decersion-estudiantil">
  <img src="imagen04.jpeg" alt="portfolio" width="100">
</a>


