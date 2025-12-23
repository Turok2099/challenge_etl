---

```markdown
# 📊 Telecom X – Análisis de Evasión de Clientes (Churn)

Este proyecto forma parte del Challenge de Alura Latam y tiene como objetivo analizar la evasión de clientes en una empresa de telecomunicaciones, utilizando técnicas de ETL, limpieza de datos, análisis exploratorio y visualización.

---

## 🎯 Propósito del Análisis

La evasión de clientes (churn) representa una pérdida directa de ingresos y una señal de insatisfacción.  
Este análisis busca:

- Identificar patrones asociados al churn  
- Detectar variables que influyen en la cancelación del servicio  
- Proponer estrategias de retención basadas en datos  
- Preparar el terreno para modelos predictivos futuros  

---

## 📁 Estructura del Proyecto

```
TelecomX/
│
├── TelecomX_Data.json              # Dataset original en formato JSON
├── TelecomX_Challenge.ipynb        # Notebook principal con ETL, EDA y visualizaciones
├── README.md                       # Este archivo
├── /assets                         # Carpeta opcional para guardar gráficos exportados
└── requirements.txt                # (Opcional) dependencias del entorno
```

---

## 📊 Ejemplos de Gráficos e Insights

### 🔹 Churn por Tipo de Contrato
Clientes con contrato mensual tienen un churn del **42.7%**, mientras que los de dos años solo **2.8%**.

### 🔹 Churn por Método de Pago
Electronic Check es el método con mayor churn.  
Métodos automáticos como tarjeta o transferencia tienen menor evasión.

### 🔹 Relación entre Daily Charges y Churn
Clientes con mayor gasto diario tienden a abandonar más.

### 🔹 Cantidad de Servicios Contratados
Clientes con más servicios (seguridad, soporte, streaming) presentan menor churn.

---

## ⚙️ Instrucciones para Ejecutar el Notebook

1. **Clona el repositorio o descarga los archivos**
   ```bash
   git clone https://github.com/tu_usuario/TelecomX.git
   ```

2. **Abre el notebook en Google Colab o Jupyter**
   - Asegúrate de tener acceso al archivo `TelecomX_Data.json`.

3. **Ejecuta las celdas en orden**
   - El notebook incluye:
     - Carga y normalización del JSON
     - Limpieza y transformación
     - Análisis exploratorio
     - Visualizaciones
     - Insights y recomendaciones

4. **Explora los gráficos y modifica parámetros si lo deseas**
   - Puedes ajustar paletas, tamaños, filtros y agregar nuevas visualizaciones.

---

## 🚀 Créditos

Desarrollado por Jorge Castro como parte del Challenge de Alura Latam.  
Incluye prácticas de ETL, análisis exploratorio, visualización con Seaborn y generación de insights accionables.

---

```

