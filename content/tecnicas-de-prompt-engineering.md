# Técnicas de Prompt Engineering

## Justificación en el Temario:

Los grandes modelos de lenguaje son hoy el núcleo de la mayoría de los agentes conversacionales, y su comportamiento depende en gran medida de las instrucciones y del contexto que reciben. Esta asignatura enseña a diseñar, evaluar y proteger esas instrucciones para obtener agentes creíbles cuyo comportamiento sea coherente, controlable y seguro.

## Temario Propuesto:

1. **El modelo visto desde el prompt**
    - Tokens, ventana de contexto y coste
    - Modelos base frente a modelos ajustados por instrucciones; roles de sistema, usuario y asistente
    - Uso práctico de la temperatura y de los demás parámetros de muestreo
2. **Diseño de instrucciones**
    - Claridad y especificidad: contexto, objetivo y criterios de éxito
    - Delimitadores y etiquetas para separar instrucciones y datos
    - Instrucciones en positivo, restricciones y formato de salida; plantillas y variables
3. **Aprendizaje en contexto**
    - Prompting sin ejemplos y con pocos ejemplos (zero-shot y few-shot)
    - Selección, orden y formato de los ejemplos; sensibilidad del modelo a la formulación
4. **Razonamiento**
    - Cadena de pensamiento (Wei et al., 2022) y su versión sin ejemplos (Kojima et al., 2022)
    - Autoconsistencia (Wang et al., 2023), descomposición de menor a mayor y árbol de pensamientos (Yao et al., 2023)
    - Modelos de razonamiento: cuándo sobran las técnicas anteriores
    - Encadenamiento de prompts
5. **Salidas estructuradas**
    - Modo JSON y salidas estructuradas con JSON Schema
    - Validación con Pydantic, reintentos y reparación de salidas
    - Decodificación restringida
6. **Ingeniería de contexto**
    - Selección y orden de la información; el problema de la información «perdida en el medio» (Liu et al., 2024)
    - Resumen y compresión del historial de conversación
    - Contexto recuperado de documentos y caché de prompts
7. **Prompts de personaje**
    - Especificación de personalidad, trasfondo, registro y límites de conocimiento
    - Coherencia del personaje en conversaciones largas y deriva del personaje
    - Juego de rol y varios personajes en una misma conversación
8. **Iteración y pruebas de prompts**
    - Conjuntos de casos de prueba y comparación entre versiones
    - Evaluadores automáticos y uso básico de un LLM como evaluador
    - Optimización automática de prompts con DSPy (Khattab et al.)
9. **Prompts adversarios**
    - Inyección de prompts directa e indirecta (Greshake et al., 2023), jailbreaks y filtración del prompt de sistema
    - Defensas desde el diseño: separación de datos no confiables, jerarquía de instrucciones y spotlighting
    - Ejercicios de red teaming

*Las estrategias de decodificación se tratan en [Introducción a la IA Generativa](introduccion-a-la-ia-generativa.md); la memoria y la recuperación de documentos, en [Agentic AI](agentic-ai.md); el diseño de métricas y evaluaciones, en [Evaluación y Validación de Agentes Creíbles](evaluacion-y-validacion-de-agentes-creibles.md); la creación narrativa de personajes, en [Narrativa, Storytelling y Creación de Personajes en Agentes Inteligentes](narrativa-storytelling-y-creacion-de-personajes.md).*

## Proyecto Final:

Diseño, evaluación y endurecimiento del prompt de sistema de un agente conversacional creíble.

Escribir el prompt de sistema de un personaje para un juego narrativo o para un asistente de atención al cliente y construir con promptfoo (u otra herramienta de evaluación equivalente) un conjunto de al menos 50 casos de prueba que midan la coherencia del personaje, el cumplimiento del formato y la resistencia a la inyección de prompts. Comparar al menos tres versiones del prompt en dos modelos distintos.

## Criterios de Evaluación:

1. Coherencia y calidad del comportamiento obtenido (30%)
2. Rigor del conjunto de pruebas y de la evaluación (25%)
3. Robustez frente a ataques (20%)
4. Documentación de versiones y decisiones de diseño (15%)
5. Presentación y defensa (10%)

## Conceptos Clave:

Prompt, prompt de sistema, ventana de contexto, few-shot, cadena de pensamiento, salidas estructuradas, ingeniería de contexto, prompt de personaje, evaluación de prompts, inyección de prompts.

## Bibliografía Obligatoria:

- "Prompt Engineering for LLMs: The Art and Science of Building Large Language Model-Based Applications" por John Berryman y Albert Ziegler.

## Bibliografía Recomendada:

- "Prompt Engineering for Generative AI" por James Phoenix y Mike Taylor.
- Schulhoff et al., 2024: "The Prompt Report: A Systematic Survey of Prompting Techniques."

## Mejor Curso Online:

- "Prompt Engineering Specialization" ofrecido por Coursera (Vanderbilt University).

## Docente Español Propuesto:

- **Profesor: Dr. José Hernández-Orallo**
- **Breve Biografía:** El Dr. José Hernández-Orallo es catedrático de Lenguajes y Sistemas Informáticos en la Universitat Politècnica de València, investigador del instituto VRAIN, director del programa de evaluación de IA de la Fundación ValgrAI y director de investigación en el Leverhulme Centre for the Future of Intelligence de la Universidad de Cambridge. Su trabajo se centra en la evaluación de sistemas de IA; es coautor del estudio publicado en Nature en 2024 que mostró que los modelos de lenguaje más grandes y más instruibles se vuelven menos fiables y que la formulación del prompt sigue influyendo en sus respuestas. En 2026 recibió el Premio Nacional de Informática Aritmel.
