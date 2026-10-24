# Análisis Forense a Memoria USB - Caso de Filtración Interna

Caso práctico hecho para la carrera de Seguridad Informática Forense.

## De qué va
En una empresa ficticia, un empleado renunció y dejó una USB de 16GB. Sospecha de fuga de información de clientes. Mi trabajo fue ver si borró algo y recuperarlo manteniendo la cadena de custodia.

## Herramientas
- FTK Imager 4.7 - imagen .E01
- Autopsy 4.20 - análisis
- USBDeview y LECmd - historial de USBs
- HashMyFiles - hashes

## Proceso
1. Cadena de custodia: etiqueta EVIDENCIA-001, foto, bloqueo de escritura.
2. Imagen forense con FTK Imager en formato E01.
3. Análisis en Autopsy: encontré 47 archivos borrados, 31 recuperables tipo clientes_2024.xlsx, modificados el 21/10/2026 11:43 PM. Rastro de Eraser 6.2 usado 3 veces.

## Conclusión
Sí hubo intento de borrar evidencia. Se recuperó info sensible.

Hecho por Ciberplata - 2026
