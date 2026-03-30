---
name: Viaje Europa — Dirección de diseño
description: Sistema visual "Carnet de Voyage" para la app de itinerario
type: project
---

Diseño "Carnet de Voyage" — diario de viaje elegante y cálido.

- **Tipografía:** Playfair Display (headers/ciudades) + Nunito (cuerpo)
- **Paleta:** fondo cálido `#FAFAF8`, acento terracota `#C4793A`, verde bosque `#2C4A3E`
- **Cards:** borde izquierdo de color según tipo de actividad, esquinas redondeadas 14px, sombra suave
- **Modal:** bottom-sheet que sube desde abajo, con handle drag, swipe-down para cerrar
- **Colores por tipo:** transporte `#4A7FA5`, visita `#C4793A`, almuerzo `#D4860A`, cena `#8B4513`, hotel `#2C6E49`, tour `#7B5EA7`, libre `#6B7280`
- **Nav:** píldoras sticky por ciudad (París/Zúrich/Múnich/Viena/Praga) con IntersectionObserver scroll spy

**Why:** Usuarios son personas mayores — fuentes mínimo 18px, touch targets mínimo 44-52px de altura.
**How to apply:** Respetar estas variables CSS al hacer cambios visuales. No reducir tamaños de fuente.
