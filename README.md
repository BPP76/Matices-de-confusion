# Matices de confusión — Análisis del corpus documental del 23F

Proyecto de Machine Learning · Máster · Curso 2025-2026  
Universidad de Navarra

## Descripción

Análisis del corpus documental desclasificado del 23F mediante técnicas de 
Machine Learning y NLP. El proyecto aborda cinco casos de uso: evolución 
temporal del discurso, clustering de documentos, red de entidades y relaciones, 
clasificación supervisada de fases históricas y recuperación semántica (RAG).

**Equipo:**  Cristina Cerezo · Daniel Fuentes · Javier Penelas · Begoña Pereiro

## Notebook principal

El notebook está alojado en Google Colab y puede abrirse directamente desde 
este enlace: (https://colab.research.google.com/drive/16Ojp_N4inGNKCWxG5lSFm9RhT0oQf78C)

## Cómo ejecutar

1. Abre el notebook en Google Colab desde el enlace de arriba.
2. Ejecuta las celdas en orden, de principio a fin.
3. La primera ejecución instala las dependencias automáticamente
4. No es necesario modificar ningún parámetro ni ruta para ejecutar el pipeline 
   completo.

## Estructura del repositorio
```
matices-de-confusion/
│
├── notebook_23f_colab.ipynb   # Notebook principal
├── README.md                  # Este archivo
│
├── data/
│   ├── raw/                   # Datos en crudo de RTVE
│   └── processed/             # Corpus limpio tras el pipeline ETL
│
├── scripts/                   # Scripts auxiliares .py
│
├── outputs/
│   ├── figures/               # Gráficos y visualizaciones
│   └── models/                # Modelos entrenados serializados
│
└── docs/                      # Informe y documentación

...
```

## Dataset

Documentos desclasificados del 23F, accesibles a través del buscador de RTVE:  
https://www.rtve.es/noticias/23f-desclasificados/buscador-23f/

## Contacto

Para cualquier duda sobre el repositorio, contactar con el equipo a través de: 

Cristina Cerezo Ortíguez <ccerezoorti@alumni.unav.es>,
Daniel Fuentes <dfuentesvaz@alumni.unav.es>,
Javier Penelas Rubio <jpenelasrub@alumni.unav.es>,
Begoña Pereiro Palomares <bpereiropal@alumni.unav.es>

