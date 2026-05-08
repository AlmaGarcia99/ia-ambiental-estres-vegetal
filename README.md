# IA Ambiental — Estrés Vegetal y Prevención de Riesgo

<div align="center">

# IA Ambiental: Del Estrés Vegetal a la Prevención de Incendios Forestales

### Monitoreo ambiental + Machine Learning + Prevención ecológica


---

# Visión del Proyecto

Este proyecto explora cómo la Inteligencia Artificial puede utilizarse para detectar condiciones de estrés ambiental antes de que ocurra un problema mayor.

La idea inicia con una planta y variables simples como:

* humedad
* temperatura
* viento
* luz solar

Pero la lógica puede escalar posteriormente hacia:

* monitoreo ecológico
* agricultura inteligente
* prevención de incendios forestales
* sistemas de alerta ambiental

---

# ¿Qué hace este sistema?

El modelo analiza patrones ambientales y clasifica niveles de riesgo utilizando Machine Learning.

## Variables analizadas

| Variable        | Descripción           |
| --------------- | --------------------- |
| Humedad      | Humedad del suelo     |
| Temperatura  | Temperatura ambiental |
| Viento       | Intensidad del viento |
| Luz solar    | Exposición solar      |

---

# ⚡ Pipeline del proyecto

```text
Sensores / Datos
        ↓
Análisis ambiental
        ↓
Visualización de patrones
        ↓
Machine Learning
        ↓
Predicción de riesgo
        ↓
Prevención
```

---

# Visualización Ambiental

## Relación entre temperatura y humedad

A mayor temperatura:

* disminuye la humedad
* aumenta el estrés ambiental
* incrementa el riesgo potencial


---

# Machine Learning

El sistema utiliza:

## Random Forest Classifier

El modelo aprende patrones ambientales a partir de datos históricos y clasifica:

| Nivel | Significado    |
| ----- | -------------- |
| 0     | Riesgo bajo    |
| 1     | Riesgo medio   |
| 2     | Riesgo alto    |
| 3     | Riesgo crítico |

---

# Ejemplo de Predicción

## Entrada

```python
nuevo_dato = {
    "humedad": 35,
    "temperatura": 30,
    "viento": 20
}
```

## Resultado

```text
[3] → Riesgo crítico
```

---

# Aplicación en plantas

Cuando la IA detecta:

* baja humedad
* temperatura elevada
* estrés ambiental

El sistema puede generar alertas como:

```text
Agregar agua
```

---

# Aplicación Forestal

La misma lógica puede escalarse a ecosistemas forestales.

## Variables ambientales críticas

* sequedad
* temperatura extrema
* viento fuerte
* baja humedad

## Resultado esperado

```text
Alta probabilidad de incendio forestal
```

---

# Tecnologías utilizadas

```text
Python
Pandas
Matplotlib
Scikit-learn
Jupyter Notebook
GitHub Pages
```

---

# Estructura del proyecto

```text
📁 ia-ambiental-estres-vegetal
 ┣ 📄 analisis_ia_ambiental.ipynb
 ┣ 📄 dataset_estres_vegetal_cdmx.csv
 ┣ 📄 dataset_estres_vegetal_cdmx.xlsx
 ┗ 📄 README.md
```

---

# Futuras mejoras

* dashboards interactivos
* APIs climáticas
* monitoreo satelital
* modelos predictivos avanzados
* alertas en tiempo real
* mapas de riesgo forestal

---

# Filosofía del Proyecto

La prevención ambiental comienza detectando pequeñas señales antes de que ocurra el desastre.

Una planta puede mostrar estrés antes de secarse.
Un bosque también puede mostrar señales antes de un incendio.

La Inteligencia Artificial puede ayudarnos a detectar esas señales a tiempo.

---

<div align="center">

# IA + Naturaleza + Prevención

### Tecnología aplicada para comprender y proteger ecosistemas

</div>
