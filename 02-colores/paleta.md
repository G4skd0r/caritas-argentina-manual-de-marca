# 02 · Colores — Paleta Institucional

## Colores primarios

Estos tres colores conforman la identidad visual de Cáritas Argentina y deben usarse en todas las comunicaciones institucionales.

| Nombre | Hex | RGB | Pantone ref. | Uso |
|---|---|---|---|---|
| **Rojo Cáritas** | `#CF2E2E` | `207, 46, 46` | ~485 C | Color principal, logo, CTAs, títulos destacados |
| **Azul Institucional** | `#004684` | `0, 70, 132` | ~286 C | Secundario, fondos, textos destacados, links |
| **Blanco** | `#FFFFFF` | `255, 255, 255` | — | Fondos, texto sobre colores, versión negativa del logo |

### Vista de swatches

```
 ████████   ████████   ████████
 #CF2E2E    #004684    #FFFFFF
 Rojo       Azul       Blanco
 Cáritas    Inst.
```

---

## Reglas de uso de color

- El **Rojo Cáritas** es el color de identidad principal. Usarlo en el logo, botones de donación y elementos de alta prioridad.
- El **Azul Institucional** complementa al rojo. Ideal para secciones de contenido, fondos de bloques y navegación.
- Sobre fondos rojos o azules, el texto debe ser siempre **blanco**.
- No combinar rojo y azul en proporciones iguales — uno debe dominar claramente.

---

## Colores de soporte

Para uso en infografías, categorización de programas y materiales de comunicación.

| Nombre | Hex | Uso sugerido |
|---|---|---|
| Rojo claro | `#E8574A` | Hover, versiones light del rojo |
| Azul claro | `#1A6BAA` | Versiones más claras del azul institucional |
| Gris oscuro | `#333333` | Texto de cuerpo |
| Gris medio | `#666666` | Texto secundario, captions |
| Gris claro | `#F4F4F4` | Fondos de sección, separadores |
| Negro | `#000000` | Uso tipográfico formal |

---

## Combinaciones recomendadas

| Fondo | Texto | Uso |
|---|---|---|
| `#CF2E2E` | `#FFFFFF` | Hero, CTA principal, encabezados |
| `#004684` | `#FFFFFF` | Bloques de contenido, footer |
| `#FFFFFF` | `#CF2E2E` | Títulos sobre fondo blanco |
| `#FFFFFF` | `#333333` | Cuerpo de texto general |
| `#F4F4F4` | `#333333` | Secciones de fondo suave |

---

## Accesibilidad

- Rojo `#CF2E2E` sobre blanco: ratio de contraste ~4.5:1 — cumple WCAG AA para texto grande
- Azul `#004684` sobre blanco: ratio ~7:1 — cumple WCAG AAA
- Texto oscuro `#333333` sobre blanco: ratio ~12:1 — óptimo

---

## Variables CSS sugeridas

```css
:root {
  --c-red: #CF2E2E;
  --c-blue: #004684;
  --c-white: #FFFFFF;

  --c-red-light: #E8574A;
  --c-blue-light: #1A6BAA;

  --c-text: #333333;
  --c-text-secondary: #666666;
  --c-bg-light: #F4F4F4;
  --c-black: #000000;
}
```
