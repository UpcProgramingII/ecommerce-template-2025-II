# 🛒 PROYECTO E-COMMERCE - PLANTILLA EDUCATIVA

## Proyecto Final - Curso de Desarrollo de Páginas Web Básico
### Universidad Popular del Cesar (UPC)

---

## 📖 Descripción

Plantilla completa de sitio web e-commerce desarrollada para estudiantes sin conocimientos previos de programación. Incluye diseño profesional, estructura organizada y código fácil de personalizar.

### ✨ Características principales:

- ✅ 6 páginas HTML completas
- ✅ Diseño responsive (se adapta a móviles)
- ✅ Sistema de cotización funcional
- ✅ Catálogo de productos personalizable
- ✅ Carousel automático de imágenes
- ✅ Código comentado y documentado
- ✅ Fácil de personalizar sin conocimientos avanzados

---

## 📁 Estructura del Proyecto

```
mi-ecommerce/
│
├── index.html              # Página de inicio
├── quienes-somos.html      # Página Quiénes Somos
├── historia.html           # Página Nuestra Historia
├── catalogo.html           # Catálogo de productos
├── cotizacion.html         # Sistema de cotización
├── creditos.html           # Página de créditos
│
├── css/
│   └── estilos.css         # Todos los estilos CSS
│
├── js/
│   └── scripts.js          # Funcionalidades JavaScript
│
└── imagenes/
    ├── banner1.jpg         # Carousel
    ├── banner2.jpg
    ├── banner3.jpg
    ├── producto1-6.jpg     # Productos
    ├── equipo1-3.jpg       # Fotos del equipo
    ├── logo-gobernacion.png
    └── logo-upc.png
```

---

## 🚀 Instalación y Configuración

### Paso 1: Descargar los archivos

1. Descarga todos los archivos del proyecto
2. Crea una carpeta llamada `mi-ecommerce`
3. Organiza los archivos según la estructura mostrada arriba

### Paso 2: Preparar las imágenes

Descarga o crea las siguientes imágenes y guárdalas en la carpeta `imagenes`:

**Requeridas:**
- 3 banners para carousel (1200x400 px)
- 6 imágenes de productos (250x200 px)
- 3 fotos del equipo (150x150 px)
- 2 logos institucionales (200x100 px)

**Opcionales:**
- Logo del e-commerce (300x80 px)
- Imágenes de contenido (600x350 px)

### Paso 3: Abrir el proyecto

1. Abre la carpeta `mi-ecommerce`
2. Haz doble clic en `index.html`
3. El sitio se abrirá en tu navegador predeterminado

---

## 🎨 Personalización Básica

### 1. Cambiar colores

**Archivo:** `css/estilos.css`

Busca estas líneas (21-27) y cambia los códigos de color:

```css
:root {
    --color-principal: #2c3e50;
    --color-secundario: #3498db;
    --color-acento: #e74c3c;
}
```

### 2. Cambiar nombre del sitio

**Archivos:** Todas las páginas HTML

Busca y reemplaza en TODAS las páginas:

```html
<h1>🛒 MI E-COMMERCE</h1>
<p>Tu tienda de confianza</p>
```

### 3. Actualizar productos

**Archivo catálogo:** `catalogo.html`
**Archivo JavaScript:** `js/scripts.js` (líneas 91-98)

⚠️ **IMPORTANTE:** Los productos deben coincidir en ambos archivos.

### 4. Completar información del equipo

**Archivo:** `creditos.html`

Completa la información de cada miembro del equipo y agrega sus fotos.

---

## 📝 Requisitos Técnicos

### Navegadores compatibles:
- Google Chrome (recomendado)
- Mozilla Firefox
- Microsoft Edge
- Safari

### Conocimientos necesarios:
- Edición básica de texto
- Manejo de carpetas y archivos
- Uso de navegador web

### NO se requiere:
- Servidor web
- Base de datos
- Conocimientos avanzados de programación

---

## 🔧 Tecnologías Utilizadas

- **HTML5** - Estructura del sitio
- **CSS3** - Estilos y diseño responsive
- **JavaScript** - Interactividad y funcionalidades
- Sin dependencias externas
- Sin frameworks complejos

---

## 📚 Documentación

### Guías incluidas:

1. **GUÍA DE PERSONALIZACIÓN ACTUALIZADA** - Paso a paso completo
2. **Comentarios en el código** - Explicaciones en cada sección
3. **Este README** - Información general del proyecto

### Archivos de apoyo:

- `estilos.css` - Comentarios explicativos en cada sección
- `scripts.js` - Código JavaScript documentado
- Todas las páginas HTML con comentarios

---

## ✅ Lista de Verificación

Antes de entregar tu proyecto, verifica:

### Archivos:
- [ ] Todos los archivos HTML en la carpeta principal
- [ ] `estilos.css` en carpeta `css`
- [ ] `scripts.js` en carpeta `js`
- [ ] Todas las imágenes en carpeta `imagenes`

### Personalización:
- [ ] Colores personalizados
- [ ] Nombre del sitio cambiado en todas las páginas
- [ ] Footer actualizado en todas las páginas
- [ ] Productos actualizados (catálogo y JavaScript)
- [ ] Página de créditos completada
- [ ] Fotos del equipo agregadas

### Funcionalidad:
- [ ] Menú funciona correctamente
- [ ] Carousel cambia automáticamente
- [ ] Cotización calcula correctamente
- [ ] Todas las imágenes se cargan
- [ ] Sitio se ve bien en móvil

---

## 🐛 Solución de Problemas

### Las imágenes no se cargan

**Solución:**
- Verifica que el nombre del archivo coincida exactamente
- Revisa que esté en la carpeta `imagenes`
- Comprueba la extensión (.jpg, .png)

### Los estilos no se aplican

**Solución:**
Verifica que todas las páginas tengan:
```html
<link rel="stylesheet" href="css/estilos.css">
```

### El JavaScript no funciona

**Solución:**
Verifica que todas las páginas tengan:
```html
<script src="js/scripts.js"></script>
```

### La cotización no calcula

**Solución:**
- Verifica que los códigos de productos coincidan
- En JavaScript, los precios NO deben tener símbolo $
- Usa punto (.) en decimales: `29.99` no `29,99`

---

## 📞 Soporte

Si tienes problemas:

1. Consulta la **GUÍA DE PERSONALIZACIÓN ACTUALIZADA**
2. Revisa los comentarios en el código
3. Consulta con tu instructor
4. Revisa la consola del navegador (F12)

---

## 👥 Créditos

### Desarrollado para:
- **Curso:** Desarrollo de Páginas Web Básico
- **Institución:** Universidad Popular del Cesar (UPC)
- **Apoyo:** Gobernación del Cesar

### Propósito:
Proyecto educativo para enseñar desarrollo web básico a estudiantes sin experiencia previa en programación.

---

## 📄 Licencia

Este proyecto es de uso educativo para estudiantes de la Universidad Popular del Cesar.

---

## 🎓 Objetivos de Aprendizaje

Al completar este proyecto, los estudiantes habrán:

1. ✅ Estructurado un sitio web completo con HTML
2. ✅ Aplicado estilos CSS y diseño responsive
3. ✅ Implementado funcionalidades con JavaScript
4. ✅ Organizado archivos y carpetas correctamente
5. ✅ Integrado imágenes y contenido multimedia
6. ✅ Creado un proyecto funcional y profesional

---

## 📊 Características del Proyecto

| Característica | Descripción |
|----------------|-------------|
| **Páginas** | 6 páginas HTML interconectadas |
| **Diseño** | Responsive y profesional |
| **Código** | Comentado y documentado |
| **Imágenes** | Sistema de fallback incluido |
| **Navegación** | Menú funcional en todas las páginas |
| **Cotización** | Sistema automático de cálculo |
| **Carousel** | Rotación automática de banners |

---

## 🌟 Características Destacadas

### Para Estudiantes:
- ✨ Código fácil de entender
- ✨ Comentarios explicativos
- ✨ Guías paso a paso
- ✨ Sin configuraciones complejas

### Para Instructores:
- ✨ Proyecto completo y funcional
- ✨ Fácil de calificar
- ✨ Escalable y personalizable
- ✨ Incluye mejores prácticas

---

## 📈 Versión

**Versión:** 1.0  
**Fecha:** Octubre 2024  
**Última actualización:** Estructura modular con archivos separados

---

## 🎯 Próximos Pasos

Después de completar este proyecto, puedes:

1. Agregar más productos al catálogo
2. Personalizar aún más los colores y diseño
3. Agregar más páginas al sitio
4. Implementar un formulario de contacto
5. Agregar animaciones CSS adicionales
6. Integrar mapas de Google
7. Añadir más funcionalidades JavaScript

---

**¡Éxito con tu proyecto! 🚀**

Para más información, consulta la **GUÍA DE PERSONALIZACIÓN ACTUALIZADA**.