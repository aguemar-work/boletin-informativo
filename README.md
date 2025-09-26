# 🚀 Generador de Boletín Informativo

Una aplicación web ligera y profesional para crear boletines informativos en segundos, sin necesidad de registro, configuración ni almacenamiento.

## ✨ Características Principales

### 🎯 Flujo de Uso Simple
1. **Redactar**: Completa el formulario con título, subtítulo, contenido, imágenes y enlaces
2. **Previsualizar**: Ve tu boletín en tiempo real con la plantilla seleccionada
3. **Copiar**: Un clic para copiar el HTML generado al portapapeles
4. **Pegar**: Pega directamente en Outlook, Gmail u otro cliente de correo

### 🎨 Plantillas Disponibles
- **Formal Corporativo**: Diseño profesional y elegante para comunicaciones oficiales
- **Moderno**: Estilo contemporáneo con colores vibrantes y tipografía moderna
- **Minimalista**: Diseño limpio y simple, enfocado en el contenido

### 🔧 Funcionalidades Técnicas
- ✅ **100% Frontend**: Sin backend ni base de datos
- ✅ **Responsive**: Funciona perfectamente en desktop y móvil
- ✅ **Accesible**: HTML semántico con roles ARIA y buen contraste
- ✅ **Tiempo Real**: Vista previa instantánea mientras escribes
- ✅ **Offline**: Funciona sin conexión después de cargado
- ✅ **Zero-Fricción**: Sin registro ni configuración necesaria

## 🚀 Instalación y Uso

### Prerrequisitos
- Node.js 18+ 
- npm o yarn

### Instalación
```bash
# Instalar dependencias
npm install

# Iniciar servidor de desarrollo
npm run dev
```

### Comandos Disponibles
```bash
npm run dev          # Servidor de desarrollo
npm run build        # Construir para producción
npm run preview      # Vista previa de la build
```

## 📝 Casos de Uso

### Empresariales
- Boletines mensuales de la empresa
- Anuncios de eventos corporativos
- Comunicados urgentes a empleados
- Reportes periódicos simplificados

### Personales
- Newsletters personales
- Invitaciones a eventos
- Comunicaciones familiares
- Actualizaciones de proyectos

## 🎨 Personalización

### Modificar Plantillas
Las plantillas se definen en `src/components/newletter/NewsletterForm.astro`:

```javascript
const templates = {
  formal: { 
    headerBg: '#2c3e50', 
    font: 'Arial, sans-serif',
    buttonBg: '#34495e',
    textColor: '#2c3e50'
  },
  // Agregar más plantillas aquí
};
```

## 🔧 Estructura del Proyecto

```
src/
├── components/
│   └── newletter/
│       ├── NewsletterForm.astro    # Formulario principal
│       ├── EmailPreview.astro      # Vista previa del email
│       └── TemplateSelector.astro  # Selector de plantillas
├── layouts/
│   └── Layout.astro               # Layout base
└── pages/
    └── index.astro               # Página principal
```

## 🌟 Características Técnicas Avanzadas

### Accesibilidad
- Etiquetas ARIA apropiadas
- Contraste de colores WCAG AA
- Navegación por teclado
- Lectores de pantalla compatibles

### Responsive Design
- Breakpoints: 480px, 768px, 1024px
- Grid adaptativo
- Botones táctiles (44px mínimo)
- Tipografía escalable

### Compatibilidad de Email
- HTML inline styles
- Imágenes optimizadas
- Fallbacks para clientes antiguos

---

**¿Necesitas ayuda?** Abre un issue en GitHub o contacta al equipo de desarrollo.
