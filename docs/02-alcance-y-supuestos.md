# 02 — Alcance y Supuestos

## Alcance

El análisis incluye los siguientes componentes:

- Robots AMR utilizados en logística interna
- Infraestructura de comunicaciones (WiFi hospitalario dedicado)
- Sistema Open-RMF (nodos, middleware, base de datos y API)
- Interacción con personal autorizado
- Procesamiento y almacenamiento de logs operativos
- Evaluación de riesgos derivados del uso del sistema

## No Alcance

Quedan fuera:

- Sistemas médicos clínicos o HIS
- Equipamiento biomédico no conectado
- Robots externos a la red hospitalaria

## Supuestos

- El centro hospitalario cuenta con red segregada para robótica
- Los usuarios cuentan con roles autorizados
- No se procesarán datos de identificación directa de pacientes (solo logs operativos)
