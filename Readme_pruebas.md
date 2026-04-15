# 🧪 README - Pruebas

## 📌 Descripción

Este documento describe cómo realizar pruebas básicas del proyecto web para asegurar su correcto funcionamiento.

## ✅ Tipos de pruebas

### 1. Pruebas funcionales

Verificar que las páginas cargan correctamente:

* `index.html` → Página principal
* `category.html` → Listado de productos
* `single-product.html` → Detalle de producto
* `cart.html` → Carrito
* `checkout.html` → Proceso de compra
* `contact.html` → Formulario de contacto

✔ Validar:

* Navegación entre páginas
* Botones y enlaces
* Visualización correcta de imágenes

---

### 2. Pruebas de formulario

Archivo: `contact.html` + `contact_process.php`

✔ Validar:

* Envío correcto del formulario
* Validación de campos (nombre, email, mensaje)
* Manejo de errores

---

### 3. Pruebas visuales (UI)

✔ Verificar:

* Responsive design (móvil, tablet, desktop)
* Compatibilidad en navegadores:

  * Chrome
  * Firefox
  * Edge

---

### 4. Pruebas de rendimiento

✔ Evaluar:

* Tiempo de carga
* Optimización de imágenes (`/img`)
* Uso de recursos CSS/JS

---

### 5. Pruebas de integración

✔ Validar:

* Integración del formulario con PHP
* Rutas relativas de archivos

---

## 🛠️ Herramientas recomendadas

* Navegador con DevTools
* Lighthouse (para performance)
* Postman (para probar endpoints si se amplía backend)

---

## 🚨 Problemas comunes

* Rutas incorrectas de imágenes
* PHP no ejecuta (requiere servidor como XAMPP o similar)
* Formularios sin validación adecuada

---

## 📌 Recomendaciones

* Automatizar pruebas con herramientas como Cypress (opcional)
* Añadir validaciones JS en formularios
* Implementar pruebas unitarias si se agrega lógica JS