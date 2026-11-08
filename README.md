# Tu Taller — Landing Page & Bio-Link

Página de conversión estilo **Bio-Link / MyLinks** para promocionar el software SaaS **Tu Taller** (sistema de gestión integral para talleres de reparación de celulares y computadoras).

## 🚀 Características
- **Ultra optimizada y liviana:** Carga instantánea en dispositivos móviles (< 50 KB), sin dependencias ni frameworks pesados.
- **Estética Dark Mode de marca:** Paleta en `#0b1110` (fondo), `#141f1c` (tarjetas), acentos en verde esmeralda `#10b981`, y bordes sutiles en `#1d2e2a`.
- **Isotipo oficial integrado:** Isotipo optimizado con fondo transparente y efecto resplandor.
- **Botones de conversión directa:**
  1. **WhatsApp:** Enlace directo con mensaje comercial predefinido (`wa.me`).
  2. **Demo Interactiva:** Acceso directo a la maqueta comercial en vivo ([tu-taller-maqueta.pages.dev](https://tu-taller-maqueta.pages.dev/)).
  3. **Email:** Contacto directo vía `mailto:` con asunto preconfigurado.
- **Sección de Beneficios Clave:** Viñetas detalladas con iconos SVG para ordenes de trabajo, caja diaria, inventario y sincronización móvil/PC.

## ⚙️ Configuración de Contactos
En `index.html`:
- **WhatsApp:** Buscar `wa.me/5491178200237` para modificar el número o el texto del mensaje.
- **Email:** Buscar `mailto:barriosmatiasivan@gmail.com` para actualizar la casilla de recepción.
- **Demo:** Buscar `https://tu-taller-maqueta.pages.dev/` para cambiar la URL de prueba.

## 🌐 Despliegue en Cloudflare Pages

### Opción A (Recomendada - Conexión Git automática):
1. El repositorio está alojado en GitHub: `https://github.com/barriosmatiasivan-ai/tutaller-landing`.
2. En el panel de **Cloudflare Dashboard** -> **Workers & Pages** -> **Create application** -> **Pages** -> **Connect to Git**.
3. Seleccionar `tutaller-landing`.
4. Build settings:
   - Framework preset: `None`
   - Build command: *(vacío)*
   - Build output directory: `/` o `.`
5. Cada commit a `main` se desplegará automáticamente con HTTPS y red global Cloudflare.

### Opción B (Despliegue directo por CLI Wrangler):
```bash
npx wrangler pages deploy . --project-name tutaller-landing
```
*(Requiere `CLOUDFLARE_API_TOKEN` configurado en el entorno).*

---
Tu Taller © 2026 · Hecho para técnicos.
