# 🦎 Darpalis Exotics

<p align="center">
  <strong>Proyecto en construcción · Desarrollo Full Stack · Darpalis Exotics</strong>
</p>

<p align="center">
  Propuesta de plataforma web para la tienda Darpalis, especializada en animales exóticos, terrarios, hábitats, alimentación y accesorios para su cuidado responsable.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/estado-en%20construcci%C3%B3n-f59e0b?style=for-the-badge" alt="Proyecto en construcción">
  <img src="https://img.shields.io/badge/desarrollo-individual-2563eb?style=for-the-badge" alt="Desarrollo individual">
</p>

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

 Estas son las **tecnologías previstas** para el proyecto. Podrán ajustarse durante el desarrollo según las necesidades reales de Darpalis.


### 🎨 Frontend

![React](https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=white)
![React Router](https://img.shields.io/badge/React_Router-8-CA4245?logo=reactrouter&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-8-646CFF?logo=vite&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?logo=css3&logoColor=white)

- **React**: crea la parte visual e interactiva de la web: páginas, tarjetas de productos, botones, buscador y carrito.
- **React Router**: permite navegar entre secciones —inicio, catálogo, fichas de especies o carrito— sin recargar toda la página.
- **Vite**: prepara el proyecto para trabajar de forma rápida durante el desarrollo y para publicarlo cuando esté terminado.
- **CSS**: lenguaje que define la apariencia de la web: colores, espacios, tamaños y diseño adaptable a móvil, tableta y ordenador.

### ⚙️ Backend

![Python](https://img.shields.io/badge/Python-3-3776AB?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?logo=sqlalchemy&logoColor=white)

- **Python**: lenguaje de programación que se utilizará para construir la parte interna de la aplicación.
- **FastAPI**: herramienta de Python para crear la API, el puente que recibe peticiones de la web, procesa la información y se comunica con la base de datos.
- **SQLAlchemy**: ayuda a que Python pueda leer, crear, modificar y eliminar datos en PostgreSQL sin tener que escribir todas las consultas manualmente.

React y Python se pueden combinar perfectamente: React muestra la web en el navegador y FastAPI entrega los datos que necesita, como productos, especies, usuarios o pedidos.

### 🗄️ Datos y herramientas

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?logo=postman&logoColor=white)

- **PostgreSQL**: base de datos donde se guardará la información de la tienda: animales, productos, categorías, clientes, pedidos y existencias.
- **Docker**: permite preparar el mismo entorno de trabajo en cualquier ordenador, incluyendo la aplicación y la base de datos.
- **Git**: sistema que registra los cambios realizados en el código, permitiendo volver a una versión anterior si algo deja de funcionar.
- **GitHub**: plataforma donde se almacenará el repositorio de Git para tener una copia online del proyecto y mostrar su evolución.
- **Postman**: aplicación para comprobar que el backend funciona correctamente antes de conectarlo con la parte visual de la web.

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

<p align="center">
  <strong>Proyecto en producción y desarrollo continuo. 🦎</strong>
</p>

