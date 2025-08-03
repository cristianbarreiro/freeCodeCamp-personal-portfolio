# 🌟 Portfolio Personal - Juan Pérez

Un portfolio personal moderno y responsivo desarrollado con HTML, CSS y JavaScript vanilla. Diseñado para mostrar proyectos, experiencia y habilidades de manera profesional y atractiva.

## 🚀 Demo

Puedes ver el portfolio en vivo aquí: [Portfolio Personal](https://juanperez.dev)

## ✨ Características

- **📱 Diseño Responsivo**: Adaptado para desktop, tablet y móviles
- **🎨 Interfaz Moderna**: Diseño limpio y profesional con colores atractivos
- **🍔 Menú Hamburguesa**: Navegación móvil intuitiva con animaciones suaves
- **⚡ Rendimiento Optimizado**: Código ligero sin dependencias externas
- **🎯 Navegación Suave**: Scroll suave entre secciones
- **♿ Accesible**: Cumple con estándares de accesibilidad web
- **🎨 Efectos Visuales**: Hover effects y transiciones elegantes

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica y accesible
- **CSS3**: Estilos modernos con Flexbox y Grid
- **JavaScript Vanilla**: Funcionalidad interactiva sin frameworks
- **CSS Variables**: Sistema de colores personalizable
- **Media Queries**: Diseño responsivo nativo

## 📁 Estructura del Proyecto

```
personal-portfolio/
│
├── index.html          # Archivo principal HTML
├── styles.css          # Estilos CSS
├── README.md           # Documentación del proyecto
├── LICENSE             # Licencia MIT
└── assets/             # Recursos (imágenes, iconos, etc.)
```

## 🎨 Paleta de Colores

```css
:root {
  --color-bg: #f8f6ff;           /* Fondo principal */
  --color-primary: #7c3aed;      /* Color primario (violeta) */
  --color-secondary: #232136;    /* Color secundario (oscuro) */
  --color-accent: #ffb4a2;       /* Color de acento (salmón) */
  --color-white: #f9f9fb;        /* Blanco suave */
  --color-gray: #6e6a86;         /* Gris medio */
  --color-highlight: #ff6f61;    /* Color de resaltado (coral) */
}
```

## 📱 Características Responsivas

### Desktop (1024px+)
- Navegación horizontal completa
- Logo visible en el navbar
- Diseño de múltiples columnas
- Efectos hover interactivos

### Tablet (768px - 1023px)
- Menú hamburguesa
- Diseño adaptado a columnas
- Espaciado optimizado

### Móvil (320px - 767px)
- Menú hamburguesa a la izquierda
- Logo oculto para maximizar espacio
- Diseño de una columna
- Botones táctiles optimizados

## 🚀 Instalación y Uso

1. **Clona el repositorio:**
   ```bash
   git clone https://github.com/cristianbarreiro/personal-portfolio.git
   ```

2. **Navega al directorio:**
   ```bash
   cd personal-portfolio
   ```

3. **Abre el archivo en tu navegador:**
   ```bash
   # Opción 1: Abrir directamente
   open index.html
   
   # Opción 2: Usar un servidor local
   python -m http.server 8000
   # Luego visita: http://localhost:8000
   ```

## ⚙️ Personalización

### Cambiar Colores
Modifica las variables CSS en `styles.css`:
```css
:root {
  --color-primary: #tu-color-aqui;
  --color-secondary: #tu-color-aqui;
  /* ... más colores */
}
```

### Actualizar Contenido
1. **Información Personal**: Edita las secciones en `index.html`
2. **Proyectos**: Modifica los `.project-tile` con tus proyectos
3. **Experiencia**: Actualiza la sección `#experience`
4. **Habilidades**: Modifica la lista en `#skills`

### Agregar Nuevas Secciones
```html
<section id="nueva-seccion">
  <h2>Nueva Sección</h2>
  <!-- Tu contenido aquí -->
</section>
```

No olvides agregar el enlace en el navbar:
```html
<li><a href="#nueva-seccion" class="nav-link">Nueva Sección</a></li>
```

## 📊 Rendimiento

- **Tiempo de carga**: < 2 segundos
- **Tamaño total**: < 50KB
- **Sin dependencias externas**
- **Optimizado para SEO**

## 🌐 Compatibilidad de Navegadores

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Opera 47+

## 📈 SEO y Accesibilidad

- **HTML Semántico**: Uso correcto de tags semánticos
- **Alt Text**: Todas las imágenes incluyen texto alternativo
- **Aria Labels**: Etiquetas de accesibilidad para elementos interactivos
- **Contraste**: Colores que cumplen WCAG 2.1 AA
- **Navegación por Teclado**: Totalmente navegable con teclado

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! Por favor:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📝 Próximas Mejoras

- [ ] Modo oscuro/claro
- [ ] Animaciones más avanzadas
- [ ] Formulario de contacto funcional
- [ ] Integración con APIs sociales
- [ ] Blog personal
- [ ] Galería de imágenes
- [ ] Múltiples idiomas

## 📞 Contacto

**Juan Pérez** - Desarrollador Web

- 🌐 Website: [juanperez.dev](https://juanperez.dev)
- 📧 Email: juan@ejemplo.com
- 💼 LinkedIn: [linkedin.com/in/juanperez](https://linkedin.com/in/juanperez)
- 🐙 GitHub: [github.com/juanperez](https://github.com/juanperez)

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.

---

⭐ **¡Si te gusta este proyecto, no olvides darle una estrella!** ⭐

---

*Desarrollado con ❤️ por Cristian Barreiro*
