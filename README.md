# LUXE Barber Studio

Sistema de reservas online con panel de administración.

## URLs

| Ruta | Descripción |
|------|-------------|
| `/` | App de reservas para clientes |
| `/admin/login.html` | Login del panel admin |
| `/admin/dashboard.html` | Panel de administración |

## Credenciales Admin

| Usuario | Contraseña |
|---------|------------|
| `admin` | `luxe2025` |
| `gerente` | `barber123` |

## Deploy en Render (Static Site)

1. Subí esta carpeta a un repositorio GitHub
2. Entrá a [render.com](https://render.com) y creá una cuenta
3. New → **Static Site**
4. Conectá tu repo de GitHub
5. Configurá:
   - **Build Command:** `echo "No build needed"` (o dejalo vacío)
   - **Publish Directory:** `.`
6. Click **Deploy**

Tu sitio quedará en `https://luxe-barber-studio.onrender.com`

## Estructura

```
/
├── index.html          # App cliente (reservas)
├── admin/
│   ├── login.html      # Login admin
│   └── dashboard.html  # Panel admin
├── render.yaml         # Configuración Render
└── README.md
```

## Tecnología

- HTML5 + CSS3 + JavaScript vanilla
- Sin dependencias de servidor
- Datos persistidos en `localStorage` del navegador
- Fuentes: Google Fonts (Outfit)
