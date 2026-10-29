# Unificación de asignaturas duplicadas

Este documento explica cómo se han unificado las asignaturas duplicadas del plan y dónde ha quedado el contenido de cada asignatura original, para poder comprobar que no se ha perdido materia. El plan pasa de 18 a 15 asignaturas. La versión anterior sigue completa en el historial del repositorio.

## Criterio

Cuando dos asignaturas cubrían esencialmente lo mismo, se han fusionado en una. Cuando el solapamiento era parcial, cada tema se ha dejado en la asignatura cuyo objeto principal es ese tema, y las demás conservan una línea en cursiva que remite a ella. De las asignaturas fusionadas se conservan todos los temas, los dos proyectos (como modalidades a elegir, cada una con sus criterios), la bibliografía, los cursos online y los docentes propuestos. Solo se han eliminado las repeticiones literales.

## Asignaturas fusionadas

| Asignatura resultante | Semestre | Procede de |
|---|---|---|
| Computación Afectiva: Análisis y Modelado de Emociones | 1 | Análisis de Emociones y Comportamiento Humano (S1) y Emociones y Comportamiento en Agentes Inteligentes (S1) |
| Análisis y Modelado de Comportamiento Humano | 1 | Se mantiene; absorbe el modelado del comportamiento humano de Emociones y Comportamiento en Agentes Inteligentes y cede las emociones a Computación Afectiva |
| Narrativa, Storytelling y Creación de Personajes en Agentes Inteligentes | 2 | Narrativa y Storytelling en Agentes Inteligentes (S1) y Narrativa y Creación de Personajes (S2) |
| Interacción Humano-Agente: Psicología y Diseño de Experiencia de Usuario | 2 | Psicología de la Interacción Humano-Máquina (S2) e Interacción Humano-Agente y Diseño de Experiencia de Usuario (S4) |

La asignatura de narrativa queda en el Semestre 2 porque la generación automática de historias se apoya en la IA generativa del Semestre 1, y así el Semestre 1, que tenía seis asignaturas, se queda en cuatro. La de interacción ocupa el lugar de Psicología de la Interacción Humano-Máquina en el Semestre 2, antes de Evaluación y Validación de Agentes Creíbles. El resultado son cuatro asignaturas por semestre, salvo el cuarto, que queda con tres.

## Solapamientos parciales resueltos

| Tema | Aparecía en | Queda en |
|---|---|---|
| Comunicación y colaboración entre agentes: protocolos, coordinación y aplicaciones en SMA; en el temario desarrollado, también negociación, confianza y resolución de conflictos | Modelado y Simulación de Agentes (S1) e IA Distribuida y Sistemas Multiagente (S4) | IA Distribuida y Sistemas Multiagente |
| Definición, tipos, modelos (incluido BDI) y arquitecturas de agentes | Temarios desarrollados de las dos asignaturas anteriores | Modelado y Simulación de Agentes |
| Modelado de agentes y del entorno; simulación de SMA | IA Distribuida y Sistemas Multiagente (S4) y Modelado y Simulación de Agentes (S1) | Modelado y Simulación de Agentes |
| Simulación, reconocimiento y expresión de emociones; resonancia emocional y empatía | Psicología de la Interacción Humano-Máquina (S2) e Interacción Humano-Agente y UX (S4) | Computación Afectiva |
| Teorías psicológicas de la emoción (temario desarrollado) | Análisis de Emociones y Comportamiento Humano (S1) y Psicología de la Interacción Humano-Máquina (S2) | Computación Afectiva |
| Emociones (del punto «Emociones y motivación») | Análisis y Modelado de Comportamiento Humano (S1) | Computación Afectiva; la motivación sigue en Comportamiento Humano |
| Diferencia entre emoción, sentimiento y estados afectivos; extracción y análisis de emociones en texto | Inteligencia Artificial Empática (S3) | Computación Afectiva |
| Introducción a la IA y al NLP | Inteligencia Artificial Empática (S3) | Introducción a la IA Generativa (S1) y Comunicación Natural, Tecnologías de Voz y PLN (S3) |
| Análisis de sentimientos con aprendizaje automático y profundo | Inteligencia Artificial Empática (S3) y Comunicación Natural, Tecnologías de Voz y PLN (S3) | Comunicación Natural, Tecnologías de Voz y PLN |

En los temarios desarrollados, los apartados repetidos se han sustituido por una remisión, y lo que solo figuraba en una de las versiones se ha trasladado literalmente a la asignatura que conserva el tema. A Modelado y Simulación de Agentes pasan la noción de autonomía, la distinción entre agentes físicos y virtuales, los agentes basados en modelos y los entornos parcialmente observables, el modelo BDI y las arquitecturas reactivas, cognitivas e híbridas. A IA Distribuida y Sistemas Multiagente pasan el modelado de conflictos y su resolución, la base en teoría de juegos y teoría de la utilidad de la negociación, y la confianza ante agentes egoístas o maliciosos.

## Repeticiones literales eliminadas

El temario desarrollado de Técnicas de Aprendizaje Automático para Agentes estaba copiado, idéntico, en Agentic AI, Fundamentos de LLMOps y Técnicas de Prompt Engineering; la copia ya venía así en la exportación original de Notion. Se mantiene en su asignatura y se han retirado las tres copias, de modo que esas tres asignaturas quedan sin temario, igual que el resto de sus apartados.

El proyecto de aprendizaje por refuerzo para jugar al ajedrez figuraba igual en Técnicas de Aprendizaje Automático para Agentes y en IA Distribuida y Sistemas Multiagente. Se queda en la primera; la segunda conserva su propio proyecto de sistema multiagente.

El primer proyecto y los criterios de evaluación de Psicología de la Interacción Humano-Máquina eran copia literal de los de Análisis y Modelado de Comportamiento Humano, donde se mantienen. La asignatura fusionada de interacción usa los criterios de Interacción Humano-Agente y UX para sus dos modalidades.

También se ha retirado la línea truncada que repetía el proyecto al final de los criterios de Narrativa y Storytelling, y la repetición de *The Design of Everyday Things* y de *Affective Computing* dentro de las asignaturas fusionadas.

## Cambios derivados de la fusión

La explicación de la teoría de James-Lange existía en dos versiones. La de Análisis de Emociones se contradecía («primero sentimos miedo, luego nuestro corazón late más rápido y finalmente interpretamos estas respuestas físicas como miedo»); la de Psicología de la Interacción Humano-Máquina daba la secuencia correcta: primero la respuesta fisiológica y luego su interpretación como miedo. El temario de Computación Afectiva conserva la secuencia correcta.

Las dos fichas originales de la asignatura de emociones proponían a la Dra. Isabel Martínez con afiliaciones distintas (Universidad de Málaga y Universidad Complutense de Madrid). Se conservan ambas biografías con una nota para verificarlo.

El enlace al temario de Análisis de Emociones apuntaba a una ruta de la exportación de Notion que no existe en el repositorio; al trasladarlo a Computación Afectiva queda enlazado.

## Solapamientos que se mantienen

| Tema | Dónde | Motivo |
|---|---|---|
| Redes neuronales y aprendizaje profundo, autoencoders y GAN | Introducción a la IA Generativa (S1) y Técnicas de Aprendizaje Automático para Agentes (S3) | Es un problema de secuencia más que de duplicación: el aprendizaje profundo se usa en el Semestre 1 y se enseña en el 3. Resolverlo exige reordenar el plan, no fusionar. |
| Aprendizaje multiagente | Técnicas de Aprendizaje Automático para Agentes (S3) y temario desarrollado de IA Distribuida y Sistemas Multiagente (S4) | Depende de qué asignatura deba introducirlo; también es una cuestión de orden. |
| Evaluación de la experiencia de usuario y pruebas con usuarios | Interacción Humano-Agente (S2) y Evaluación y Validación de Agentes Creíbles (S4) | Una lo trata como parte del ciclo de diseño y la otra como metodología de evaluación. |
| Personalidad | Comportamiento Humano (teorías), Computación Afectiva (modelos computacionales) y Narrativa (arquetipos) | Son tres enfoques distintos del mismo concepto. |
| Ética | Cada asignatura y Ética y Legislación (S4) | Ética transversal más una asignatura específica, por diseño del plan. |
