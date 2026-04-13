# Aprendizaje No Supervisado - Clustering de Transporte Masivo

## Actividad 6 - Inteligencia Artificial

---

## 👥 Integrantes y Aportes

| Integrante | Aporte en el Proyecto | 
|------------|----------------------|
| Jose Andres de la Ossa C | Creación del dataset y descripción de datos, Implementación del modelo K-Means y notebook, Documentación, pruebas y mapa conceptual |


---

## 📋 Descripción del Proyecto

Este proyecto aplica técnicas de **aprendizaje no supervisado** para identificar patrones ocultos en un sistema de transporte masivo. Utilizamos el algoritmo **K-Means Clustering** para agrupar estaciones según su flujo de pasajeros, sin tener etiquetas previas sobre qué tipo de demanda existe.

**Objetivo:** Descubrir automáticamente grupos de estaciones con comportamientos similares para optimizar la planificación del servicio.

---

---

## 🛠️ Requisitos

- Python 3.8 o superior
- Librerías:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn
  - joblib

---

## 📦 Instalación

### Opción 1: Google Colab (Recomendado)
1. Abrir el archivo `no_supervisado.ipynb` en [Google Colab](https://colab.research.google.com/)
2. Subir el archivo `datos_clustering.csv` a la carpeta del notebook
3. Ejecutar todas las celdas en orden

### Opción 2: Local
```bash
# Instalar dependencias
pip install pandas numpy scikit-learn matplotlib seaborn joblib

# Clonar el repositorio
git clone [URL_DEL_REPOSITORIO]

# Ejecutar el notebook
jupyter notebook no_supervisado.ipynb
