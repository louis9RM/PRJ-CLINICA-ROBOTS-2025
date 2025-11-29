# 08 — RGPD y Privacidad

Este proyecto implica el uso de robots autónomos en entornos hospitalarios. Si bien el sistema no gestiona directamente datos clínicos de pacientes, sí procesa y almacena información operacional que puede considerarse dato personal indirecto (metadatos, trazabilidad, usuario operador).

## Análisis legal aplicable

| Norma | Aplicación |
|--------|------------|
| Reglamento (UE) 2016/679 — RGPD | Aplicación obligatoria debido a tratamiento de datos personales operacionales |
| ISO/IEC 27701 | Extensión de SGSI para Gestión de Privacidad |
| ENS — Seguridad de la Información | Cumplimiento en entornos institucionales |

## Categorías de datos procesados

| Tipo | Ejemplo | Observación |
|------|---------|-------------|
| Identificación técnica | ID de robot, IP, MAC, logs | No identifican persona por sí solos |
| Registro de operación | usuario que ejecuta la acción en Open-RMF | Datos personales asociados a roles |
| Telemetría | rutas, estado, localización | No contiene información médica |
| Seguridad | accesos, auditoría | Obligatorio por cumplimiento normativo |

## Evaluación de Impacto (DPIA)

Se identifican los siguientes riesgos de privacidad:

| Riesgo | Descripción | Nivel |
|--------|-------------|------|
| Perfilado implícito | Log de acciones puede identificar hábitos del personal | Medio |
| Trazabilidad de ubicación | Ubicación exacta del robot y responsable | Medio |
| Técnicas de identificación indirecta | Correlación entre parámetros técnicos y persona | Bajo |

## Salvaguardas aplicadas

✔ Minimización de datos  
✔ Retención limitada  
✔ Cifrado en tránsito y reposo  
✔ Control de accesos basado en roles (RBAC)  
✔ Auditoría continua  
✔ Registro DPIA en versión del repositorio

## Conclusión

No se identifica tratamiento de datos médicos ni información de pacientes, por lo que no aplica consentimiento explícito.

Sin embargo, se requiere:

- Registro oficial de tratamiento
- Contrato de encargado externo para soporte Open-RMF
- Registro DPIA
