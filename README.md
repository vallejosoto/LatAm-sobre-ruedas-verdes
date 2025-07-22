# ⚡ LatAm sobre ruedas verdes: inteligencia artificial para mapear el camino hacia la neutralidad de carbono 🚲🛴🌎

## 🧠 Descripción del Proyecto

Este proyecto propone una solución basada en **inteligencia artificial (IA)**, específicamente mediante técnicas de **clustering no supervisado** (`K-Means` y `DBSCAN`), para **identificar qué ciudades latinoamericanas presentan mejores condiciones** para implementar sistemas de **micromovilidad eléctrica**, como bicicletas, scooters y vehículos de baja velocidad.

📌 Esta propuesta se enmarca dentro de una **transición energética justa**, promoviendo:
- ⚖️ Equidad territorial
- 🌱 Movilidad sostenible
- 💨 Reducción de emisiones

---

## 📊 Datos Utilizados

Se construyó una **base de datos multivariable** con los siguientes indicadores:

| Indicador | Fuente | Finalidad |
|----------|--------|-----------|
| 💰 PIB per cápita | Banco Mundial | Capacidad económica |
| 🌫️ Emisiones de CO₂ per cápita | Kaggle | Impacto ambiental |
| 👥 Población total | Our World in Data | Tamaño del mercado |
| 🧱 Densidad poblacional | Banco Mundial | Concentración urbana |
| 🚗 Tráfico urbano | Kaggle | Congestión vial |

➡️ Los datos fueron limpiados y normalizados para construir:
- Un **índice de viabilidad por país**
- Un **índice de tráfico urbano por ciudad**

---

## 🧪 Modelamiento y Resultados

Se aplicaron dos técnicas de clustering:

1. **K-Means (k=3)**  
   🔹 Agrupó las ciudades en tres grupos (alto, medio y bajo potencial)  
   ✅ Útil para decisiones estratégicas claras

2. **DBSCAN**  
   🔸 Identificó clústeres densos y casos atípicos  
   🔍 Revela agrupamientos naturales sin estructura jerárquica

📍 **Resultados clave:**
- `K-Means` fue más efectivo por su **claridad interpretativa** y **representación territorial precisa**
- **Ciudades con mayor potencial** detectadas:
  - 🇲🇽 Ciudad de México  
  - 🇨🇴 Bogotá  
  - 🇵🇪 Lima

---

## ✅ Conclusiones

🌍 La **micromovilidad eléctrica** representa una **solución viable y deseable** para América Latina desde el punto de vista:
- Social
- Ambiental
- Económico

🧠 El uso de IA:
- Permite **clasificación objetiva** sin etiquetas predefinidas
- Revela patrones naturales

📌 Aunque la **falta de datos limitó** el número de ciudades incluidas, los resultados permiten:
- **Guiar políticas públicas**
- **Orientar inversiones privadas** hacia territorios con mayor potencial

