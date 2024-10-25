# Teoría cuántica básica, Observables y Medidas
## Introducción

Este repositorio contiene un simulador cuántico que permite realizar ejercicios de mecánica cuántica, basados en los conceptos descritos en clase. A continuación, se indican las instrucciones para instalar las librerías necesarias , el contenido de cada uno de los archivos y cómo ejecutar los ejercicios.
# Tabla de Contenido

## 1. (archivo "primera parte") Simulación de un Sistema Cuántico 
El sistema consiste en una partícula confinada a un conjunto discreto de posiciones en una línea. El simulador debe permitir especificar el número de posiciones y un vector ket de estado asignando las amplitudes.

1. El sistema debe calcular la probabilidad de encontrarlo en una posición en particular.
2. El sistema, si se le da otro vector ket, debe buscar la probabilidad de transitar del primer vector al segundo.

## 2. (archivo "segunda parte") Retos de Programación del Capítulo 4
Complete los retos de programación del capítulo 4.

1. Amplitud de transición: el sistema puede recibir dos vectores y calcular la probabilidad de transitar del uno al otro después de hacer la observación.
2. Con una matriz que describa un observable y un vector ket, el sistema revisa que la matriz sea hermitiana, y si lo es, calcula la media y la varianza del observable en el estado dado.
3. El sistema calcula los valores propios del observable y la probabilidad de que el sistema transite a alguno de los vectores propios después de la observación.
4. Se considera la dinámica del sistema. Ahora, con una serie de matrices unitarias, el sistema calcula el estado final a partir de un estado inicial.

## 3. (archivo "ejercicios cap4") Problemas Adicionales
Realice los siguientes problemas e inclúyalos como ejemplos:
- Problema 4.3.1
- Problema 4.3.2
- Problema 4.4.1
- Problema 4.4.2

## Requisitos

Para ejecutar los ejercicios, necesitarás tener instaladas las siguientes librerías de Python:

- `numpy`
- `jupyter`

Puedes instalar estas librerías usando `pip`. Si no tienes `pip` instalado, asegúrate de hacerlo antes de continuar.

## Instalación de librerías

Ejecuta los siguientes comandos en tu terminal o símbolo del sistema:

```bash
pip install numpy jupyter
