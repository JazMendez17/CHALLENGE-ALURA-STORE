# CHALLENGE-ALURA-STORE
Proyecto de análisis de datos del Challenge de Data Science (Alura Latam). Se estudian ventas, categorías, calificaciones y costos de envío de 4 tiendas online, identificando la menos rentable. Incluye importación de datos en Python, análisis exploratorio y visualización con Pandas y Matplotlib.

# 🏪 Proyecto Challenge - Alura Store

Este proyecto corresponde al **Challenge de Data Science (Latam) de Alura**, donde se analizan los datos de **4 tiendas en línea** con el objetivo de identificar la tienda menos rentable para recomendar su venta.  

---

## 📂 Contenido del proyecto
1. **Importación de datos** desde archivos CSV en GitHub.  
2. **Análisis exploratorio** de las ventas, calificaciones, categorías y costos de envío.  
3. **Visualización de datos** mediante gráficos con Matplotlib.  
4. **Conclusiones y recomendaciones** basadas en los resultados obtenidos.  

---

## 📊 Resultados principales

### 1. Facturación por tienda
- La facturación total se calculó sumando los ingresos por tienda.  
- Resultado:  
  - **Tienda 1** → Mayor facturación.  
  - **Tienda 4** → Menor facturación.  

![Ingresos Totales](imagen_facturacion.png)

---

### 2. Ventas por categoría
- Se agruparon las ventas según la categoría del producto.  
- Algunas categorías como *Electrónica* y *Ropa* presentan mayor volumen de ventas.  

![Ventas por Categoría](imagen_categorias.png)

---

### 3. Calificación promedio por tienda
- Se calculó el promedio de la columna **Calificación**.  
- Todas las tiendas tienen calificaciones similares (entre 3.7 y 4.1).  

![Calificaciones](imagen_calificaciones.png)

---

### 4. Productos más y menos vendidos
- **Top 5 productos más vendidos**: Identificados con mayor frecuencia en cada tienda.  
- **Bottom 5 productos menos vendidos**: Productos con menor rotación.  

![Más vendidos](imagen_top.png)  
![Menos vendidos](imagen_bottom.png)

---

### 5. Costos de envío
- Se comparó el costo promedio de envío en cada tienda.  
- La **Tienda 4** tiene costos de envío ligeramente más bajos.  

![Costo de envío](imagen_envio.png)

---

## 📌 Conclusión y recomendación
Tras el análisis se determinó que:  
- La **Tienda 4** presenta la facturación más baja, a pesar de tener costos de envío más bajos.  
- Su desempeño global es menor en comparación con las otras tiendas.  

👉 **Recomendación:** La **Tienda 4** es la candidata más adecuada para ser vendida.  

---

## ⚙️ Tecnologías utilizadas
- **Python 3**  
- **Pandas** → Manejo y análisis de datos.  
- **Matplotlib** → Visualización de resultados.  
- **Jupyter Notebook / VS Code** (para desarrollo).  

---

## 🚀 Cómo ejecutar el proyecto
1. Clonar el repositorio:  
   ```bash
   git clone https://github.com/tuusuario/alura-store-challenge.git
