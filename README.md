# Decodificación neural intracortical con redes de impulsos (SNN)

Código del Trabajo Fin de Grado "Desarrollo de Redes Neuronales Basadas en
Impulsos Mediante Frameworks de Alto Nivel" (ETSII-UPM).

Replica el sistema de Martis et al. (2024) sobre el dataset de Brochier et al.
(2018) con snnTorch: detección de impulsos sobre la señal del Utah Array y
entrenamiento de una SNN feedforward 96-64-128-64-5 para decodificar la
velocidad y las cuatro fuerzas de agarre.

## Contenido
- SpikeDetectionSimplificado.ipynb: detección de impulsos y extracción de la
  matriz de actividad multiunitaria (MUA) desde la señal neural cruda.
- Entrenamiento_exp08_definitivo.ipynb: entrenamiento y evaluación del
  experimento final (exp_08, evaluación continua).
- Entrenamiento_exp07_definitivo.ipynb: experimento previo de la progresión
  metodológica (exp_07).

## Requisitos
Python 3 con: PyTorch, snnTorch, Neo, NumPy, SciPy.
Instalación: pip install torch snntorch neo numpy scipy

## Datos
Los datos originales son públicos (Brochier et al. 2018):
https://doi.gin.g-node.org/10.12751/g-node.f83565

## Autora
Ainhoa Pardo Alegría. ETSII-UPM.
