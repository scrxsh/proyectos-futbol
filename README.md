# ⚽ Proyectos Fútbol

Este repositorio contiene una colección de notebooks y datos dedicados al análisis de rendimiento, visualización avanzada y exploración estadística del fútbol profesional. Se utilizan fuentes como **Fotmob** y **Sofascore**, junto con herramientas como `pandas`, `matplotlib` y `mlpsoccer` que fueron ejecutadas gracias a librería de federicorabanos conocida como [LanusStats](https://github.com/federicorabanos/LanusStats) para generar insights valiosos sobre equipos y jugadores.

---

## 📁 Estructura del proyecto

proyectos-futbol/  
├── Fotmob/  
│ ├── csv/  
│ │ ├── final_uel.csv  
│ │ ├── premier_league_defenders.csv  
│ │ └── fotmob.ipynb  
│  
├── Rendimientos/  
│ ├── fonts/  
│ │ └── SpaceGrotesk-Regular.ttf  
│ ├── equipos_fpc.json  
│ ├── equipos.json  
│ └── rendimiento.ipynb  
│  
├── ShotMaps/  
│ ├── shotmap.ipynb  
│ └── shotmap.csv  
│  
├── Sofascore/  
│ └── sofascore.ipynb  



---

## 📊 Funcionalidades principales

- **Análisis de datos de ligas europeas y locales** a partir de CSV y JSON.
- **Visualización de rendimiento** individual y colectivo en ligas como la Premier League y el Fútbol Profesional Colombiano (FPC).
- **Mapas de disparo (Shot Maps)** personalizados con estilos y tipografías propias.
- **Exploración y visualización de estadísticas desde APIs y exportaciones de plataformas deportivas** como Sofascore y Fotmob.

---

## 📊 Descripción de los notebooks

| Notebook | Descripción |
|----------|-------------|
| `fotmob.ipynb` | Análisis de datos de la Europa League y defensores de la Premier League usando estadísticas de Fotmob. |
| `rendimiento.ipynb` | Visualización y análisis del rendimiento de equipos del FPC con datos en formato JSON. |
| `shotmap.ipynb` | Generación de mapas de disparo a partir de datos posicionados en cancha. |
| `sofascore.ipynb` | Exploración de datos tomados de Sofascore para evaluar desempeño en partidos. |

---

## 🔧 Herramientas utilizadas

- Python 3.13
- Jupyter Notebook
- LanusStats (https://github.com/federicorabanos/LanusStats)
- Tipografía personalizada (SpaceGrotesk)


## 🚀 Cómo ejecutar

1. Clona el repositorio:

   ```bash
   git clone https://github.com/scrxsh/proyectos-futbol.git
   cd proyectos-futbol
2. Crea y activa un entorno virtual en Windows
**Windows:**
	```bash
	python -m venv .venv
	.venv/bin/activate 
### 🛠 Requisitos
---
Este proyecto depende de las siguientes bibliotecas de Python:

    lanusstats
    jupyter
    lxml

Para ello se debe instalar las librerías ubicadas en el archivo requeriments.txt

```bash
pip install -r requirements.txt
```
## 📝 Notas adicionales
El archivo SpaceGrotesk-Regular.ttf puede ser usado para personalizar visualmente los gráficos.

Los datos .csv y .json están estructurados para facilitar comparaciones por equipos, competiciones y jugadores. (Lo puedes crear)

Las visualizaciones se generan usando los datos crudos de partidos exportados o recolectados.

