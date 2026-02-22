# TEST CASES
Proyecto: Testing Página Ofertas - PrestaShop  
QA: Hernán Machado  
Fecha: 22/02/2026  

---

## TC-01 - Validar carga correcta de productos

**ID:** TC-01  
**Módulo:** Listado de productos  
**Tipo de prueba:** Funcional  
**Prioridad:** Alta  

**Precondición:**  
El usuario accede a la página de ofertas.

**Pasos:**
1. Ingresar a la URL de la página de ofertas.
2. Esperar que la página cargue completamente.

**Resultado esperado:**
- Se visualiza el listado de productos.
- Cada producto muestra imagen, nombre y precio.
- No hay imágenes rotas.
- No se muestran errores visibles en pantalla.

---

## TC-02 - Validar redirección al detalle del producto

**ID:** TC-02  
**Módulo:** Navegación  
**Tipo de prueba:** Funcional  
**Prioridad:** Alta  

**Precondición:**  
El listado de productos se encuentra visible.

**Pasos:**
1. Hacer clic en un producto del listado.
2. Observar la redirección.

**Resultado esperado:**
- El sistema redirige correctamente a la página de detalle del producto.
- La URL cambia acorde al producto seleccionado.
- No se produce error 404.
- La información del producto se muestra correctamente.

---

## TC-03 - Validar comportamiento responsive en dispositivo móvil

**ID:** TC-03  
**Módulo:** Interfaz de usuario (UI)  
**Tipo de prueba:** No funcional (Responsive)  
**Prioridad:** Media  

**Precondición:**  
Página abierta en Google Chrome.

**Pasos:**
1. Abrir DevTools.
2. Activar modo responsive.
3. Seleccionar simulación de dispositivo móvil (ej: iPhone 14).
4. Navegar por la página y hacer scroll.

**Resultado esperado:**
- No hay superposición de elementos.
- Los textos son legibles.
- Los botones son clickeables.
- El scroll funciona correctamente.

---

## TC-04 - Validar validación de campo email con formato inválido

**ID:** TC-04  
**Módulo:** Formulario  
**Tipo de prueba:** Funcional (Negativa)  
**Prioridad:** Alta  

**Precondición:**  
Existe un formulario con campo email disponible.

**Pasos:**
1. Ingresar un email inválido (ej: test@).
2. Intentar enviar el formulario.

**Resultado esperado:**
- El sistema muestra mensaje de error.
- No permite el envío del formulario.
- El mensaje indica claramente que el formato es inválido.

---

## TC-05 - Prueba exploratoria de navegación general

**ID:** TC-05  
**Módulo:** Navegación general  
**Tipo de prueba:** Exploratoria  
**Prioridad:** Media  

**Precondición:**  
Página cargada correctamente.

**Pasos:**
1. Navegar entre distintos productos.
2. Utilizar el botón "Atrás" del navegador.
3. Realizar múltiples clics rápidos en distintos elementos.
4. Hacer scroll continuo hacia arriba y abajo.

**Resultado esperado:**
- No se producen errores de navegación.
- No aparecen pantallas en blanco.
- No se detectan errores visibles en consola.
- La experiencia de usuario se mantiene estable.
