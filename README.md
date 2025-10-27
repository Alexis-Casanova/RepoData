# 📊 RepoData

Repositorio público para compartir archivos de datos y ejemplos de análisis.

---

## 📁 Contenido

En este repositorio encontrarás distintos archivos de datos (por ejemplo, en formato `.csv`) que pueden ser utilizados para prácticas, proyectos o análisis exploratorios.

Ejemplo:
- `TB_POBLACION_INEI.csv` — Tabla con información de población del INEI (Perú).

---

## 🧠 Uso del repositorio

Puedes descargar o acceder directamente a los archivos desde GitHub o mediante código en Python.

### 🔹 Descargar desde navegador
Haz clic en el archivo deseado y presiona el botón **"Download raw file"**.

### 🔹 Leer directamente desde Python

```python
import pandas as pd

url = "https://raw.githubusercontent.com/Alexis-Casanova/RepoData/main/TB_POBLACION_INEI.csv"
df = pd.read_csv(url)

print(df.head())
