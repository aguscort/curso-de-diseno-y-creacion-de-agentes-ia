# Computación Afectiva: Análisis y Modelado de Emociones

*Asignatura resultante de unificar «Análisis de Emociones y Comportamiento Humano» y «Emociones y Comportamiento en Agentes Inteligentes». El modelado del comportamiento humano no afectivo se trata en [Análisis y Modelado de Comportamiento Humano](analisis-y-modelado-de-comportamiento-humano.md).*

## Justificación en el Temario:

Para crear agentes creíbles, es fundamental comprender y analizar las emociones humanas y saber modelarlas y simularlas en los propios agentes. Esta asignatura aborda ambas caras: cómo los agentes pueden reconocer y responder a las emociones humanas, y cómo modelar y simular emociones y comportamientos en agentes inteligentes, para lograr una interacción más empática, humana y realista.

## Temario Propuesto:

1. **Qué es una emoción**
    - Emoción, estado de ánimo, afecto, sentimiento y rasgo; componentes de la emoción según el modelo de procesos componentes (Scherer)
    - Teorías clásicas: James-Lange, Cannon-Bard y Schachter-Singer
    - Emociones básicas (Ekman) y modelos dimensionales: circumplejo de Russell (1980) y modelo PAD (Mehrabian y Russell, 1974)
    - Teorías de la valoración cognitiva (Lazarus, Scherer, modelo OCC) y enfoque constructivista (Barrett)
2. **Expresión de las emociones y comunicación no verbal**
    - Expresión facial y sistema de codificación de unidades de acción FACS (Ekman y Friesen, 1978)
    - Postura, gesto, mirada y prosodia
    - Variación cultural y reglas de expresión; el debate sobre la universalidad (Barrett et al., 2019)
    - Emociones en la interacción humano-máquina
3. **Reconocimiento de emociones en el rostro y el cuerpo**
    - Detección de rostros, puntos faciales y unidades de acción con OpenFace y Py-Feat
    - Modelos profundos de reconocimiento de expresiones faciales y corporales
    - Conjuntos de datos CK+, FER2013 y AffectNet; etiquetas categóricas frente a continuas
    - Condiciones reales: iluminación, oclusión, pose y desequilibrio demográfico de los datos
4. **Emoción en la voz y en las señales fisiológicas**
    - Rasgos acústicos y prosódicos: tono, energía y MFCC; conjunto eGeMAPS con openSMILE
    - Modelos autosupervisados de voz (wav2vec 2.0) para reconocer emociones; corpus IEMOCAP y RAVDESS
    - Señales fisiológicas: actividad electrodérmica, variabilidad de la frecuencia cardiaca, temperatura de la piel y EEG
    - Wearables y detección de estrés y activación; conjuntos WESAD y DEAP
5. **Emoción en el texto**
    - Léxicos afectivos: NRC EmoLex y NRC VAD (Mohammad)
    - Clasificadores clásicos y ajuste fino de transformers; conjunto GoEmotions (Demszky et al., 2020)
    - Ironía, negación y dependencia del contexto
6. **Fusión multimodal, anotación y métricas**
    - Fusión temprana, tardía e híbrida; modelado temporal
    - Anotación y verdad de referencia: autoinforme frente a observador; acuerdo entre anotadores
    - Métricas (exactitud, F1, coeficiente de correlación de concordancia) y generalización entre corpus
7. **Modelos computacionales de emoción para agentes**
    - Modelos basados en la valoración: OCC (Ortony, Clore y Collins, 1988) y EMA (Marsella y Gratch, 2009)
    - Modelos dimensionales de estado de ánimo: ALMA (Gebhard, 2005) y WASABI (Becker-Asano y Wachsmuth)
    - La personalidad como parámetro del agente: el modelo de los Cinco Grandes
    - FAtiMA Toolkit; selección de conducta guiada por la emoción y comportamiento adaptativo
8. **Expresión emocional en agentes virtuales**
    - Agentes conversacionales corporeizados; marco SAIBA y lenguaje BML (Kopp et al., 2006); plataforma Greta (Pelachaud)
    - Correspondencia entre emociones y unidades de acción; mirada, gesto y voz emocional
    - Interacción emocional con el usuario: contagio y resonancia emocional; agentes empáticos y asistentes emocionales
    - Casos: tutores afectivos, salud, videojuegos y atención al cliente

*El análisis de sentimientos se trata en [Comunicación Natural, Tecnologías de Voz y Procesamiento del Lenguaje en Agentes](comunicacion-natural-tecnologias-de-voz-y-procesamiento-del-lenguaje.md); el reconocimiento de emociones a lo largo de una conversación y la generación de respuestas empáticas, en [Inteligencia Artificial Empática](inteligencia-artificial-empatica.md); la animación facial de personajes, en [Narrativa, Storytelling y Creación de Personajes en Agentes Inteligentes](narrativa-storytelling-y-creacion-de-personajes.md).*

*Desarrollo en prosa de la versión anterior del temario, que todavía no sigue esta estructura: [temario-propuesto.md](computacion-afectiva/temario-propuesto.md).*

## Conceptos Clave:

Emociones, análisis de comportamiento humano, reconocimiento de emociones, modelado y simulación de emociones, interacción emocional, agentes empáticos.

## Proyecto Final:

El alumno elige una de estas dos modalidades, que proceden de las dos asignaturas unificadas.

**Modalidad A (análisis):** Implementación de un sistema que pueda analizar y reaccionar a las emociones y comportamientos humanos en tiempo real. Propuesta: utilizar técnicas de procesamiento de señales y aprendizaje automático para analizar datos de un wearable (por ejemplo, un Apple Watch) y predecir estados emocionales.

**Modalidad B (modelado):** Implementación de un agente creíble con emociones y comportamientos adaptativos. Propuesta: utilizar un motor de IA como TensorFlow para entrenar un agente en un videojuego que cambie su comportamiento en función de cinco emociones básicas (alegría, tristeza, ira, miedo, sorpresa).

## Criterios de Evaluación:

Modalidad A:

1. Precisión en la detección de emociones/comportamientos (30%)
2. Utilidad y aplicabilidad del sistema (25%)
3. Robustez y manejo de casos límite (20%)
4. Documentación técnica (15%)
5. Presentación y explicación (10%)

Modalidad B:

1. Autenticidad emocional (30%)
2. Adaptabilidad del agente (25%)
3. Integración con otros sistemas (20%)
4. Documentación y análisis (15%)
5. Presentación y defensa (10%)

## Bibliografía Obligatoria:

- "Affective Computing" por Rosalind W. Picard.
- "Emotion Modeling: Towards Pragmatic Computational Models of Affective Processes" por Sidney D'Mello et al.

## Bibliografía Recomendada:

- "Emotion Recognition: A Pattern Analysis Approach" por Arvind K. Bansal et al.
- "The Emotion Machine: Commonsense Thinking, Artificial Intelligence, and the Future of the Human Mind" por Marvin Minsky.
- "Handbook of Affective Computing" por Rafael Calvo et al.

## Mejor Curso Online:

- "Emotion and Cognition in the Age of AI" ofrecido por edX.
- "Emotional Intelligence at Work" ofrecido por Coursera.

## Docente Español Propuesto:

- **Profesor: Dra. Isabel Martínez**
- **Nota de unificación:** las fichas de las dos asignaturas originales proponían a la misma docente con afiliaciones distintas (Universidad de Málaga y Universidad Complutense de Madrid). Conviene verificarlo.
- **Breve Biografía (ficha de Análisis de Emociones y Comportamiento Humano):** La Dra. Isabel Martínez es profesora en la Universidad de Málaga y una destacada experta en análisis de emociones y comportamiento humano. Su investigación se ha centrado en el reconocimiento de emociones y el diseño de agentes empáticos, contribuyendo significativamente al campo de la informática afectiva.
- **Breve Biografía (ficha de Emociones y Comportamiento en Agentes Inteligentes):** La Dra. Isabel Martínez es profesora en la Universidad Complutense de Madrid y experta en el modelado de emociones y comportamiento en agentes inteligentes. Ha contribuido en áreas como la interacción emocional, la salud mental y la tecnología educativa.
