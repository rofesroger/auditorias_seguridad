# Cybersecurity Portfolio - Roger Rofes Garrido

Repositorio que recopila auditorías de seguridad e investigaciones forenses realizadas en entornos controlados y empresariales.

---

## Objetivo

Mostrar capacidades en:

- Análisis de eventos de seguridad (Windows Logs)
- Investigación de incidentes
- Auditorías de seguridad
- Identificación de causas raíz
- Propuesta de mitigaciones

---

##  Casos de análisis

🔍 Auditoría de Seguridad – ASIX.local

Análisis realizado sobre un entorno Windows Server 2022.

- +1000 eventos analizados
- Detección de ataque de fuerza bruta (4625 → 4624)
- Identificación de accesos no autorizados
- Propuesta de medidas de seguridad

📎 Ver reporte completo → [Reporte completo](https://github.com/rofesroger/auditorias_seguridad/blob/main/Informe%20Auditoria%20de%20seguridad.pdf)

---

🔍 Análisis de Incidente – Apagado Crítico (False Positive)

Investigación de un incidente reportado como posible malware.

- Event ID 41 y 6008 analizados
- Test de memoria sin errores
- Inspección física del equipo

Resultado:
Se descarta infección por malware.

💥 Causa real:
Sobrecalentamiento causado por batería degradada y uso prolongado conectado a corriente.

📎 Ver análisis completo → [Reporte completo](https://github.com/rofesroger/auditorias_seguridad/blob/main/Auditor%C3%ADa%20empresa%20laptop%20mantenimento.pdf)

---

## Tecnologías utilizadas

- Windows Event Viewer
- PowerShell
- Diagnóstico de Hardware
- Microsoft Azure / Intune

---

🔍 Análisis de Incidente – Posible Troyano (Scareware)

Investigación de un incidente reportado como posible infección por malware en un equipo Windows 11 gestionado mediante Intune y Azure.

- Revisión de eventos Microsoft Defender (1116, 1117, 1118 y 5007)
- Análisis del historial de navegación
- Validación del estado del sistema mediante Microsoft Defender
- Investigación de posible campaña de ingeniería social

Resultado:
Se descarta la presencia de malware o indicadores de compromiso en el sistema.

💥 Causa real:
El usuario accedió a una página de descarga no oficial que empleaba técnicas de scareware para simular una infección y promover la contratación o instalación de un supuesto antivirus.

📎 Ver análisis completo 



## 🚀 En desarrollo

Ampliando el portfolio con:

- Laboratorio de detección y respuesta (Blue Team)
- Análisis forense avanzado
- Seguridad en entornos cloud

---
``
