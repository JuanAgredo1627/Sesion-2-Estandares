# ✅ Casos de Prueba (IEEE 29119-3)

> Propósito: Definir casos ejecutables con entradas, pasos y resultados esperados.

## 1. Convenciones
- **Estado**: Pendiente / Ejecutado / Bloqueado
- **Resultado**: OK / Falla
- **Severidad** (si falla): Crítica / Alta / Media / Baja

## 2. Tabla de Casos
| ID Caso | Título | Precondiciones | Pasos de Ejecución | Datos | Resultado Esperado | Trazabilidad (REQ/CPD) |
|---------|--------|----------------|--------------------|-------|--------------------|-------------------------|
| CP-001  | Login válido | Usuario activo | 1)… 2)… 3)… | u:…, p:… | Acceso exitoso | REQ-001, CPD-001 |
| CP-002  | Login inválido | Usuario existente | 1)… 2)… | u:…, p:inv | Mensaje de error | REQ-001, CPD-002 |

> **Nota:** si un caso requiere varios conjuntos de datos, puedes duplicarlo con sufijos (CP-001-a, CP-001-b) o usar una tabla de parámetros.
