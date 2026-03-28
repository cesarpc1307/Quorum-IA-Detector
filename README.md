# ⚖️ Quórum-IA: Auditor de Integridad Académica

Este proyecto implementa un sistema de **auditoría forense digital** diseñado para validar la autoría humana en textos científicos. Desarrollado en el marco de la investigación "Hacia una Gestión de Proximidad" de la **UNAH**, esta herramienta utiliza un quórum de redes neuronales profundas para garantizar la transparencia académica.

## 🤖 El Escuadrón de Jueces
Para minimizar los falsos positivos, el sistema utiliza un consenso de tres modelos independientes:

1. **Juez 1 (RoBERTa Base):** Analiza la predictibilidad estadística (perplejidad).
2. **Juez 2 (ChatGPT Detector):** Especialista en identificar la "huella digital" semántica de modelos GPT.
3. **Juez 3 (RoBERTa Large):** Evaluación de contexto profundo con alta precisión (355M de parámetros).

## 📊 Caso de Éxito
En pruebas reales con artículos científicos de gestión universitaria, el sistema arrojó un **Índice de Probabilidad IA del 8.93%**, confirmando una **Integridad Verificada** y superando los estándares de originalidad exigidos por revistas indexadas.

## 🚀 Uso rápido
Puedes ejecutar este auditor directamente en Google Colab haciendo clic en el botón azul de la parte superior del cuaderno. Solo necesitas cargar tu archivo `.docx` y ejecutar las celdas.
