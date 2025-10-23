# PatagoniaX - Sitio Web Corporativo

## Descripción del Proyecto
Sitio web corporativo para PatagoniaX, una startup argentina líder en desarrollo de software a medida desde 1998. El sitio presenta todos los servicios, proyectos y soluciones tecnológicas que ofrece la empresa.

## Características Principales

### Tecnologías Utilizadas
- **HTML5** semántico para estructura optimizada
- **CSS3** con variables personalizadas y animaciones
- **Bootstrap 5** para grid system y componentes responsivos
- **Tailwind CSS** para estilos utility-first
- **JavaScript Vanilla** para interactividad
- **Particles.js** para animación de fondo del hero
- **Swiper.js** para carrusel de clientes
- **AOS.js** para animaciones al scroll
- **Font Awesome 6** para iconografía

### Secciones del Sitio
1. **Navbar** - Navegación fija transparente que cambia a fondo blanco al hacer scroll, inspirada en Grupo Vansur
2. **Hero Section** - Animación de partículas con mensajes clave y badge "Since 1998"
3. **Sobre Nosotros** - Historia, estadísticas, misión, visión y valores
4. **Servicios** - 15 servicios detallados (sistemas agroindustriales, CRM, etc.)
5. **Proyectos** - 6 tipos de proyectos llave en mano
6. **Marketing Digital** - Área especializada con imagen de equipo trabajando
7. **Clientes** - Carrusel rotativo de logos de clientes
8. **Contacto** - Formulario y datos de contacto
9. **Footer** - Enlaces rápidos y redes sociales

### Optimización SEO
- Meta tags completos (descripción, keywords, author)
- Open Graph para redes sociales
- Twitter Cards
- Sitemap.xml
- Robots.txt
- Estructura semántica HTML5
- URLs canónicas

### Seguridad Web
- Headers de seguridad configurados (X-Frame-Options, X-XSS-Protection, etc.)
- Cache-Control para prevenir caching de contenido desactualizado
- Content Security Policy implementado
- Validación de formularios en frontend

### Diseño y Branding
- **Colores principales**: Dorado (#D4AF37), gradientes gold
- **Tipografía**: JetBrains Mono (títulos), Inter (cuerpo)
- **Logo**: PatagoniaX con símbolo atómico dorado
- **Estilo**: Moderno, tecnológico, profesional

### Características Responsive
- Diseño mobile-first
- Breakpoints optimizados para todos los dispositivos
- Navbar colapsable en móviles con menú hamburguesa
- Grid adaptativo para tarjetas de servicios
- Navbar transparente en todos los dispositivos

## Estructura de Archivos
```
/
├── index.html              # Página principal
├── server.py              # Servidor web Python con headers de seguridad
├── sitemap.xml            # Mapa del sitio para SEO
├── robots.txt             # Instrucciones para crawlers
├── assets/
│   ├── css/
│   │   └── styles.css     # Estilos personalizados
│   ├── js/
│   │   └── main.js        # JavaScript interactivo (scroll, navbar, particles)
│   └── images/
│       ├── logo-gold.png        # Logo para navbar con scroll
│       ├── logo-silver.png
│       └── logo-gradient.png    # Logo para navbar transparente
└── attached_assets/
    └── stock_images/
        └── team_working_in_mode_a9c94638.jpg  # Imagen Marketing Digital
```

## Frases de Marca
- "Líderes en soluciones tecnológicas"
- "Since 1998"
- "Innovación digital que impulsa tu crecimiento"
- "Startup #1 en tecnología y desarrollo"

## Datos de Contacto
- **Teléfono**: +542994211249
- **Email**: comercial@patagoniax.com
- **Ubicación**: Argentina

## Cambios Recientes
**23 de octubre de 2025 - Actualización de UI**
- Navbar ahora es transparente inicialmente y cambia a fondo blanco al hacer scroll
- Logo cambia dinámicamente de logo-gradient.png a logo-gold.png al scrollear
- Hero section optimizado: eliminado "Líderes en soluciones tecnológicas"
- "Since 1998" reubicado debajo de los botones CTA con estilo gris claro
- Botón de contacto renombrado de "Hablemos" a "Contacto"
- Sección Marketing Digital actualizada con imagen profesional de equipo
- Mejoras en navbar mobile con mejor contraste y legibilidad
- Content Security Policy reforzado sin 'unsafe-inline' en scripts

**23 de octubre de 2025 - Lanzamiento Inicial**
- Creación inicial del sitio web completo
- Implementación de todas las secciones
- Configuración de servidor web con seguridad
- Optimización SEO completa

## Próximas Mejoras Propuestas
- Integración de analytics y tracking
- Sistema de blog para casos de éxito
- Portal de clientes
- Formulario de cotización interactivo
- Versión multiidioma (Español/Inglés)

## Notas Técnicas
- El servidor corre en puerto 5000
- Headers de seguridad configurados en server.py
- Cache deshabilitado para desarrollo
- Animaciones optimizadas con AOS
- Carrusel con autoplay cada 3 segundos
