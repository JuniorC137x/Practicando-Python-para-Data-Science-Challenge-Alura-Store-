#  Alura Store — Análisis de Rendimiento de Tiendas

## 1.  Propósito del Análisis

El Sr. Juan es dueño de una cadena de 4 tiendas y desea vender una de ellas para invertir en un nuevo negocio. El objetivo de este análisis es identificar **cuál de las 4 tiendas tiene el menor rendimiento**, evaluando los siguientes indicadores:

-  Facturación total por tienda
-  Categorías de productos más vendidas
-  Calificación promedio de los clientes
-  Productos más y menos vendidos
-  Costo promedio de envío

Con base en estos datos, se emite una **recomendación final** sobre qué tienda debería vender el Sr. Juan.

---

## 2.  Estructura del Proyecto
```
alura-store/
│
├── AluraStoreLatam.ipynb   # Notebook principal con todo el análisis
└── README.md               # Este archivo
```

Los datos se cargan directamente desde el repositorio oficial de Alura, por lo que no es necesario descargar ningún archivo CSV de forma manual.

---

## 3.  Ejemplos de Gráficos e Insights

### Facturación Total
Gráfico de barras comparando los ingresos totales de cada tienda.
>  **Insight:** Se puede identificar claramente qué tienda genera más y menos ingresos acumulados.

### Ventas por Categoría
4 gráficos de barras mostrando qué categorías dominan en cada tienda.
>  **Insight:** Categorías como Electrónicos y Muebles tienden a liderar en la mayoría de las tiendas.

### Calificación Promedio
Barras comparativas con una línea de referencia en la nota media (3/5).
>  **Insight:** Las tiendas con calificación más baja podrían tener problemas de satisfacción al cliente.

### Productos Más Vendidos
Barras horizontales con el Top 5 de productos por tienda.
>  **Insight:** Permite identificar qué productos impulsan las ventas y cuáles no tienen demanda.

### Costo de Envío Promedio
Comparativa del flete promedio entre las 4 tiendas.
>  **Insight:** Un costo de envío alto puede desincentivar compras y afectar la competitividad.

---

## 4.  Instrucciones para Ejecutar el Notebook

### Opción A — Google Colab (recomendado, sin instalación)

1. Descarga el archivo `AluraStoreLatam.ipynb`
2. Entra a [colab.research.google.com](https://colab.research.google.com)
3. Haz clic en **Archivo → Subir notebook**
4. Selecciona el archivo descargado
5. Ejecuta todas las celdas con `Ctrl + F9`


