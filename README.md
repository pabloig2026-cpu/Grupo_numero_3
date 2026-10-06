# Proyecto: E-commerce & Blog con Bootstrap (Grupo Número 3)

Este repositorio contiene el código fuente para el diseño, maquetación e integración de un sitio web completo, funcional y responsive (E-commerce y Blog), desarrollado de forma colaborativa bajo la metodología **Gitflow** y utilizando **HTML5, CSS3 y Bootstrap**.

🌐 **Sitio en vivo:** [https://grupo-numero-3.vercel.app/](https://grupo-numero-3.vercel.app/)

---

## Equipo de Desarrollo

* Valenzuela, Wilfredo Fabián
* Avila, Pablo Ignacio
* Bertini, Jose Francisco
* Villarroel, Matías Abel
* Simón, Juan Enrique

---

## 🛠️ Tecnologías y Criterios Técnicos

* **Frontend Framework:** Bootstrap (diseño completamente *responsive* para dispositivos móviles, tablets y escritorios).
* **Control de Versiones:** Git y GitHub corporativo, aplicando flujos de trabajo basados en ramas (`main`, `dev`, `feature/`, `fix/`) y resolución colaborativa de conflictos de código.
* **Metodología Ágil:** Planificación, asignación y seguimiento de tareas mediante un tablero en Trello.
* **Buenas Prácticas:** Estructuración modular de estilos CSS, código limpio, semántica HTML y validación de componentes interactivos nativos sin uso de lógica JavaScript compleja.

---

## 🧩 Componentes Globales

* **Navbar Fijo:** Barra de navegación superior accesible en todas las páginas con enlaces directos a las secciones de la tienda, Login, Contacto, Acerca de nosotros y un botón interactivo que despliega una **Ventana Modal** de suscripción.
* **Footer Responsive:** Pie de página estructurado con identidad visual unificada, columnas de navegación rápida, redes sociales e información institucional que se adapta fluidamente a pantallas de celulares.
* **Sidebar / Barra Lateral:** Panel unificado e integrado con campos de búsqueda optimizados, filtrado rápido por categorías de productos y espacios publicitarios adaptativos.

---

## 📂 Estructura de Páginas del Sitio

* **Página Principal (`index.html`):** 
  * Carrusel / Slider principal de ancho completo.
  * Grilla de productos/artículos destacados con diseño limpio y moderno.
  * Barra lateral personalizada con buscador integrado, listado de categorías interactivas (*Almohadas*, *Espejos*, *Pie de Cama*) y elementos de publicidad.
* **Páginas de Detalle de Productos (`pages/detalle_Producto.html`, etc.):** 
  * Vistas detalladas dedicadas a artículos individuales con especificaciones técnicas, galería multimedia, precio y sección interactiva inferior para comentarios de usuarios.
* **Páginas de Autenticación y Registro (`pages/login.html`, `pages/registrarse.html`):** 
  * Interfaces optimizadas con diseño visual unificado, formularios de acceso con alternativas de redes sociales y opciones para recuperación de credenciales.
* **Contacto (`pages/contacto.html`):** 
  * Formulario completo de atención al cliente y consulta comercial acompañado de integración geográfica o visualización de ubicación física.
* **Acerca de Nosotros (`pages/sobre_nosotros.html`):** 
  * Sección institucional centrada en los valores del equipo de desarrollo, presentación de integrantes con avatares personalizados y filosofías de trabajo.
* **Página de Error 404 (`pages/error_404.html`):** 
  * Pantalla de redirección estilizada para rutas no encontradas o enlaces en desarrollo, manteniendo la experiencia de navegación del usuario.

---

## 🚀 Despliegue y Control de Cambios

El proyecto cuenta con integración continua conectada a **Vercel**, permitiendo que cada fusión exitosa (*merge*) en la rama de producción actualice de manera automática el entorno público disponible en la web.
