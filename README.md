# Sistema de Visión Artificial para la Identificación y Clasificación Automatizada de Objetos Celestes

## Descripción

Proyecto modular de Ingeniería Informática orientado al desarrollo de una plataforma de visión artificial basada en Inteligencia Artificial y Deep Learning para procesar imágenes astronómicas e identificar y clasificar automáticamente objetos celestes.

## Problema

El procesamiento y catalogación de imágenes astronómicas presenta dificultades debido a la dependencia de análisis manuales y de algoritmos tradicionales de visión artificial que pueden presentar limitaciones ante imágenes con ruido visual. El crecimiento de los datos astronómicos hace necesario contar con una herramienta informática capaz de interpretar, filtrar y clasificar automáticamente los objetos celestes de manera eficiente.

## Objetivo general

Desarrollar una plataforma informática modular basada en Inteligencia Artificial y visión artificial que permita procesar imágenes astronómicas para segmentar, identificar y clasificar automáticamente objetos celestes.

## Objetivos particulares

1. Preparar y preprocesar datasets públicos de imágenes astronómicas para su utilización en el entrenamiento y evaluación del modelo.

2. Diseñar y entrenar un modelo de Deep Learning basado en Redes Neuronales Convolucionales (CNN) para identificar y clasificar objetos celestes.

3. Implementar una interfaz básica que permita ingresar imágenes astronómicas y visualizar los resultados de su clasificación.

4. Evaluar el funcionamiento del sistema mediante métricas de precisión, tiempo de inferencia y capacidad de clasificación de al menos tres categorías de objetos celestes.

## Alcance

El proyecto contempla:

- Desarrollo de la plataforma utilizando Python.
- Preparación y preprocesamiento de imágenes astronómicas.
- Utilización de datasets públicos para el entrenamiento del modelo.
- Diseño y entrenamiento de un modelo de Deep Learning/CNN.
- Identificación y clasificación de objetos celestes.
- Clasificación inicial de estrellas, galaxias y nebulosas.
- Evaluación del modelo mediante un conjunto de datos de prueba.
- Medición de precisión y tiempo de inferencia.
- Desarrollo de una interfaz básica para visualizar los resultados.
- Documentación técnica del sistema.

## Fuera de alcance

La primera versión del proyecto no contempla:

- Control físico de un telescopio como requisito indispensable.
- Construcción de hardware astronómico propio.
- Desarrollo de un telescopio o sistema de captura físico.
- Clasificación de todas las categorías existentes de objetos astronómicos.
- Procesamiento directamente desde un telescopio físico como requisito principal.
- Sustitución de software astronómico profesional.

Las funcionalidades de navegación, integración con hardware y ampliación de categorías se consideran posibles extensiones futuras.

## MVP (Minimum Viable Product)

La versión mínima viable del proyecto consistirá en una aplicación capaz de recibir una imagen astronómica, procesarla mediante un modelo de Deep Learning/CNN y clasificar automáticamente el objeto celeste identificado en al menos una de tres categorías:

- Estrella
- Galaxia
- Nebulosa

El MVP deberá permitir visualizar el resultado de la clasificación y demostrar un funcionamiento medible mediante una precisión objetivo de al menos 85 % sobre el conjunto de prueba y un tiempo de inferencia inferior a 2 segundos por imagen.

## Criterios de éxito

El proyecto se considerará funcional cuando:

- Alcance una precisión mínima del 85 % en el conjunto de prueba.
- Procese cada imagen en menos de 2 segundos.
- Sea capaz de clasificar al menos tres categorías de objetos celestes.
- Permita visualizar el resultado de la clasificación.

## Tecnologías

- Python
- TensorFlow y/o PyTorch
- OpenCV
- Git
- GitHub
- Visual Studio Code

## Datasets y fuentes de información

Se contempla el uso de datasets públicos de imágenes astronómicas, incluyendo recursos como:

- Sloan Digital Sky Survey (SDSS)
- Galaxy Zoo
- Catálogos y bases de datos astronómicas disponibles públicamente

## Equipo

### Amaya Itzel Reyes Nuñez

**Rol:** Líder técnico

Responsable de coordinar las actividades del equipo, establecer prioridades, supervisar el desarrollo del proyecto, dar seguimiento a los avances y verificar el cumplimiento de los objetivos.

### Diego Antonio Hernandez Anaya 

**Rol:** Integrador / Validación y Pruebas

Responsable de integrar el modelo de Inteligencia Artificial con el procesamiento de imágenes, la interfaz y los demás componentes del sistema, además de diseñar y ejecutar pruebas de validación.

### Jesus Emmanuel Salas Rios

**Rol:** Documentación

Responsable de elaborar y mantener actualizada la documentación técnica, registrar avances, decisiones y resultados del proyecto.

## Estado del proyecto

El proyecto se encuentra en etapa inicial de planificación y organización del desarrollo.

## Organización del trabajo

El trabajo será gestionado mediante GitHub Issues y GitHub Projects, utilizando los estados:

- Backlog
- To Do
- In Progress
- Done
