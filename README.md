# Práctica IA (RA4 · b+c) — Big Data, análisis, rentabilidad y valoración IA

## 1) Caso y objetivo de negocio
- Empresa/sector (real o ficticia): Netflix (sector streaming audiovisual).
- Problema a resolver: Alta tasa de cancelación de suscripciones (churn) y dificultad para mantener a los usuarios activos.
- Objetivo de negocio (rentabilidad): (reducir costes / aumentar ventas / reducir riesgos / etc.): Reducir cancelaciones y aumentar el tiempo de visualización para incrementar ingresos recurrentes.

## 2) Big Data: recogida masiva de datos
Describe por qué es Big Data (volumen, velocidad, variedad).
- Fuente 1: Historial de visualización (series y películas vistas, duración, pausas).
- Fuente 2: Interacciones en la plataforma (búsquedas, clics, valoraciones).
- Fuente 3: Datos contextuales (dispositivo, franja horaria, ubicación aproximada).
- Volumen/velocidad (estimación): Millones de reproducciones diarias, eventos generados en tiempo real por segundo.
- Formatos (texto, eventos, series temporales, imágenes, etc.): Eventos (clics), series temporales (horas de consumo), texto (búsquedas), datos estructurados (perfil usuario), imágenes/vídeos (metadatos de contenido).

## 3) Tratamiento/análisis: pipeline de datos
Explica el flujo de forma ordenada: 
- Ingesta (captura/eventos): Registro en tiempo real de cada interacción del usuario.
- Limpieza/normalización: Eliminación de datos erróneos, estandarización de categorías de contenido.
- Almacenamiento (data lake/warehouse): para datos brutos de visualización y análisis de negocio.
- Preparación de variables (features): Tiempo medio de visualización, géneros preferidos, frecuencia semanal de uso, probabilidad histórica de abandono.
- Análisis/BI (opcional): Paneles para medir retención, popularidad de contenidos y comportamiento por segmento.

## 4) IA aplicada: modelo y decisión
- Tipo de IA/técnica (clasificación, predicción, recomendación, anomalías, NLP...):  Modelo de predicción de churn (clasificación), sistema de recomendación personalizado.
- Entrada del modelo (qué datos usa): Historial de consumo, frecuencia de uso, géneros favoritos, tiempo desde última conexión.
- Salida del modelo (qué produce): Probabilidad de que el usuario cancele la suscripción, lista personalizada de contenidos recomendados.
- Decisión que habilita (qué hace la empresa con esa salida): Ofrecer promociones o contenido destacado a usuarios con riesgo de abandono, personalizar portada y recomendaciones para aumentar engagement.
  
## 5) Rentabilidad: KPIs antes/después (mínimo 3)
KPI 1 (ingresos/coste/eficiencia):
- Antes: 8 % mensual
- Después: 5 % mensual
- Por qué mejora la rentabilidad: Más clientes mantienen su suscripción, aumentando ingresos recurrentes.

KPI 2:
- Antes: 6 horas
- Después: 8 horas
- Por qué mejora la rentabilidad: Mayor engagement → menor probabilidad de cancelación.

KPI 3:
- Antes: 100 % (base)
- Después: +12 %
- Por qué mejora la rentabilidad: Más retención y mayor fidelización aumentan los ingresos totales.

## 6) Diagrama del pipeline (ASCII o Mermaid)
Usuarios → Eventos en tiempo real → Limpieza/Normalización
        → Data Lake → Preparación de features
        → Modelo IA (Churn + Recomendador)
        → Decisiones (Promos + Personalización)
        → Mayor retención e ingresos

## 7) Riesgos y mitigación
Riesgo 1: Uso indebido de datos personales.
- Mitigación 1: Cumplimiento del Reglamento General de Protección de Datos (RGPD), anonimización y consentimiento informado.

Riesgo 2: Sesgos algorítmicos que limiten diversidad de contenidos.
- Mitigación 2: Auditorías periódicas del modelo y métricas de diversidad y equidad.

## 8) Valoración (criterio c): importancia presente y futura de la IA (10–15 líneas)
- Importancia actual (hoy): La IA es esencial en plataformas como Netflix para personalizar la experiencia del usuario y mantener la competitividad. El volumen de datos generado hace imposible la gestión manual. La personalización aumenta satisfacción y fidelización.
- Importancia futura (3–5 años): La IA evolucionará hacia modelos generativos capaces de crear tráilers personalizados o incluso contenidos adaptados al perfil del usuario. La hiperpersonalización será clave en el mercado del entretenimiento digital.
- Condiciones/limitaciones (datos, costes, regulación, ética, seguridad, empleo): Dependencia de datos de calidad, costes tecnológicos elevados, regulación en privacidad, riesgos éticos y competencia creciente.
- Conclusión razonada: La IA es un pilar estratégico en el sector del streaming. Permite maximizar ingresos recurrentes y mejorar la experiencia del usuario. Su desarrollo futuro consolidará aún más su papel como ventaja competitiva clave.

## 9) Fuentes oficiales (mín. 2)
- Big Data/analítica (enlace oficial): https://digital-strategy.ec.europa.eu/en/policies/data-act
- IA/técnica/modelo (enlace oficial): https://oecd.ai/en/ai-principles
