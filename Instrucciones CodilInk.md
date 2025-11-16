# 📘 CodiLink – Guía de Uso y Organización del Proyecto

Este README explica cómo utilizar **CodiLink** para ejecutar proyectos web y cómo debes organizar tus archivos **HTML**, **CSS** y **JavaScript** para que funcionen correctamente dentro del entorno.

---

## 🚀 1. ¿Qué es CodiLink?

**CodiLink** es un entorno online donde puedes ejecutar código web (HTML, CSS, JS) sin necesidad de instalar nada en tu computadora.  
Permite cargar archivos, editar en tiempo real y previsualizar el resultado.

---

## 📁 2. Estructura recomendada del proyecto

Para que CodiLink cargue correctamente tus archivos, utiliza esta estructura:
```html
/project-folder
│
├── index.html          # Archivo principal
│
├── css/
│   └── styles.css      # Tus estilos
│
├── js/
│   └── app.js          # Tu código JavaScript
│
└── assets/             # Imágenes, íconos, sonidos, etc.
    └── logo.png
```


### ✔ ¿Por qué así?

- `index.html` debe estar en la raíz del proyecto.  
- CSS dentro de una carpeta `css/`.  
- JS dentro de una carpeta `js/`.  
- Recursos dentro de `assets/`.

---

## 🧩 3. Cómo enlazar los archivos HTML, CSS y JS

En tu `index.html`, agrega:

### 📌 CSS
```html
<link rel="stylesheet" href="css/styles.css">
<script src="js/app.js"></script>
```
## 🛠 4. Cómo usar CodiLink paso a paso

### 🔹 1. Ingresa a CodiLink

Ve al sitio oficial: https://codilink.com



(o la URL que te hayan proporcionado en tu curso o taller)

---

### 🔹 2. Crea un nuevo proyecto

- Haz clic en **New Project**
- Selecciona **HTML / CSS / JS Project**

---

### 🔹 3. Sube tu carpeta de proyecto

- Arrastra tu carpeta completa (`project-folder`) al editor.
- Verás tus carpetas en la barra lateral.

---

### 🔹 4. Abre `index.html`

Este será el archivo que se visualiza como página principal.

---

### 🔹 5. Verifica los enlaces

Asegúrate de que las rutas sean correctas:

- Si los estilos no cargan → revisar `css/styles.css`
- Si JavaScript no funciona → revisar `js/app.js`

---

### 🔹 6. Ejecuta tu proyecto

Haz clic en **Run**, **Preview**, o en el botón de **Play**, según CodiLink.



