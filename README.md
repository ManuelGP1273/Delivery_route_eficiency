# 🚚 Delivery Route Efficiency Analysis

## 📌 Descripción del proyecto

Este proyecto analiza la **eficiencia operativa de rutas de entrega** utilizando datos de pedidos de comida a domicilio. El objetivo principal es identificar **desbalances entre las zonas de los restaurantes y las zonas de los clientes**, los cuales pueden generar mayores tiempos de entrega y afectar la eficiencia logística.

A través de análisis exploratorio, métricas de eficiencia y visualizaciones como *heatmaps*, el proyecto busca detectar oportunidades de mejora en la **asignación de zonas de cobertura** y apoyar la toma de decisiones operativas basadas en datos.

Este trabajo forma parte de mi **portafolio profesional como Analista de Datos Junior**.

---

## 🎯 Objetivos

* Analizar la distribución de pedidos por zona de restaurante y zona de cliente.
* Evaluar los tiempos promedio de entrega por combinación de zonas.
* Identificar pedidos atendidos fuera de la zona natural del restaurante.
* Detectar posibles ineficiencias operativas mediante métricas y visualizaciones.
* Proponer mejoras para optimizar la eficiencia de entrega.

---

## 🗂️ Estructura del repositorio

```
Delivery_route_eficiency/
│
├── Delivery route efficiency.ipynb
├── data/
│   └── Food_Delivery_Route_Efficiency_Dataset.csv
├── README.md
```

---

## 🧰 Tecnologías utilizadas

* **Python 3**
* **Pandas** – manipulación y análisis de datos
* **NumPy** – cálculos numéricos
* **Matplotlib & Seaborn** – visualización de datos
* **Jupyter Notebook** – desarrollo y documentación del análisis

---

## 📊 Flujo del análisis

1. **Carga y exploración de datos**

   * Revisión de estructura, tipos de datos y valores faltantes.

2. **Limpieza y preparación**

   * Eliminación de inconsistencias.
   * Transformación de variables relevantes.

3. **EDA general (Exploratory Data Analysis)**

   * Distribución global de pedidos.
   * Análisis general por zonas y modos de entrega.

4. **Análisis por zonas**

   * Comparación entre zonas de restaurantes y clientes.
   * Identificación de patrones operativos.

5. **Métricas de eficiencia**

   * Tiempo promedio de entrega por combinación de zonas.
   * Porcentaje de pedidos atendidos fuera de la zona natural del restaurante.

6. **Visualizaciones clave**

   * Heatmaps para analizar relaciones entre zonas y modos de entrega.
   * Gráficos de apoyo para interpretar patrones y desbalances.

7. **Conclusiones y recomendaciones**

---

## 📈 Hallazgos principales

* Se identificaron **desbalances entre las zonas de los restaurantes y las zonas de los clientes**.
* Un porcentaje relevante de pedidos se atiende fuera de la zona natural del restaurante, lo que incrementa los tiempos promedio de entrega.
* Los patrones observados son consistentes entre restaurantes, por lo que una **visión general del sistema** resulta suficiente para detectar ineficiencias.
* La reasignación de zonas de cobertura podría mejorar la eficiencia operativa y reducir los tiempos de entrega.

---

## 🚀 Cómo ejecutar el proyecto

1. Clona el repositorio:

```bash
git clone https://github.com/ManuelGP1273/Delivery_route_eficiency.git
```

2. Accede a la carpeta del proyecto:

```bash
cd Delivery_route_eficiency
```

3. Instala las dependencias necesarias:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

4. Abre el notebook:

```bash
jupyter notebook
```

5. Ejecuta las celdas en orden para reproducir el análisis.

---

## 👤 Autor

**Manuel García**
Analista de Datos Junior

---

⭐ *Proyecto orientado al análisis operativo y a la mejora de procesos logísticos mediante el uso de datos.*