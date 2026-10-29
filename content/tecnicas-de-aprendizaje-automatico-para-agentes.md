# Técnicas de Aprendizaje Automático para Agentes

## Justificación en el Temario:

El aprendizaje automático es esencial en el diseño de agentes creíbles, ya que permite que los agentes aprendan y se adapten a partir de los datos y la experiencia. Esta asignatura proporcionará a los estudiantes una comprensión sólida de las técnicas de aprendizaje automático aplicadas a agentes inteligentes.

## Temario Propuesto:

1. **El flujo de trabajo del aprendizaje automático**
    - Formulación del problema; datos de interacción de agentes y usuarios
    - Limpieza, preparación y selección de características; clases desequilibradas
    - Partición de datos, validación cruzada y métricas (exactitud, F1, AUC ROC, error cuadrático medio)
    - Sobreajuste, regularización L1 y L2, y ajuste de hiperparámetros (rejilla, aleatorio y bayesiano)
2. **Aprendizaje supervisado**
    - Regresión lineal y logística
    - Árboles de decisión y métodos de conjunto: bosques aleatorios y gradient boosting
    - Máquinas de vectores de soporte y vecinos más cercanos
    - Interpretación de modelos con SHAP y LIME
3. **Redes neuronales profundas**
    - Perceptrón multicapa, retropropagación y optimizadores (SGD, Adam)
    - Regularización: dropout y normalización por lotes
    - Redes convolucionales para la percepción y redes recurrentes (LSTM) para secuencias
    - Aprendizaje por transferencia y ajuste fino de modelos preentrenados con PyTorch
4. **Aprendizaje no supervisado y modelado de usuarios**
    - Agrupamiento (k-medias, DBSCAN) y reducción de dimensionalidad (PCA, UMAP)
    - Detección de anomalías
    - Modelado de jugadores y usuarios (Yannakakis y Togelius, *Artificial Intelligence and Games*)
5. **Fundamentos del aprendizaje por refuerzo**
    - Procesos de decisión de Markov y ecuaciones de Bellman
    - Programación dinámica, métodos de Monte Carlo y diferencias temporales
    - Q-learning y SARSA; exploración frente a explotación (ε-voraz, UCB)
6. **Aprendizaje por refuerzo profundo**
    - DQN (Mnih et al., 2015)
    - Gradiente de política (REINFORCE), actor-crítico, PPO (Schulman et al., 2017) y SAC
    - Diseño de recompensas y aprendizaje por currículo
    - Entornos y bibliotecas: Gymnasium, Stable-Baselines3 y CleanRL
7. **Búsqueda y juego**
    - Búsqueda en árbol de Monte Carlo (MCTS)
    - AlphaZero: autojuego con redes de política y de valor (Silver et al., 2018)
8. **Aprender de demostraciones y de preferencias humanas**
    - Clonación de comportamiento y DAgger; aprendizaje por refuerzo inverso y GAIL
    - Modelos de recompensa y RLHF (Ouyang et al., 2022); optimización directa de preferencias, DPO (Rafailov et al., 2023)
9. **Métodos evolutivos**
    - Algoritmos genéticos
    - Neuroevolución (NEAT) y algoritmos de calidad-diversidad (MAP-Elites) para obtener comportamientos variados
10. **Aprendizaje para agentes creíbles**
    - Adaptación en tiempo real y ajuste dinámico de la dificultad
    - Comportamiento humano frente a comportamiento óptimo: imitación al servicio de la credibilidad

*El aprendizaje con varios agentes se trata en [Inteligencia Artificial Distribuida y Sistemas Multiagente](inteligencia-artificial-distribuida-y-sistemas-multiagente.md); los modelos generativos, en [Introducción a la IA Generativa](introduccion-a-la-ia-generativa.md).*

*Desarrollo en prosa de la versión anterior del temario, que todavía no sigue esta estructura: [temario-propuesto.md](tecnicas-de-aprendizaje-automatico-para-agentes/temario-propuesto.md).*

## Proyecto Final:

Implementación de algoritmos de aprendizaje automático para mejorar el rendimiento de un agente creíble.

Implementar y entrenar un agente de aprendizaje por refuerzo para jugar un juego de mesa como el ajedrez. Evaluar su rendimiento contra jugadores humanos y otros agentes.

## Criterios de Evaluación:

1. Aplicación efectiva de algoritmos de ML (30%)
2. Mejoras en el rendimiento del agente (25%)
3. Documentación del proceso de aprendizaje (20%)
4. Código y reproducibilidad (15%)
5. Presentación y defensa (10%)

## Conceptos Clave:

Aprendizaje automático, aprendizaje por refuerzo, redes neuronales, algoritmos genéticos, aprendizaje por imitación, RLHF.

## Bibliografía Obligatoria:

- "Pattern Recognition and Machine Learning" por Christopher M. Bishop.

## Bibliografía Recomendada:

- "Deep Learning" por Ian Goodfellow, Yoshua Bengio, y Aaron Courville.
- "Reinforcement Learning: An Introduction" por Richard S. Sutton y Andrew G. Barto.

## Mejor Curso Online:

- "Deep Learning Specialization" ofrecido por Coursera.

## Docente Español Propuesto:

- **Profesor: Dr. Marta González**
- **Breve Biografía:** La Dra. Marta González es profesora en la Universidad Carlos III de Madrid. Es una experta en aprendizaje automático y sus aplicaciones en agentes inteligentes. Su investigación se centra en técnicas avanzadas como el aprendizaje por refuerzo y el aprendizaje multiagente.