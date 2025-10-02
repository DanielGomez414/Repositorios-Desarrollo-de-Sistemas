# Proyecto AdA

## 📂 Contenido

### Datos del archivo AdA 2.xlsx (carpeta `data/`)
- `HU Taller en clase.docx → Taller realizado en clase día 1/10/2025.
- `arbol_problemas.csv` → Árbol de problemas identificado en el proyecto.  
- `arbol_objetivos.csv` → Árbol de objetivos derivados de los problemas.  
- `arbol_acciones.csv` → Árbol de acciones propuestas.  
- `matriz_seleccion_alternativas.csv` → Matriz utilizada para la evaluación y selección de alternativas.  
- `matriz_marco_logico.csv` → Matriz de marco lógico con indicadores y supuestos.

### Datos del archivo RFy NF.xlsx (carpeta `requerimientos/`)
- `requerimientos_funcionales.csv` → Lista de requerimientos funcionales del sistema.  
- `requerimientos_no_funcionales.csv` → Lista de requerimientos no funcionales del sistema.  

## 📌 Uso 

Python:

```python
import pandas as pd

df1 = pd.read_csv("data/arbol_problemas.csv")
df2 = pd.read_csv("requerimientos/requerimientos_funcionales.csv")

print(df1.head())
print(df2.head())
```

---
