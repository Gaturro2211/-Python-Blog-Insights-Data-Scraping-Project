# 🐍 Análisis de Datos: Python Insider Blog

## 📌 Tema del Proyecto
El tema central es el **Monitoreo de Lanzamientos de Software**. Se ha seleccionado el blog **"Python Insider"**, que es la fuente oficial de noticias sobre el desarrollo del lenguaje de programación Python.

### ¿Por qué este tema?
1. **Datos Estructurados:** Los títulos siguen un patrón claro (Versión + Estado + Fecha).
2. **Relevancia:** Es un sitio crítico para la comunidad tecnológica global.
3. **Frecuencia:** Permite obtener más de 20 registros fácilmente para cumplir con los requisitos mínimos de la tarea.
## 🎯 El Desafío
¿De qué habla la comunidad oficial de Python en 2026? Este proyecto utiliza **Scrapeo Estático** para capturar, limpiar y resumir los titulares más recientes del blog oficial, transformando texto desordenado en información estratégica.

## 🛠️ Stack Tecnológico
| Herramienta | Función |
| :--- | :--- |
| **Python 3.12** | Motor principal del proyecto |
| **BeautifulSoup4** | Extracción quirúrgica de HTML |
| **Pandas** | Procesamiento y estructuración de CSV |
| **GitHub Pages** | Despliegue del Dashboard interactivo |

## 📂 Laboratorio de Datos (Outputs)
Nuestros activos digitales están organizados en la carpeta `/data`:

1.  **[raw.csv](./data/raw.csv)**: La "fotografía" original del sitio (más de 20 registros).
2.  **[clean.csv](./data/clean.csv)**: Datos normalizados con cálculo de métricas de lectura.
3.  **[summary.csv](./data/summary.csv)**: El "Top 10" de conceptos clave detectados.

---

## 📈 Metodología
1. **Captura:** Petición HTTP al servidor de Google Blogger.
2. **Refinado:** Eliminación de ruido visual y etiquetas HTML.
3. **Análisis:** Tokenización de palabras para detectar la frecuencia de temas.

---
*Desarrollado para el curso de Herramientas Digitales - 2026*
