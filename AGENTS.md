# AGENTS.md - Guía Rápida para IA

## Proyecto: Electrónica Mulka NEA

**Tipo:** Landing page estática para service técnico de electrónica industrial.

### Info Clave
- **WhatsApp:** +54 9 3755 665972
- **Ubicación:** Oberá, Misiones, Argentina
- **Repo:** https://github.com/dnx92/landing-electronica-radar
- **Deploy:** Vercel (auto-deploy al pushear a master)

### Stack
- HTML5 + Tailwind CSS (CDN)
- Google Fonts (Inter, Poppins)
- Imágenes: WebP optimizadas
- Sin backend (página estática)

### Estructura Principal
- `index.html` - Todo el sitio (927 líneas)
- `resultado-*.webp` - Imágenes de resultados de reparaciones

### Sección Actual del Proyecto
El sitio ya está funcionando con:
- Hero con CTA de WhatsApp
- 6 servicios con cards
- 3 casos de éxito
- 3 testimonios
- Mapa de ubicación
- Widget de chat WhatsApp
- Google AdSense (ca-pub-8997813107321023)

### Cambios Recientes
- Landing page completa funcional
- Imágenes optimizadas a WebP
- Eliminado sistema de auth/admin (temporal, tuvo problemas)
- Google AdSense agregado

### Pendiente ( Ideas del Cliente )
- Sistema de usuarios con Supabase (futuro)
- Panel admin para gestionar solicitudes (futuro)
- Marketplace de productos (futuro)
- Integración MercadoPago (futuro)

### Para Continuar Trabajo
1. `git pull` antes de editar
2. Editar `index.html`
3. `git add . && git commit -m "descripción" && git push`
4. NO usar `git push --force`

### Cliente
**Sandra** - Dueña de Electrónica Mulka NEA
- Necesita landing page profesional
- Canal principal de contacto: WhatsApp
- Quiere monetizar con AdSense
- Planea expandir a marketplace

### Errores Comunes a Evitar
⚠️ NO hacer force push - destruye el historial
⚠️ Verificar que index.html esté en raíz del repo, no en subcarpeta
⚠️ Hacer pull antes de push para evitar conflictos
