# ⚖️ Quórum-IA: Auditor de Integridad Académica

> 💡 **Nota:** Se recomienda hacer **Ctrl + Clic** en el botón para abrir el auditor en una pestaña nueva y mantener esta guía abierta.

<a href="https://colab.research.google.com/github/cesarpc1307/Quorum-IA-Detector/blob/main/Quórum_IA.ipynb" target="_blank" rel="noopener noreferrer">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab">
</a>

---

Este proyecto implementa un sistema de **auditoría forense digital** diseñado para validar la autoría humana en textos científicos. Desarrollado en el marco de la investigación *"Hacia una Gestión de Proximidad"* de la **UNAH**, esta herramienta utiliza un quórum de redes neuronales profundas para garantizar la transparencia académica.

## 🤖 El Escuadrón de Jueces
Para minimizar los falsos positivos y asegurar un análisis riguroso, el sistema utiliza un consenso de tres modelos independientes:

1.  **Juez 1 (RoBERTa Base):** Analiza la predictibilidad estadística y la **perplejidad**.
2.  **Juez 2 (ChatGPT Detector):** Especialista en identificar la **"huella digital" semántica**.
3.  **Juez 3 (RoBERTa Large):** Evaluación de **contexto profundo** con alta precisión.

---

## 📊 Caso de Éxito: Validación Científica
En pruebas reales con artículos científicos de gestión universitaria, el sistema arrojó:

* **Párrafos procesados:** 84
* **Índice de Probabilidad IA:** **8.93%**
* **Veredicto:** ✅ **INTEGRIDAD VERIFICADA**

---

## 🚀 Guía de Uso Rápido
1.  **Abrir el cuaderno:** Haz clic en el botón **Open in Colab** (arriba).
2.  **Subir archivo:** En el panel izquierdo de Colab, sube tu archivo `.docx`.
3.  **Ejecutar:** En la última celda, coloca el nombre de tu archivo y presiona **Play**.

---

## 🏛️ Créditos
Proyecto desarrollado por **César Pineda**.
