# 02 · Colores — Paleta Institucional

## Colores primarios

Estos colores conforman la identidad visual de Cáritas Argentina y deben usarse en todas las comunicaciones institucionales.

| Nombre | Hex | RGB | Uso |
|---|---|---|---|
| **Rojo Cáritas** | `#AE3336` | `174, 51, 54` | Color principal, logo, CTAs, fondos de sección, títulos destacados |
| **Azul Institucional** | `#004684` | `0, 70, 132` | Secundario, fondos, textos destacados, links |
| **Azul Navy** | `#0C2868` | `12, 40, 104` | Fondos oscuros, encabezados, footer |
| **Blanco** | `#FFFFFF` | `255, 255, 255` | Fondos, texto sobre colores, versión negativa del logo |

### Vista de swatches

```
 ████████   ████████   ████████   ████████
 #AE3336    #004684    #0C2868    #FFFFFF
 Rojo       Azul       Navy       Blanco
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
| Verde WhatsApp | `#25D366` | Botón de contacto por WhatsApp |
| Gris oscuro | `#32373C` | Texto de cuerpo, footer |
| Gris medio | `#666666` | Texto secundario, captions |
| Gris claro | `#F4F4F4` | Fondos de sección, separadores |
| Negro | `#000000` | Uso tipográfico formal |

---

## Combinaciones recomendadas

| Fondo | Texto | Uso |
|---|---|---|
| `#AE3336` | `#FFFFFF` | Hero, CTA principal, encabezados |
| `#004684` | `#FFFFFF` | Bloques de contenido, footer |
| `#FFFFFF` | `#AE3336` | Títulos sobre fondo blanco |
| `#FFFFFF` | `#333333` | Cuerpo de texto general |
| `#F4F4F4` | `#333333` | Secciones de fondo suave |

---

## Accesibilidad

- Rojo `#AE3336` sobre blanco: ratio de contraste ~4.5:1 — cumple WCAG AA para texto grande
- Azul `#004684` sobre blanco: ratio ~7:1 — cumple WCAG AAA
- Texto oscuro `#333333` sobre blanco: ratio ~12:1 — óptimo

---

## Variables CSS (del HTML del sitio)

```css
:root {
  --c-red: #AE3336;       /* Rojo Cáritas — principal */
  --c-blue: #004684;      /* Azul Institucional */
  --c-navy: #0C2868;      /* Azul Navy — fondos oscuros */
  --c-white: #FFFFFF;

  /* Soporte */
  --c-whatsapp: #25D366;
  --c-text: #32373C;
  --c-text-secondary: #666666;
  --c-bg-light: #F4F4F4;
  --c-black: #000000;
}
```
