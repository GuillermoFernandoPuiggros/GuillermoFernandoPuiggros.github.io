# Sugerencias de Mejora para el Portfolio

## 🔴 Prioridad Alta - Personalización Básica

### 1. Actualizar `_config.yml`

El archivo de configuración aún contiene información del template original. Debes personalizarlo con tu información:

```yaml
title: Guillermo Puiggros
description: Tu Descripción Profesional
site_title: '@Guillermo-Puiggros - Guillermo Puiggros'
github_username: Guillermo-Puiggros
email: tu-email@ejemplo.com
blog_url: https://tu-blog.com (si tienes uno)
# Eliminar o actualizar redes sociales que no uses
```

### 2. Personalizar Sección "About" (`_includes/about.html`)

- Reemplazar el texto genérico con tu propia biografía profesional
- Actualizar enlaces a tu blog y GitHub
- Escribir en español o inglés según tu preferencia

### 3. Actualizar Proyectos (`assets/js/projects.js`)

- Eliminar los proyectos de ejemplo del template
- Agregar tus propios proyectos reales
- Asegurarte de que las imágenes existan en `assets/images/`
- Actualizar categorías según tus proyectos

### 4. Personalizar Habilidades (`_includes/skills.html`)

- Actualizar el resumen profesional
- Modificar las habilidades técnicas según tu experiencia
- Ajustar los porcentajes de competencia

### 5. Actualizar Sección de Contacto (`_includes/extra.html`)

- Personalizar el texto de contacto
- Actualizar enlaces a tu CV/resume
- Eliminar referencias a PGP key si no la usas

## 🟡 Prioridad Media - Mejoras de Contenido

### 6. Agregar Meta Tags SEO

En `_includes/head.html`, agregar:

- Meta description personalizada
- Open Graph tags para compartir en redes sociales
- Twitter Card tags
- Keywords relevantes

### 7. Mejorar Accesibilidad

- Agregar atributos `alt` descriptivos a todas las imágenes
- Verificar contraste de colores
- Agregar `aria-labels` donde sea necesario
- Asegurar navegación por teclado

### 8. Optimización de Imágenes

- Comprimir imágenes en `assets/images/` para mejorar tiempos de carga
- Usar formatos modernos (WebP) con fallback
- Agregar lazy loading a imágenes de proyectos

### 9. Agregar Analytics

- Configurar Google Analytics en `_config.yml` si lo deseas
- O considerar alternativas como Plausible Analytics

### 10. Internacionalización

- Si planeas tener contenido en múltiples idiomas, considerar i18n
- O mantener consistencia en un solo idioma

## 🟢 Prioridad Baja - Mejoras Técnicas

### 11. Actualizar Dependencias

- Revisar `Gemfile` y actualizar versiones de Jekyll y plugins
- Verificar compatibilidad con GitHub Pages

### 12. Agregar Tests

- Considerar tests básicos para verificar que el sitio se construye correctamente
- Validar HTML/CSS

### 13. Mejorar Performance

- Minificar CSS y JavaScript en producción
- Implementar service worker para cache (PWA)
- Optimizar fuentes web

### 14. Agregar Dark Mode

- Implementar toggle para modo oscuro
- Guardar preferencia del usuario

### 15. Mejorar Formulario de Contacto

- Si agregas un formulario, considerar servicios como Formspree o Netlify Forms
- Agregar validación del lado del cliente

### 16. Agregar Blog Funcional

- Si planeas blog, configurar posts en `_posts/`
- Personalizar `_includes/blogs.html`

### 17. Agregar Certificados/Educación

- Considerar agregar una sección para certificaciones o educación
- Mostrar logros profesionales

### 18. Mejorar Responsive Design

- Probar en diferentes dispositivos
- Ajustar breakpoints si es necesario
- Verificar que todas las animaciones funcionen en móvil

## 📝 Notas Adicionales

### Checklist de Personalización

- [ ] Actualizar `_config.yml` con tu información
- [ ] Personalizar sección About
- [ ] Reemplazar proyectos de ejemplo
- [ ] Actualizar habilidades
- [ ] Personalizar sección de contacto
- [ ] Agregar tus propias imágenes
- [ ] Actualizar README (ya hecho ✅)
- [ ] Configurar Google Analytics (opcional)
- [ ] Probar el sitio localmente
- [ ] Verificar que GitHub Pages funciona correctamente

### Recursos Útiles

- [Documentación de Jekyll](https://jekyllrb.com/docs/)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Jekyll Themes](https://jekyllthemes.io/) para inspiración

---

**Nota**: Estas son sugerencias generales. Prioriza según tus necesidades y objetivos profesionales.
