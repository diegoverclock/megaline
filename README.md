# 📱 Análisis de Planes de Megaline

## 📌 Descripción del proyecto
Este proyecto analiza el comportamiento de clientes de la empresa de telecomunicaciones Megaline, con el objetivo de determinar cuál de sus planes (Surf o Ultimate) genera mayores ingresos.

Se realiza un análisis exploratorio de datos (EDA) considerando variables como consumo de llamadas, mensajes y datos móviles, así como el ingreso mensual por usuario.

---

## 🎯 Objetivos
- Analizar el comportamiento de los usuarios según su plan
- Comparar ingresos generados entre los planes Surf y Ultimate
- Evaluar patrones de consumo (llamadas, SMS y datos)
- Identificar qué plan es más rentable para la empresa

---

## 🗂️ Conjunto de datos
El análisis se basa en los siguientes datasets:

- `users.csv` → Información de usuarios  
- `calls.csv` → Registro de llamadas  
- `messages.csv` → Mensajes enviados  
- `internet.csv` → Consumo de datos  
- `plans.csv` → Información de planes  

---

## 🛠️ Herramientas utilizadas
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 🔧 Proceso del análisis

### 1. Preparación de datos
- Limpieza y transformación de datos
- Conversión de tipos
- Manejo de valores faltantes
- Agregación de datos por usuario y mes

### 2. Análisis exploratorio (EDA)
- Consumo promedio por usuario
- Distribución de llamadas, mensajes y datos
- Comparación entre planes
- Visualización de ingresos mensuales

### 3. Análisis de ingresos
- Cálculo de ingresos por usuario
- Comparación entre planes Surf y Ultimate
- Evaluación de rentabilidad

---

## 📊 Principales hallazgos
- Existen diferencias claras en el consumo entre usuarios de distintos planes
- El plan Ultimate genera mayores ingresos en promedio
- Los usuarios del plan Surf tienden a exceder límites, generando cargos adicionales
- El comportamiento de consumo influye directamente en la rentabilidad

---

## 📈 Conclusiones
El análisis muestra que el plan Ultimate es más rentable en términos de ingresos promedio por usuario.  
Sin embargo, el plan Surf también representa una fuente importante de ingresos debido a cargos adicionales por excedentes.

Estos resultados pueden ayudar a la empresa a:
- Optimizar su estrategia de precios  
- Mejorar la segmentación de clientes  
- Diseñar campañas de marketing más efectivas  

---

## 🚀 Cómo ejecutar el proyecto

1. Clona este repositorio:
```bash
git clone https://github.com/diegoverclock/megaline.git
```

2. Instala las dependencias:
```bash
pip install pandas numpy matplotlib seaborn
```

3. Abre el notebook:
```bash
jupyter notebook
```

---

## 📁 Estructura del proyecto
```
📦 proyecto-megaline
 ┣ 📜 megaline.ipynb
 ┣ 📂 datasets
 ┗ 📜 README.md
```

---

## 💡 Autor
Ing. Diego Alonso Morales Salazar
