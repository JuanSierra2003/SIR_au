# Simulación de Modelo SIR en Redes

Este repositorio contiene un código en Python para simular un modelo SIR (Susceptible-Infectado-Recuperado) en una red utilizando NetworkX, Matplotlib y NumPy.

## Descripción

El código simula la propagación de una enfermedad infecciosa en una red usando el modelo SIR. Se emplea la red Watts-Strogatz generada con NetworkX como la estructura sobre la cual se propagará la enfermedad.
Librerías Utilizadas

    NetworkX: Utilizada para crear y analizar la red Watts-Strogatz.
    Matplotlib: Empleada para visualizar la propagación de la enfermedad en la red.
    NumPy: Usada para manipular arreglos y operaciones numéricas.

## Detalles del Modelo

El código inicia la simulación con un nodo infectado y aplica las reglas del modelo SIR, donde se consideran las tasas de transmisión, recuperación y mortalidad. Además, se introduce un período de exposición para el estado de "Expuesto" antes de que un individuo se vuelva infeccioso.
Parámetros

    Tasa de transmisión (beta): 0.2
    Tasa de recuperación (gamma): 0.15
    Tasa de mortalidad (alpha): 0.01
    Tiempo final de simulación: 150 unidades de tiempo
    Tiempo de recuperación: 10 unidades de tiempo

## Visualización

La visualización se realiza en diferentes instantes de tiempo (cada 10 unidades de tiempo hasta t=80) utilizando Matplotlib para representar la red con colores distintos para los estados de los nodos (Susceptible, Infectado, Recuperado, Expuesto y Muerto).


## Uso

El archivo principal es modelo_SIR_aumentado.ipynb. Puedes ejecutarlo con Python 3.x y las librerías mencionadas instaladas.

## Contribuciones

¡Se aceptan contribuciones para mejorar este modelo o añadir funcionalidades nuevas!