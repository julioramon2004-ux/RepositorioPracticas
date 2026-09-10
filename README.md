# Análisis Bioinformático de Datos RNA-seq - EPILAB

[![Autor](https://img.shields.io/badge/Autor-Julio_Colodrero_Bernad-blue)]()
[![Institución](https://img.shields.io/badge/Institución-Pontificia_Universidad_Javeriana-red)]()
[![Herramientas](https://img.shields.io/badge/Tools-Bash%20|%20Subread%20|%20FastQC-brightgreen)]()

## 📌 Descripción del Proyecto
Este repositorio contiene el flujo de trabajo y el análisis bioinformático de datos de secuenciación masiva (RNA-seq), desarrollado durante la estancia de investigación internacional en el **EPILAB** (Instituto de Genética Humana, Pontificia Universidad Javeriana, Bogotá). 

El objetivo de este repositorio es documentar un pipeline eficiente y reproducible para el procesamiento, control de calidad y alineamiento de secuencias genómicas, sirviendo como portafolio de habilidades en biología computacional. El registro de los comandos ejecutados, la terminal y los resultados se encuentra detallado en el reporte `Practica_EPILAB.html` [cite: 1].

---

## 🛠️ Tecnologías y Herramientas Utilizadas
El análisis se ejecutó íntegramente en un entorno Linux utilizando herramientas de línea de comandos, orquestando el flujo de datos mediante scripts y documentando el proceso en Jupyter.

*   **Gestión de Entornos:** `micromamba`
*   **Procesamiento y Control de Calidad (QC):** `FastQC`, `fastp`
*   **Alineamiento Bioinformático:** `Subread`
*   **Procesamiento por Terminal:** Comandos Bash, `awk`, `grep`
*   **Entornos de Desarrollo:** VS Code, Jupyter Notebooks

---

## 🧬 Flujo de Trabajo (Pipeline)
El repositorio demuestra la ejecución del siguiente pipeline analítico:

1.  **Exploración de Datos Crudos:** Inspección de los archivos de secuenciación iniciales en formato FastQ.
2.  **Control de Calidad Inicial:** Evaluación de la calidad de las lecturas mediante `FastQC` para identificar posible contaminación por adaptadores o caídas de calidad en los extremos de las secuencias.
3.  **Trimming y Filtrado:** Implementación de `fastp` para recortar adaptadores y descartar lecturas que no superan los umbrales de calidad Phred requeridos.
4.  **Alineamiento de Secuencias:** Mapeo y alineamiento de las lecturas procesadas contra el genoma de referencia utilizando los algoritmos de `Subread`.
5.  **Automatización:** Creación y ejecución de scripts `.sh` en Bash para procesar flujos de datos y automatizar las tareas bioinformáticas sobre múltiples archivos de manera estructurada.

---

## 📂 Archivos Destacados
*   📄 **`Practica_EPILAB.html`**: Documento interactivo principal que contiene la bitácora completa del proyecto, incluyendo el código ejecutado en consola y los outputs del análisis [cite: 1].

---

## 💡 Sobre el Autor
**Julio Colodrero Bernad**  
Estudiante de Grado en Biotecnología (Especialidad en Biotecnología de la Salud) por la Universidad de Córdoba. Con un fuerte enfoque en el emprendimiento biotecnológico, el análisis de datos genómicos y la gestión de tecnologías en el sector salud.
