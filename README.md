# 🏠 AirBnB Madrid — Optimización de Precios

> **Proyecto Final — Data Storytelling**
> Máster en Data Analysis — Nuclio Digital School
> Autora: Claudia Balseiros

---

## 📌 Contexto del proyecto

Un cliente del sector inmobiliario opera en Madrid con una cartera importante de viviendas publicadas en AirBnB. Nos encarga un análisis para responder a la siguiente pregunta clave:

> **¿Qué puedo hacer para optimizar el precio de mis viviendas?**

El objetivo es construir un **Data Storytelling** completo que guíe al cliente desde el contexto del mercado hasta recomendaciones concretas y accionables.

---

## 🎯 Objetivos del análisis

- Elaborar un contexto del mercado AirBnB en Madrid
- Definir y desarrollar el roadmap del análisis
- Identificar los principales factores que influyen en el precio
- Construir un storytelling con insights claros para el cliente

---

## 📁 Estructura del repositorio

```
📁 airbnb-madrid-price-optimization/
├── 📓 proyecto_final_Claudia_Balseiros.ipynb   # Notebook principal
├── 📄 README.md
├── 📄 requirements.txt
├── 📄 .gitignore
└── 📁 data/
    ├── airbnb_madrid_host.parquet
    ├── airbnb_madrid_location.parquet
    ├── airbnb_madrid_property.parquet
    ├── airbnb_madrid_conditions.parquet
    └── airbnb_madrid_reviews.parquet
```

---

## 📊 Descripción de los datos

El dataset está dividido en 5 archivos en formato Parquet:

| Fichero | Descripción |
|--------|-------------|
| `airbnb_madrid_host.parquet` | Información del propietario (superhost, verificaciones, antigüedad) |
| `airbnb_madrid_location.parquet` | Barrio, coordenadas, distancia al centro y al aeropuerto |
| `airbnb_madrid_property.parquet` | Tipo de vivienda, habitaciones, camas, amenities |
| `airbnb_madrid_conditions.parquet` | Precio, noches mínimas, política de cancelación |
| `airbnb_madrid_reviews.parquet` | Puntuaciones, número de reseñas, idiomas |

---

## 🔧 Tecnologías y librerías utilizadas

| Librería | Uso |
|----------|-----|
| `pandas` | Manipulación y análisis de datos |
| `numpy` | Operaciones numéricas |
| `matplotlib` / `seaborn` | Visualización estática |
| `plotly` | Visualización interactiva |

---

## 📖 Estructura del análisis

1. **Contexto del problema** — Exploración inicial del mercado AirBnB en Madrid: distribución geográfica, tipos de vivienda, rangos de precio
2. **Definición del problema** — ¿Qué variables influyen en el precio?
3. **Roadmap del análisis** — Identificación de los ejes de investigación
4. **Insights clave** — Hallazgos principales para el storytelling final
5. **Conclusiones y recomendaciones** — Estrategias accionables para el cliente

---

## 🚀 Cómo ejecutar el proyecto

### 1. Clona el repositorio

```bash
git clone https://github.com/claucurtis/airbnb-madrid-price-optimization.git
cd airbnb-madrid-price-optimization
```

### 2. Instala las dependencias

```bash
pip install -r requirements.txt
```

### 3. Abre el notebook

```bash
jupyter notebook proyecto_final_Claudia_Balseiros.ipynb
```

> **Nota:** Los archivos de datos deben estar en la carpeta `data/` para que el notebook funcione correctamente.

---

## 👩‍💻 Autora

**Claudia Balseiros**
Máster en Data Analysis — Nuclio Digital School
[LinkedIn](https://www.linkedin.com/in/claudia-balseiros) · [GitHub](https://github.com/claucurtis)
