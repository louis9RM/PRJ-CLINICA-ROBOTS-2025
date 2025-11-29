# 04 — Inventario de Activos

El siguiente inventario corresponde a los activos identificados durante el análisis de riesgos realizado con MicroPILAR. Los activos están clasificados según su naturaleza (servicios, infraestructura, datos, personal y terceros).

| Código | Activo | Categoría | Tipo | Criticidad |
|--------|--------|------------|------|------------|
| ACT-RMF-01 | Sistema de Coordinación Central Open-RMF | Servicio | Software | Alta |
| ACT-RBT-01 | Flota de Robots Autónomos de Transporte Clínico | Hardware / Servicio | Físico | Alta |
| ACT-SRV-01 | Servidor Local del Sistema Open-RMF | Hardware | Infraestructura | Alta |
| ACT-DBT-01 | Base de Datos Operacional del Sistema RMF | Datos / Software | Crítico | Alta |
| ACT-NET-01 | Red Wi-Fi Operacional Dedicada a la Flota Robótica | Comunicaciones | Infraestructura | Alta |
| ACT-SEC-01 | Firewall Institucional y Control de Acceso de Red | Seguridad / Infraestructura | Lógica | Media |
| ACT-SEC-02 | VPN Institucional de Acceso Seguro | Seguridad / Infraestructura | Lógica | Media |
| ACT-3RD-01 | Soporte Externo y Comunidad Open-RMF | Servicio Externo | Terceros | Media |

## Observaciones

- Los activos críticos están relacionados con la operación continua del sistema robótico hospitalario.
- La información gestionada incluye logs operacionales, rutas de navegación, telemetría y estado técnico del robot.
- La disponibilidad del sistema es esencial para garantizar continuidad logística hospitalaria.
