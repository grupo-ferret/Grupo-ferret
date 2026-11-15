# Guía de Desarrollo - Grupo Ferret

## Contexto del Proyecto
- *Negocio:* Ferretería industrial y comercial (enfoque Costa Rica y Nicaragua).
- *Stack Tecnológico:* 
  - Frontend: GitHub Pages (index.html con Tailwind CSS y FontAwesome).
  - Base de Datos/CMS: Google Sheets (vía enlace CSV).
  - Automatización: Google Apps Script (registro de búsquedas fallidas con parámetros ?q=).

## Reglas de Trabajo para Claude
1. *Memoria y Contexto:* Mantén siempre presente que trabajamos con un archivo único optimizado (index.html) para evitar romper la estructura de Tailwind o la lógica de caché.
2. *Salidas Limpias:* Proporciona bloques de código completos o diffs precisos. Evita explicaciones redundantes; prioriza la velocidad y la eficiencia de tokens.
3. *Flujo de Cambios:* Cada modificación debe asegurar la compatibilidad con los números de WhatsApp configurados y la moneda local (colones ₡).
