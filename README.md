# 🧠 Proyecto Final - Machine Learning
## Analisis de sentimientos en conversaciones whatsapp :

## 📌 Definición del Problema :
Actualmente, el gimnasio enfrenta deserciones de cclientes que, en muchos casos, podrían haberse anticipado. A través del análisis de las conversaciones de WhatsApp entre el dueño y los clientes, se busca identificar patrones de comunicación que preceden a estas bajas.
### 🎯 Objetivo :
Detectar señales tempranas de deserción en la comunicación para implementar acciones de retención efectivas.
## 📌 Justificación
Identificar patrones previos a la deserción de clientes tiene un alto impacto potencial en la retención. Prevenir una baja puede ser más económico que adquirir un nuevo cliente. Con esta información, el gimnasio puede:
- Ajustar el estilo de comunicación.
- Identificar clientes en riesgo antes de que se vayan.
- Medir la efectividad de cambios en la forma de interactuar.
## 📌 Stakeholders Clave
- **Dueño del gimnasio:** Principal interesado en reducir la tasa de deserción y optimizar la experiencia del cliente.
- **Clientes:** Afectados directamente por la calidad de la comunicación y la atención recibida.
- **Equipo de soporte (opcional en futuro):** Podría implementar mejoras basadas en las recomendaciones.
## 📌 Acciones Pre-modelo (Análisis previo al ML)
Antes de entrenar un modelo, es esencial realizar:
1. **Análisis exploratorio del texto:**
   - Frecuencia de palabras.
   - Tono emocional (positivo, negativo, neutral).
   - Presencia de quejas, silencios, o rupturas abruptas en la conversación.
2. **Clasificación de mensajes por roles:**
   - Cliente vs. dueño: ¿Quién envía qué tipo de mensaje?
3. **Evaluación de estilo del dueño:**
   - ¿Su comunicación es empática, reactiva, cortante?
   - ¿Aumenta el riesgo de deserción?
   - 
## 📌 Documentación sobre los Datos
- **Origen:** Exportación de chats de WhatsApp.
- **Formato:** Texto plano (.txt).
- **Período cubierto:** 2023, 2024 y lo que va de 2025.
- **Estructura:** Conversaciones con múltiples clientes; se preservó el contenido completo, sin multimedia, para asegurar mayor cantidad mensajes en el tiemppo.
- **Procesamiento:** Conversión a DataFrame, limpieza, normalización, anonimización, análisis exploratorio.

## 📌 Metodología y Despliegue
- **Metodología de trabajo:** Scrum (aplicada de forma individual), organizada en sprints semanales. Esta metodología me permite una planificación clara, entregas regulares, me es muy util para organizarme.
- **Gestión del proyecto:** GitHub, con seguimiento del código, versión de los entregables y documentación.
- **Despliegue (previsto):**
  - Notebooks documentados para exploración y modelado.
