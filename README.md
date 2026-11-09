# Prompts RAG · IA para Alta Dirección

Herramienta de apoyo para la sesión 2 («Retrieval-Augmented Generation») del programa «IA para Alta Dirección y Productividad Ejecutiva» de Next Leap. Enseña a dirigir un proyecto de RAG con prompts Rol · Contexto · Instrucción, sin ser ingeniero.

**Publicado en:** https://next-leap-s-a-s.github.io/prompts-rag-direccion/ 

## Qué contiene

- **Landing (`index.html`).** La clase como página: qué es RAG, preparación, decisiones, riesgos y piloto. Enlaza a `biblioteca.html`.
- **Biblioteca (`biblioteca.html`).** 30 prompts, 5 por área: entender y explicar RAG, elegir el corpus, preparar los datos, arquitectura y proveedores, casos de uso y retorno, riesgos y gobernanza.
- **Laboratorio.** Constructor con medidor de calidad en vivo y detector de datos personales.
- **Ejercicio.** Clasificación de fragmentos en Rol, Contexto o Instrucción, 5 rondas.

## Cómo está construido

Dos archivos autocontenidos (`index.html` y `biblioteca.html`), generado con `python3 src/build.py` desde `src/template.html`, `src/prompts-*.js` y `src/rondas.js`.

## Manejo de información

Los prompts trabajan con información anonimizada.

Next Leap S.A.S.
