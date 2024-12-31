# 📊 **Análisis de Bombardeos en la Guerra de Corea (1950-1952)**

---

<p align="center">
  <img src="./data/images/korean-war-500810027.jpg" alt="corea" width="600"> 
</p>

---
Este proyecto contiene el análisis detallado de datos históricos relacionados con misiones de bombardeo durante la **Guerra de Corea**, desde 1950 hasta 1952. Los datos se procesaron y analizaron para obtener insights clave sobre las operaciones militares, eficiencia, bajas y uso de armamento.
---

## 🗂️ **Descripción del Proyecto**

1. **Propósito**:
   - Analizar datos históricos de bombardeos para identificar patrones, eficiencia operativa y métricas clave.
2. **Período Analizado**:
   - Desde **junio de 1950** hasta **junio de 1952**.
3. **Fuente de Datos**:
   - Dataset histórico "THOR_KOREAN_DATA.csv", procesado y validado.

---

## 📈 **Resultados Clave**

### ✈️ **Misiones y Operaciones**
- **Número total de misiones**: `12,878`.
- **Bases de lanzamiento más utilizadas**:
  | Base              | Frecuencia |
  |-------------------|------------|
  | **Kadena AFB**    | `1,137`    |
  | **Yokota AFB**    | `912`      |
  | **Clark AFB**     | `49`       |
- **Eficiencia promedio de las misiones**: `98.56%`.

### 🌍 **Países y Bases**
- **Países con mayor actividad**:
  | País         | Frecuencia |
  |--------------|------------|
  | **Okinawa**  | `1,137`    |
  | **Japón**    | `912`      |
  | **Filipinas**| `49`       |

### 🧍‍♂️ **Bajas**
- **Totales**:
  - **Muertos en acción (KIA)**: `116`.
  - **Heridos en acción (WIA)**: `127`.
  - **Desaparecidos en acción (MIA)**: `404`.
- **Promedios por misión**:
  - **KIA por misión**: `0.0090`.
  - **WIA por misión**: `0.0098`.
  - **MIA por misión**: `0.0317`.

### 💥 **Armamento**
- **Total de bombas lanzadas**: `106,392 toneladas`.
- **Total de cohetes disparados**: `238,076`.
- **Total de balas disparadas**: `844,472`.
- **Promedios por misión**:
  - **Bombas**: `8.26 toneladas`.
  - **Cohetes**: `18.49`.
  - **Balas**: `65.57`.

### 📅 **Temporalidad**
- **Meses con más actividad**:
  | Mes        | Misiones   |
  |------------|------------|
  | **Diciembre 1950** | `1,575` |
  | **Enero 1951**     | `1,711` |

---

## 🧐 **Observaciones Clave**
1. **Eficiencia Operativa**:
   - Las bases de **Clark AFB (Filipinas)** y **Kadena AFB (Okinawa)** demostraron altos niveles de eficiencia, con tasas superiores al **97%**.
2. **Impacto de Valores Nulos**:
   - Muchas columnas contienen valores nulos (`NaN`), especialmente en registros de bajas y armamento, lo que puede reflejar inconsistencias históricas o datos no reportados.
3. **Estacionalidad**:
   - La actividad fue más intensa en los meses de invierno (diciembre y enero), posiblemente debido a la estrategia militar y las condiciones climáticas.

---

## 🛠️ **Tecnologías Utilizadas**
- **Lenguaje de Programación**: Python 🐍
- **Bibliotecas**:
  - `Pandas` para manipulación de datos.
  - `Matplotlib` y `Seaborn` para visualización.
  - `Folium` para mapas interactivos.

---

## 📌 **Conclusiones**
- Este análisis revela la importancia estratégica de ciertas bases y meses clave durante la guerra.
- Aunque los datos son extensos, la presencia de valores nulos subraya la necesidad de interpretarlos con cautela.
- Las tasas de eficiencia y el impacto del armamento ofrecen un contexto invaluable para estudios históricos y estratégicos.

---

💡 **¿Qué sigue?**
- Mejorar el manejo de valores nulos para análisis más precisos.
- Explorar correlaciones entre tipo de misión y resultados para estudios futuros.

