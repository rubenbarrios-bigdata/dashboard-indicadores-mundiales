# 📊 Dashboard Indicadores Mundiales – Power BI

[![Ver Dashboard Interactivo](https://img.shields.io/badge/Power_BI-Ver_Dashboard_Interactivo-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://app.powerbi.com/view?r=eyJrIjoiMmNiYTkyNzctNDM3My00MTUzLWJiZTQtMjBkYWIzMmZhNjhhIiwidCI6IjgxY2NjYzQzLWI1NjEtNDFmNy05NDgwLWU5ZThmMDI3YzQ0MyIsImMiOjR9)
[![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)](https://github.com/rubenbarrios-bigdata)
[![Estado](https://img.shields.io/badge/Estado-Completado-brightgreen?style=for-the-badge)](https://github.com/rubenbarrios-bigdata)

> 🚀 **¡Demo interactiva en vivo!** Haz clic en el botón superior **"Ver Dashboard Interactivo"** para explorar los indicadores mundiales de salud, demografía y rankings por continentes en tiempo real sin requerir cuenta ni descargas.


---

## 📌 Descripción del Proyecto

Este proyecto presenta un **Dashboard de Indicadores Mundiales** desarrollado en Power BI, cuyo objetivo es analizar y comparar indicadores demográficos y de salud a nivel global: **población**, **esperanza de vida** y **mortalidad infantil**, con cobertura de **216 países** distribuidos en 5 continentes.

El informe está organizado en dos páginas de análisis:
- **Indicadores Mundiales** — visión global de esperanza de vida y mortalidad infantil por país y continente
- **Población por Área** — distribución y ranking de población mundial por país y región

El dashboard está diseñado con enfoque ejecutivo para facilitar la toma de decisiones basada en datos demográficos y sanitarios.

---

## 🎯 Objetivos del Análisis

- Comparar la esperanza de vida promedio entre continentes y países.
- Identificar los países con mayor y menor mortalidad infantil a nivel mundial.
- Analizar la distribución de la población mundial por continente y país.
- Detectar brechas sanitarias y demográficas entre regiones.
- Apoyar decisiones de política pública y análisis geopolítico basados en datos.

---

## 📊 Indicadores Clave (KPIs)

| Indicador | Valor |
|---|---|
| Población Mundial Total | 7.413.672.933 |
| Esperanza de Vida Promedio Global | 72,28 años |
| Mortalidad Infantil Promedio Global | 35,83 muertes / 1.000 niños |

---

## 📈 Visualizaciones Incluidas

- 📌 Mapa mundial interactivo con indicadores por país
- 📌 Ranking de países por esperanza de vida (mayor y menor)
- 📌 Ranking de países por mortalidad infantil
- 📌 Distribución de población por continente
- 📌 Top países por volumen de población
- 📌 Tarjetas ejecutivas con KPIs globales
- 📌 Filtros dinámicos por continente y país

---

## 🔎 Principales Hallazgos

✅ **Europa lidera en esperanza de vida** con un promedio de 78,70 años, seguida de América (75,83) y Asia (73,47).

⚠️ **África concentra la mayor mortalidad infantil** con un promedio de 77,94 muertes por cada 1.000 niños, más del doble que el promedio global (35,83).

🌍 **Angola es el país con mayor mortalidad infantil** del mundo con 191,19 muertes por cada 1.000 niños, seguido de Afganistán (163,07) y Sierra Leona (143,64).

🏆 **Mónaco lidera en esperanza de vida** con 89,5 años, seguido de Singapur y Japón (85 años cada uno).

📉 **Chad y Guinea-Bissau** registran las esperanzas de vida más bajas (50,2 y 50,6 años respectivamente), evidenciando una brecha de casi 40 años respecto a los países líderes.

🌏 **Asia concentra el 61,2% de la población mundial** con 4.539 millones de habitantes. China (1.378M) e India (1.324M) representan juntos el 36,5% de la población global.

---

## 🗂 Modelo de Datos

El modelo está compuesto por **5 tablas** relacionadas:

| Tabla | Descripción |
|---|---|
| `Población` | Población total por país |
| `Mortalidad Infantil` | Tasa de mortalidad infantil por país |
| `Esperanza de Vida` | Esperanza de vida promedio por país |
| `Countries` | Dimensión geográfica en inglés (Country Code, Country, Continent) |
| `Paises` | Dimensión geográfica en español (Código País, País, Continente) |

Relación principal: tablas de indicadores → dimensión geográfica a través del campo `Country` (Muchos a Uno)

---

## 🛠 Herramientas Utilizadas

- Power BI Desktop
- Power BI Service

## 🧩 Habilidades Aplicadas

- DAX
- Modelado de datos relacional
- Diseño de visualizaciones ejecutivas
- Storytelling con datos
- Análisis demográfico y sanitario

---

## 🧠 Enfoque Analítico

El dashboard fue diseñado bajo principios de:

- Jerarquía visual clara con dos páginas temáticas diferenciadas
- Uso estratégico de mapas para análisis geoespacial
- Comparativas por continente para identificar brechas regionales
- Análisis descriptivo orientado a negocio y política pública
- Rankings para facilitar la identificación de outliers

---

## 📂 Estructura del Proyecto

```
dashboard-indicadores-mundiales/
│
├── data/
│   └── dataset.csv
│
├── dashboard/
│   └── indicadores_mundiales.pbix
│
├── images/
│   └── preview.png
│
└── README.md
```

---

## 📌 Aplicabilidad Empresarial

Este tipo de análisis es útil para:

- Organismos internacionales (ONU, OMS, Banco Mundial)
- Equipos de análisis geopolítico y estratégico
- Consultoras de desarrollo internacional
- Analistas de Business Intelligence con foco en datos públicos
- Investigadores y equipos académicos

---

## 👤 Autor

**Ruben Barrios**
Proyecto práctico desarrollado como parte de portafolio profesional en análisis de datos y Business Intelligence.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ruben-barrios)

Fuente de datos: Academia Datdata

---

## ⭐ Si este proyecto te parece interesante

No olvides darle una estrella al repositorio y conectar en LinkedIn.

`#DataAnalytics` `#PowerBI` `#BusinessIntelligence` `#DemographicAnalysis` `#DAX` `#DataPortfolio` `#GlobalIndicators` #Datdata
