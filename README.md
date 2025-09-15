# 📊 Análisis de Tamizajes Visuales en Python

Este proyecto permite analizar datos de **tamizajes visuales** a partir de archivos `.csv`, generando estadísticas, gráficos exploratorios y un **reporte PDF automatizado**.  
Fue desarrollado en **Google Colab**, pero puede ejecutarse también en **Jupyter Notebook**.

---

## 🚀 Funcionalidades principales
- **Limpieza de datos**:
  - Elimina columnas vacías o sin nombre.
  - Convierte fechas y edades a formatos correctos.
  - Completa valores faltantes en el campo **Sexo**.
  - Evita registros duplicados basados en el `Id`.
- **Análisis exploratorio**:
  - Distribución de sexo.
  - Histograma de edades.
  - Promedio de indicadores visuales.
  - Boxplots y correlaciones.
  - Mapas de calor por grupo de edad.
- **Generación de reportes PDF**:
  - Incluye tablas y gráficos.
  - Reportes individuales o de lotes de archivos.
  - Exportación automática para descarga.
- **Interfaz interactiva** con `ipywidgets`:
  - 📄 Analizar un archivo.
  - 📂 Analizar lote de archivos.
  - 🔗 Fusionar y analizar varios archivos juntos.

---

## 📦 Requisitos
Antes de ejecutar el notebook, instala las dependencias necesarias:

```bash
pip install pandas matplotlib seaborn ipywidgets fpdf pillow
