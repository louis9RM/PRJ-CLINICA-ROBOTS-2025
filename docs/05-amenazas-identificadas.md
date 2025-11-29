# 05 — Amenazas Identificadas

Durante el análisis se identificaron amenazas potenciales contempladas en el catálogo de MicroPILAR, agrupadas según la naturaleza del riesgo:

| Categoría | Amenaza | Aplicación al sistema |
|-----------|---------|----------------------|
| Acceso no autorizado | Personal interno o externo intenta acceso indebido al sistema | Alta |
| Fallo de autenticación | Credenciales débiles o suplantación de identidad | Media |
| Interrupción del servicio | Fallos del servidor Open-RMF o red Wi-Fi | Alta |
| Manipulación de datos | Modificación maliciosa de telemetría o rutas de navegación | Alta |
| Robo o pérdida de información | Exfiltración de logs e información operativa | Media |
| Vulnerabilidades técnicas | Software desactualizado, configuraciones débiles | Alta |
| Fallo físico | Daño o pérdida de robots o servidores | Media |
| Malware o ransomware | Infección del sistema RMF o dispositivos conectados | Alta |

## Notas

- La probabilidad de ataque deliberado aumenta por la criticidad del entorno hospitalario.
- Se identificaron posibles atacantes: personal interno, proveedores, actores externos y servicios conectados.
