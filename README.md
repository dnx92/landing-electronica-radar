# Electrónica Mulka NEA - Landing Page

## Resumen del Proyecto

Landing page profesional para **Electrónica Mulka NEA**, un service técnico de electrónica industrial en Oberá, Misiones, Argentina.

- **WhatsApp:** +54 9 3755 665972
- **Ubicación:** Bahía Blanca 1551 N 3361, N3360 Oberá, Misiones
- **GitHub:** https://github.com/dnx92/landing-electronica-radar
- **Vercel:** https://landing-electronica-radar.vercel.app

---

## Stack Tecnológico

| Tecnología | Uso |
|------------|-----|
| HTML5 + Tailwind CSS | Frontend (CDN) |
| Google Fonts | Tipografía (Inter, Poppins) |
| Vercel | Hosting (conectado a GitHub) |
| Google AdSense | Monetización (ca-pub-8997813107321023) |

---

## Estructura de Archivos

```
├── index.html          # Página principal (927 líneas)
├── resultado-*.webp   # Imágenes optimizadas
├── .gitignore         # Archivos ignorados
└── Dockerfile         # Docker (no usado activamente)
```

---

## Secciones del Sitio

1. **Header** - Navegación fija + botón WhatsApp
2. **Hero** - Título, estadísticas, servicios rápidos con enlaces a WhatsApp
3. **Trust Banner** - "¿Por qué nosotros?" con 17 años de experiencia
4. **Contacto** - Mapa de Google, horarios, WhatsApp, service a domicilio
5. **Servicios** - 6 cards con imágenes de Unsplash (electrónica industrial, soldadoras, etc.)
6. **Resultados** - 3 casos de éxito con fotos WebP
7. **Testimonios** - 3 reseñas con estrellas
8. **CTA Final** - Llamada a la acción con WhatsApp
9. **Footer** - Links, contacto, redes sociales
10. **Chat Widget** - Widget flotante con opciones rápidas de WhatsApp
11. **WhatsApp Button** - Botón flotante móvil

---

## Imágenes

| Archivo | Tamaño | Uso |
|---------|--------|-----|
| resultado-variador.webp | 45 KB | Variador de frecuencia reparado |
| resultado-freezer.webp | 49 KB | Freezer industrial reparado |
| resultado-heladera.webp | 14 KB | Heladera inverter reparada |

Las imágenes fueron convertidas de PNG/JPG a WebP para optimizar carga (reducción ~95%).

---

## Notas Importantes

### Sobre el Repositorio Git

⚠️ **ALERTA:** El historial de git se dañó durante el desarrollo por force pushes. El historial actual tiene solo los commits recientes. Si necesitás restaurar una versión anterior, verificá en Vercel Dashboard.

### Buenos Prácticas para Evitar Problemas

1. **NUNCA hacer `git push --force`** a menos que sea absolutamente necesario
2. Hacer `git pull` antes de hacer `git push`
3. Si hay conflicto, resolverlo localmente antes de pushear
4. Mantener backups locales de archivos importantes
5. No guardar archivos grandes (>1MB) en git si no son necesarios
6. Usar `.gitignore` para excluir node_modules, builds, etc.

### Antes de Editar desde Otra IA

1. Ejecutar `git pull` para tener la última versión
2. Hacer cambios en local
3. Hacer `git commit` con mensaje descriptivo
4. Hacer `git push` (sin --force)

---

## Pendiente / Futuras Mejoras

- [ ] Sistema de autenticación de usuarios (eliminado temporalmente)
- [ ] Panel admin para gestionar solicitudes (eliminado temporalmente)
- [ ] Integración con MercadoPago para cobros
- [ ] Marketplace de productos
- [ ] Optimizar imágenes de servicios (Unsplash)

---

## Comandos Útiles

```bash
# Clonar repositorio
git clone https://github.com/dnx92/landing-electronica-radar.git

# Actualizar local
git pull origin master

# Hacer cambios y subir
git add .
git commit -m "Descripción del cambio"
git push origin master

# Ver estado
git status
git log --oneline
```

---

## Contacto del Desarrollador Original

Creado con asistencia de Claude Code (AI) en abril 2026.
Para consultas técnicas, contactar al dueño del proyecto.
