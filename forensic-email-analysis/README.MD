# Email Forensic Analysis

## Descripción

Análisis forense de un correo electrónico sospechoso para determinar su autenticidad.

## Objetivo

Identificar si el correo representa un intento de fraude o phishing.

## Metodología

Se aplicó un proceso forense estructurado:

1. Preparación
2. Evaluación
3. Adquisición
4. Preservación
5. Análisis
6. Presentación

## Herramientas utilizadas

- Visor de archivos .eml
- HashCalc
- VirusTotal
- MXToolbox

## Análisis realizado

### Verificación de integridad

- El hash SHA-256 del archivo no coincide con el original
- Indica posible manipulación de evidencia

### Análisis de encabezados

- Servidor de envío identificado
- IP asociada a servicios de correo público

### Indicadores de fraude

- Mensaje de donación millonaria
- Uso de lenguaje emocional
- Múltiples destinatarios ocultos
- Cuenta de correo genérica

## Hallazgos

- El correo presenta características típicas de scam
- Se detecta posible alteración del archivo
- Coincide con patrones de fraude conocidos

## Conclusión

El correo es fraudulento y corresponde a una estafa tipo “herencia falsa”.

## Recomendaciones

- No responder al correo
- Eliminar el mensaje
- Capacitar usuarios en phishing
- Implementar filtros de seguridad

