---
name: Viaje Europa 2026 — Estructura del proyecto
description: App de itinerario estático para abuelos viajando por Europa en abril 2026
type: project
---

App de itinerario de viaje publicada en GitHub Pages (HTML/CSS/JS puro, sin build step).

**Archivos principales:**
- `index.html` — app principal con itinerario por días, cards y modal bottom-sheet
- `data.js` — todos los datos del viaje como array TRIP_DATA + CITY_INFO + TYPE_LABELS
- `style.css` — estilos completos (diseño "Carnet de Voyage")
- `admin.html` — panel admin protegido con contraseña (hardcoded `ADMIN_PASSWORD = "CHANGE_ME"`)
- `docs/README.md` — instrucciones para añadir PDFs

**Datos del viaje:** 30 actividades, 14 días, 5 ciudades: París → Zúrich → Múnich → Viena → Praga (9–22 abril 2026).

**Persistencia:** admin.html guarda cambios en localStorage bajo la key `viaje_europa_data`. index.html lee localStorage primero, con fallback a TRIP_DATA.

**Why:** App para los abuelos políticos del usuario — diseñada para personas mayores en móvil (fuentes grandes, touch targets grandes).
**How to apply:** Mantener accesibilidad y legibilidad en cualquier cambio de UI. Respetar la estructura de datos de data.js al añadir funcionalidades.
