# 🎂 Feliz Cumpleaños Emmanuel - 18 Años

Página web especial de cumpleaños con galería de fotos, música y video de Minecraft.

## 📋 Requisitos para que funcione en GitHub Pages

### 1. Estructura de archivos necesaria

Tu repositorio debe tener esta estructura:

```
tu-repositorio/
├── index.html          (el archivo principal)
├── 1.avif             (imagen de cumpleaños principal)
├── 2.jpeg             (foto 1)
├── 3.jpeg             (foto 2)
├── 5.jpeg             (foto 3)
├── 8.jpeg             (foto 4)
├── 9.jpeg             (foto 5)
├── 10.jpeg            (foto 6)
├── 11.jpeg            (foto 7)
├── 12.jpeg            (foto 8)
├── 13.jpeg            (foto 9)
├── 15.jpeg            (foto 10)
├── 17.jpeg            (foto 11)
├── 18.jpeg            (foto 12)
├── 22.jpeg            (foto 13)
├── 23.jpeg            (foto 14)
├── 24.jpeg            (foto 15)
├── 26.jpeg            (foto 16)
├── 29.jpeg            (foto 17)
├── 30.jpeg            (foto 18)
├── 35.jpeg            (foto 19)
└── grado.png          (imagen de graduación)
```

### 2. Pasos para subir a GitHub Pages

#### Opción A: Desde la interfaz web de GitHub

1. **Crea un nuevo repositorio en GitHub:**
   - Ve a https://github.com/new
   - Nombre sugerido: `cumpleanos-emmanuel`
   - Márcalo como público
   - Click en "Create repository"

2. **Sube los archivos:**
   - Click en "uploading an existing file"
   - Arrastra TODOS los archivos (index.html y todas las imágenes)
   - Click en "Commit changes"

3. **Activa GitHub Pages:**
   - Ve a Settings (Configuración) del repositorio
   - En el menú lateral, click en "Pages"
   - En "Source", selecciona "main" o "master"
   - Click en "Save"
   - Espera 1-2 minutos

4. **Accede a tu página:**
   - La URL será: `https://tu-usuario.github.io/cumpleanos-emmanuel`

#### Opción B: Desde la línea de comandos

```bash
# 1. Inicializa git en tu carpeta del proyecto
cd ruta/a/tu/proyecto
git init

# 2. Agrega todos los archivos
git add .

# 3. Crea el primer commit
git commit -m "Página de cumpleaños de Emmanuel"

# 4. Conecta con tu repositorio de GitHub
git remote add origin https://github.com/TU-USUARIO/cumpleanos-emmanuel.git

# 5. Sube los archivos
git push -u origin main

# 6. Activa GitHub Pages desde Settings > Pages
```

### 3. Solución de problemas comunes

#### ❌ "Las imágenes no se ven"
- **Causa:** Los archivos de imagen no se subieron o tienen nombres incorrectos
- **Solución:** 
  - Verifica que TODAS las imágenes estén en el repositorio
  - Los nombres deben coincidir exactamente (2.jpeg, 3.jpeg, etc.)
  - Las extensiones importan (.jpeg, .png, .avif)

#### ❌ "El video de fondo no se ve"
- **Causa:** El navegador bloqueó la reproducción automática
- **Solución:** 
  - Esto es normal en algunos navegadores móviles
  - El video es opcional, la página funciona sin él
  - Si quieres, puedes cambiar el video por otro en YouTube

#### ❌ "No se escucha la música"
- **Causa:** Navegadores bloquean audio automático
- **Solución:**
  - Presiona el botón 🔊 en la esquina superior derecha
  - El audio usa YouTube, funciona en todos los navegadores

### 4. Personalización opcional

#### Cambiar la música de fondo:
En el archivo `index.html`, busca esta línea (aproximadamente línea 650):

```html
<iframe 
    id="audioPlayer"
    src="https://www.youtube.com/embed/Vt2qAOXqrE8?autoplay=1&loop=1&playlist=Vt2qAOXqrE8"
```

Reemplaza `Vt2qAOXqrE8` con el ID de otro video de YouTube.

#### Cambiar el video de Minecraft:
Busca esta línea (aproximadamente línea 638):

```html
src="https://www.youtube.com/embed/XJqx8nnppE0?autoplay=1&mute=1&loop=1&playlist=XJqx8nnppE0"
```

Reemplaza `XJqx8nnppE0` con el ID del nuevo video.

### 5. Optimización de imágenes (Opcional)

Para que la página cargue más rápido:

1. **Comprime las imágenes:**
   - Usa https://tinypng.com/
   - Arrastra cada imagen JPEG
   - Descarga las versiones optimizadas
   - Reemplaza las originales

2. **Mantén los nombres originales:**
   - No cambies los nombres de los archivos
   - Solo reemplaza el contenido

### 6. Compartir la página

Una vez publicada, puedes compartir el enlace:
- `https://tu-usuario.github.io/cumpleanos-emmanuel`

También puedes crear un código QR del enlace para imprimir.

## 🎮 Características

- ✨ Galería de 20 fotos con animaciones mágicas
- 🎵 Música de fondo automática (YouTube)
- 🎬 Video de fondo de Minecraft
- 🎈 Animaciones de globos, confetti y destellos
- 📱 Totalmente responsive (funciona en móviles)
- 🌐 Compatible con todos los navegadores modernos

## 💡 Notas importantes

- GitHub Pages es GRATIS
- La página estará disponible 24/7
- Puedes actualizar el contenido cuando quieras
- No necesitas conocimientos técnicos avanzados

## 🆘 Soporte

Si tienes problemas:
1. Verifica que todos los archivos estén subidos
2. Espera 2-5 minutos después de activar GitHub Pages
3. Prueba en modo incógnito de tu navegador
4. Verifica la consola del navegador (F12) para errores

---

**Hecho con ❤️ para Emmanuel en su cumpleaños #18**
