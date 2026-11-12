# Sistema inmótico de detección temprana de incendios
**Control Automático I · Mecatrónica · FP-UNA · 2026**
Propuesta de implementación con Siemens LOGO! V8.0 (12/24RCE) para el laboratorio de electrónica de la Facultad Politécnica, UNA.

## Equipo
- Roddy Iván Romero Centurión
- Miguel Matías Cardozo Barboza
- Emanuel Augusto Duré Obando
- Adolfo Abigail Jara Benítez

**Docentes:** Prof. Ing. Felipe R. Chena C. · Prof. Ing. Christian Ledesma A.

## Qué hace el sistema
Confirma el incendio con humo y temperatura (T ≥ 50 °C, retardo de 3 s), arranca la bomba en estrella–triángulo con protecciones y avisa por Web Server y SMS. Programado en FUP (IEC 61131-3).

## Contenido del repositorio
| Carpeta | Contenido |
|---|---|
| `programa_logo/` | Programa FUP del LOGO! Soft Comfort `[programa_logo.lsc]` |
| `simulador_3d/` | Gemelo digital 3D `[HTML]` |
| `diagramas/` | Diagrama de bloques y esquemas de conexión (.drawio y PDF) |
| `documentacion/` | Documento explicativo |

## Cómo evaluar
1. Botón verde **Code → Download ZIP** y descomprimir.
2. Abrir `programa_logo/[archivo]` con LOGO! Soft Comfort V8 y ejecutar la simulación.
3. Abrir el simulador 3D: `[laboratorio interactivo]`.
4. Escenarios validados: 8 de 8 en LOGO! y en el simulador.

## Estado
Propuesta de implementación; los parámetros del simulador son supuestos y se validarán con maqueta física.
