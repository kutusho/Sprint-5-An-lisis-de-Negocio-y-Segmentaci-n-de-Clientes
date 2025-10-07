# Sprint 5 – Análisis de Negocio y Segmentación de Clientes

## 📄 Descripción
Este proyecto forma parte del Sprint 5 del Bootcamp de **Data Analytics – TripleTen**.  
El objetivo principal fue **analizar el comportamiento de los clientes de una empresa de suscripción digital** para identificar segmentos rentables, calcular métricas clave (LTV, CAC, ROI) y proponer estrategias de retención.

Se desarrolló un pipeline analítico completo desde la carga de datos hasta la visualización de cohortes y métricas de negocio.

---

## 🎯 Objetivo
Determinar qué cohortes de usuarios y qué canales de adquisición generan **mayor valor a largo plazo (LTV)** y evaluar el **retorno de inversión (ROI)** de cada segmento.

---

## 🧩 Contexto del caso
Una empresa SaaS busca entender su crecimiento y la rentabilidad de sus campañas de marketing.  
Para ello, se analizaron los datos de clientes, transacciones y gastos publicitarios a lo largo de varios meses.

---

## 🧠 Metodología

1. **Carga y limpieza de datos**
   - Archivos: `visits.csv`, `orders.csv`, `costs.csv`
   - Conversión de fechas, validación de duplicados y formato de columnas.

2. **Cálculo de métricas clave**
   - **Conversion Rate (CR)** = `orders / visits`
   - **Average Revenue per User (ARPU)** = `revenue / users`
   - **Customer Lifetime Value (LTV)** = `revenue / unique customers`
   - **Customer Acquisition Cost (CAC)** = `marketing_spend / new_customers`
   - **ROI** = `(LTV – CAC) / CAC`

3. **Análisis de cohortes**
   - Agrupación por mes de adquisición.
   - Seguimiento del comportamiento de retención y gasto promedio en el tiempo.

4. **Visualización**
   - Gráficos de cohortes de retención, evolución del LTV y comparativas por canal.
   - Herramientas: Matplotlib, Seaborn.

---

## 📊 Resultados principales

- El **canal Organic Search** mostró el **mejor ROI ( +68 %)**.  
- El **canal Paid Ads** tuvo el costo de adquisición más alto ( CAC ≈ 25 USD ) con ROI negativo.  
- Las cohortes del **Q2 2023** mostraron una **retención superior al 40 % a los 3 meses**, indicando usuarios más leales.  
- La relación **LTV/CAC > 3** se consideró umbral para rentabilidad sostenida.

---

## 📈 Conclusiones
El análisis permitió identificar los **canales más eficientes** y las **cohortes más rentables**.  
Se recomienda priorizar la inversión en marketing orgánico y referidos, así como fortalecer la retención posventa mediante comunicación personalizada.

---

## 🧰 Herramientas y tecnologías
- **Python:** pandas, numpy, matplotlib, seaborn, datetime  
- **Análisis:** Cohortes, ROI, LTV, CAC, retención, conversion rate  
- **Control de versiones:** Git · GitHub  
- **Visualización:** Gráficos de cohortes y evolución temporal

---

