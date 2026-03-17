# 🎓 AI Live Class: Tutor Extraescolar Inmersivo

![Status](https://img.shields.io/badge/Status-En%20Desarrollo-green)
![Tech](https://img.shields.io/badge/IA-Gemini%20%7C%20GPT--4-blue)
![Focus](https://img.shields.io/badge/Enfoque-Video%20en%20Vivo%20y%20Pizarra-orange)

## 📺 Visión del Proyecto
Este proyecto redefine el apoyo escolar mediante la creación de un **Tutor Virtual en Vivo**. No es un simple chat de texto; es una experiencia de aula completa donde un avatar de IA interactúa por video, habla con el alumno y utiliza una **pizarra digital** para explicar conceptos, resolver ecuaciones y dibujar esquemas en tiempo real.

El sistema está diseñado para ser un mentor extraescolar disponible 24/7, capaz de "enseñar a pensar" en lugar de solo dar respuestas.

---

## 🧠 Arquitectura de Inteligencia y Flujo de Datos
Para maximizar la eficiencia y el aprendizaje del sistema, el backend opera bajo la siguiente lógica (basada en búsqueda semántica):

1.  **Entrada del Alumno:** Pregunta por voz o texto.
2.  **Consulta en Base de Datos de Conocimiento:** * El sistema utiliza **Embeddings** para buscar si una duda similar ya ha sido resuelta.
    * **SI existe:** Devuelve la respuesta optimizada (Ahorro de costes y latencia).
    * **NO existe:** Llama a la API de IA (Gemini/GPT-4).
3.  **Selección Inteligente de Modelo:** * **Preguntas Simples:** Procesadas por modelos ligeros (eficiencia).
    * **Preguntas Complejas:** Escaladas a modelos grandes para razonamiento profundo.
4.  **Aprendizaje Continuo:** Cada nueva interacción se guarda para enriquecer la base de datos futura.

---

## ✨ Características Principales
* **🎥 Avatar Humanoide en Vivo:** Interacción visual mediante video generado en tiempo real.
* **🖍️ Pizarra Dinámica:** El tutor escribe y pone ejemplos visuales en una pizarra mientras explica.
* **🛡️ Privacidad desde el Diseño (RGPD):** Solo se almacenan datos académicos (pregunta, respuesta, tema, nivel). **Cero datos personales** identificables.
* **📈 Memoria Adaptativa:** El tutor recuerda el nivel educativo del alumno para ajustar la complejidad de sus explicaciones.

---

## 🛠️ Stack Tecnológico Planteado
* **IA Cognitiva:** Google Gemini API (Modelos Flash y Pro).
* **Motor de Video:** Integración con SDK de Avatares Interactivos (HeyGen / Vapi).
* **Base de Datos:** Vector Database para búsqueda semántica y caché de respuestas.
* **Interfaz:** React + Canvas API para la pizarra interactiva.

---

## 📂 Estructura del Repositorio
* `/brain`: Lógica de decisión, prompts socráticos y gestión de modelos de IA.
* `/database`: Configuración de embeddings y almacenamiento de conocimiento anonimizado.
* `/classroom`: Interfaz de usuario, streaming de video y control de la pizarra.
* `/legal`: Documentación sobre el cumplimiento de RGPD y ética educativa.

---

## 🚀 Cómo empezar (Planteamiento)
1.  Configura tus claves de API en el archivo `.env`.
2.  Inicializa la base de datos de conocimiento con los materiales curriculares.
3.  Lanza el entorno del aula virtual para comenzar la tutoría en vivo.

---

**Transformando las clases particulares en una experiencia tecnológica sin precedentes.** 🚀
