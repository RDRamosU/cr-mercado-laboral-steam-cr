# 💼 Mercado Laboral Tech en Costa Rica — Análisis de Brecha STEAM

![Estado](https://img.shields.io/badge/Estado-En%20progreso-yellow)
![Proyecto](https://img.shields.io/badge/Portafolio-Proyecto%202%20de%204-purple)
![Licencia](https://img.shields.io/badge/Licencia-MIT-green)

> **Proyecto 2 de 4** de la serie
> [Radiografía de Empleabilidad STEAM en Costa Rica](https://github.com/RDRamosU/data-portfolio)

---

## 🔍 Pregunta central

**¿Existe una brecha entre los graduados STEAM que produce Costa Rica
y los empleos tech disponibles?**

---

## 📌 Preguntas de análisis

1. ¿Cuál es el desempleo de graduados STEM vs el promedio nacional en 2019 y 2022?
2. ¿A qué ritmo crece el empleo en el sector TIC vs la producción de graduados STEAM?
3. ¿Qué disciplinas tech tienen mayor inserción laboral y menor desvinculación?
4. ¿Existe una brecha de género en la inserción laboral STEM?
5. ¿Cómo se comparan los salarios del sector TIC vs el promedio nacional?

---

## 🎯 Hallazgo principal (anticipado)

> La brecha de talento tech en Costa Rica **no es de exceso de graduados
> sin empleo — es exactamente la contraria.**
> El mercado absorbe prácticamente todos los graduados tech disponibles
> y crece más rápido que la capacidad del sistema educativo de producirlos.

**Evidencia:**
- Desempleo STEM: **4.2%** vs desempleo nacional **12.2%** (2022)
- Empleo sector TIC creció **37.3%** en un solo año (2020→2021)
- Zona Franca sector servicios tech creció **10% anual** sostenido 2020–2024
- Computación: desempleo cercano a **0%** según Radiografía Laboral 2019

---

## 📂 Fuentes de datos

| Fuente | Institución | Datos clave | Periodo |
|--------|------------|-------------|---------|
| Radiografía Laboral III | CONARE-OPES | Desempleo/subempleo por carrera STEM | 2019 |
| Radiografía Laboral IV | CONARE-OPES | Desempleo/subempleo por carrera STEM | 2022 |
| Indicadores Nacionales CTI | MICITT | Empleo sector TIC formal | 2020–2021 |
| Exportación servicios TIC | BCCR | Empleo empresas exportadoras TIC | 2022 |
| Balance Zona Franca | PROCOMER | Empleo ZF · salarios · género | 2020–2024 |
| ECE 1987–2025 | INEC | Empleo, desempleo y fuerza laboral | 2014–2025 |
| Estadísticas empresariales | BCCR | Salarios por sector y sexo | 2005–2024 |
| Estudio sector empleador | CONARE | Competencias demandadas · brecha género STEM | 2023 |

> ⚠️ **Política de datos:** Todos los datasets son de acceso público,
> no contienen PII y provienen de fuentes institucionales oficiales.

---

## 🗂️ Estructura del proyecto

```
cr-mercado-laboral-steam-cr/
├── README.md
├── requirements.txt
├── .gitignore
├── data/
│   ├── raw/                          # Datos originales sin modificar
│   └── processed/                    # Datos limpios para análisis
├── notebooks/
│   ├── 01_definicion_problema.ipynb
│   ├── 02_exploracion_datos.ipynb
│   ├── 03_limpieza_preparacion.ipynb
│   └── 04_visualizaciones_hallazgos.ipynb
└── assets/
    └── graficas/                     # Visualizaciones exportadas
```

---

## 📓 Notebooks

| Notebook | Descripción | Estado |
|----------|-------------|--------|
| [01 — Definición del problema](notebooks/01_definicion_problema.ipynb) | Contexto, preguntas, inventario de fuentes y hallazgo anticipado | 🟢 Completado |
| [02 — Exploración de datos](notebooks/02_exploracion_datos.ipynb) | Carga y primera inspección de todas las fuentes | 🟢 Completado |
| [03 — Limpieza y preparación](notebooks/03_limpieza_preparacion.ipynb) | Consolidación, validación cruzada y dataset final | 🟢 Completado |
| [04 — Visualizaciones y hallazgos](notebooks/04_visualizaciones_hallazgos.ipynb) | Gráficas, tendencias y conclusiones | 🟢 Completado |

---

## 📊 Variables clave del análisis

| Variable | Fuente | Tipo |
|----------|--------|------|
| Tasa de desempleo STEM por carrera | Radiografía Laboral 2019 y 2022 | % |
| Tasa de desempleo nacional | INEC ECE | % |
| Empleo sector TIC formal | MICITT CTI | Personas |
| Empleo empresas exportadoras TIC | BCCR | Personas |
| Empleo directo Zona Franca servicios | PROCOMER | Personas |
| Salario promedio ZF vs nacional | PROCOMER / BCCR | USD/mes |
| Graduados STEAM anuales | OPES-CONARE (Proyecto 1) | Diplomas |
| Brecha de género en inserción STEM | Radiografía Laboral 2022 | % |

---

## 🔧 Cómo ejecutar este proyecto

```bash
git clone https://github.com/RDRamosU/cr-mercado-laboral-steam-cr.git
cd cr-mercado-laboral-steam-cr
pip install -r requirements.txt
jupyter notebook
```

> También puede ejecutarse en **Google Colab** sin instalación local.

---

## 🛠️ Tecnologías

`Python 3.11+` `pandas` `NumPy` `Matplotlib` `Seaborn` `openpyxl` `Jupyter`

---

## 📎 Parte de la serie

| # | Proyecto | Estado |
|---|----------|--------|
| 1 | [Graduados STEAM en CR 2014–2022](https://github.com/RDRamosU/cr-graduados-steam-analisis) | [🟢 Completado](https://www.linkedin.com/pulse/graduados-steam-de-las-universidades-estatales-costa-rica-zaj4e) |
| **2** | **Mercado laboral tech en CR** ← estás aquí | 🟢 Completado |
| 3 | [Habilidades demandadas tech CR](https://github.com/RDRamosU/cr-habilidades-demanda-tech) | 🟢 Completado |
| 4 | [CR vs Latinoamérica en STEAM](https://github.com/RDRamosU/cr-steam-comparativa-regional) | 🟢 Completado |

---

## 📰 Artículo publicado

Análisis completo publicado en LinkedIn:  
[Mercado laboral tech en Costa Rica](https://www.linkedin.com/pulse/graduados-steam-de-las-universidades-estatales-costa-rica-zaj4e)

---

## 👤 Autor

**Ruben Dario Ramos Ulate**
🌐 [rubendario.dev](https://rubendario.dev) · 💼 [LinkedIn](https://www.linkedin.com/in/ruben-ramos) · 🐙 [GitHub](https://github.com/RDRamosU)
