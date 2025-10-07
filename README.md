# Unclic.tech Website

Sitio web corporativo para Unclic.tech - Empresa especializada en bots de WhatsApp y asistentes de voz con LiveKit.

## Deploy en Railway

### Opción 1: Desde la interfaz web de Railway

1. Ve a [Railway.app](https://railway.app)
2. Crea un nuevo proyecto
3. Selecciona "Deploy from GitHub repo" o "Deploy from local"
4. Conecta este repositorio o sube la carpeta `unclic-website`
5. Railway detectará automáticamente el Dockerfile
6. El sitio estará disponible en la URL que Railway te proporcione

### Opción 2: Usando Railway CLI

```bash
# Instalar Railway CLI
npm i -g @railway/cli

# Login
railway login

# Inicializar proyecto
railway init

# Deploy
railway up
```

### Opción 3: Build y test local

```bash
# Build la imagen Docker
docker build -t unclic-website .

# Correr localmente
docker run -p 8080:80 unclic-website

# Acceder en: http://localhost:8080
```

## Estructura

- `index.html` - Sitio web completo con todos los estilos incluidos
- `Dockerfile` - Configuración para crear la imagen Docker con nginx
- `nginx.conf` - Configuración del servidor nginx

## Contacto

- Email: marcos076@yahoo.com
- WhatsApp: +502 3443 2011
