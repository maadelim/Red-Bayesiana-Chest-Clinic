# Red-Bayesiana-Chest-Clinic
Implementación del modelo Chest Clinic (Asia) usando Redes Bayesianas en Python. Proyecto de diagnóstico médico probabilístico con pgmpy.
# Diagnóstico Probabilístico: Modelo Chest Clinic (Asia) 🏥

Este repositorio contiene la resolución de la **Evaluación Continua 2 (EC3)** centrada en el uso de **Redes Bayesianas** para el diagnóstico médico. Se utiliza el modelo estándar "Asia" para calcular probabilidades de enfermedades pulmonares basándose en factores de riesgo y evidencia clínica.

##  Descripción del Problema
El modelo simula el razonamiento de una clínica especializada en el pecho, relacionando variables como:
- **Factores de Riesgo:** Visita a Asia, Tabaquismo.
- **Enfermedades:** Tuberculosis, Cáncer de Pulmón, Bronquitis.
- **Síntomas y Evidencia:** Disnea (dificultad para respirar), Resultados de Rayos X.



##  Tecnologías y Librerías
- **Lenguaje:** Python 3.12
- **Librería Principal:** `pgmpy` (Probabilistic Graphical Models)
- **Otras:** `numpy`, `pandas`, `VariableElimination`

##  Resultados de Inferencia Clave
A través del motor de inferencia, el proyecto responde a consultas críticas como:
* **Probabilidad de Cáncer:** Un fumador con disnea y Rayos X anormales tiene un **69.33%** de probabilidad de padecer Cáncer de Pulmón.
* **Impacto del viaje a Asia:** La probabilidad de Tuberculosis aumenta significativamente al **33.77%** si el paciente visitó Asia y presenta una radiografía anormal.

##  Referencias
El desarrollo se apoya en la literatura proporcionada en el curso, incluyendo el artículo de **Prakash P. Shenoy (2023)** sobre inferencia en redes bayesianas incompletas.

---
Desarrollado para el curso de Inteligencia Artificial.
