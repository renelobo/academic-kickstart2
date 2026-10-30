---
title: Konrad Think-Pair-Share
summary: Una plataforma Think-Pair-Share con inteligencia artificial para fomentar el pensamiento creativo y el aprendizaje colaborativo
date: 2025-01-01
tags:
  - Inteligencia artificial
  - Analítica del aprendizaje
  - Aprendizaje colaborativo
---

Konrad Think-Pair-Share es una plataforma de aprendizaje colaborativo que desarrollé en la Fundación Universitaria Konrad Lorenz para estudiar cómo integrar la inteligencia artificial en la metodología Think-Pair-Share (TPS) y cómo la analítica del aprendizaje puede medir su efecto en el pensamiento creativo de los estudiantes.

## La plataforma

Una plataforma web propia con sincronización en tiempo real y analítica del aprendizaje integrada, que sigue las tres fases de TPS:

- **Think – Reflexión (8 min):** cada estudiante reflexiona y escribe de forma individual en un espacio privado.
- **Pair – Parejas (20 min):** parejas anónimas escriben juntas en un editor sincronizado. En la versión con IA, ambos estudiantes pueden consultar a *Lupi*, un chatbot basado en Google Gemini con instrucciones de ayudarles a reflexionar sobre el tema *sin dar respuestas directas*: hace preguntas, sugiere otras perspectivas y da retroalimentación sobre la estructura y la claridad.
- **Share – Compartir (15 min):** las parejas presentan y discuten sus conclusiones con toda la clase.

La plataforma registra cada interacción de escritura, los textos finales y los diálogos completos entre estudiantes y chatbot para su análisis.

<div style="display:grid;grid-template-columns:repeat(auto-fill,minmax(min(600px,100%),1fr));gap:1rem;align-items:start">
  <img src="/en/projects/konrad-think-pair-share/tps-home.jpg" alt="Página de inicio de la plataforma con acceso para estudiantes y profesores y las tres fases de TPS" loading="lazy" style="width:100%;height:auto;border-radius:8px;margin:0">
  <img src="/en/projects/konrad-think-pair-share/tps-think.jpg" alt="Fase de reflexión individual con el tema, preguntas orientadoras y temporizador" loading="lazy" style="width:100%;height:auto;border-radius:8px;margin:0">
  <img src="/en/projects/konrad-think-pair-share/tps-pair.jpg" alt="Fase en parejas: editor compartido y el asistente de IA Lupi" loading="lazy" style="width:100%;height:auto;border-radius:8px;margin:0">
</div>

Los docentes crean y administran las actividades, configuran los parámetros de cada fase y siguen el progreso de sus estudiantes; a cada estudiante se le asigna automáticamente una sala con un compañero.

## El estudio

Un estudio cuasiexperimental con asignación aleatoria por grupos y **140 estudiantes de Ingeniería de Sistemas** de siete cursos (Fundamentos de Programación, Análisis y Diseño de Software, e Ingeniería de Software): 80 estudiantes usaron la plataforma con IA y 60 la misma plataforma sin IA. La creatividad lingüística se analizó en cuatro dimensiones (fluidez, flexibilidad, originalidad y elaboración) mediante diversidad léxica (TTR, MTLD), modelado de tópicos, métricas de productividad y la similitud entre los textos de los estudiantes y las respuestas del chatbot.

<div style="display:grid;grid-template-columns:repeat(auto-fill,minmax(260px,1fr));gap:1rem;align-items:start">
  <img src="/en/projects/konrad-think-pair-share/tps-classroom-1.jpg" alt="Una estudiante en la fase en parejas con el asistente de IA" loading="lazy" style="width:100%;height:auto;border-radius:8px;margin:0">
  <img src="/en/projects/konrad-think-pair-share/tps-classroom-2.jpg" alt="Una estudiante escribiendo en el editor colaborativo" loading="lazy" style="width:100%;height:auto;border-radius:8px;margin:0">
</div>

## Resultados

- Los mejores resultados se obtuvieron con una **integración moderada** de las sugerencias de la IA (similitud de 0,3–0,7 con las respuestas del chatbot), que alcanzó el 70 % de los participantes.
- El grupo con IA mostró **entre 30 % y 37 % más productividad** y un **aumento del 99 % en la diversidad temática**, con efectos moderados de estandarización léxica.
- Para la práctica docente: incluir una fase de reflexión individual antes de la escritura con IA, diseñar un apoyo de IA que promueva la diversidad lingüística sin quitar autonomía creativa a los estudiantes, y no depender de métricas sensibles a la longitud, como el TTR, para evaluar la creatividad.

Lee el artículo completo, publicado en acceso abierto en el *Journal of Learning Analytics*: [AI-Enhanced Think-Pair-Share: A Learning Analytics Approach to Foster Linguistic Creative Thinking and Collaborative Learning](https://doi.org/10.18608/jla.2025.8807).
