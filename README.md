# 📝 Lista de la Compra - Cuaderno Digital

Una aplicación web completa para gestionar listas de la compra con control de presupuestos, persistencia local y sistema de listas guardadas.

## ✨ **Características Principales**

### **🛒 Gestión de Lista Actual**
- ✅ Añadir productos con cantidad
- 💰 Editar precios individualmente después de la compra
- ✅ Tachar productos comprados (suma al total gastado)
- 🗑️ Eliminar productos con confirmación
- 📊 Total gastado en tiempo real (solo productos tachados)

### **📚 Sistema de Listas Guardadas**
- 💾 Guardar listas con nombre personalizado
- 📂 Cargar listas anteriores
- 🗑️ Eliminar listas guardadas
- 📄 Exportar cualquier lista en formato TXT
- 📋 Miniaturas con resumen (fecha, items, total)

### **🎨 Interfaz de Usuario**
- 📖 Diseño de "cuaderno de notas" con líneas y tapas marrones
- ✍️ Fuentes manuscritas (Caveat y Reenie Beanie)
- 🎭 Modales personalizados para todas las confirmaciones
- 📱 Totalmente responsive para móviles
- 🔔 Notificaciones toast para feedback inmediato

### **💾 Persistencia y Seguridad**
- 🌐 Funciona 100% offline
- 💻 Guarda en localStorage del navegador
- 🔄 Recupera datos al recargar la página
- 🛡️ No requiere servidor ni conexión a internet

## 🚀 **Instalación y Uso**

### **Requisitos**
- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Conexión inicial para cargar Bootstrap y Google Fonts

### **Instalación**
1. **Descarga** el archivo `lista-de-la-compra.html`
2. **Abre** el archivo en tu navegador
3. **¡Listo!** La aplicación funciona inmediatamente

### **Uso Básico**
1. **Añadir productos**: Escribe el nombre + cantidad + Enter
2. **Marcar como comprado**: Tacha el checkbox
3. **Poner precio**: Edita el campo € del producto tachado
4. **Ver total**: Se actualiza automáticamente
5. **Guardar lista**: Botón "💾 Guardar" (pide nombre)
6. **Gestionar listas**: Usa las miniaturas abajo

## 🎯 **Flujo de Trabajo Recomendado**
1. Añade todos los productos planeados 🛒
2. Ve al supermercado con la lista 📋
3. Al comprar, marca ✓ y pon el precio real 💰
4. El total gastado se actualiza automáticamente 📊
5. Al terminar, guarda la lista 💾
6. Para la próxima compra, carga una lista anterior 📂


## 🔧 **Funcionalidades Avanzadas**

### **Control de Presupuesto**
- Solo suma productos **tachados** con precio
- Si destachas un producto, se resta del total
- Precios editables en cualquier momento
- Exportación con subtotales detallados

### **Gestión de Listas Múltiples**
- **Listas ilimitadas** guardadas localmente
- **Miniaturas informativas** con estadísticas
- **Carga rápida** reemplazando la actual
- **Exportación individual** de cada lista

### **Interfaz Intuitiva**
- **Modales confirmatorios** para acciones destructivas
- **Toast notifications** para feedback
- **Animaciones suaves** y hover effects
- **Teclado shortcuts** (Enter para añadir)

## 📱 **Responsive Design**
- ✅ **Desktop**: Layout completo con pestañas
- 📱 **Tablet**: Inputs adaptados horizontalmente
- 📴 **Móvil**: Inputs verticales, botones grandes
- 🔍 **Touch-friendly**: Botones y checkboxes grandes

## 🎨 **Diseño y Estilo**

### **Tema Visual**
- **Cuaderno físico**: Textura de papel con líneas
- **Tapas marrones**: Bordes estilo libreta
- **Degradados**: Colores modernos y profesionales
- **Iconos emoji**: Interfaz amigable y visual

### **Tipografía**
- **Caveat**: Texto principal (estilo manuscrito)
- **Reenie Beanie**: Títulos y totales (más decorativa)
- **Bootstrap**: Componentes UI consistentes

### **Colores**
- 🟢 **Verde**: Dinero, éxito, productos comprados
- 🔴 **Rojo**: Eliminar, advertencias
- 🟠 **Naranja**: Reset, acciones de limpieza
- 🟤 **Marrón**: Tema de cuaderno/libreta

## 💻 **Tecnologías Usadas**

- **HTML5**: Estructura semántica
- **CSS3**: Estilos modernos con Grid/Flexbox
- **JavaScript ES6+**: Lógica interactiva
- **Bootstrap 5.3**: Componentes UI responsive
- **localStorage**: Persistencia de datos
- **Google Fonts**: Tipografía personalizada

Estructura del Código

📁 HTML
├── Estructura responsive con Bootstrap
├── Modales personalizados
└── Componentes interactivos

📁 CSS
├── Diseño de cuaderno (textura, bordes)
├── Fuentes manuscritas
├── Animaciones y transiciones
└── Responsive breakpoints

📁 JavaScript
├── Gestión de estado (currentItems, savedLists)
├── Renderizado dinámico de listas
├── localStorage CRUD operations
├── Event listeners completos
└── Funciones utilitarias (export, toast)

Exportación de Datos

LISTA GUARDADA: Mi Compra Semanal
Fecha: 16/10/2025
Total: 45.67€

✅ 2x Leche - 1.89€ x 2 = 3.78€
⭕ 1x Pan - Sin precio
✅ 5x Manzanas - 0.45€ x 5 = 2.25€