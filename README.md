# Modelo de Lenguaje Biomédico Personalizado (LLM Clínico)

Este proyecto busca desarrollar un modelo de lenguaje especializado en medicina clínica, capaz de detectar patrones en síntomas, diagnósticos e inferencias médicas, con enfoque en enfermedades neurológicas, psiquiátricas y glioblastomas.

## 🧠 Objetivo

Entrenar un modelo NLP que procese y genere inferencias clínicas útiles a partir de textos médicos, aplicando IA avanzada en contextos reales de salud.

---

## 🧩 Estructura del proyecto

### 🔹 Fase 1: Fundamentos
- Dominio de herramientas: Python, PyTorch, Transformers de HuggingFace
- Tokenización (BPE, WordPiece), Self-Attention
- Lectura de artículos biomédicos (PubMed, medRxiv)
- Dataset base: MIMIC-IV

### 🔹 Fase 2: Dataset y Preprocesamiento
- Filtrado de MIMIC-IV, CORD-19, OpenNeuro
- Normalización y limpieza de texto clínico
- Tokenización para tareas NLP

### 🔹 Fase 3: Entrenamiento de Modelos
- Modelos candidatos: DistilBERT, BioBERT, GPT-2 Small
- Tareas: Clasificación, Parafraseo, Clustering sintomático, Inferencia clínica

### 🔹 Fase 4: Evaluación e Inferencias
- Reportes clínicos automáticos
- Visualización de relaciones sintomáticas
- Evaluación de precisión y profundidad inferencial

---

## 🛠 Herramientas utilizadas

- **Lenguaje:** Python  
- **Frameworks:** PyTorch, HuggingFace Transformers  
- **Datasets:** MIMIC-IV, OpenNeuro, CORD-19  
- **Otros:** Pandas, Numpy, Docker, Gradio/Streamlit (demo), TensorBoard

---

## 🚀 Estado actual

✅ Fase 1 completada  
🟡 Fase 2 en desarrollo (preprocesamiento y tokenización)

---

## 🧑‍💻 Autor

Fernando Otero Muñiz  
[LinkedIn](https://www.linkedin.com/in/fernando-otero-muñiz-36b0a1225/)
