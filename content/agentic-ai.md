# Agentic AI

## Justificación en el Temario:

Un agente basado en un modelo de lenguaje no se limita a responder: planifica, usa herramientas, recuerda y actúa sobre su entorno con cierto grado de autonomía. Esta asignatura enseña a diseñar estos sistemas y a dotarlos de la memoria, la planificación y el control necesarios para que se comporten como agentes creíbles, partiendo de los fundamentos clásicos vistos en Modelado y Simulación de Agentes.

## Temario Propuesto:

1. **Del modelo de lenguaje al agente**
    - Agencia y grados de autonomía; flujos de trabajo frente a agentes (Anthropic, 2024)
    - El bucle percibir-razonar-actuar y su relación con las arquitecturas clásicas de agente
    - Cuándo no conviene un agente: coste, latencia y fiabilidad
2. **Razonar y actuar**
    - ReAct (Yao et al., 2023)
    - Planificación: planificar y ejecutar, descomposición de tareas y replanificación
    - Reflexión y autocrítica: Reflexion (Shinn et al., 2023) y Self-Refine (Madaan et al., 2023)
3. **Herramientas**
    - Llamadas a funciones: esquemas, elección de herramienta y gestión de errores
    - Diseño de herramientas para agentes: nombres, descripciones y mensajes de error (interfaz agente-ordenador; Yang et al., 2024)
    - Agentes que escriben y ejecutan código (CodeAct) y agentes que manejan el navegador o el escritorio
4. **Model Context Protocol (MCP)**
    - Arquitectura: anfitriones, clientes y servidores
    - Primitivas (herramientas, recursos y prompts) y transportes (stdio y HTTP)
    - Construcción de un servidor MCP; riesgos de las herramientas maliciosas o envenenadas
5. **Memoria**
    - Memoria de trabajo y memoria a largo plazo episódica, semántica y procedimental (marco CoALA; Sumers et al., 2024)
    - Embeddings y almacenes vectoriales para recuperar recuerdos; RAG como memoria de conocimiento
    - Consolidación, resumen y gestión virtual del contexto (MemGPT; Packer et al., 2023)
6. **Agentes generativos y comportamiento creíble**
    - Flujo de memoria y puntuación por recencia, importancia y relevancia (Park et al., 2023)
    - Reflexión y planificación del día; comportamiento social emergente
    - Coherencia del personaje a lo largo del tiempo
7. **Patrones de diseño agéntico**
    - Encadenamiento, enrutamiento, paralelización, orquestador-trabajadores y evaluador-optimizador
    - Intervención humana: puntos de aprobación antes de acciones irreversibles e interrupciones
    - Gestión del estado, persistencia y agentes de larga duración
8. **Marcos de desarrollo**
    - El bucle del agente en Python sin marco
    - LangGraph: grafos de estado, puntos de control e intervención humana
    - Kits de desarrollo de agentes de los proveedores de modelos y criterios de elección
9. **Robustez de los agentes**
    - Fallos típicos: bucles, uso indebido de herramientas, llamadas alucinadas y deriva del objetivo
    - Permisos mínimos, entornos aislados (sandbox) y límites de pasos y de coste
    - Inyección indirecta a través de herramientas y documentos
    - Trazas y depuración de trayectorias

*Las arquitecturas clásicas de agente se tratan en [Modelado y Simulación de Agentes](modelado-y-simulacion-de-agentes.md); los sistemas de varios agentes basados en LLM y el protocolo A2A, en [Inteligencia Artificial Distribuida y Sistemas Multiagente](inteligencia-artificial-distribuida-y-sistemas-multiagente.md); la operación de RAG en producción, en [Fundamentos de LLMOps](fundamentos-de-llmops.md); los bancos de pruebas de agentes, en [Evaluación y Validación de Agentes Creíbles](evaluacion-y-validacion-de-agentes-creibles.md).*

## Proyecto Final:

Diseño e implementación de un agente creíble con memoria, planificación y uso de herramientas.

Usar un marco de agentes como LangGraph y servidores MCP para crear un personaje no jugador de un mundo simulado que recuerde sus interacciones, reflexione sobre ellas y planifique su día, siguiendo la arquitectura de los agentes generativos de Park et al. Evaluar mediante entrevistas al agente, como en el estudio original, cómo afectan la memoria y la reflexión a la credibilidad de su comportamiento.

## Criterios de Evaluación:

1. Credibilidad y coherencia del comportamiento del agente (30%)
2. Arquitectura del agente: memoria, planificación y herramientas (25%)
3. Rigor de la evaluación (20%)
4. Documentación, seguridad y control (15%)
5. Presentación y defensa (10%)

## Conceptos Clave:

Agente basado en LLM, autonomía, ReAct, uso de herramientas, MCP, memoria, RAG, agentes generativos, patrones agénticos, supervisión humana, robustez de los agentes.

## Bibliografía Obligatoria:

- "Building Applications with AI Agents: Designing and Implementing Multiagent Systems" por Michael Albada.

## Bibliografía Recomendada:

- Park et al., 2023: "Generative Agents: Interactive Simulacra of Human Behavior."
- Yao et al., 2023: "ReAct: Synergizing Reasoning and Acting in Language Models."

## Mejor Curso Online:

- "Agentic AI" ofrecido por DeepLearning.AI.

## Docente Español Propuesto:

- **Profesor: Dr. Javier Palanca Cámara**
- **Breve Biografía:** El Dr. Javier Palanca Cámara es profesor titular del Departamento de Sistemas Informáticos y Computación de la Universitat Politècnica de València, en la Escuela Politécnica Superior de Gandia, e investigador del instituto VRAIN. Es autor de SPADE, una plataforma de sistemas multiagente en Python basada en mensajería instantánea (XMPP), y de SPADE-LLM, la extensión que integra modelos de lenguaje en sus agentes con uso de herramientas, recuperación aumentada y soporte del protocolo MCP, lo que une los sistemas multiagente clásicos con los agentes basados en LLM.
