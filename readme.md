# Sistema de control de vehículos autónomos mediante aprendizaje por refuerzo con garantías de seguridad

Este repositorio contiene el diseño, modelado y validación de un sistema de control para vehículos autónomos basado en aprendizaje por refuerzo profundo, evaluado en un entorno de simulación 3D.

El proyecto integra modelado dinámico, percepción por visión por computadora y entrenamiento de agentes inteligentes con restricciones de seguridad.

---

## Descripción general

El trabajo desarrolla un sistema de conducción autónoma capaz de operar en entornos dinámicos mediante aprendizaje por refuerzo profundo.

Se implementa un modelo dinámico vehicular validado en simulación, junto con un sistema de percepción encargado de estimar variables relevantes como desviación lateral, ángulo de conducción y distancia a otros vehículos.

Posteriormente, se entrena un agente que aprende a mantenerse dentro del carril, evitar colisiones y regular la velocidad, incorporando criterios de seguridad durante la toma de decisiones.

---

## Contenido del repositorio

- **/docs/**  
  Informe completo del proyecto de graduación.

---

## Arquitectura del sistema

1. **Modelo dinámico:**  
   Representa el comportamiento del vehículo y traduce acciones en movimiento.

2. **Sistema de percepción:**  
   Estima variables del entorno mediante visión por computadora.

3. **Agente de control:**  
   Algoritmo de aprendizaje por refuerzo (PPO) que decide las acciones.

4. **Entorno de simulación:**  
   Escenario 3D donde se entrena y valida el sistema.

---

## Resultados experimentales

El sistema fue evaluado completamente en simulación, mostrando un desempeño estable en tareas de conducción autónoma.

- Desviación lateral máxima: **0.73 m**  
- Error máximo de ángulo: **0.28 rad**  
- Capacidad de mantener carril y evitar colisiones  

Los resultados evidencian que el agente aprende comportamientos seguros en entornos controlados.

---

## Conclusiones

El uso de aprendizaje por refuerzo permite desarrollar controladores adaptativos para conducción autónoma.

La integración con un sistema de percepción y un modelo dinámico permite validar el comportamiento del sistema en simulación sin recurrir a pruebas físicas.

---

## Recomendaciones para futuros desarrollos

- Transferir el sistema a plataforma física  
- Mejorar robustez ante condiciones reales  
- Incorporar sensores adicionales y fusión sensorial  
- Evaluar en escenarios más complejos  

