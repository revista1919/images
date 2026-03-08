markdown
# Repositorio de Imágenes - Revista Nacional de Ciencias para Estudiantes

Este repositorio almacena y sirve las imágenes utilizadas en la revista a través de GitHub Pages.

## 📸 URLs de imágenes

Todas las imágenes están disponibles en:
https://revista1919.github.io/images/[nombre-del-archivo].[webp|gif|svg]

text

## 🖼️ Formatos soportados

- **WebP** (recomendado): Optimizado automáticamente desde JPG/PNG
- **GIF**: Mantiene animaciones
- **SVG**: Vectores sin optimizar

## ⚙️ Automatización

El workflow de GitHub Actions:

1. **Optimiza** automáticamente JPG/PNG a WebP (calidad 80-85%)
2. **Mantiene** GIFs animados sin modificar
3. **Genera** una galería visual en `index.html`
4. **Crea** un archivo `list.json` con metadatos
5. **Despliega** a GitHub Pages

## 🚀 Uso

### Subir una imagen

1. Haz push al repositorio
2. El workflow optimizará y desplegará automáticamente
3. La imagen estará disponible en minutos

### URLs amigables

Las imágenes mantienen su nombre original:
subida: imagen-principal.jpg
resultado: https://revista1919.github.io/images/imagen-principal.webp

text

### Desde el panel de administración

Usa la función `manageImages` para subir/editar imágenes programáticamente.

## 📊 Estadísticas

- ⚡ Imágenes optimizadas en WebP
- 🎨 Calidad 80% para balance óptimo
- 📱 CDN automático vía GitHub Pages
- 🔄 Actualización automática al hacer push

## 🔧 Mantenimiento

Para forzar una optimización manual:
1. Ve a Actions
2. Selecciona "Optimize and Deploy Images"
3. Click en "Run workflow"

## 📝 Notas

- Los GIFs mantienen su formato original (no se convierten a WebP)
- Las imágenes se sirven con caché de 1 hora
- La galería se actualiza automáticamente