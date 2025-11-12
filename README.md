# Alura Store Latam – Análisis de Ventas Multitienda

## Descripción del Proyecto
Este proyecto forma parte del **Challenge Data Science Latam de Alura**, en el cual se analizan los datos de ventas de cuatro tiendas ficticias de la cadena **Alura Store**.  
El objetivo principal es determinar **cuál de las tiendas debería vender el Sr. Juan**, con base en un análisis integral de desempeño financiero, satisfacción del cliente y distribución geográfica de las ventas.

Se aplican técnicas de **análisis exploratorio de datos (EDA)**, visualización y síntesis de resultados para orientar la toma de decisiones empresariales.

---

## Objetivos del Análisis
1. Evaluar el desempeño de cada tienda en términos de ventas, rentabilidad y satisfacción del cliente.  
2. Identificar patrones de consumo por categoría de producto y ciudad.  
3. Analizar la distribución geográfica de las ventas para determinar la dominancia de mercado por ubicación.  
4. Formular una recomendación estratégica sobre cuál tienda vender, respaldada en evidencia cuantitativa.

---

## Estructura del Proyecto
El análisis se desarrolla en un único notebook de Jupyter con el siguiente flujo de trabajo:

1. **Importación y exploración de datos**  
   - Carga de los datasets de las cuatro tiendas (CSV).  
   - Revisión de estructura, duplicados y valores nulos.

2. **Análisis general por tienda**  
   - Facturación total y costo de envío promedio.  
   - Distribución de ventas por categoría de producto.  
   - Cálculo de calificación promedio de los clientes.  
   - Identificación de productos más y menos vendidos.

3. **Visualizaciones**  
   - Gráficos de barras, dispersión y radar para comparar métricas clave.  
   - Mapas y análisis geográfico mediante latitud y longitud.  
   - Representación de las ciudades donde cada tienda domina en ventas.

4. **Análisis geográfico adicional (extra)**  
   - Cálculo de las ciudades dominadas por cada tienda.  
   - Representación geoespacial de ventas para visualizar el alcance territorial.

5. **Conclusión y recomendación final**  
   - Identificación de la tienda menos eficiente.  
   - Argumentación técnica para la venta de la Tienda 4.  

---

## Resultados Principales

### Rendimiento General
- **Tienda 1:** Mayor facturación total y fuerte presencia en varias ciudades.  
- **Tienda 2:** Buen equilibrio entre ingresos y satisfacción del cliente.  
- **Tienda 3:** Mejor calificación promedio, reflejando alto nivel de satisfacción.  
- **Tienda 4:** Menor facturación total y bajo desempeño relativo.

### Análisis Geográfico
- Las cuatro tiendas operan en las mismas 19 ciudades de Colombia.  
- Cada tienda presenta un patrón de dominancia en distintas zonas:  
  - Tienda 1 domina en Bogotá, Cali y Cúcuta.  
  - Tienda 2 en Medellín y Santa Marta.  
  - Tienda 3 en Barranquilla, Cartagena y Leticia.  
  - Tienda 4 en Bucaramanga, Pereira, Neiva y Riohacha.  

### Recomendación Final
Se recomienda **vender la Tienda 4**, debido a:
- Su menor volumen de facturación.  
- Rendimiento medio en satisfacción del cliente.  
- Escasa dominancia geográfica en comparación con las demás tiendas.  

Esta acción permitiría optimizar recursos y concentrar la inversión en las tres tiendas con mejor desempeño financiero y operativo.

---

## Tecnologías Utilizadas
- **Python 3.10+**
- **Pandas** (análisis de datos)
- **Matplotlib** (visualizaciones)
- **NumPy** (operaciones numéricas)
- **Jupyter Notebook**

---

## Ejecución del Proyecto

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/usuario/alura-store-latam.git
   cd alura-store-latam
