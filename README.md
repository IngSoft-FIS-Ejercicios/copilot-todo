# Usando GitHub Copilot para Crear una Lista de Tareas

## 🎯 Objetivos
- Configurar GitHub Copilot en Visual Studio Code: Aprender a instalar y autenticar la extensión de GitHub Copilot para comenzar a usarla.
- Generar código automáticamente con Copilot: Utilizar Copilot para sugerir y completar el código necesario para crear una aplicación de lista de tareas.
- Integrar HTML, CSS y JavaScript: Implementar la funcionalidad de la lista de tareas y personalizar el estilo para que sea atractivo.
- Aprender a optimizar el flujo de trabajo con Copilot: Explorar cómo Copilot puede agilizar el desarrollo y resolver problemas comunes en la programación.

## ⚙️ Configuración Inicial

### Prerrequisitos

- Asegurate de tener **Visual Studio Code** instalado.
- Instala la **extensión de GitHub Copilot** y autenticate con tu cuenta de GitHub.

## 🧠 Generación del Código Usando GitHub Copilot

Abre cada uno de los archivos y sigue las indicaciones a continuación para generar el código utilizando Copilot:

### Paso 1: Generar la estructura básica del HTML

En `index.html`, escribe un comentario para indicar a Copilot que genere la estructura HTML básica:

```html
<!-- @workspace, genera la estructura básica del HTML -->
```

Presiona `Ctrl + Enter` (o `Cmd + Enter` en Mac) para que Copilot sugiera la estructura inicial del archivo. Acepta la sugerencia.

### Paso 2: Crear un formulario para agregar tareas

Añade un formulario con un campo de texto y un botón para agregar tareas:

```html
<!-- @workspace, genera un formulario con un input para agregar tareas y un botón de agregar -->
```

### Paso 3: Mostrar la lista de tareas y el formulario

Configura la estructura HTML para que la lista de tareas se muestre arriba del formulario:

```html
<!-- @workspace, genera una lista de tareas en una lista ordenada con el formulario para agregar tareas debajo -->
```

### Paso 4: Agregar funcionalidad con JavaScript

En `script.js`, escribe lo siguiente para que Copilot genere el código necesario para agregar tareas a la lista:

```javascript
// @workspace, genera el JavaScript necesario para agregar tareas a la lista y mostrarlas en la interfaz
```

### Paso 5: Editar el estilo con CSS

En `styles.css`, pídele a Copilot que sugiera un estilo moderno para el formulario y la lista de tareas:

```css
/* @workspace, sugiere un estilo moderno para la lista de tareas y el formulario */
```

### Paso 6: Agregar funcionalidad adicional

Para agregar un checkbox en cada tarea, sigue estos pasos en `index.html`:

```html
<!-- @workspace, agrega un checkbox a cada elemento de la lista de tareas para marcarlo como completado -->
```

En `script.js`, agrega el comportamiento para tachar la tarea cuando se marque el checkbox:

```javascript
// @workspace, añade el código para tachar la tarea cuando el checkbox esté marcado
```

### Paso 7: Agregar un botón para eliminar tareas

Pídele a Copilot que añada un botón de eliminación junto a cada tarea:

```html
<!-- @workspace, agrega un botón para eliminar cada tarea en la lista -->
```

### Paso 8: Editar el estilo del checkbox y del botón

Utiliza `styles.css` para modificar el estilo del checkbox y del botón de eliminación:

```css
/* @workspace, edita el estilo del checkbox y el botón de eliminación para que combinen con el diseño */
```

### Paso 9: Sustituir el botón de eliminación por un ícono de papelera

Si tienes un ícono de papelera (`papelera.png`), pídele a Copilot que lo utilice en lugar del botón:

```html
<!-- @workspace, usa "papelera.png" como ícono de eliminación y ajústalo al tamaño adecuado -->
```

En `styles.css`, ajusta el tamaño de la imagen de la papelera:

```css
/* @workspace, ajusta el tamaño de "papelera.png" para que combine con el resto de la interfaz */
```

## 💻 Ejecución del Proyecto

1. Abre el archivo `index.html` en tu navegador para ver la aplicación funcionando.
2. Prueba agregar, marcar como completadas y eliminar tareas para verificar que todo funcione como se espera.

---

**Nota:** Este README fue generado con la ayuda de una herramienta de inteligencia artificial
