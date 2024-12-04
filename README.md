# Document Similarity with Bag-of-Words and Cosine Similarity

## 📄 Descripción del Proyecto
Este proyecto implementa un análisis de similitud entre documentos utilizando las técnicas de **Bag-of-Words (BoW)** y **TF-IDF**, combinadas con la métrica de **cosine similarity**. El objetivo es explorar la relación entre el contenido de los documentos y su similitud mediante representaciones vectoriales, para identificar patrones y temáticas comunes.

Los documentos analizados tratan temas relacionados con tecnología móvil y vehículos eléctricos, lo que permite observar tendencias de similitud entre documentos que comparten estas temáticas.

---

## 🎯 Objetivo
- Construir representaciones vectoriales de documentos mediante **Bag-of-Words** y **TF-IDF**.
- Calcular la similitud entre documentos usando la métrica de **cosine similarity**.
- Analizar los resultados y observar relaciones entre los temas tratados en los documentos.

---

## 🛠️ Herramientas y Bibliotecas Utilizadas
- **Python**
- **NLTK** para procesamiento de texto
- **NumPy** para manipulación de vectores
- **PyTorch** para cálculos de similitud
- **Scikit-learn** para el modelo TF-IDF
- **Matplotlib** y **Seaborn** para visualización

---

## 📁 Estructura del Proyecto
```
root/
├── docs/                       # Carpeta que contiene los documentos de entrada en formato .docx
├── results/                    # Carpeta que contiene las imagenes de los resultados
├── main.py                     # Script principal del proyecto
├── requirements.txt            # Lista de dependencias del proyecto
├── README.md                   # Archivo de descripción (este archivo)
```

---

## 🚀 Cómo Ejecutar el Proyecto
### 1. Pre-requisitos
Asegúrate de tener instalado Python 3.8+ y las dependencias del proyecto. Para instalarlas, usa:

```bash
pip install -r requirements.txt
```

### 2. Ejecución
Ejecuta el archivo principal del proyecto:

```bash
python main.py
```

### 3. Resultados
El proyecto generará:
- Una matriz de similitud calculada con **Bag-of-Words** y otra con **TF-IDF**.
- Gráficos de calor (heatmaps) de las matrices de similitud.
- Un gráfico de barras con las palabras más relevantes según **TF-IDF**.

---

## 📊 Ejemplo de Resultados
### Heatmap de Similitud (Bag-of-Words)
Se genera un mapa de calor que muestra la similitud entre documentos usando la representación **Bag-of-Words**.

<div align= "center"">
    <h2>Heatmap de Similitud BOW</h2>
    <img src="./results/similarity_matrix_heat_map.png" alt="Heatmap de Similitud BOW" style="max-width: 100%; height: auto;">
</div>

### Heatmap de Similitud (TF-IDF)
Similitud entre documentos utilizando vectores TF-IDF.

<div align= "center"">
    <h2>Heatmap de Similitud (TF-IDF)</h2>
    <img src="./results/TF-IDF_similarity_matrix_heat_map.png" alt="Heatmap de Similitud TF-IDF" style="max-width: 100%; height: auto;">
</div>

## 🧑‍💻 Créditos
Creado por:
- [Susana Suárez](https://github.com/susanasrez).
- [Mara Pareja](https://github.com/marapareja17).
```

