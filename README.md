# XarxaLlibres Lite 📚

Proyecto intermodular del Ciclo Formativo de Grado Superior en  
**Desarrollo de Aplicaciones Multiplataforma (DAM)**.

---

## 📌 Descripción del proyecto

**XarxaLlibres Lite** es una aplicación multiplataforma cuyo objetivo es facilitar la
gestión y consulta de libros de texto dentro de una comunidad educativa.

El sistema permite a los usuarios iniciar sesión, consultar un catálogo de libros,
añadir nuevos ejemplares y visualizar información detallada de cada libro.  
El proyecto se desarrolla siguiendo una arquitectura cliente-servidor y se divide en
varios módulos independientes.

---

## 🧩 Arquitectura general

El proyecto está dividido en las siguientes partes:

- **Base de datos (PostgreSQL)**  
  Diseño y gestión del modelo de datos.

- **API REST (Node.js + Express)**  
  Encargada de la lógica de negocio y la comunicación con la base de datos.

- **Aplicación móvil (Android)**  
  Desarrollada en Kotlin con Jetpack Compose.

- **Aplicación de escritorio (Java)**  
  Cliente de escritorio que consume la misma API REST.

Cada parte se comunica exclusivamente a través de la API, evitando accesos directos a la base de datos desde los clientes.

---

## 👥 Equipo de trabajo

Proyecto realizado por un equipo de **3 personas**, con reparto de tareas definido:

- **Gema** → Base de datos (modelado, MySQL, scripts SQL)
- **Santiago** → API REST (Node.js + Express)
- **Eneko** → Aplicación móvil Android (Kotlin + Jetpack Compose)

La aplicación de escritorio se desarrollará de forma rotativa entre los miembros del equipo.

---

## 📱 Aplicación móvil (Android)

### Tecnologías utilizadas
- Lenguaje: **Kotlin**
- UI: **Jetpack Compose**
- Arquitectura: **MVVM**
- Navegación: **Navigation Compose**
- Comunicación con API: **Retrofit** (fase posterior)
- Gestión de estados: `State`, `remember`, `mutableStateOf`

---

## 🖥️ Backend / API

- Entorno: **Node.js**
- Framework: **Express**
- Tipo: **API REST**
- Comunicación mediante JSON
- Autenticación básica (en fases posteriores)

La API será desplegada en la nube usando servicios gratuitos.

---

## 🗄️ Base de datos

- Sistema gestor: **PostgreSQL**
- Diseño normalizado
- Acceso exclusivo desde la API
- Alojada en la nube (servicio gratuito)

---

## 🚧 Estado del proyecto

🔧 **En desarrollo**

Este repositorio se actualizará progresivamente conforme avance el proyecto.

---

## 📄 Licencia

Proyecto desarrollado con fines educativos como parte de  
**Proyecto Intermodular** del CFGS DAM.

No destinado a uso comercial.
