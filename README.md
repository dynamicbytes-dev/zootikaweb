# 🌾 Zootika Web — Sitio Oficial & Landing Page

<p align="center">
  <img src="logo.png" alt="Zootika Logo" width="160" style="border-radius: 16px; margin-bottom: 14px;" />
</p>

<p align="center">
  <strong>Landing page oficial y portal web de presentación de Zootika: Plataforma Integral de Gestión Agropecuaria Multi-Granja y Multi-Rol.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/WhatsApp_API-Direct-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp API" />
  <img src="https://img.shields.io/badge/Licencia-MIT-green?style=for-the-badge" alt="MIT License" />
</p>

---

## 📖 Descripción del Proyecto

Este repositorio contiene el sitio web y landing page comercial de **Zootika**, concebido con una estética moderna, limpia y rústica, optimizada para productores agropecuarios, administradores de fincas, directores de cooperativas y asesores técnicos de campo.

La página comunica la propuesta de valor de la plataforma SaaS, presentando detalladamente sus **8 módulos canónicos de gestión**, la jerarquía de roles multi-tenant, la integración de mapas geoespaciales (GeoJSON) y canales de contacto directo vía WhatsApp para demostraciones y cotizaciones inmediatas.

---

## ✨ Características Principales de la Web

- 🎨 **Diseño y Estética Premium**: Construido con Tailwind CSS y tipografía moderna de Google Fonts (*Plus Jakarta Sans* & *Inter*), empleando una paleta de colores armónica (Verde Bosque `#064E3B`, Verde Esmeralda `#10B981` y acentos Ámbar `#F59E0B`).
- 📱 **100% Responsivo & Mobile-First**: Menú interactivo colapsable para dispositivos móviles y botones de acción accesibles en pantallas táctiles de campo.
- 📦 **Exhibición de los 8 Módulos Canónicos**:
  1. 🌱 **Potreros y Pasturas (`potreros`)**: Delimitación geoespacial con Leaflet / GeoJSON, cálculo de áreas (ha), rotación y aforos de biomasa (kg MS/ha).
  2. 🐄 **Lotes y Ganadería (`lots`)**: Trazabilidad individual, pesajes, curvas de engorde y fichas técnicas en PDF.
  3. 🏷️ **Especies Pecuarias (`species`)**: Catálogo maestro zootécnico y tipificación productiva.
  4. 🐔 **Galpones e Instalaciones (`barns`)**: Control de postura diaria, clasificación y mermas de huevos.
  5. 📦 **Inventario Agropecuario (`inventory`)**: Gestión multialmacén, vencimientos y trazabilidad de insumos.
  6. 📋 **Actividades y Tareas (`activities`)**: Asignación de labores de campo y bitácora fotográfica.
  7. 📊 **Analítica y Reportes (`analytics`)**: Tableros de KPIs en tiempo real e informes ejecutivos PDF (`jsPDF-AutoTable`).
  8. 🛡️ **Historial y Auditoría (`history`)**: Logs inmutables y trazabilidad por granja.
- 👥 **Sección de Jerarquía de Roles**: Desglose claro de privilegios para *Superadministrador (`root`)*, *Administrador de Finca (`admin`)* y *Encargado de Campo (`encargado`)*.
- 💬 **Integración WhatsApp Directa**: Botones de llamada a la acción y widget flotante vinculados directamente al canal de atención comercial y demos: [`+58 412 9412599`](https://wa.me/584129412599).
- ⚡ **Rendimiento Ultrarrápido**: Cero dependencias pesadas de construcción para despliegues instantáneos en cualquier servidor web, GitHub Pages, Vercel, Netlify o hosting tradicional.

---

## 📁 Estructura del Repositorio

```text
zootikaweb/
├── index.html       # Landing page principal, maquetación semántica y estilos
├── logo.png         # Logotipo oficial de Zootika en alta resolución
├── favicon.png      # Favicon e icono para accesos directos web
├── .gitignore       # Archivos y temporales excluidos
└── README.md        # Documentación oficial del repositorio
```

---

## 🚀 Despliegue y Visualización Local

Al ser un sitio web estático optimizado, no requiere procesos complejos de compilación:

### Opción 1: Abrir directamente en el navegador
Simplemente haz doble clic sobre `index.html` o ábrelo desde cualquier navegador web.

### Opción 2: Servidor local ligero (Python)
```bash
# Python 3
python3 -m http.server 3000
```
Luego abre tu navegador en: `http://localhost:3000`

### Opción 3: Servidor local con Node.js (npx serve)
```bash
npx serve .
```

---

## 📲 Canal de Contacto y Demos

- **WhatsApp Oficial**: [+58 412 9412599](https://wa.me/584129412599)
- **Correo de Soporte**: [soporte@zootika.com](mailto:soporte@zootika.com)

---

## 📄 Licencia

Este proyecto está distribuido bajo la licencia [MIT](LICENSE).

---

<p align="center">
  Desarrollado con dedicación para el sector agropecuario por <strong>Dynamic Bytes Dev</strong>.
</p>
