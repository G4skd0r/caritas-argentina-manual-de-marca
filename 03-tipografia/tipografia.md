# 03 · Tipografía

## Familia tipográfica

Cáritas Argentina utiliza **Montserrat** como tipografía principal en todas sus comunicaciones digitales. Es una fuente sans-serif geométrica creada por la diseñadora argentina Julieta Ulanovsky, inspirada en la cartelería del barrio porteño de Montserrat. Su origen local la hace especialmente apropiada para una organización con raíces profundas en la identidad argentina.

### Importar desde Google Fonts

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
```

```css
font-family: 'Montserrat', 'Helvetica Neue', Arial, sans-serif;
```

---

## Tokens tipográficos (Elementor)

El sitio está construido en WordPress + Elementor. Estos son los tokens globales exactos definidos en el tema:

```css
--e-global-typography-primary-font-family: "Montserrat";
--e-global-typography-primary-font-weight: 600;

--e-global-typography-secondary-font-family: "Montserrat";
--e-global-typography-secondary-font-weight: 400;

--e-global-typography-text-font-family: "Montserrat";
--e-global-typography-text-font-size: 16px;
--e-global-typography-text-font-weight: 500;

--e-global-typography-accent-font-family: "Montserrat";
--e-global-typography-accent-font-weight: 500;
```

**Fallback del sistema:**
```css
font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto,
             "Helvetica Neue", Arial, "Noto Sans", sans-serif;
```

---

## Roles tipográficos

| Rol Elementor | Peso | Uso |
|---|---|---|
| **Primary** | 600 (SemiBold) | Títulos principales, H1, H2 |
| **Secondary** | 400 (Regular) | Subtítulos, H3, texto de apoyo |
| **Text** | 500 (Medium) · 16px | Cuerpo de texto, párrafos |
| **Accent** | 500 (Medium) | Botones, etiquetas, CTAs |

---

## Jerarquía tipográfica

### H1 — Titular principal
```
Font: Montserrat SemiBold (600)
Size: 40–56px (desktop) / 28–36px (mobile)
Case: Sentence case o MAYÚSCULAS según contexto
Color: #FFFFFF (sobre rojo/azul) o #AE3336 (sobre blanco)
Ejemplo: "70 años alentando la esperanza"
```

### H2 — Título de sección
```
Font: Montserrat SemiBold (600)
Size: 28–36px
Color: #AE3336 o #004684
Ejemplo: "Nuestros programas" / "¿Cómo ayudar?"
```

### H3 — Subtítulo / Nombre de programa
```
Font: Montserrat Regular (400)
Size: 18–22px
Color: #333333 o #004684
Ejemplo: "Seguridad alimentaria" / "Primera infancia"
```

### Body — Texto de cuerpo
```
Font: Montserrat Medium (500)
Size: 16px
Line-height: 1.7
Color: #333333
```

### Caption / Texto secundario
```
Font: Montserrat Regular (400)
Size: 13–14px
Color: #666666
```

### Botones / CTAs
```
Font: Montserrat Medium (500)
Size: 15–16px
Case: Sentence case
Color: #FFFFFF sobre rojo o azul
Ejemplo: "Donar aquí" / "Colaborá con Cáritas"
```

---

## Uso en impresión

Para piezas gráficas impresas donde no se disponga de la fuente digital:
- Reemplazar **Montserrat** por **Gill Sans** o **Futura**
- Fallback seguro: **Arial** o **Helvetica**

---

## Reglas generales

- Montserrat es la única familia tipográfica de la marca — no mezclar con otras
- Mantener consistencia en los pesos: no usar Light para CTAs ni ExtraBold para texto largo
- El texto en botones siempre en blanco sobre color institucional
- Evitar texto centrado en párrafos extensos — alinear a la izquierda para mejor lectura
