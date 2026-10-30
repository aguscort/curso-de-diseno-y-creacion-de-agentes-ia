# Fundamentos de LLMOps

## Justificación en el Temario:

Llevar un agente basado en modelos de lenguaje del prototipo a producción exige prácticas propias: los modelos no son deterministas, son caros de ejecutar y difíciles de evaluar, y su comportamiento puede degradarse sin que nada falle de forma visible. Esta asignatura adapta las prácticas de MLOps al ciclo de vida de las aplicaciones con LLM para que los agentes creíbles diseñados en el resto del plan funcionen de manera fiable, segura y sostenible.

## Temario Propuesto:

1. **Ciclo de vida de una aplicación con LLM**
    - De MLOps a LLMOps: qué cambia con los modelos fundacionales
    - Arquitectura de referencia: pasarela, capa de prompts, recuperación, modelo y posprocesado
    - Entornos de desarrollo, preproducción y producción; mantenimiento y actualización de agentes
2. **Selección y enrutamiento de modelos**
    - API comerciales frente a modelos de pesos abiertos; licencias
    - Compromisos entre coste, latencia y calidad de respuesta; enrutamiento por complejidad y modelos de respaldo
    - Pasarelas de modelos y límites de uso
3. **Servicio e inferencia**
    - Servidores de inferencia: vLLM y PagedAttention (Kwon et al., 2023); ejecución local con llama.cpp
    - Cuantización (GPTQ, AWQ, GGUF), caché KV, batching continuo y decodificación especulativa
    - Caché de prompts, dimensionamiento de GPU y medición del consumo energético
4. **Versiones y reproducibilidad**
    - Prompts como código y registros de prompts
    - Versionado de modelos, datos y configuraciones; seguimiento de experimentos con MLflow
    - Fuentes de no determinismo
5. **RAG en producción**
    - Ingesta y troceado de documentos; modelos de embeddings
    - Bases de datos vectoriales (pgvector, Qdrant, Milvus) y búsqueda híbrida con BM25
    - Reordenación con codificadores cruzados y actualización incremental del índice
    - Métricas de recuperación: recall@k y MRR
6. **Adaptación de modelos**
    - Cuándo ajustar el modelo, cuándo usar RAG y cuándo basta el prompt
    - Ajuste fino eficiente: LoRA (Hu et al., 2021) y QLoRA (Dettmers et al., 2023)
    - Preparación de datos para el ajuste supervisado; destilación en modelos pequeños
7. **Integración y despliegue continuos**
    - Conjuntos de evaluación como pruebas automáticas y umbrales de regresión
    - Despliegues canario y en sombra; banderas de funcionalidad
    - Gestión de incidentes y reversión
8. **Observabilidad y monitorización**
    - Trazas de llamadas y de agentes con OpenTelemetry y MLflow Tracing
    - Métricas: tiempo hasta el primer token, tokens por segundo y coste por conversación
    - Detección de deriva y de alucinaciones; retroalimentación de los usuarios; alertas
9. **Seguridad en producción**
    - OWASP Top 10 para aplicaciones LLM (2025)
    - Filtros de entrada y salida; detección y enmascarado de datos personales
    - Gestión de secretos y permisos de las herramientas; cadena de suministro de modelos (safetensors y procedencia)

*El diseño de prompts se trata en [Técnicas de Prompt Engineering](tecnicas-de-prompt-engineering.md); la memoria y la arquitectura de los agentes, en [Agentic AI](agentic-ai.md); el diseño de métricas y de evaluaciones, en [Evaluación y Validación de Agentes Creíbles](evaluacion-y-validacion-de-agentes-creibles.md); las obligaciones legales y la gobernanza, en [Ética y Legislación en Inteligencia Artificial y Agentes Virtuales](etica-y-legislacion-en-inteligencia-artificial-y.md).*

## Proyecto Final:

Puesta en producción de un agente basado en LLM con evaluación continua y observabilidad.

Servir con vLLM un modelo de pesos abiertos para un agente conversacional, registrar con MLflow las trazas, el coste y la latencia de cada interacción, y montar un flujo de integración continua que bloquee cualquier cambio de prompt o de modelo que empeore los resultados de un conjunto de evaluación automática.

## Criterios de Evaluación:

1. Fiabilidad y reproducibilidad del despliegue (30%)
2. Calidad del sistema de evaluación continua (25%)
3. Observabilidad y control de costes (20%)
4. Documentación y operación (15%)
5. Presentación y defensa (10%)

## Conceptos Clave:

LLMOps, ciclo de vida, versionado de prompts, inferencia, cuantización, RAG, ajuste fino eficiente, evaluación continua, observabilidad, guardarraíles.

## Bibliografía Obligatoria:

- "AI Engineering: Building Applications with Foundation Models" por Chip Huyen.

## Bibliografía Recomendada:

- "LLM Engineer's Handbook" por Paul Iusztin y Maxime Labonne.
- "Designing Machine Learning Systems" por Chip Huyen.

## Mejor Curso Online:

- "Large Language Model Operations (LLMOps) Specialization" ofrecido por Coursera (Duke University).

## Docente Español Propuesto:

- **Profesor: Dr. Silverio Martínez-Fernández**
- **Breve Biografía:** El Dr. Silverio Martínez-Fernández es profesor agregado del Departamento de Ingeniería de Servicios y Sistemas de Información (ESSI) de la Universitat Politècnica de Catalunya y, desde enero de 2026, dirige el grupo de investigación GESSI, dedicado a la ingeniería del software y los sistemas basados en IA. Investiga en ingeniería del software para sistemas de aprendizaje automático, MLOps e IA sostenible, y es responsable de la asignatura Machine Learning Systems in Production en los grados de Ciencia de Datos e Informática de la UPC.
