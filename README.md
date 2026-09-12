# LexNova · Simulación Estratégica FODA & Gestión de Decisiones

**LexNova** es una herramienta interactiva web (*branching scenario*) diseñada para entornos de educación ejecutiva, programas de posgrado y talleres corporativos. Permite experimentar la toma de decisiones gerenciales mediante un modelo dinámico donde la Matriz FODA y los estados financieros evolucionan en tiempo real a lo largo de un año fiscal (Q1-Q4).

---

## 📌 Características Principales

*   **Línea de Tiempo Fiscal (Q1–Q4):** Simulación estructurada en 4 trimestres que abarcan disrupción de mercado, asignación de capital, expansión regional y gestión de crisis regulatoria/talento.
*   **Matriz FODA Dinámica por Dimensiones:** Clasificación automática de factores internos y externos ponderados por ámbito: Financiero, Comercial, Tecnológico, Humano y Operativo.
*   **Modelo de Flujo de Caja y Opex Recurrente:** Simulación de impacto financiero directo en liquidez ($), margen operativo (%) y riesgo de concentración de clientes (%). Considera la acumulación de costos fijos mensuales (Opex) y desembolsos de capital únicos.
*   **Índice de Calidad de Decisión (ICD):** Métrica sintética ponderada (0–100) que evalúa la solvencia, la sostenibilidad del margen y la gestión del riesgo de la firma[cite: 1].
*   **Análisis Contrafactual Integrado:** Algoritmo que identifica la **Decisión Determinante** del caso y muestra qué alternativas habrían cambiado el arquetipo estratégico final[cite: 1].
*   **Visualización SVG:** Gráfico dinámico de la trayectoria trimestral de la caja[cite: 1].
*   **Exportación de Resultados:** Generación de reporte completo en formato texto (`.txt`) con las decisiones tomadas, KPIs finales, gráfico de flujo, arquetipo TOWS/CAME y preguntas de reflexión pedagógica[cite: 1].

---

## 📐 Arquetipos Estratégicos (Modelo TOWS/CAME)

La herramienta evalúa la suma de pesos acumulados en la matriz y clasifica el resultado en 4 patrones gerenciales[cite: 1]:

| Arquetipo | Dominancia Interna | Dominancia Externa | Enfoque de Gestión |
| :--- | :--- | :--- | :--- |
| **FO · Estrategia Ofensiva** | Fortalezas (F ≥ D) | Oportunidades (O ≥ A) | Crecimiento y captura de mercado apalancado en capacidades[cite: 1]. |
| **FA · Estrategia Defensiva** | Fortalezas (F ≥ D) | Amenazas (O < A) | Protecciones y blindaje interno ante riesgos del entorno[cite: 1]. |
| **DO · Reorientación** | Debilidades (F < D) | Oportunidades (O ≥ A) | Reestructuración de capacidades para aprovechar el entorno[cite: 1]. |
| **DA · Supervivencia** | Debilidades (F < D) | Amenazas (O < A) | Contención de daños y minimización de pérdidas[cite: 1]. |

---

## 🛠️ Tecnologías Utilizadas

*   **HTML5 / CSS3:** Interfaz responsive con variables CSS, arquitectura tipo *Dashboard/Paper* y soporte para pantallas táctiles/móviles[cite: 1].
*   **JavaScript Vanilla (ES6+):** Sin dependencias ni *frameworks* externos. Ejecución 100% del lado del cliente[cite: 1].
*   **SVG Native:** Renderizado dinámico de la gráfica de flujo de caja trimestral[cite: 1].
*   **Web Storage API:** Persistencia local del historial de corridas anteriores (`localStorage`)[cite: 1].

---

## 🚀 Instalación y Uso

Al ser una aplicación autosuficiente de un solo archivo, no requiere instalación de dependencias ni servidores como Node.js, Python o PHP[cite: 1].

1. **Clonar el repositorio:**
   ```bash
   git clone [https://github.com/tu-usuario/lexnova-foda-simulation.git](https://github.com/tu-usuario/lexnova-foda-simulation.git)
