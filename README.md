# ✈️ Airport Data Analysis – Tukan Airlines Expansion

Análisis de datos desarrollado para **Tukan Airlines**, una aerolínea caribeña con ambición de expandirse al mercado asiático.  
Este proyecto incluye procesos de **ETL, almacenamiento en MySQL, análisis exploratorio con Python** y un **dashboard interactivo en Power BI** para la toma de decisiones estratégicas. 🚀  

---

## 📑 Tabla de Contenidos
- [💡 Acerca del Proyecto](#-acerca-del-proyecto)
- [✈️ El Desafío](#️-el-desafío-de-tukan-airlines)
- [📈 Metodología](#-metodología)
- [🛠️ Tecnologías Utilizadas](#️-tecnologías-utilizadas)
- [📂 Estructura del Proyecto](#-estructura-del-proyecto)
- [📦 Instalación y Uso](#-instalación-y-uso)
- [📊 Dashboard y KPIs](#-dashboard-y-kpis-clave)
- [🎯 Conclusiones](#-conclusiones-estratégicas-y-recomendaciones)
- [📧 Contacto](#-contacto)
- [🙏 Agradecimientos](#-agradecimientos)

---

## 💡 Acerca del Proyecto
Este repositorio contiene el análisis de datos realizado para **Tukan Airlines**, una aerolínea con sede en el Caribe que busca establecer una fuerte presencia en el dinámico mercado asiático.  

Como equipo de **Oracle Data Labs**, la tarea fue proporcionar un análisis profundo para identificar patrones operativos, tendencias de reservas y métricas clave que guíen la estrategia de expansión.

---

## ✈️ El Desafío de Tukan Airlines
Tukan Airlines enfrenta el reto de entender un nuevo mercado con dinámicas diferentes. Algunas preguntas clave fueron:  

- ¿Cuáles son los patrones de reserva más comunes?  
- ¿Qué aeronaves son más eficientes para ciertos rangos de ruta?  
- ¿Cómo se distribuyen los ingresos entre distintos modelos de avión y condiciones de tarifa?  
- ¿Qué horarios muestran picos de demanda?  
- ¿Cuáles son las ciudades más populares y las menos activas?  

Nuestro análisis buscó responder estas preguntas para sentar las bases de una expansión exitosa.

---

## 📈 Metodología
1. **ETL** → Extracción desde SQLite, limpieza y transformación.  
   - Generación de **8 CSVs consolidados**: aircrafts, airports, bookings, flights, tickets, etc.  
2. **Almacenamiento en MySQL** → Carga de los datos en un servidor para consultas y análisis.  
3. **EDA con Python** → Limpieza, estadísticas descriptivas, correlaciones y visualizaciones.  
4. **Dashboard en Power BI** → Consolidación de KPIs y visualización interactiva para negocio.  

---

## 🛠️ Tecnologías Utilizadas
- **Lenguajes:** Python, SQL  
- **Librerías Python:** Pandas, Matplotlib, Seaborn, sqlite3, mysql.connector  
- **Base de Datos:** MySQL Server  
- **Entornos:** Jupyter Notebook / JupyterLab  
- **Visualización final:** Power BI  

---

## 📂 Estructura del Proyecto
airport-data-analysis/
├── data/ # CSV resultantes del ETL
├── notebooks/ # Jupyter Notebooks (EDA, ETL)
├── sql/ # Scripts SQL para carga de datos
├── requirements.txt # Dependencias Python
└── README.md # Este archivo

---

## 📦 Instalación y Uso
1. **Clonar el repositorio**
```bash
git clone https://github.com/LucasGomez35/airport-data-analysis.git
cd airport-data-analysis
```
2. **Configurar entorno virtual (opcional)**

```bash

python -m venv venv
source venv/bin/activate   # macOS/Linux
.\venv\Scripts\activate    # Windows
```
3. **Instalar dependencias**

```bash
pip install -r requirements.txt
```

4. **Configurar Base de Datos MySQL**

```bash

Crear la base tukan_airlines_db.

Ejecutar los scripts SQL en /sql/.

Verificar credenciales de conexión en los notebooks.
```
5. **Ejecutar el análisis**

```bash
jupyter notebook
```

## 📊 Dashboard y KPIs Clave

El dashboard interactivo en Power BI incluye:

Reservas → volumen total y evolución.

Clientes → base de clientes y comportamiento.

Ingresos → total y desglose por categorías.

Destinos → ciudades más populares.

Horas de vuelo → distribución horaria de actividad.

Tendencias → patrones estacionales.


![Dashboard Ejemplo](<img width="1422" height="798" alt="Captura de pantalla 2025-06-01 224919" src="https://github.com/user-attachments/assets/82dc7824-dfd5-4de5-994e-8b184a914d16" />
)
---

## 🎯 Conclusiones Estratégicas y Recomendaciones

Optimización de horarios: aprovechar picos de reservas para marketing y staffing.

Rutas asiáticas: priorizar destinos dentro del rango de aeronaves actuales.

Estrategia de precios: ajustar tarifas según patrones de demanda premium vs económica.

Ciudades clave: enfocar expansión en hubs con mayor potencial de demanda.

---

## 📧 Contacto

👤 Lucas Gomez  
📩 [lucasgomez.05.03@gmail.com](mailto:lucasgomez.05.03@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/lucas-gomez-79a720211)

---

## 🙏 Agradecimientos

A Kaggle por los datos de vuelo y reservas.

A la comunidad de Python por las librerías de análisis y visualización.


