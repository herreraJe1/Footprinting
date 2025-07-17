# 🕵️‍♀️ Recopilación de Información – Supermaxi

## 1. Introducción

Este informe presenta un análisis de footprinting aplicado al sitio web de Supermaxi. Se utilizaron técnicas pasivas para identificar posibles exposiciones de datos.

## 2. Navegación Web

- Sitio inspeccionado: https://www.supermaxi.com  
- Herramientas: F12, DeadLinkChecker  
- Hallazgos: 15 enlaces rotos (404, 403, 401)

## 3. robots.txt

- URL: https://www.supermaxi.com/robots.txt  
- Rutas bloqueadas: `/wp-content/uploads/wpforms/`  
- Sitemap detectado: `/sitemap_index.xml`

## 4. Descarga del Sitio

- Herramienta: HTTrack  
- Archivos inspeccionados: HTML, JS  
- Comentarios encontrados: sin datos críticos

## 5. Metadatos

- Herramienta: FOCA  
- Documentos PDF en directorios 2019, 2022, 2023  
- Tamaños: 53.57 KB – 12.68 MB
## 6. Google Dorks

- Operadores: `site:`, `inurl:`, `filetype:`, `cache:`  
- Archivos públicos encontrados: PDF, formularios

## 7. Correos y filtraciones

- Ejemplo: `gerencias@favorita.com`  
- No se detectaron filtraciones en Have I Been Pwned

## 8. Conclusión

La información pública puede ser usada para mapear vectores de ataque. Aunque no se detectaron fallos graves, se evidenció exposición de rutas y metadatos.
