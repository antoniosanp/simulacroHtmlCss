# Guía de Recursos — Kora Estudio (Remodelación de Casas y Manejo de Espacios)

Este documento reúne todos los recursos visuales y técnicos utilizados en el diseño web responsivo (**Desktop y Mobile**) de **Kora Estudio**, pensado para ser replicado únicamente con **HTML5 y CSS3** (sin JavaScript ni pseudo-selectores).

---

## 1. Fuentes Tipográficas (Google Fonts)

- **Fuente para Títulos y Marca (`Fraunces`)**:
  - **Enlace de la fuente**: https://fonts.google.com/specimen/Fraunces
  - **Pesos utilizados**: `600` (SemiBold), `700` (Bold)
  - **Declaración CSS**: `font-family: 'Fraunces', serif;`

- **Fuente para Cuerpo de Texto, Botones y Navegación (`Plus Jakarta Sans`)**:
  - **Enlace de la fuente**: https://fonts.google.com/specimen/Plus+Jakarta+Sans
  - **Pesos utilizados**: `400` (Regular), `500` (Medium), `600` (SemiBold), `700` (Bold)
  - **Declaración CSS**: `font-family: 'Plus Jakarta Sans', sans-serif;`

- **Enlace directo para importar en el `<head>` del HTML**:
  ```html
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,600;9..144,700&family=Plus+Jakarta+Sans:wght@400;500;600;700&display=swap" rel="stylesheet">
  ```

---

## 2. Paleta de Colores en Formato RGB

El diseño emplea una paleta cálida de inspiración arquitectónica (terracota, piedra travertino, salvia, ocre y espresso profundo):

| Uso en la interfaz | Nombre del color | Valor en RGB / RGBA |
| :--- | :--- | :--- |
| **Fondo principal de la página** | Alabastro Cálido | `rgb(248, 245, 240)` |
| **Fondo secundario (Sección Soluciones / Métricas)** | Arena Travertino | `rgb(239, 233, 224)` |
| **Fondo de tarjetas y Header Desktop** | Blanco Puro | `rgb(255, 255, 255)` |
| **Fondo de Footer y Navbar Vertical Mobile** | Espresso Arquitectónico | `rgb(34, 30, 28)` |
| **Fondo de inputs y botones sociales en Footer** | Carbón Cálido | `rgb(48, 43, 40)` |
| **Color Primario (Botones, acentos, link activo)** | Terracota Principal | `rgb(184, 92, 56)` |
| **Color Primario Oscuro (Gradiente del Banner CTA)** | Arcilla Profunda | `rgb(142, 64, 36)` |
| **Texto Principal y Títulos** | Espresso Oscuro | `rgb(34, 30, 28)` |
| **Subtítulos del Hero** | Nogal Oscuro | `rgb(58, 49, 44)` |
| **Texto de Párrafos y Navegación** | Taupe Medio | `rgb(92, 83, 76)` |
| **Texto Secundario en Tarjetas** | Piedra Grisácea | `rgb(105, 95, 87)` |
| **Texto Claro en Footer y Sidebar Mobile** | Lino Claro | `rgb(235, 228, 218)` |
| **Texto Secundario en Footer** | Arena Suave | `rgb(194, 184, 172)` |
| **Bordes de Secciones y Divisores** | Borde Piedra | `rgb(228, 220, 209)` |
| **Bordes de Tarjetas** | Borde Marfil | `rgb(233, 226, 216)` |
| **Icono / Badge 1 — Fondo Terracota Suave** | Rosa Arcilla | `rgb(247, 232, 225)` |
| **Icono / Badge 1 — Color Terracota** | Terracota Principal | `rgb(184, 92, 56)` |
| **Icono / Badge 2 — Fondo Ocre Suave** | Crema Ámbar | `rgb(250, 240, 222)` |
| **Icono / Badge 2 — Color Ocre Dorado** | Ocre Dorado | `rgb(196, 134, 52)` |
| **Icono / Badge 3 — Fondo Salvia Suave** | Verde Niebla | `rgb(232, 240, 230)` |
| **Icono / Badge 3 — Color Verde Salvia** | Verde Salvia | `rgb(90, 114, 85)` |
| **Icono / Badge 4 — Fondo Cobre Suave** | Arena Rosada | `rgb(243, 233, 228)` |
| **Icono / Badge 4 — Color Cobre** | Cobre Tierra | `rgb(142, 74, 49)` |
| **Puntos de paginación inactivos** | Gris Cálido | `rgb(216, 206, 194)` |

---

## 3. Iconos Utilizados (Google Material Symbols Outlined)

- **Catálogo general de iconos**: https://fonts.google.com/icons?icon.set=Material+Symbols&icon.style=Outlined
- **Enlace CDN para incluir en el `<head>`**:
  ```html
  <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@24,500,0,0" />
  ```

### Lista detallada de iconos por sección:

1. **Logo / Marca (`architecture` — Compás de arquitectura)**:
   - Nombre en HTML: `<span class="material-symbols-outlined">architecture</span>`
   - Link directo: https://fonts.google.com/icons?selected=Material+Symbols+Outlined:architecture:FILL@0;wght@500;GRAD@0;opsz@24

2. **Navbar — Inicio / Home (`home`)**:
   - Nombre en HTML: `<span class="material-symbols-outlined">home</span>`
   - Link directo: https://fonts.google.com/icons?selected=Material+Symbols+Outlined:home:FILL@0;wght@500;GRAD@0;opsz@24

3. **Navbar y Servicio 1 — Manejo de Espacios (`space_dashboard`)**:
   - Nombre en HTML: `<span class="material-symbols-outlined">space_dashboard</span>`
   - Link directo: https://fonts.google.com/icons?selected=Material+Symbols+Outlined:space_dashboard:FILL@0;wght@500;GRAD@0;opsz@24

4. **Navbar — Nosotros (`groups`)**:
   - Nombre en HTML: `<span class="material-symbols-outlined">groups</span>`
   - Link directo: https://fonts.google.com/icons?selected=Material+Symbols+Outlined:groups:FILL@0;wght@500;GRAD@0;opsz@24

5. **Navbar — Proyectos (`grid_view`)**:
   - Nombre en HTML: `<span class="material-symbols-outlined">grid_view</span>`
   - Link directo: https://fonts.google.com/icons?selected=Material+Symbols+Outlined:grid_view:FILL@0;wght@500;GRAD@0;opsz@24

6. **Navbar — Testimonios (`star`)**:
   - Nombre en HTML: `<span class="material-symbols-outlined">star</span>`
   - Link directo: https://fonts.google.com/icons?selected=Material+Symbols+Outlined:star:FILL@0;wght@500;GRAD@0;opsz@24

7. **Navbar — Contacto (`mail`)**:
   - Nombre en HTML: `<span class="material-symbols-outlined">mail</span>`
   - Link directo: https://fonts.google.com/icons?selected=Material+Symbols+Outlined:mail:FILL@0;wght@500;GRAD@0;opsz@24

8. **Servicio 2 — Reforma Integral (`home_repair_service`)**:
   - Nombre en HTML: `<span class="material-symbols-outlined">home_repair_service</span>`
   - Link directo: https://fonts.google.com/icons?selected=Material+Symbols+Outlined:home_repair_service:FILL@0;wght@500;GRAD@0;opsz@24

9. **Servicio 3 — Mobiliario a Medida (`chair`)**:
   - Nombre en HTML: `<span class="material-symbols-outlined">chair</span>`
   - Link directo: https://fonts.google.com/icons?selected=Material+Symbols+Outlined:chair:FILL@0;wght@500;GRAD@0;opsz@24

10. **Servicio 4 — Luz y Materiales (`light`)**:
    - Nombre en HTML: `<span class="material-symbols-outlined">light</span>`
    - Link directo: https://fonts.google.com/icons?selected=Material+Symbols+Outlined:light:FILL@0;wght@500;GRAD@0;opsz@24

11. **Tarjetas de Proyectos — Flecha "Ver proyecto" (`arrow_forward`)**:
    - Nombre en HTML: `<span class="material-symbols-outlined">arrow_forward</span>`
    - Link directo: https://fonts.google.com/icons?selected=Material+Symbols+Outlined:arrow_forward:FILL@0;wght@500;GRAD@0;opsz@24

12. **Banner CTA Inferior — Regla de Medición (`straighten`)**:
    - Nombre en HTML: `<span class="material-symbols-outlined">straighten</span>`
    - Link directo: https://fonts.google.com/icons?selected=Material+Symbols+Outlined:straighten:FILL@0;wght@500;GRAD@0;opsz@24

13. **Footer Contáctenos — Botón Enviar (`send`)**:
    - Nombre en HTML: `<span class="material-symbols-outlined">send</span>`
    - Link directo: https://fonts.google.com/icons?selected=Material+Symbols+Outlined:send:FILL@0;wght@500;GRAD@0;opsz@24

14. **Footer Datos de Estudio — Ubicación, Teléfono y Horario (`location_on`, `call`, `schedule`)**:
    - Ubicación (`location_on`): https://fonts.google.com/icons?selected=Material+Symbols+Outlined:location_on:FILL@0;wght@500;GRAD@0;opsz@24
    - Teléfono (`call`): https://fonts.google.com/icons?selected=Material+Symbols+Outlined:call:FILL@0;wght@500;GRAD@0;opsz@24
    - Horario (`schedule`): https://fonts.google.com/icons?selected=Material+Symbols+Outlined:schedule:FILL@0;wght@500;GRAD@0;opsz@24

15. **Footer Redes / Portafolio (`public`, `photo_camera`, `smart_display`)**:
    - Web (`public`): https://fonts.google.com/icons?selected=Material+Symbols+Outlined:public:FILL@0;wght@500;GRAD@0;opsz@24
    - Galería (`photo_camera`): https://fonts.google.com/icons?selected=Material+Symbols+Outlined:photo_camera:FILL@0;wght@500;GRAD@0;opsz@24
    - Video (`smart_display`): https://fonts.google.com/icons?selected=Material+Symbols+Outlined:smart_display:FILL@0;wght@500;GRAD@0;opsz@24

---

## 4. Imágenes Utilizadas (Enlaces Directos de Unsplash)

1. **Imagen de Fondo del Hero (Casa remodelada con ventanales e iluminación cálida)**:
   - `https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=1400&q=80`

2. **Sección "¿Qué es Kora Estudio?" (Sala y comedor integrados con madera y luz natural)**:
   - `https://images.unsplash.com/photo-1600607687939-ce8a6c25118c?auto=format&fit=crop&w=1000&q=80`

3. **Sección "Proyectos que inspiran" (4 tarjetas de proyectos)**:
   - **Proyecto 1 — Casa Roble Abierto (Cocina y zona social)**:
     `https://images.unsplash.com/photo-1556911220-e15b29be8c8f?auto=format&fit=crop&w=800&q=80`
   - **Proyecto 2 — Apartamento Loft 84 (Optimización de 58 m²)**:
     `https://images.unsplash.com/photo-1600210492486-724fe5c67fb0?auto=format&fit=crop&w=800&q=80`
   - **Proyecto 3 — Residencia Terracota (Reforma estructural)**:
     `https://images.unsplash.com/photo-1600566753376-12c8ab7fb75b?auto=format&fit=crop&w=800&q=80`
   - **Proyecto 4 — Villa Patio de Luz (Exterior e interior)**:
     `https://images.unsplash.com/photo-1600585154526-990dced4db0d?auto=format&fit=crop&w=800&q=80`

4. **Sección "Soluciones de manejo espacial" (3 tarjetas con fotografías)**:
   - **Solución 1 — Almacenamiento invisible**:
     `https://images.unsplash.com/photo-1586023492125-27b2c045efd7?auto=format&fit=crop&w=800&q=80`
   - **Solución 2 — Amplitud e iluminación**:
     `https://images.unsplash.com/photo-1618221195710-dd6b41faaea6?auto=format&fit=crop&w=800&q=80`
   - **Solución 3 — Ambientes híbridos**:
     `https://images.unsplash.com/photo-1616486338812-3dadae4b4ace?auto=format&fit=crop&w=800&q=80`

5. **Sección "Lo que dicen nuestros clientes" (Avatar del testimonio)**:
   - `https://images.unsplash.com/photo-1573496359142-b8d87734a5a2?auto=format&fit=crop&w=300&q=80`
