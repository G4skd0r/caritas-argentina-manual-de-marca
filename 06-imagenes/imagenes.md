# 06 · Imágenes y Fotografía

## Estilo fotográfico

Las imágenes de Cáritas Argentina son **documentales y humanas**. Muestran realidades concretas con dignidad: personas reales, momentos reales, sin glamour ni artificialidad. La fotografía es una herramienta de testimonio, no de marketing.

---

## Criterios generales

### ✅ Usar

- Fotografías de personas en sus propios espacios y comunidades
- Momentos de encuentro real: voluntario y vecino, distribución de alimentos, actividades educativas
- Expresiones genuinas — emoción sin pose
- Luz natural, entornos auténticos (no estudios)
- Diversidad de género, edad, región y origen étnico
- Planos cercanos que humanicen (primeros planos de manos, rostros, detalles)
- Imágenes que transmitan dignidad aún en contextos difíciles

### ✗ Evitar

- Fotos que victimicen o refuercen la imagen de pobreza como destino permanente
- Imágenes de niños sin autorización explícita de padres o tutores
- Stock photos genérico sin contexto local
- Fotos sensacionalistas de emergencias o crisis
- Edición excesiva, filtros o retoques que alejen de la realidad
- Encuadres que quiten agencia a las personas fotografiadas

---

## Dignidad ante todo

Toda fotografía debe poder ser mostrada a la persona fotografiada sin que sienta vergüenza. Si hay duda, no usar la imagen.

---

## Tratamiento visual

### Fotos en web
- Usar overlays suaves para garantizar contraste con texto superpuesto
- Color del overlay: oscuro (`rgba(0,0,0,0.4)`) o rojo institucional con baja opacidad
- Las fotos de hero pueden tener un recorte oscuro progresivo (degradado abajo-arriba)

```css
/* Overlay estándar */
background: linear-gradient(to top, rgba(0,0,0,0.6), rgba(0,0,0,0.1));
```

### Fotos en impresión
- Alta resolución: mínimo 300 dpi para impresión
- Formato: TIFF o JPG de alta calidad

---

## Iconografía

Cáritas Argentina puede usar íconos para representar sus programas y áreas de acción.

**Estilo recomendado:**
- Line icons o íconos sólidos simples
- Color: rojo `#AE3336` o azul `#004684`
- Trazo uniforme, sin decoración
- Tamaño mínimo funcional: 24×24px

**Ejemplo de íconos por programa:**
```
🎓 Educación
👶 Primera Infancia
💼 Trabajo
🍎 Seguridad Alimentaria
🏠 Vivienda
🚨 Emergencias
🤝 Integración de Barrios
```

---

## Proporciones de imagen

| Contexto | Proporción |
|---|---|
| Hero / Banner web | 16:9 o full width |
| Card de programa | 4:3 |
| Foto de testimonio | 3:2 o libre vertical |
| Avatar / Voluntario | 1:1 (círculo) |
| Redes sociales (feed) | 1:1 o 4:5 |
| Redes sociales (stories) | 9:16 |

---

## Derechos y privacidad

- Obtener siempre autorización escrita de las personas fotografiadas, especialmente menores
- Guardar los consentimientos en archivos organizados por campaña
- No publicar imágenes de personas en situaciones de crisis sin su consentimiento explícito
- Especial cuidado con imágenes de contextos de salud, adicciones o violencia
