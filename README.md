# 💻 trabajo01indtd2025: Métodos de Decisión bajo Incertidumbre

## Descripción del Proyecto Individual

Este repositorio contiene la resolución del primer trabajo individual de la asignatura de Teoría de la Decisión, desarrollado en RStudio y Quarto. [cite_start]El objetivo es aplicar los **métodos de decisión bajo incertidumbre** para resolver dos problemas inventados[cite: 20, 21].

[cite_start]El trabajo se ha estructurado en dos documentos Quarto (`.qmd`) para cumplir con el requisito de **separar el enunciado de la resolución**[cite: 18].

---

## Contenido del Repositorio

| Archivo | Contenido |
| :--- | :--- |
| **enunciados.qmd** | Documento que contiene exclusivamente el enunciado completo de los dos problemas inventados. |
| **Trabajo1.qmd** | Documento Quarto (la resolución) que incluye el código R, la matriz de decisión, la aplicación de todos los criterios y la **conclusión final** de la decisión para ambos problemas. |
| **teoriadecision\_funciones\_incertidumbre.R** | Archivo de funciones R proporcionado por la asignatura, utilizado para ejecutar los diferentes criterios. |
| **README.md** | Este documento. |

---

## Resumen de Problemas Resueltos

### Problema 1: Inversión en Start-up de Tecnología
* **Tipo:** Tabla de decisión con valores inventados (beneficios/costes).
* **Resolución:** Resuelto con las funciones de incertidumbre **individuales** (Wald, Optimista, Hurwicz, Savage, Laplace, Punto Ideal) por separado, evaluando tanto la situación favorable como la desfavorable.

### Problema 2: Lanzamiento de un Nuevo Producto
* **Tipo:** Situación real (cuota de mercado).
* **Resolución:** Resuelto utilizando la función **consolidada** `criterio.Todos` para evaluar todos los métodos simultáneamente y obtener una decisión por consenso (Agresiva, seleccionada por 4 de 6 criterios).

---
