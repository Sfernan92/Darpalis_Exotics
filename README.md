# 🦎 Darpalis Exotics

> Propuesta de página web para una tienda especializada en animales exóticos, productos de mantenimiento y cuidado responsable.

## 🌿 Sobre el proyecto

**Darpalis Exotics** será una plataforma web creada para la tienda Darpalis, especializada en animales exóticos y productos para su cuidado. Permitirá descubrir y consultar animales, terrarios, hábitats, alimentación, iluminación, climatización y accesorios. Su objetivo es ofrecer a clientes y personas interesadas una experiencia clara, visual y educativa sobre reptiles, invertebrados y otras especies.

El proyecto se desarrolla desde cero con el propósito de convertirse en una herramienta real para el negocio. A la vez, su creación permitirá practicar un desarrollo full stack completo: interfaz, gestión de datos, usuarios, API y publicación de la web.

## ✨ Funcionalidades previstas

### 🛍️ Catálogo de productos y animales

- Explorar animales y productos por categoría, especie o tipo de hábitat.
- Consultar fichas detalladas con imágenes, descripción, precio, disponibilidad y cuidados básicos.
- Buscar por nombre, categoría o características.
- Filtrar y ordenar resultados por precio, disponibilidad o tipo de producto.

### 🐍 Fichas de especies

- Información básica y recomendaciones de cuidado responsable.
- Requisitos de terrario, temperatura, humedad, alimentación e iluminación.
- Productos recomendados para cada especie.

### 🧺 Carrito y pedidos

- Añadir, modificar o eliminar productos del carrito.
- Resumen del pedido y cálculo del importe.
- Proceso de compra simulado en una primera versión.
- Historial de pedidos para usuarios registrados en fases posteriores.

### 👤 Usuarios y administración

- Registro e inicio de sesión.
- Perfil de usuario con datos personales y pedidos.
- Panel de administración para crear, editar y eliminar productos, especies y categorías.
- Gestión de stock y disponibilidad.

### 📚 Contenido educativo

- Guías sobre el mantenimiento de animales exóticos.
- Avisos sobre tenencia responsable y requisitos legales aplicables.
- Artículos o consejos asociados a cada categoría.

## 🚀 Propuesta de evolución

| Fase | Objetivo |
| --- | --- |
| 1 | Diseño responsive, navegación y catálogo con datos de prueba. |
| 2 | API, base de datos, filtros y fichas dinámicas. |
| 3 | Autenticación, carrito, roles y panel de administración. |
| 4 | Pedidos, validaciones, pruebas automatizadas y despliegue. |

## 🧰 Tecnologías propuestas

### Frontend

- **React**: creación de una interfaz dinámica basada en componentes.
- **Vite**: entorno rápido de desarrollo y compilación.
- **React Router**: navegación entre páginas.
- **CSS, Tailwind CSS o CSS Modules**: estilos responsive y mantenibles.

### Backend recomendado

- **Python + FastAPI**: API REST rápida, moderna y fácil de documentar. FastAPI genera documentación interactiva automáticamente, lo que resulta especialmente útil mientras aprendes.
- **SQLAlchemy**: conexión y modelado de datos en PostgreSQL.
- **Pydantic**: validación de los datos que recibe y devuelve la API.

React y Python se pueden combinar perfectamente: React se encarga de la interfaz en el navegador y Python/FastAPI expone una API REST que React consume mediante peticiones HTTP.

### Base de datos

- **PostgreSQL**: opción recomendada. Es una base de datos relacional sólida y muy utilizada profesionalmente; encaja bien con productos, categorías, usuarios, pedidos y stock.

### Herramientas complementarias

- **Git y GitHub**: control de versiones y colaboración.
- **Docker**: entorno reproducible para frontend, backend y base de datos.
- **Postman o Insomnia**: pruebas de la API.
- **Pytest** y **Vitest**: pruebas del backend y frontend, respectivamente.

## 🏗️ Arquitectura inicial

```text
React + Vite  ──HTTP/JSON──>  FastAPI  ──SQL──>  PostgreSQL
     │                            │
 Interfaz y rutas              API, lógica y autenticación
```

## 📁 Estructura sugerida

```text
darpalis-exotics/
├── frontend/          # Aplicación React
├── backend/           # API con FastAPI
├── docs/              # Bocetos, documentación y decisiones técnicas
├── docker-compose.yml # Servicios de desarrollo (opcional)
└── README.md
```

## 🎯 Objetivos de aprendizaje

- Construir una interfaz responsive y accesible.
- Diseñar una API REST y conectarla con React.
- Modelar una base de datos relacional con PostgreSQL.
- Implementar autenticación, autorización y validación de datos.
- Aplicar Git, pruebas, variables de entorno y despliegue.

## ⚠️ Nota sobre bienestar animal

La plataforma debe promover siempre la tenencia responsable, el bienestar animal y el cumplimiento de la normativa aplicable. La información publicada tendrá un propósito orientativo y no sustituirá el asesoramiento profesional o veterinario.

---

Proyecto en producción y desarrollo continuo. 🦎
