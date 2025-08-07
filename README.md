# 📊 Análisis de Línea 144 (Enero - Junio 2023)

Este proyecto presenta un análisis exploratorio y de segmentación sobre los registros de la **Línea 144** en Argentina, correspondiente al período **enero a junio de 2023**. La Línea 144 brinda atención, contención y asesoramiento a personas en situación de violencia por razones de género.

📁 **Fuente de datos**: [datos.gob.ar](https://datos.gob.ar)

---

## 🔍 Contexto

La **Línea 144** es un servicio gratuito y confidencial que funciona los 365 días del año, las 24 horas del día. Brinda asistencia en situaciones de:

- Violencia física
- Violencia psicológica
- Violencia sexual
- Violencia económica y patrimonial
- Violencia simbólica

Además, contempla modalidades como la violencia doméstica, institucional, laboral, mediática, obstétrica, contra la libertad reproductiva y otras.

---

## 🎯 Objetivos del proyecto

- Obtener estadísticas sobre el género de las personas en situación de violencia y de las personas agresoras.
- Analizar la distribución de casos por provincia y por mes.
- Identificar los tipos y modalidades de violencia más frecuentes.
- Evaluar la relación/vínculo más común entre víctima y agresor/a.
- Observar los grupos etarios más afectados.
- Aplicar **Machine Learning no supervisado (clusterización)** para agrupar características comunes de los casos.

---

## 🧠 Técnicas aplicadas

- Limpieza y transformación de datos con **pandas**
- Visualización con **matplotlib** y **seaborn**
- Agrupamiento de datos y análisis porcentual
- Aplicación de **algoritmos de clustering** (como KMeans)
- Interpretación de resultados orientada a posibles políticas públicas

---

## 🗂️ Estructura del notebook

1. Introducción y contexto
2. Exploración inicial del dataset
3. Limpieza y tratamiento de variables
4. Análisis descriptivo
5. Visualizaciones clave
6. Aplicación de modelos de agrupamiento
7. Conclusiones y reflexiones

---

## 📌 Requisitos

Para ejecutar este notebook necesitarás tener instalado:

- Python 3.8+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- jupyter (opcional para ejecución local)

Podés instalar los requerimientos con:

```bash
pip install -r requirements.txt
