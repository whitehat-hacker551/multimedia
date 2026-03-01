# Zona Multimedia — APAR

Sitio web estático de presentación de los distintos proyectos desarrollados para **APAR**, una tienda en línea de repuestos y accesorios para vehículos ubicada en Charlestown, Nevis, West Indies.

---

## 📁 Estructura del proyecto

```
multimedia/
├── index.html                        # Página de inicio: portal de acceso a todos los proyectos
├── style.css                         # Estilos globales de la página de inicio
│
├── disenyoCSS/                       # Proyecto 1 — Diseño CSS
│   ├── indexAPARSemantico.html
│   └── static/
│       ├── css/styles.css
│       └── public/
│           ├── images/
│           └── ...
│
├── multimedia/                       # Proyecto 2 — Multimedia
│   ├── indexAPARSemantico.html
│   └── static/
│       ├── css/styles.css
│       └── public/
│           ├── audio/
│           │   └── ComposicionFinal.mp3
│           ├── video/
│           │   └── Videomultimedia.mp4
│           └── images/
│
├── proyectoAAA/                      # Proyecto 3 — Proyecto AAA
│   ├── indexAPARSemantico.html
│   └── static/
│
└── proyectoUsabilidad/               # Proyecto 4 — Usabilidad
    ├── indexAPARSemantico.html
    └── static/
```

---

## 🌐 Descripción general

La página principal (`index.html`) actúa como portal de acceso a cuatro versiones del mismo sitio web de APAR, cada una centrada en un aspecto distinto del desarrollo web:

| Carpeta | Enfoque |
|---|---|
| `disenyoCSS` | Diseño visual y maquetación con CSS |
| `multimedia` | Integración de recursos multimedia (audio, vídeo, imágenes) |
| `proyectoAAA` | Estándares de accesibilidad WCAG nivel AAA y semántica HTML |
| `proyectoUsabilidad` | Usabilidad, rendimiento y buenas prácticas UX |

---

## ✨ Características del sitio APAR

- **Barra superior** con dirección física, horario de atención, selector de divisa (USD / EUR / LB) y selector de idioma.
- **Búsqueda de productos** en toda la tienda.
- **Wishlist y carrito de compras** accesibles desde el encabezado.
- **Buscador de piezas por vehículo**: selección de marca, modelo y año.
- **Sección de servicios**: envío gratuito, productos 100 % genuinos, devoluciones fáciles y programa de fidelidad.
- **Diseño responsivo** adaptado a dispositivos móviles, tabletas y escritorio.
- **Accesibilidad**: HTML semántico, atributos ARIA, navegación por teclado con indicadores de foco visibles.

---

## 🛠️ Tecnologías utilizadas

| Tecnología | Uso |
|---|---|
| HTML5 | Estructura semántica de las páginas |
| CSS3 | Estilos, diseño responsivo y animaciones |
| [Bootstrap Icons 1.10.5](https://icons.getbootstrap.com/) | Iconografía |
| [Google Fonts](https://fonts.google.com/) | Tipografías *Nova Square* y *Noto Sans Linear B* |

> No se utiliza ningún framework de JavaScript. El proyecto es completamente estático.

---

## 🚀 Cómo ejecutar el proyecto

Al tratarse de un proyecto estático (solo HTML y CSS), no necesitas instalar dependencias ni ejecutar ningún servidor.

1. Clona el repositorio:

   ```bash
   git clone https://github.com/whitehat-hacker551/multimedia.git
   ```

2. Abre el archivo `index.html` directamente en tu navegador, o usa una extensión como **Live Server** en VS Code para servirlo en local.

3. Desde la página de inicio, accede a cualquiera de los cuatro proyectos haciendo clic en el enlace correspondiente.

---

## 📂 Recursos multimedia

Los recursos se encuentran dentro de cada subcarpeta bajo `static/public/`:

- **Imágenes** (`.webp`, `.png`) — logotipos, fondos, productos destacados y marcas.
- **Audio** — `ComposicionFinal.mp3` (carpeta `multimedia`).
- **Vídeo** — `Videomultimedia.mp4` (carpeta `multimedia`).

---

## ♿ Accesibilidad

El proyecto pone especial atención en la accesibilidad web:

- Uso de roles ARIA (`role="banner"`, `aria-label`, `aria-hidden`).
- Encabezados jerárquicos correctos (`h1` → `h2` → `h3`).
- Textos alternativos en imágenes.
- Foco visible en enlaces (`:focus-visible`).
- El proyecto `proyectoAAA` busca cumplir con el nivel **AAA** de las [WCAG 2.1](https://www.w3.org/TR/WCAG21/).
