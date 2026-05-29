# Regresión Lineal Múltiple: Rendimiento de Combustible de Automóviles

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)

##  Descripción del proyecto

Este repositorio contiene el análisis completo de regresión lineal múltiple aplicado al conjunto de datos **Auto MPG** del repositorio UCI. El objetivo es modelar el rendimiento de combustible (millas por galón, mpg) de automóviles en función de características como cilindrada, potencia, peso, año del modelo y origen del vehículo. El trabajo incluye:

- Limpieza y preparación de datos.
- Análisis exploratorio con gráficos de correlación y pares.
- Construcción e interpretación de un modelo de regresión lineal múltiple.
- Verificación de supuestos: normalidad de residuos, independencia y multicolinealidad.
- Respuesta a preguntas clave: ¿Qué variable afecta más el consumo? ¿El peso influye positiva o negativamente? ¿Los autos más nuevos consumen menos?
- Generación de informe en LaTeX y gráficos listos para publicación.

##  Estructura del repositorio
regresion-autos/
├── datos/ # Base de datos limpia

│ └── auto_mpg_limpio.csv

├── codigo/ # Script principal en Python

│ └── regresion_autos.py

├── graficos/ # Figuras generadas

│ ├── matriz_correlacion.png

│ ├── pairplot.png

│ ├── qqplot.png

│ └── residuos_vs_ajustados.png

├── informe/ # Documento final (LaTeX y PDF)

│ ├── informe_regresion.tex

│ └── informe_regresion.pdf

├── requirements.txt # Dependencias de Python

└── README.md # Este archivo


## Requisitos e instalación

### Requisitos previos
- Python 3.8 o superior
- Git (opcional, para clonar)

### Instalación de dependencias
Clona el repositorio y crea un entorno virtual (recomendado):

```bash
git clone https://github.com/TU_USUARIO/regresion-autos.git
cd regresion-autos
python -m venv venv
source venv/bin/activate   # En Windows: venv\Scripts\activate
pip install -r requirements.txt

