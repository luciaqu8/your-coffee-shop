# Your Coffee Shop - Onepage Landing Template

---

## Índice

- [Descripción](#descripción)  
- [Características](#características)  
- [Instalación](#instalación)  
- [Estructura de Archivos](#estructura-de-archivos)  
- [Personalización](#personalización)  
  - [Cambiar textos](#cambiar-textos)  
  - [Modificar imágenes](#modificar-imágenes)  
  - [Colores y estilos](#colores-y-estilos)  
  - [Fuentes](#fuentes)  
  - [Menú móvil](#menú-móvil)  
- [Licencias](#licencias)  
- [Soporte](#soporte)  
- [Notas adicionales](#notas-adicionales)  

---

## Descripción

**Your Coffee Shop** es un template moderno, responsive y multipropósito de una sola página (onepage) ideal para cafeterías, negocios pequeños o proyectos creativos.  
Está construido con HTML5, CSS3 y JavaScript, usando fuentes locales y librerías populares como FontAwesome y Swiper para sliders.

---

## Características

- Diseño responsive y adaptable a dispositivos móviles, tablets y desktop.  
- Fuentes locales optimizadas con formatos `.woff2` y `.woff`.  
- Navegación accesible con soporte ARIA y teclado.  
- Slider de testimonios con Swiper.js.  
- Variables CSS para fácil personalización de colores, tamaños y radios.  
- Código limpio, modular y comentado.  
- Optimizado para SEO básico y performance.  

---

## Instalación

1. Descarga y descomprime el paquete completo.  
2. Abre el archivo `index.html` en tu navegador para ver el template.  
3. Para desarrollo, edita los archivos en la carpeta `css/`, `js/` y `assets/`.  
4. Para producción, usa los archivos minificados (`style.min.css`, `script.min.js`).  

---

## Estructura de Archivos

```
├── index.html              # Archivo principal
├── css/
│   └── style.min.css       # Estilos principales (minificado)
├── js/
│   └── script.js           # Funciones JS (menú, slider, etc.)
├── assets/
│   ├── hero.png            # Imagen principal del hero
│   ├── menu*.png           # Imágenes del menú
│   ├── user*.png           # Avatares de testimonios
│   └── aboutus.png         # Imagen sección "About Us"
├── vendor/
│   ├── fontawesome/        # Íconos
│   └── swiper/             # Librería slider
└── README.md               # Documentación
```

---

## Personalización

### Cambiar textos

- Abre `index.html` con un editor de texto o código (VSCode, Sublime, etc).  
- Busca los textos dentro de las etiquetas `<h2>`, `<p>`, `<a>`, etc.  
- Modifica los textos según tu contenido.  
- Ejemplo: Cambia el título en la sección Hero:  

```html
<h2 class="title">Probably World's 2nd Best Coffee</h2>
<h2 class="title">Welcome to My Coffee Shop</h2>
```

### Modificar imágenes

- Las imágenes están en la carpeta `/assets/images/` (o `/assets/` según tu estructura).  
- Reemplaza las imágenes por las tuyas manteniendo el mismo nombre o actualiza el atributo `src` en el HTML.  
- Asegúrate de mantener el formato y tamaño para evitar problemas de diseño.  
- Usa `loading="lazy"` para optimizar carga.  

### Colores y estilos

Los colores y estilos principales están definidos en variables CSS dentro de `css/style.css` o `style.min.css` en el selector `:root`.  
Ejemplo de variables:  

```css
:root {
  --primary-color: #3b141c;
  --secondary-color: #f3961c;
  --white-color: #fff;
  --dark-color: #252525;
  /* ... */
}
```

### Fuentes

- La fuente principal es **Poppins**, cargada localmente con `@font-face` en CSS.  
- Los archivos `.woff2` y `.woff` están en `/assets/fonts/Poppins/`.  
- Para cambiar la fuente, reemplaza los archivos y actualiza las reglas `@font-face` en `style.css`.  
- Mantén la propiedad `font-display: swap;` para mejorar la experiencia de carga.  

---

## Licencias

- **Fuente Poppins**: Licencia SIL Open Font License (OFL) 1.1 — uso libre para proyectos comerciales.  
  Más info: https://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL  

- **FontAwesome**: Licencia FontAwesome Free — uso libre con atribución.  
  Más info: https://fontawesome.com/license/free  

- **Swiper.js**: Licencia MIT — uso libre para proyectos comerciales.  
  Más info: https://github.com/nolimits4web/swiper/blob/master/LICENSE  

---

## Soporte

Este template no incluye soporte personalizado.  
Para dudas o problemas, revisa la documentación y los comentarios en el código.  
Puedes contactarme para servicios de personalización o desarrollo adicional.  

---

## Notas adicionales

¡Gracias por elegir este template!  
Esperamos que te ayude a crear sitios web increíbles y fáciles de personalizar.  