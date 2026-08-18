# Bitácora de IA — HW04 UX + Tailwind CSS

## ¿Usaste IA para escoger una paleta de colores de Tailwind?

Sí.

### Paleta sugerida por la IA

La IA sugirió una paleta basada principalmente en:

- `emerald-600` para acciones principales y elementos relacionados con salud/farmacia.
- `slate-50`, `slate-100`, `slate-900` y `slate-950` para fondos claros y oscuros.
- `slate-600` y `slate-300` para textos secundarios.
- `sky`, `amber` y `violet` como colores auxiliares para diferenciar información y roles.

### ¿Qué cambié?

La propuesta inicial usaba más tonos verdes en casi todos los componentes. La ajusté para dejar el verde esmeralda únicamente como color principal de la interfaz y utilicé colores secundarios en etiquetas y tarjetas. De esta manera se conserva una identidad visual asociada con farmacia y salud, pero se mejora la jerarquía visual y se evita que toda la página se vea del mismo color.

También adapté los tonos para modo oscuro con variantes como `dark:bg-slate-950`, `dark:bg-slate-900`, `dark:text-slate-100` y colores oscuros equivalentes para las etiquetas.

## Uso de IA

La IA también ayudó a organizar las clases utilitarias de Tailwind para que la página fuera responsive con variantes `sm:`, `md:` y `lg:`, y a implementar el cambio entre modo claro y oscuro guardando la preferencia en `localStorage`.
