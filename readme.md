# CRUDScope – HTML MediaPanel

##  Descripción general
Este proyecto es una página HTML estática que simula el panel de un sistema CRUD de tareas.  
El objetivo principal es practicar la estructura semántica de HTML5, etiquetas no semánticas, multimedia y elementos poco comunes como `<base>`, `<abbr>` y `<time>`.

También se incluyen listas, tablas, formularios y navegación interna en una sola página.

---

##  Investigación de etiquetas

### **1. Estructura**
**Etiquetas:** html, head, body, title, base, meta  
**Uso:** Definen la estructura principal del documento HTML.  
**Caso típico:** Toda página web inicia con estas etiquetas.

---

### **2. Etiquetas semánticas**
**Etiquetas:** header, nav, main, section, article, aside, footer, address, time  
**Uso:** Dan significado al contenido y mejoran accesibilidad y SEO.  
**Caso típico:** Organizar un sitio en secciones claras y comprensibles.

---

### **3. Etiquetas no semánticas**
**Etiquetas:** div, span  
**Uso:** Agrupan o resaltan contenido sin aportar significado semántico.  
**Caso típico:** Dar estilos o crear contenedores sin relevancia lógica.

---

### **4. Texto y formato**
**Etiquetas:** h1, h2, h3, p, strong, em, u, mark, abbr  
**Uso:** Encabezados, párrafos y resaltado de texto.  
**Caso típico:** Presentar información con importancia diferenciada.

---

### **5. Tablas**
**Etiquetas:** table, tr, th, td  
**Uso:** Mostrar datos tabulares.  
**Caso típico:** Listados o reportes.

---

### **6. Formularios**
**Etiquetas:** form, label, input, textarea, button  
**Uso:** Captura de datos.  
**Caso típico:** Formularios de registro, login o creación de tareas.

---

### **7. Multimedia**
**Etiquetas:** img, audio, video, source  
**Uso:** Mostrar contenido multimedia directamente en el navegador.  
**Caso típico:** Reproductores nativos sin plugins externos.

---

##  Diferencia entre etiquetas semánticas y no semánticas

### **Semánticas**
Aportan significado al contenido, útil para navegadores, accesibilidad y SEO.  
**Ejemplo:** `<header>` indica un encabezado, `<article>` representa contenido independiente.

**Se usan cuando el contenido tiene una función clara dentro de la estructura.**

### **No semánticas**
No describen el propósito del contenido.  
**Ejemplo:** `<div>` solo es un contenedor genérico.

 **Se usan cuando se necesita agrupar elementos sin un rol específico.**

---

##  Enfoque en etiquetas poco comunes

### **`<base>`**
Define una URL base para todos los enlaces relativos de la página.  
Permite que `<a href="pagina.html">` apunte automáticamente a la URL base.

### **`<abbr>`**
Indica una abreviatura, permitiendo mostrar su significado al pasar el cursor.  
Ejemplo: `<abbr title="Create Read Update Delete">CRUD</abbr>`

### **`<time>`**
Representa una fecha u hora en formato legible para máquinas.  
Ayuda a buscadores y sistemas automatizados.

### **Ventajas del audio y video HTML5**
- No requieren plugins externos (como Flash).
- Funcionan nativamente en navegadores modernos.
- Permiten controles integrados.
- Mayor accesibilidad.

---

##  Referencias
- MDN Web Docs  
- W3Schools HTML Guide  
- Documentación oficial HTML Living Standard  

---

## ✔ Autor
meikuto — 2025

