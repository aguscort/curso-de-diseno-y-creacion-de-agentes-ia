# Comunicación Natural, Tecnologías de Voz y Procesamiento del Lenguaje en Agentes

## Justificación en el Temario:

Esta asignatura aborda la tecnología esencial detrás de la comunicación verbal y escrita de los agentes, una clave en la creación de agentes creíbles que puedan interactuar de manera natural y convincente con los humanos.

## Temario Propuesto:

1. **Lingüística computacional y procesamiento del texto**
    - Niveles de análisis: morfología, sintaxis, semántica y pragmática
    - Particularidades del español: morfología flexiva, clíticos y variación dialectal
    - Normalización y tokenización (BPE, WordPiece, SentencePiece); lematización y etiquetado morfosintáctico con spaCy y Stanza
2. **Análisis sintáctico y semántico**
    - Análisis de constituyentes y de dependencias (Universal Dependencies)
    - Reconocimiento de entidades, etiquetado de roles semánticos y correferencia
    - Semántica léxica y desambiguación del sentido de las palabras (WordNet)
3. **Representaciones del significado**
    - Semántica distribucional: word2vec (Mikolov et al., 2013), GloVe y fastText
    - Representaciones contextuales: BERT (Devlin et al., 2019); modelos para el español: BETO, MarIA y la familia ALIA
    - Embeddings de oraciones (Sentence-BERT)
4. **Tareas de PLN con transformers**
    - Clasificación de textos y análisis de sentimientos, de polaridad y basado en aspectos, con aprendizaje automático y profundo
    - Extracción de información, resumen automático y respuesta a preguntas
    - Ajuste fino frente a uso de LLM mediante prompts
5. **Sistemas de diálogo**
    - Arquitectura orientada a tareas: comprensión (intenciones y entidades), seguimiento del estado, política y generación
    - Plataformas: Rasa y Dialogflow CX
    - Chatbots de dominio abierto y arquitecturas híbridas con LLM
    - Derivación de la conversación a un operador humano
6. **Reconocimiento automático del habla**
    - Señal de voz, espectrogramas y MFCC
    - Del modelo acústico clásico (HMM-GMM) al reconocimiento de extremo a extremo (CTC, atención, RNN-T)
    - Whisper (Radford et al., 2022); tasa de error de palabras; diarización con pyannote
    - Robustez ante acentos y ruido; reconocimiento del español
7. **Síntesis de voz**
    - De la síntesis concatenativa a la neuronal: Tacotron 2, FastSpeech 2 y VITS
    - Vocoders neuronales: WaveNet y HiFi-GAN
    - Clonación de voz con pocas muestras; control de la prosodia con SSML
    - Adaptación y personalización de la voz; voz expresiva
8. **Agentes de voz**
    - Arquitectura en cascada (reconocimiento, LLM y síntesis) frente a modelos de voz a voz
    - Presupuesto de latencia, detección de actividad vocal y detección del fin de turno
    - Toma de turnos, interrupciones (barge-in) y modelos dúplex completos (Moshi)
    - Integración telefónica (SIP) y web (WebRTC)

*La emoción en la voz se trata en [Computación Afectiva: Análisis y Modelado de Emociones](computacion-afectiva.md); la generación de respuestas empáticas, en [Inteligencia Artificial Empática](inteligencia-artificial-empatica.md); los grandes modelos de lenguaje, en [Introducción a la IA Generativa](introduccion-a-la-ia-generativa.md).*

## Conceptos Clave:

Procesamiento del Lenguaje Natural, reconocimiento de voz, síntesis de voz, lingüística computacional, sistemas de diálogo, agentes de voz.

## Proyecto Final: 

Desarrollo de un agente creíble que pueda interactuar usando voz y texto de forma natural.

Usar Dialogflow y Google Text-to-Speech para crear un agente virtual que pueda responder a preguntas frecuentes y transferir la conversación a un operador humano mediante una señal de alerta.

## Criterios de Evaluación:

1. Naturalidad y fluidez en la comunicación (30%)
2. Implementación técnica (25%)
3. Innovación en el enfoque (20%)
4. Documentación y análisis (15%)
5. Presentación y defensa (10%)

## Bibliografía Obligatoria:

- "Speech and Language Processing" por Dan Jurafsky y James H. Martin.

## Bibliografía Recomendada:

- "Natural Language Processing in Python" por DataCamp.
- "Handbook of Speech Processing" por Jacob Benesty, M. Mohan Sondhi, y Yiteng Huang.

## Mejor Curso Online:

- "Natural Language Processing Specialization" ofrecido por Coursera.

## Docente Español Propuesto:

- **Profesor: Dra. Lucía Méndez**
- **Breve Biografía:** La Dra. Lucía Méndez es una destacada experta en procesamiento del lenguaje natural y tecnologías de voz. Es profesora en la Universidad de Granada y ha trabajado en proyectos innovadores en el campo de la lingüística computacional y la comunicación humano-máquina. Su enfoque interdisciplinario y su compromiso con la ética en la tecnología la convierten en una figura prominente en su campo.