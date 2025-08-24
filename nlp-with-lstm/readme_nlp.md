# Proyecto de Procesamiento de Lenguaje Natural y Clasificación con PyTorch Lightning

Este proyecto realiza clasificación de textos utilizando **PyTorch** y **PyTorch Lightning**. Se incluyen técnicas de NLP como tokenización, stemming, normalización de texto y análisis con lexicón de sentimientos.

---

## Requisitos

Antes de ejecutar el proyecto, asegúrate de tener Python instalado y las librerías necesarias. Todas las dependencias están listadas en `requirements.txt`.

Para instalarlas, ejecuta:

```bash
pip install -r requirements.txt
```

---

## Uso en Google Colab

1. Abrir un nuevo notebook en [Google Colab](https://colab.research.google.com/).
2. Configurar el entorno para usar **GPU**:
   - Ve a `Entorno de ejecución` → `Cambiar tipo de entorno de ejecución` → `Acelerador de hardware` → `GPU`.
3. Sube el archivo `requirements.txt` a Colab.
4. Instalar las librerías en el notebook:

```python
!pip install -r requirements.txt
```

5. Cargar código y datasets, ejecutar las celdas para entrenar y evaluar el modelo.

---


## Notas

- El proyecto está optimizado para ejecución en **GPU**, lo que acelera significativamente el entrenamiento de modelos de deep learning.
- Se usa **PyTorch Lightning** para un entrenamiento más estructurado y manejo de callbacks como early stopping y métricas.
- Todos los datasets pueden cargarse desde **Hugging Face Datasets**, o desde archivos locales en formato CSV/JSON.


