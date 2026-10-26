# Laboratorio para instalar tú mismo un agente de programación: instala opencode y conéctalo a un modelo, en un proyecto pequeño con pruebas

[English](README.md) | [Français](README.fr.md) | [Español](README.es.md) | [日本語](README.ja.md) | [Deutsch](README.de.md)

[![check](https://github.com/mitsurutech/lab-ai-agent-install/actions/workflows/check.yml/badge.svg)](https://github.com/mitsurutech/lab-ai-agent-install/actions/workflows/check.yml)

Un laboratorio listo para usar en clase, de la [MitsuruTech Learning Platform](https://mitsurutech.co.uk/learning), donde colegios, institutos, centros de formación y universidades dan a cada estudiante sus propias bases de datos, contenedores y terminal en el navegador. Es un laboratorio en el que no hay nada instalado: instalas opencode, un agente de IA de código abierto, le dices dónde está su modelo y luego lo usas en un proyecto pequeño con pruebas.

## Uso en la plataforma

**Este laboratorio funciona solo en la plataforma.** Su agente accede a un modelo y a un proxy de paquetes que la plataforma proporciona junto a la copia de cada estudiante, así que `compose.yaml` no arranca por sí solo en tu ordenador. Cada estudiante tiene una copia privada sin salida a internet.

**Para probarlo:** abre la [página de contenedores](https://mitsurutech.co.uk/container), busca este laboratorio en **Sample labs** y pulsa Start. Hace falta una cuenta gratuita.

**Para ponerlo como tarea a una clase:**

1. En tu módulo, crea una tarea de tipo **Lab** y elige **In a GitHub repository**.
2. Indica `https://github.com/mitsurutech/lab-ai-agent-install` con la rama `main`. El archivo compose es el predeterminado, `compose.yaml`. Haz antes un fork del repositorio si quieres cambiarlo.
3. Publica. La copia de cada estudiante parte de la versión (commit) que publicaste, así que un cambio posterior aquí no altera un laboratorio ya asignado.

La [página de este laboratorio](https://mitsurutech.co.uk/help/lab-ai-agent-install) del manual de ayuda y su [guía de laboratorios de contenedores](https://mitsurutech.co.uk/help/labs) explican el resto. La lección básica correspondiente es **AI Coding Agent Basics**. ¿Aún no tienes cuenta de centro? [El primer año es gratis](https://mitsurutech.co.uk/pricing) hasta 50 estudiantes, y [registrarse](https://mitsurutech.co.uk/signup) solo pide una dirección de correo.

## Qué conviene saber

El comentario del principio de `compose.yaml` explica cómo arrancar y qué puede hacer el agente. El agente pregunta antes de cambiar un archivo o ejecutar un comando: lee lo que quiere hacer y di que sí solo cuando lo entiendas. **Nada se guarda**: al detener el laboratorio se olvidan todos los archivos, de modo que el estudiante descarga su trabajo antes de pararlo. Lo que responde un asistente cambia de una ejecución a otra, así que no se promete ningún resultado.

## Licencia

Esta obra está bajo la licencia [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Puedes compartirla y adaptarla para aprender y enseñar, si reconoces la autoría de Mitsuru Technologies Ltd, no la usas con fines comerciales y compartes lo que crees a partir de ella bajo la misma licencia. El texto completo está en el archivo `LICENSE`.

## Acerca de

Creado por [Mitsuru Technologies](https://mitsurutech.co.uk) para la [MitsuruTech Learning Platform](https://mitsurutech.co.uk/learning): Python, Java, Go, Node, SQL y Linux en el navegador para colegios, institutos y centros de formación, con laboratorios de contenedores, aplicaciones web desplegadas desde GitHub y cuestionarios que se corrigen solos. Prueba código sin cuenta en el [playground](https://mitsurutech.co.uk/playground).

Más laboratorios del mismo sitio: [lab-ai-agent](https://github.com/mitsurutech/lab-ai-agent), [lab-quantum-sim](https://github.com/mitsurutech/lab-quantum-sim), [lab-jupyter-data](https://github.com/mitsurutech/lab-jupyter-data) y [lab-git-gitea](https://github.com/mitsurutech/lab-git-gitea).
