# TRNP-Model_EII
Este repositorio contiene la implementación computacional, scripts de análisis y rutinas de visualización desarrolladas para el **Documento Técnico de Metodologías de Cálculo de Ruido**.

# Modelación de Ruido de Tráfico Urbano (Proyecto FONDEF)

El proyecto implementa un acoplamiento matemático entre modelos microscópicos de tráfico y modelos macroscópicos de emisión acústica para predecir niveles de ruido ($L_{eq}$) y su sensibilidad marginal ($dL/dk$).

## 🚀 Funcionalidades Principales

* **Modelos de Tráfico:** Implementación de las curvas $v-k$ de Greenshields (Lineal), Greenberg (Logarítmico) y Drake (Exponencial).
* **Modelo Acústico:** Implementación del modelo de emisión de Cai (2015) adaptado.
* **Cálculo Simbólico:** Derivación automática de gradientes de ruido usando `SymPy`.
* **Simulación:** Generación de curvas teóricas de $L_{eq}$ vs. Densidad y Flujo.
* **Visualización:** Scripts para generar las gráficas comparativas incluidas en el informe técnico.

## 🛠️ Estructura del Código

* `/src`: Código fuente principal (módulos de tráfico y acústica).
* `/notebooks`: Jupyter Notebooks/colabs con ejemplos de uso y generación de gráficos.
* `/docs`: Documentación auxiliar y referencias matemáticas.

## 📋 Requisitos

El código está escrito en Python 3.8+. Las dependencias principales son:
* `numpy`
* `matplotlib`
* `sympy`
* `pandas`

---
**Nota:** Actualmente se utiliza el modelo de **Greenshields** como estándar por defecto para la calibración operativa.

## 📄 Licencia

Este proyecto se distribuye bajo la licencia **MIT**. Consulta el archivo [LICENSE](LICENSE) para más detalles.

Copyright (c) 2025 Pontificia Universidad Católica de Valparaíso / Universidad del Desarrollo.