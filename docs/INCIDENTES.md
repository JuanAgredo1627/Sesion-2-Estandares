# 🐞 Registro de Incidentes (IEEE 29119-3)

> Propósito: Documentar desviaciones/defectos hallados durante las pruebas.

## 1. Tabla de Incidentes
| ID Incidente | Título | Descripción | Severidad | Estado | Responsable | Versión | Evidencia | Relación (Caso/Req) |
|--------------|--------|-------------|-----------|--------|-------------|---------|-----------|---------------------|
| INC-001      | Error login con “ñ” | 500 en POST /login | Alta | Abierto | Backend | 1.0.3 | /evidencias/inc001.png | CP-002, REQ-001 |
| INC-002      | PDF vacío | Reporte financiero descarga sin contenido | Media | En progreso | Frontend | 1.0.3 | /evidencias/inc002.mp4 | CP-020, REQ-010 |

## 2. Flujo de Estados
- **Abierto → Asignado → En corrección → Verificado → Cerrado**
- Reapertura si no cumple criterios de aceptación.

## 3. Criterios de Severidad
- **Crítica**: caída total, pérdida de datos, seguridad.
- **Alta**: función principal inutilizable sin alternativa.
- **Media**: impacto funcional con workaround.
- **Baja**: cosmetic/UX, textos, mínimos.

## 4. Notas
- Registrar pasos para reproducir, entorno, logs adjuntos, condiciones específicas.
