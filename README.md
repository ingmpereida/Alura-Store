# 📊 Alura Store Latam --- Análisis Exploratorio de Datos (EDA)

Este proyecto contiene un análisis exploratorio de datos (EDA) realizado
a partir del conjunto de datos de **Alura Store**, una tienda
latinoamericana dedicada a la venta de productos electrónicos. El
objetivo del análisis es comprender el comportamiento de ventas,
identificar patrones relevantes y preparar la base para futuros modelos
de Machine Learning.

El análisis completo se encuentra en el archivo:\
📁 **AluraStoreLatam.ipynb**

------------------------------------------------------------------------

## 🧠 Objetivo del Proyecto

-   Integrar diversas bases de datos relacionadas con ventas, productos
    y clientes.\
-   Realizar limpieza, tratamiento y enriquecimiento de datos.\
-   Generar métricas clave de negocio.\
-   Detectar oportunidades comerciales y patrones en el comportamiento
    de compra.\
-   Preparar los datos para tareas posteriores como segmentación o
    predicción.

------------------------------------------------------------------------

## 📁 Estructura del Notebook

El notebook está organizado en secciones que permiten seguir el flujo
natural de un análisis profesional:

### **1. Análisis de facturación**

Incluye: - Cálculo del total facturado por período. - Identificación de
tendencias de ingresos. - Detección de meses con mayor o menor
facturación. - Visualizaciones básicas para entender la evolución
temporal.

### **2. Base de datos del proyecto**

-   Importación de las diferentes fuentes de datos.
-   Validación de estructura, tipos y consistencia.
-   Identificación de duplicados y valores nulos.

### **3. Tratamiento de datos**

Incluye: - Imputación o eliminación de valores faltantes. - Corrección
de tipos de datos. - Normalización de nombres de columnas. - Limpieza de
registros inconsistentes. - Combinación de tablas mediante `merge` y
`concat`.

### **4. Concatenación de hojas de cálculo**

-   Unificación de múltiples archivos o pestañas en un único DataFrame.
-   Uso de `pd.concat()` para generar una tabla central unificada.

### **5. Base de datos resultante**

-   Base final libre de duplicados, valores inválidos y con estructura
    estandarizada.
-   Lista para aplicar análisis, visualizaciones o modelos predictivos.

------------------------------------------------------------------------

## 🛠 Tecnologías utilizadas

-   Python 3.x\
-   Pandas\
-   NumPy\
-   Matplotlib / Seaborn\
-   Google Colab / Jupyter Notebook

------------------------------------------------------------------------

## ▶️ Cómo ejecutar el proyecto

1.  Clonar el repositorio:

```{=html}

```
    git clone https://github.com/usuario/AluraStoreLatam.git

2.  Abrir el notebook en Google Colab o Jupyter Notebook:

```{=html}

```
    jupyter notebook AluraStoreLatam.ipynb

3.  Instalar dependencias:

```{=html}

```
    pip install -r requirements.txt

4.  Ejecutar las celdas en orden.

------------------------------------------------------------------------

## 📌 Resultados obtenidos

El EDA permite:

-   Comprender el comportamiento de ventas en diferentes períodos.\
-   Identificar productos más vendidos y categorías destacadas.\
-   Detectar problemas de calidad en los datos antes de un modelo.\
-   Generar una base consolidada lista para Machine Learning.

------------------------------------------------------------------------

## 📄 Licencia

Este proyecto se distribuye bajo la licencia MIT.

------------------------------------------------------------------------

## 🤝 Contribuciones

Las contribuciones, sugerencias o mejoras son bienvenidas.\
Puedes abrir un *issue* o enviar un *pull request*.
