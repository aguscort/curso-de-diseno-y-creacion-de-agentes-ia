# Modelado y Simulación de Agentes

## Justificación en el Temario:

Esta asignatura proporciona los fundamentos teóricos y prácticos necesarios para modelar y simular agentes. Se centra en las técnicas de representación, razonamiento y simulación que son fundamentales para el diseño de agentes creíbles.

## Temario Propuesto:

1. **Agentes y entornos**
    - Definición de agente, autonomía y racionalidad; descripción de tareas PEAS (prestaciones, entorno, actuadores y sensores)
    - Propiedades del entorno: observable o parcialmente observable, determinista o estocástico, episódico o secuencial, estático o dinámico, discreto o continuo
    - Tipos de agente: reactivo simple, basado en modelos, basado en objetivos, basado en utilidad y que aprende (Russell y Norvig)
2. **Arquitecturas de agente**
    - Arquitecturas reactivas: la arquitectura de subsunción (Brooks, 1986)
    - Arquitecturas deliberativas y modelo BDI de creencias, deseos e intenciones (Rao y Georgeff, 1995); programación en AgentSpeak con Jason
    - Arquitecturas híbridas por capas: TouringMachines e InteRRaP
3. **Toma de decisiones**
    - Teoría de la utilidad y decisión con incertidumbre; árboles de decisión
    - Máquinas de estados finitos y árboles de comportamiento (behavior trees)
    - IA basada en utilidad (utility AI) para personajes de videojuego
4. **Planificación y movimiento**
    - Planificación clásica: STRIPS, PDDL y búsqueda en el espacio de estados
    - Planificación jerárquica de tareas (HTN)
    - Planificación orientada a objetivos en videojuegos: GOAP (Orkin, 2006)
    - Búsqueda de caminos: A* y mallas de navegación
5. **Modelado basado en agentes**
    - Enfoque ascendente, emergencia y relación entre los niveles micro y macro
    - Modelos clásicos: segregación de Schelling, Sugarscape (Epstein y Axtell, 1996), boids (Reynolds, 1987) y epidemias SIR basadas en agentes
    - Representación del entorno (rejillas, redes, espacio continuo y SIG) y planificación temporal síncrona y asíncrona
    - Descripción de modelos con el protocolo ODD (Grimm et al.)
6. **Herramientas de simulación**
    - NetLogo
    - Mesa (Python): agentes, modelos, activación, recogida de datos y visualización
    - Repast, MASON, GAMA y AnyLogic: comparación y criterios de elección
7. **Experimentación, calibración y validación**
    - Estocasticidad, semillas aleatorias y número de réplicas
    - Barridos de parámetros y análisis de sensibilidad local y global (índices de Sobol)
    - Verificación del código y comparación entre implementaciones (docking)
    - Calibración con datos y validación empírica; modelado orientado a patrones (Grimm et al., 2005)
8. **Casos de estudio**
    - Epidemias y estrategias de mitigación
    - Tráfico y movilidad
    - Mercados y sistemas socioecológicos

*La comunicación, la coordinación y la negociación entre agentes se tratan en [Inteligencia Artificial Distribuida y Sistemas Multiagente](inteligencia-artificial-distribuida-y-sistemas-multiagente.md); los agentes basados en modelos de lenguaje, en [Agentic AI](agentic-ai.md); las arquitecturas cognitivas y los modelos de multitudes, en [Análisis y Modelado de Comportamiento Humano](analisis-y-modelado-de-comportamiento-humano.md).*

*Desarrollo en prosa de la versión anterior del temario, que todavía no sigue esta estructura: [temario-propuesto.md](modelado-y-simulacion-de-agentes/temario-propuesto.md).*

## Conceptos Clave:

Modelado de agentes, simulación, arquitecturas de agentes, planificación, sistemas multiagente.

## Proyecto Final: 

Diseño y simulación de un agente creíble en un contexto específico (por ejemplo, asistente virtual de atención médica).

Desarrollar un modelo de agentes que simule la propagación de una enfermedad en una población, usando Python y la librería Mesa. Evaluar diferentes estrategias de mitigación.

## Criterios de Evaluación:

1. Completitud del modelo (30%)
2. Realismo en la simulación (25%)
3. Documentación y análisis (20%)
4. Presentación y defensa del proyecto (15%)
5. Innovación y creatividad (10%)

## Bibliografía Obligatoria:

- "Multiagent Systems: Algorithmic, Game-Theoretic, and Logical Foundations" por Yoav Shoham y Kevin Leyton-Brown.

## Bibliografía Recomendada:

- "Artificial Intelligence: A Modern Approach" por Stuart Russell y Peter Norvig.
- "Agent-Based and Individual-Based Modeling: A Practical Introduction" por Steven F. Railsback y Volker Grimm.

## Mejor Curso Online:

- "Multi-Agent Systems" ofrecido por edX.

## Docente Español Propuesto:

- **Profesor: Dra. Carmen Vidal**
- **Breve Biografía:** La Dra. Carmen Vidal es una destacada investigadora en el Instituto de Robótica e Informática Industrial de Barcelona. Su trabajo en el modelado y simulación de agentes ha llevado a innovaciones en áreas como la inteligencia artificial distribuida y los sistemas multiagente. Ha colaborado en proyectos internacionales y es autora de varios libros y artículos en su campo.