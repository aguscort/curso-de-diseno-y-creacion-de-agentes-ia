# Introduccion a la IA Generativa

**Justificación:**

La inteligencia artificial (IA) generativa es un subcampo emergente de la IA que se centra en crear nuevos contenidos o modelos a partir de conjuntos de datos existentes. Esta área combina elementos del aprendizaje profundo, aprendizaje automático, y otros campos relacionados para producir resultados que pueden ser indistinguibles de los creados por humanos. Dada la creciente relevancia de la IA generativa en sectores como las artes, la medicina, la ingeniería y más, es fundamental que los estudiantes adquieran una comprensión sólida de sus principios y técnicas.

## Temario Propuesto:

1. **Qué es un modelo generativo**
    - Modelos generativos y discriminativos; distribuciones de probabilidad, verosimilitud y muestreo
    - Variables latentes y espacios latentes
    - Evolución histórica, de las cadenas de Markov y los n-gramas a los modelos fundacionales; aplicaciones en la industria y la academia
2. **Redes neuronales imprescindibles para la generación**
    - Neuronas, capas y funciones de activación
    - Función de pérdida, descenso de gradiente y retropropagación, a nivel conceptual
    - Representaciones vectoriales (embeddings); primeros pasos con PyTorch
3. **Autoencoders y autoencoders variacionales**
    - Autoencoders y compresión en un espacio latente
    - Autoencoder variacional: cota inferior de la evidencia (ELBO) y truco de reparametrización (Kingma y Welling, 2013)
    - Interpolación y edición en el espacio latente
4. **Redes generativas adversarias**
    - Juego minimax entre generador y discriminador (Goodfellow et al., 2014)
    - Inestabilidad del entrenamiento y colapso de modos
    - Variantes: DCGAN, GAN condicionales y StyleGAN (Karras et al., 2019)
5. **Atención y transformers**
    - Mecanismo de atención, autoatención y atención multicabeza
    - Codificación posicional; arquitecturas de codificador, de decodificador y de codificador-decodificador (Vaswani et al., 2017)
    - Generación autorregresiva y estrategias de decodificación: voraz, por haz, temperatura, top-k y top-p (Holtzman et al., 2020)
6. **Grandes modelos de lenguaje**
    - Preentrenamiento por predicción del siguiente token y composición de los datos
    - Leyes de escala (Kaplan et al., 2020; Hoffmann et al., 2022)
    - Ajuste por instrucciones y alineamiento con preferencias humanas: visión general
    - Modelos de razonamiento y cómputo en tiempo de inferencia; modelos abiertos y cerrados
7. **Modelos de difusión**
    - Difusión con eliminación de ruido, DDPM (Ho et al., 2020)
    - Difusión latente (Rombach et al., 2022) y guía sin clasificador
    - Condicionamiento y personalización: ControlNet, LoRA y DreamBooth
    - Generación de vídeo: visión general
8. **Modelos multimodales**
    - CLIP y alineamiento entre texto e imagen (Radford et al., 2021)
    - Modelos de visión y lenguaje
    - Generación de audio y música: visión general
    - Generación de recursos para agentes: avatares, rostros expresivos y escenarios
9. **Métricas de los modelos generativos**
    - Verosimilitud y perplejidad
    - FID (Heusel et al., 2017) y CLIP score
    - Evaluación por preferencias humanas y comparaciones por pares

*El entrenamiento de redes en profundidad y el aprendizaje con retroalimentación humana se tratan en [Técnicas de Aprendizaje Automático para Agentes](tecnicas-de-aprendizaje-automatico-para-agentes.md); el uso de los modelos mediante prompts, en [Técnicas de Prompt Engineering](tecnicas-de-prompt-engineering.md); la síntesis de voz, en [Comunicación Natural, Tecnologías de Voz y Procesamiento del Lenguaje en Agentes](comunicacion-natural-tecnologias-de-voz-y-procesamiento-del-lenguaje.md).*

## Conceptos Clave:

Modelos Generativos, Redes Generativas Adversarias (GANs), Transformadores, Autoencoders, Modelos de Difusión, Grandes Modelos de Lenguaje, Validación y Evaluación.

## Proyecto Final: 

Creación de una obra de arte o narrativa generada mediante técnicas de IA.

Utilizar GANs (Redes Antagónicas Generativas) para generar imágenes de rostros que expresan emociones específicas. Evaluar la calidad mediante métricas como FID (Frechet Inception Distance).

## Criterios de Evaluación:

1. Presentación (10%)
2. Documentación y explicación del proceso (15%)
3. Aplicación de conceptos aprendidos (20%)
4. Creatividad y originalidad (25%)
5. Calidad técnica del proyecto (30%)

## Bibliografía Obligatoria:

- "Generative Deep Learning: Teaching Machines to Paint, Write, Compose, and Play" por David Foster.

## Bibliografía Recomendada:

- "Deep Learning" por Ian Goodfellow, Yoshua Bengio, y Aaron Courville.
- "Neural Networks and Deep Learning: A Textbook" por Charu Aggarwal.
- "GANs in Action: Deep learning with Generative Adversarial Networks" por Jakub Langr y Vladimir Bok.

## Mejor Curso Online:

- "Deep Learning Specialization" por Andrew Ng en Coursera.

**Docente Español Propuesto:Dr. Francisco Herrera Triguero**

- **Breve Biografía:** El Dr. Francisco Herrera Triguero es Catedrático en el Departamento de Ciencias de la Computación e Inteligencia Artificial de la Universidad de Granada, España. Ha trabajado en numerosos proyectos relacionados con la inteligencia artificial, enfocándose en áreas como sistemas difusos, algoritmos evolutivos y redes neuronales. Ha publicado ampliamente en revistas internacionales y ha sido reconocido por su contribución significativa a la comunidad de inteligencia artificial en España. Su experiencia combinada en aprendizaje automático y deep learning lo hace un candidato ideal para enseñar una introducción a la IA generativa.