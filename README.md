# Your Coffee Shop - Onepage Landing Template

---

## Table of Contents

- [Description](#description)  
- [Features](#features)  
- [Installation](#installation)  
- [File Structure](#file-structure)  
- [Customization](#customization)  
  - [Change Texts](#change-texts)  
  - [Modify Images](#modify-images)  
  - [Colors and Styles](#colors-and-styles)  
  - [Fonts](#fonts)  
  - [Mobile Menu](#mobile-menu)  
- [Licenses](#licenses)  
- [Support](#support)  
- [Additional Notes](#additional-notes)  

---

## Description

**Your Coffee Shop** is a modern, responsive, and multipurpose one-page template ideal for coffee shops, small businesses, or creative projects.  
It is built with HTML5, CSS3, and JavaScript, using local fonts and popular libraries like FontAwesome and Swiper for sliders.

---

## Features

- Responsive design adaptable to mobile devices, tablets, and desktops.  
- Local fonts optimized with `.woff2` and `.woff` formats.  
- Accessible navigation with ARIA and keyboard support.  
- Testimonial slider with Swiper.js.  
- CSS variables for easy customization of colors, sizes, and border-radius.  
- Clean, modular, and well-commented code.  
- Basic SEO and performance optimized.  

---

## Installation

1. Download and unzip the complete package.  
2. Open `index.html` in your browser to view the template.  
3. For development, edit the files in the `css/`, `js/`, and `assets/` folders.  
4. For production, use the minified files (`style.min.css`, `script.min.js`).  

---

## File Structure

```
├── index.html              # Main file
├── css/
│   └── style.min.css       # Main styles (minified)
├── js/
│   └── script.js           # JS functions (menu, slider, etc.)
├── assets/
│   ├── hero.png            # Main hero image
│   ├── menu*.png           # Menu images
│   ├── user*.png           # Testimonial avatars
│   └── aboutus.png         # About Us section image
├── vendor/
│   ├── fontawesome/        # Icons
│   └── swiper/             # Slider library
└── README.md               # Documentation
```

---

## Customization

### Change Texts

- Open `index.html` with a text or code editor (VSCode, Sublime, etc.).  
- Find the texts inside `<h2>`, `<p>`, `<a>`, etc.  
- Modify the texts according to your content.  
- Example: Change the title in the Hero section:

```html
<h2 class="title">Probably World's 2nd Best Coffee</h2>
<h2 class="title">Welcome to My Coffee Shop</h2>
```

### Modify Images

- Images are in the `/assets/images/` (or `/assets/` depending on your structure).  
- Replace the images with yours keeping the same name or update the `src` attribute in the HTML.  
- Make sure to maintain format and size to avoid layout issues.  
- Use `loading="lazy"` for optimized loading.  

### Colors and Styles

Main colors and styles are defined in CSS variables inside `css/style.css` or `style.min.css` under the `:root` selector.  
Example of variables:

```css
:root {
  --primary-color: #3b141c;
  --secondary-color: #f3961c;
  --white-color: #fff;
  --dark-color: #252525;
  /* ... */
}
```

### Fonts

- The main font is **Poppins**, loaded locally using `@font-face` in CSS.  
- The `.woff2` and `.woff` files are in `/assets/fonts/Poppins/`.  
- To change the font, replace the files and update the `@font-face` rules in `style.css`.  
- Keep `font-display: swap;` for better loading experience.  

---

## Licenses

- **Poppins Font**: SIL Open Font License (OFL) 1.1 — free for commercial projects.  
  More info: https://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL  

- **FontAwesome**: FontAwesome Free License — free to use with attribution.  
  More info: https://fontawesome.com/license/free  

- **Swiper.js**: MIT License — free for commercial projects.  
  More info: https://github.com/nolimits4web/swiper/blob/master/LICENSE  

---

## Support

This template does not include personalized support.  
For questions or issues, check the documentation and code comments.  
You can contact me for customization or additional development services.  

---

## Additional Notes

Thank you for choosing this template!  
We hope it helps you create amazing and easily customizable websites.

