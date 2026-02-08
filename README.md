# Wedding Landing Page - Elizabeth & Juan Pablo

## 📁 Estructura de archivos

```
wedding-landing/
├── index.html          (página principal)
├── style.css           (estilos)
├── images/             (CREAR ESTA CARPETA)
│   └── hero.jpg        (foto de ustedes en la playa)
└── audio/              (CREAR ESTA CARPETA - opcional)
    └── caetano.mp3     (música de fondo)
```

## 🚀 Cómo subir a Vercel (5 minutos)

### Paso 1: Preparar los archivos
1. Descargá la carpeta `wedding-landing` de donde Claude la guardó
2. Creá una carpeta llamada `images` dentro
3. Metele adentro tu foto de la playa y renombrala a `hero.jpg`
4. (Opcional) Creá una carpeta `audio` y metele `caetano.mp3`

### Paso 2: Subir a Vercel
1. Andá a https://vercel.com
2. Logueate (con GitHub, Google, o email)
3. Click en "Add New..." → "Project"
4. Arrastrá la carpeta `wedding-landing` completa al área de upload
5. ¡Listo! Vercel la va a deployar automáticamente

### Paso 3: Conectar tu dominio
1. Una vez deployado, andá a "Settings" del proyecto
2. Click en "Domains"
3. Agregá tu dominio (el que compraste)
4. Seguí las instrucciones para configurar los DNS

## 🎨 Personalizaciones rápidas

### Cambiar colores
En `style.css`, buscá estas variables:
- `#6BA5A0` = Verde agua/teal
- `#E8DCC4` = Beige cálido
- `#D4A574` = Dorado

### Cambiar la foto del hero
En `style.css`, línea 38:
```css
background-image: url('images/hero.jpg');
```
Reemplazá `hero.jpg` por el nombre de tu foto.

### Activar la música
En `index.html`, descomentá las líneas 14-16:
```html
<audio id="background-music" autoplay loop>
    <source src="audio/caetano.mp3" type="audio/mpeg">
</audio>
```

## 🔗 Próximos pasos

1. **Tally Form**: Cuando lo tengas listo, reemplazá el `href="#confirmar"` del botón RSVP con el link de Tally
2. **Fotos adicionales**: Podés agregar más fotos en diferentes secciones si querés
3. **Ajustes de texto**: Todo el texto está en `index.html`, editalo directo ahí

## 💡 Tips

- La página es 100% responsive (se ve bien en mobile/tablet/desktop)
- El hero tiene efecto parallax (se mueve al scrollear)
- Hay animaciones suaves al scrollear
- El Cristo en el footer es un SVG simple (si querés uno más detallado, avisame)

## ❓ Si algo no funciona

1. Verificá que las fotos estén en la carpeta correcta
2. Verificá que los nombres de archivo coincidan (case-sensitive)
3. Abrí la consola del navegador (F12) para ver errores
4. Pedile ayuda a Claude

¡Éxitos con el casamiento! 🎉
