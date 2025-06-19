# Detección Automática de Retinopatía Diabética con Deep Learning

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg)](https://tensorflow.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Complete-success.svg)]()

> **Sistema automatizado para detección temprana de retinopatía diabética mediante técnicas avanzadas de computer vision y deep learning**

<div align="center">
 <img src="https://drive.google.com/file/d/1SSCzyMbr7bhXLqMb7REMks0Vq7NfwCOc/view?usp=sharing" alt="Pipeline Overview" width="800"/>
</div>

## 🎯 Descripción del Proyecto

La retinopatía diabética es la principal causa de ceguera en adultos en edad laboral. Este proyecto desarrolla un **pipeline completo de detección automática** que combina preprocesamiento especializado, transfer learning y técnicas de optimización avanzadas para lograr un **F1-Score de 0.93** y **Recall de 0.92**.

### 🏥 Relevancia Médica
- **Detección temprana**: Identifica signos antes de síntomas visibles
- **Alta sensibilidad**: Minimiza falsos negativos críticos en diagnóstico
- **Escalabilidad**: Procesamiento automatizado para screening masivo
- **Accesibilidad**: Democratiza acceso a diagnóstico especializado

## 🔬 Metodología en 3 Fases

### 📋 Fase I: Exploración y Preprocesamiento
- **Dataset**: RFMiD (3,200 imágenes profesionales)
- **Evaluación**: 9 filtros de preprocesamiento especializados

### ⚡ Fase II: Clasificación (Baseline)
- **Evaluación**: 9 filtros de preprocesamiento especializados
- **Arquitectura**: MobileNetV2 + capas densas

### 🚀 Fase III: Optimización y Técnicas Avanzadas
- **Migración**: TensorFlow Data API nativo
- **Optimizaciones**: GPU acceleration, cache, prefetch
- **Callbacks**: EarlyStopping, ModelCheckpoint
- **Resultado**: 15% reducción en tiempo de entrenamiento
- **Data Augmentation**: Rotación, brillo, contraste
- **Regularización**: Dropout (30%), Batch Normalization
- **Fine-Tuning**: Descongelamiento selectivo desde block_7_expand

## 🛠️ Tecnologías Utilizadas

<div align="center">

| Categoría | Tecnologías |
|-----------|-------------|
| **Deep Learning** | TensorFlow, Keras, MobileNetV2 |
| **Computer Vision** | OpenCV, PIL, CLAHE, Sobel |
| **Data Science** | NumPy, Pandas, Scikit-learn |
| **Visualización** | Matplotlib, Seaborn |
| **Optimización** | GPU acceleration, Multiprocessing |

</div>
