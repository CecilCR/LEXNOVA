# LexNova

**Simulador interactivo de decisiones organizacionales para estudiantes de Administración y Gestión.**

LexNova sitúa al estudiante en la dirección de un estudio legal que atraviesa un año de transformación. A lo largo de cuatro trimestres, debe tomar doce decisiones reales —sobre clientes, capital, expansión y regulación— y observar cómo cada una afecta los indicadores del estudio, la matriz FODA acumulada y el balance final del año.

El objetivo no es maximizar ningún indicador. El objetivo es que el estudiante **comprenda que cada decisión tiene costos directos y costos de oportunidad**, y que las consecuencias organizacionales no se reducen a lo financiero.

---

## Tabla de contenidos

- [¿Para quién es?](#para-quién-es)
- [¿Qué se aprende?](#qué-se-aprende)
- [Cómo usarlo](#cómo-usarlo)
- [Estructura de la simulación](#estructura-de-la-simulación)
- [Análisis posteriores](#análisis-posteriores)
- [Aspectos técnicos](#aspectos-técnicos)
- [Decisiones de diseño](#decisiones-de-diseño)
- [Estado del proyecto](#estado-del-proyecto)
- [Licencia](#licencia)

---

## ¿Para quién es?

- **Estudiantes** de Administración de Empresas y de Gestión de las Relaciones en las Organizaciones, de media carrera o perfil ejecutivo.
- **Docentes** que buscan un caso práctico para talleres de toma de decisiones, análisis FODA o gestión del cambio.
- **Diseñadores instruccionales** interesados en simuladores de bajo costo técnico y alta carga pedagógica.

No requiere conocimientos previos de Derecho, finanzas, tecnología ni compliance. Los términos técnicos se explican la primera vez que aparecen.

---

## ¿Qué se aprende?

Al completar la simulación, el estudiante puede:

- Analizar situaciones organizacionales realistas.
- Identificar alternativas de decisión y comparar sus implicaciones.
- Reconocer que cada alternativa implica beneficios, riesgos y costos.
- Entender que los indicadores financieros son contexto, no objetivo.
- Distinguir costos directos (inversión, opex) de costos de oportunidad.
- Reflexionar sobre las decisiones tomadas y las alternativas descartadas.
- Reconocer que algunas debilidades estructurales no se resuelven en un año.

---

## Cómo usarlo

### Uso directo

1. Descargar el archivo `index.html`.
2. Abrirlo en cualquier navegador moderno (Chrome, Firefox, Edge, Safari).
3. No requiere servidor, instalación ni conexión a internet.

El progreso del estudiante se guarda localmente en el navegador. Al cerrar y volver a abrir, la reflexión escrita se conserva.

### Flujo de la simulación

```
Q1 → consecuencia → Q2 → consecuencia → Q3 → consecuencia → Q4 → consecuencia
                                                                     ↓
                                                        Reporte final del año
                                                                     ↓
                                                        Análisis contrafactual
                                                                     ↓
                                                        Reflexión (4 preguntas)
                                                                     ↓
                                                        Exportar resumen (.txt)
```

En cada trimestre, el estudiante:

1. Lee una situación organizacional.
2. Compara tres alternativas.
3. Ve, en cada alternativa: beneficio esperado, riesgo principal y costo declarado.
4. Elige una.
5. Lee la consecuencia simulada.
6. Avanza al siguiente trimestre.

---

## Estructura de la simulación

### Los cuatro trimestres

| Trimestre | Tema | Dilema |
|---|---|---|
| **Q1** | Mercado | Un cliente recurrente migra a una plataforma legaltech. ¿Bajar tarifas, digitalizar la revisión de contratos o reenfocar la cartera? |
| **Q2** | Capital | El estudio tiene un fondo de reserva. ¿Mantenerlo intacto, invertir en una plataforma digital o construir software propio? |
| **Q3** | Expansión | Llega una licitación regional. ¿Derivar a estudios locales, formar una sociedad conjunta o comprar estudios ya operando? |
| **Q4** | Crisis | Se aprueba una regulación sobre origen de fondos. ¿Cumplir recortando, diversificar hacia compliance o aceptar la reestructuración? |

### Matriz FODA acumulada

Cada decisión añade factores a la matriz FODA visible en pantalla. La matriz arranca con cuatro factores del punto de partida y se enriquece a lo largo del año. Los factores se agrupan por lote (punto de partida, Q1, Q2, Q3, Q4) y por tipo (financiero, comercial, tecnológico, humano, operativo).

Al final del año, la combinación de fortalezas, debilidades, oportunidades y amenazas determina un **arquetipo estratégico** (ofensivo, defensivo, de reorientación o de supervivencia). El arquetipo es una etiqueta orientativa, no una calificación.

### Indicadores

Se muestran tres indicadores del estudio durante toda la simulación:

- **Margen operativo** (%): ganancia por sol facturado.
- **Caja** (USD): flujo de caja disponible.
- **Riesgo de concentración** (%): dependencia de clientes clave.

Acompañados de una nota que aclara: **los indicadores son contexto, no objetivo. No hay combinación óptima.**

---

## Análisis posteriores

### Reporte final

Al cerrar el año, el estudiante accede a un **balance de consecuencias** que incluye:

- El arquetipo estratégico resultante.
- Las decisiones que llevaron a ese patrón.
- La evolución financiera del año (gráfico de caja por trimestre).
- El balance visible de fortalezas, debilidades, oportunidades y amenazas.
- El reconocimiento explícito de que algunas debilidades estructurales no se resuelven en un año.

### Análisis contrafactual

Sección que compara la decisión tomada en cada trimestre con las alternativas no elegidas. Para cada alternativa descartada, muestra:

- Beneficio principal.
- Riesgo principal.
- Costo declarado.

El objetivo no es identificar la alternativa perfecta, sino comparar qué se habría ganado, qué se habría sacrificado y qué riesgo adicional se habría asumido.

### Reflexión final

Cuatro preguntas abiertas, sin mínimo de extensión, con persistencia automática:

1. ¿Qué decisión produjo el beneficio más importante para la organización y por qué?
2. ¿Qué riesgo aceptaste o decidiste no aceptar al tomar una de tus decisiones?
3. ¿Qué consecuencia no habías previsto o subestimaste y qué información adicional habrías necesitado?
4. ¿Qué aprendiste sobre la relación entre beneficios, riesgos y recursos al gestionar un proceso de cambio?

### Exportación

El resumen descargable (`.txt`) incluye decisiones, indicadores finales, evolución de caja, arquetipo estratégico, alternativas relevantes, respuestas de reflexión y matriz FODA completa.

### Historial

Cada corrida completada se guarda en el navegador con fecha, arquetipo final, indicador de crisis (si aplica) y las decisiones tomadas. Permite comparar varias partidas.

---

## Aspectos técnicos

### Estructura

```
lexnova/
├── index.html      # Aplicación completa (HTML + CSS + JS embebidos)
└── README.md       # Este archivo
```

Un solo archivo, sin dependencias, sin build, sin servidor.

### Compatibilidad

- Navegadores modernos con soporte de ES6 y `localStorage`.
- Escritorio, tablet y móvil (diseño adaptable).
- Navegación por teclado.
- Persistencia local (el progreso no sale del dispositivo del estudiante).

### Accesibilidad

- Cuadrantes FODA accesibles por teclado.
- Áreas de texto etiquetadas y descritas.
- Modal de confirmación con roles ARIA.
- Contraste suficiente en todos los textos.
- Estados de foco visibles.

### Privacidad

LexNova no envía datos a ningún servidor. Todo el progreso (decisiones, reflexión, historial) se guarda en el `localStorage` del navegador del estudiante. Si el estudiante borra los datos del navegador, el progreso se pierde.

---

## Decisiones de diseño

Estas son las decisiones pedagógicas y técnicas que definen la herramienta. Se documentan porque no son obvias y conviene respetarlas en futuras modificaciones.

### No hay índice de calidad único

No se calcula un puntaje que determine si las decisiones fueron "buenas" o "malas". El resultado se interpreta como un balance de consecuencias. Un ICD basado en resultados financieros reduciría el ejercicio a optimización, lo cual contradice el propósito pedagógico.

### Los indicadores no son el objetivo

Los tres indicadores (margen, caja, concentración) son contexto del estado del estudio, no metas a maximizar. El estudiante puede terminar el año con margen alto y caja baja, o viceversa, y ninguna combinación es "la correcta".

### Un dilema por trimestre

Cada trimestre introduce un único desafío. No se añaden dilemas paralelos dentro de una misma etapa, porque incrementan la carga cognitiva sin mejorar el aprendizaje.

### El costo de oportunidad se trabaja en el contrafactual

La pantalla de decisión muestra cinco bloques por opción (título, descripción, beneficio, riesgo, costo). Añadir un sexto bloque con "lo que se deja de lado" sobrecargaría la pantalla. El costo de oportunidad se explora después, en el análisis contrafactual, donde el estudiante ya tomó la decisión y puede comparar.

### Sin mínimo de extensión en la reflexión

Las cuatro preguntas se responden libremente. No se exige un mínimo de líneas ni de caracteres. La profundidad no se mide en longitud.

### Continuidad narrativa

El proyecto de norma sobre compliance que aparece como oportunidad en el punto de partida se materializa en Q4 como regulación aprobada. No se introducen sorpresas: lo que aparece en la matriz al inicio se concreta o se tensiona a lo largo del año.

### Debilidades estructurales

Algunas debilidades del estudio (por ejemplo, la dependencia de horas facturables) no se resuelven en el horizonte de un año. La herramienta lo reconoce explícitamente en el reporte final. No es una carencia del diseño: es parte del aprendizaje.

---

## Estado del proyecto

**Versión actual:** 2.0

**Estado:** estable, listo para uso en aula.

Todas las mejoras identificadas en la auditoría interna están implementadas, salvo una deuda técnica documentada:

- Los manejadores de eventos de algunos botones están definidos de forma inline. No afecta la experiencia del estudiante ni la funcionalidad. Se puede migrar a delegación de eventos en una futura iteración.

### Qué no es LexNova

- No es una evaluación con puntaje. No genera calificaciones.
- No es una simulación financiera completa. Las cifras son simplificaciones pedagógicas.
- No pretende ser exhaustiva. Cubre cuatro dilemas representativos de un año de gestión, no todas las decisiones posibles.
- No reemplaza el trabajo del docente. Es un insumo para el taller, no un sustituto.

---

## Licencia

[Especificar licencia según preferencia del autor]

Por defecto, todo el contenido de este repositorio se publica bajo [Creative Commons BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) o [MIT](https://opensource.org/licenses/MIT), a elección del autor.

---

## Créditos

**Diseño pedagógico, contenido y desarrollo:** [Nombre del autor o institución]

**Contexto:** Herramienta desarrollada para talleres de Administración de Empresas y Gestión de las Relaciones en las Organizaciones.

Si usas LexNova en tu curso, taller o investigación, se agradece la mención.
