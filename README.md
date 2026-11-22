# 🎮 MOBA TACTIC — Landing Page Web

Página web moderna y atractiva para la aplicación **MOBA TACTIC**, diseñada con estética gaming/cyberpunk, soporte para descargas en múltiples plataformas (Android APK y Windows .EXE), animaciones de partículas, efectos 3D interactivos y métricas dinámicas.

---

## 📋 ¿Qué necesitas para abrirlo?

No necesitas instalar herramientas complejas ni frameworks pesados (Node.js, npm, etc.). Es un proyecto construido con tecnologías web estándar (**HTML5**, **CSS3**, **JavaScript Vanilla**):

- Un navegador web moderno (Google Chrome, Microsoft Edge, Mozilla Firefox, Brave, Opera, etc.).
- Conexión a internet la primera vez para cargar las fuentes tipográficas de Google Fonts y los iconos de FontAwesome (CDN).

---

## 🚀 Opciones para abrir la página

Tienes **dos opciones** muy sencillas:

### Opción 1: Abrir directamente (Más rápida)
1. Entra en esta carpeta (`MOBA-TACTIC-Web`).
2. Haz **doble clic** sobre el archivo `index.html`.
3. Se abrirá automáticamente en tu navegador predeterminado.

---

### Opción 2: Usar un servidor local ligero (Recomendado para la mejor experiencia)
Para que todas las animaciones, transiciones y recursos locales se ejecuten bajo protocolo HTTP:

#### Con Python (si lo tienes instalado en tu PC):
1. Abre una terminal (PowerShell o CMD) dentro de esta carpeta.
2. Ejecuta:
   ```bash
   python -m http.server 8080
   ```
3. Abre tu navegador y accede a:
   [http://localhost:8080](http://localhost:8080)

#### Con la extensión Live Server de VS Code:
1. Abre esta carpeta en **Visual Studio Code**.
2. Haz clic derecho en `index.html` y selecciona **"Open with Live Server"**.

---

## 📁 Estructura de archivos

```text
MOBA-TACTIC-Web/
├── index.html        # Estructura principal y secciones de la web
├── styles.css        # Estilos, efectos de brillo (glow), gradientes y diseño responsive
├── script.js         # Canvas de partículas, efectos 3D tilt, contadores y acordeón FAQ
├── README.md         # Instrucciones de uso
└── assets/           # Imágenes y recursos multimedia
    └── img/
```

---

## ✨ Características incluidas
- **Hero Section:** Botones de descarga directa para Android (`APK` / Play Store) y Windows (`.EXE` / Portable). Detección automática del sistema operativo del usuario.
- **Efectos visuales:** Partículas reactivas en canvas, cursor glow, tarjetas 3D tilt en juegos soportados.
- **Métricas interactivas:** Contadores dinámicos que se animan al hacer scroll.
- **Secciones completas:** Juegos soportados (Mobile Legends, Wild Rift, LoL, Dota 2, AoV), cómo funciona, testimonios, especificaciones de descarga y preguntas frecuentes (FAQ).
