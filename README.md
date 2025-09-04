# Temario-de-App-web

Propósito de Aprendizaje 1: Comprender los fundamentos del desarrollo de aplicaciones web.

<img width="292" height="173" alt="image" src="https://github.com/user-attachments/assets/5b8e8591-659a-4da6-9307-8673c150a2d1" />

<ins> **1.-Introducción al desarrollo web** </ins>

La introducción al desarrollo web abarca los conceptos básicos y la evolución histórica de cómo se crean y publican sitios y aplicaciones en internet. Se estudia cómo han surgido diferentes tecnologías y metodologías a lo largo del tiempo, desde las primeras páginas web estáticas hasta las aplicaciones web dinámicas y complejas que existen hoy en día.  
También se analizan los distintos tipos de aplicaciones web, como:

- **Estáticas:** Páginas cuyo contenido no cambia, escritas principalmente en HTML y CSS.
- **Dinámicas:** Sitios cuyo contenido puede cambiar en función de la interacción del usuario y suelen usar bases de datos y lenguajes de programación del lado del servidor.
- **SPA (Single Page Application):** Aplicaciones que cargan una sola página HTML y actualizan dinámicamente el contenido mediante JavaScript sin recargar la página completa.
- **PWA (Progressive Web App):** Aplicaciones web que ofrecen experiencias similares a las aplicaciones móviles, incluyendo el uso offline, notificaciones push y acceso desde la pantalla de inicio.

Además, se explora cómo el desarrollo web ha impactado la vida cotidiana, permitiendo desde la consulta de información hasta la realización de compras, la comunicación en redes sociales y el acceso a servicios en la nube. Comprender estos conceptos es fundamental para entender la importancia y el alcance de las aplicaciones web en el mundo moderno, así como los retos y oportunidades que presenta su desarrollo.



<ins> **2.Arquitectura de aplicaciones web** </ins>

En el desarrollo de aplicaciones web, la arquitectura define cómo se organizan y comunican los diferentes componentes del sistema. A continuación, se describen algunos de los modelos y enfoques más comunes:

### 1. Cliente-Servidor
Es el modelo fundamental en las aplicaciones web. El **cliente** (usualmente el navegador del usuario) solicita recursos o servicios, y el **servidor** responde proporcionando los datos o ejecutando acciones. Esta separación permite que múltiples clientes accedan simultáneamente a los servicios ofrecidos por un servidor central.

### 2. Arquitectura de tres capas (presentación, lógica, datos)
Este modelo divide la aplicación en tres capas independientes:
- **Presentación:** Es la interfaz gráfica que interactúa con el usuario (por ejemplo, páginas web con HTML, CSS y JavaScript).
- **Lógica de negocio:** Gestiona las reglas y procesos de la aplicación (por ejemplo, scripts PHP o aplicaciones backend en Node.js).
- **Datos:** Se encarga de almacenar y recuperar la información (por ejemplo, bases de datos como MySQL).

Esta separación facilita el mantenimiento, la escalabilidad y la reutilización del código.

### 3. REST y API-first design
- **REST (Representational State Transfer):** Es un estilo de arquitectura que utiliza los métodos HTTP (GET, POST, PUT, DELETE, etc.) para crear servicios web que pueden ser consumidos fácilmente por diferentes aplicaciones y dispositivos. Las APIs RESTful son sencillas, escalables y ampliamente utilizadas.
- **API-first design:** Es un enfoque donde el diseño y desarrollo de la API es la prioridad inicial en el proceso de construcción de una aplicación. Esto permite definir claramente cómo interactuarán los diferentes componentes y facilita la integración con otros sistemas desde el principio.

---
En conjunto, estos conceptos permiten crear aplicaciones web modernas, modulares y fáciles de mantener, favoreciendo la comunicación entre diferentes sistemas y la experiencia de usuario.


<ins> **3. -Lenguajes y tecnologías fundamentales** </ins>

En el desarrollo web, existen ciertos lenguajes y tecnologías que son considerados fundamentales para crear sitios y aplicaciones dinámicas, visualmente atractivas y funcionales. A continuación, se describen brevemente los más importantes:

### 1. HTML (HyperText Markup Language)
Es el lenguaje de marcado principal para crear páginas web. Sirve para estructurar el contenido de la web mediante etiquetas, como encabezados, párrafos, listas, enlaces, imágenes, etc. HTML define la estructura básica de una página web, pero no su apariencia visual.

### 2. CSS (Cascading Style Sheets)
Es el lenguaje encargado de dar estilo y diseño a las páginas web creadas con HTML. Permite modificar colores, fuentes, tamaños, márgenes, posiciones y efectos visuales, logrando así una presentación atractiva y adaptada a diferentes dispositivos (responsive design).

### 3. JavaScript
Es un lenguaje de programación que se ejecuta principalmente en el navegador del usuario. Permite añadir interactividad, dinamismo y funcionalidades avanzadas a las páginas web, como validación de formularios, animaciones, manejo de eventos y actualización de contenidos sin recargar la página (AJAX).

### 4. PHP (Hypertext Preprocessor)
Es un lenguaje de programación del lado del servidor, utilizado para desarrollar aplicaciones web dinámicas. PHP permite procesar formularios, gestionar sesiones, interactuar con bases de datos y generar contenido HTML de manera dinámica antes de enviarlo al navegador del usuario.

### 5. MySQL
Es un sistema de gestión de bases de datos relacional (SGBD). Se utiliza para almacenar, organizar y recuperar datos de manera eficiente. MySQL es muy común en aplicaciones web y suele usarse junto con PHP para crear sitios web dinámicos que requieren almacenar información de usuarios, productos, publicaciones, etc.



<ins> **4.-Control de versiones** </ins>

El control de versiones es fundamental en el desarrollo de software moderno, ya que permite gestionar y registrar los cambios realizados en el código fuente a lo largo del tiempo. A continuación, se explican las herramientas y conceptos clave relacionados:

### 1. Git y GitHub
- **Git** es un sistema de control de versiones distribuido que permite a varios desarrolladores trabajar en el mismo proyecto de manera eficiente. Con Git, es posible guardar el historial de cambios, volver a versiones anteriores y colaborar sin sobrescribir el trabajo de otros.
- **GitHub** es una plataforma en línea que permite alojar repositorios de Git, facilitando la colaboración, el seguimiento de problemas y la integración de código entre diferentes desarrolladores mediante herramientas sociales y de automatización.

### 2. Flujo de trabajo con ramas (branching, merge, pull requests)
- **Branching (ramas):** Permite crear copias paralelas del código para desarrollar nuevas características, corregir errores o experimentar, sin afectar la rama principal (por lo general llamada `main` o `master`).
- **Merge (fusión):** Es el proceso de integrar los cambios realizados en una rama secundaria de vuelta a la rama principal, unificando el trabajo realizado de forma independiente.
- **Pull Requests:** Son solicitudes para fusionar los cambios de una rama en otra (normalmente en la rama principal). Este proceso permite la revisión y discusión del código antes de que se integre definitivamente, mejorando la calidad y la colaboración entre los miembros del equipo.

---

En conjunto, Git, GitHub y las prácticas de ramificación y fusión de código facilitan la colaboración, la organización y el mantenimiento eficiente de proyectos de software.



Propósito de Aprendizaje 2: Desarrollar componentes y funcionalidades de una aplicación web

<img width="294" height="171" alt="image" src="https://github.com/user-attachments/assets/3157d0f7-d482-48dd-9730-c11823e9394b" />

<ins>**1.-Diseño e implementación del frontend**</ins>

El **frontend** es la parte visible de una aplicación web, responsable de la experiencia del usuario.

## Maquetación, Wireframe y Mockup

**Maquetación:** Estructura visual de la página usando HTML y CSS.
**Wireframe:** Boceto simple para planificar la distribución de elementos.
**Mockup:** Diseño visual detallado que muestra el aspecto final.

## API

El frontend utiliza **APIs** para comunicarse con el backend, enviando y recibiendo datos mediante peticiones HTTP. Así, se integra información dinámica y funcionalidades en la interfaz.


<ins>**2.-Diseño e implementación del backend**</ins>

El backend es la parte de una aplicación web que se encarga de procesar la lógica, gestionar los datos y responder a las solicitudes del usuario desde el servidor. A continuación, se explican los conceptos clave en el diseño e implementación del backend:

### 1. Servidor
El servidor es el componente encargado de recibir las solicitudes de los clientes (generalmente navegadores web), procesarlas y devolver una respuesta adecuada. Puede estar implementado en diferentes lenguajes y frameworks (como Node.js, PHP, Python, Java, entre otros). El servidor ejecuta la lógica de la aplicación, controla la seguridad y gestiona la comunicación con otros servicios y bases de datos.

### 2. Manejo de peticiones y respuestas HTTP
El backend debe gestionar el ciclo de vida de las peticiones (requests) y respuestas (responses) HTTP. Esto implica:
- Recibir peticiones del cliente (GET, POST, PUT, DELETE, etc.).
- Procesar los datos enviados o solicitados.
- Generar y enviar una respuesta adecuada, que puede ser una página, un archivo, o datos en formato JSON o XML.
Este manejo es fundamental para la comunicación entre el cliente y el servidor en aplicaciones web.

### 3. Conexión a bases de datos (MySQL, PostgreSQL, MongoDB)
El backend suele interactuar con bases de datos para almacenar, consultar, modificar o eliminar información. Los sistemas de bases de datos más comunes son:
- **MySQL** y **PostgreSQL:** Bases de datos relacionales que organizan la información en tablas y permiten realizar consultas complejas usando SQL.
- **MongoDB:** Base de datos NoSQL orientada a documentos, ideal para manejar datos no estructurados o de rápida evolución.
La conexión y gestión eficiente de las bases de datos es esencial para el correcto funcionamiento y rendimiento de la aplicación web.

---

En conjunto, estos elementos permiten que una aplicación web procese información, responda a las acciones de los usuarios y mantenga los datos organizados y accesibles.


<ins>**3.-Bases de datos**</ins>

Las bases de datos son sistemas que almacenan, organizan y gestionan la información necesaria para una aplicación web.

## Modelado de datos y relaciones

**Modelado de datos:**

  Proceso de definir cómo se estructuran los datos (tablas, campos) y cómo se relacionan entre sí.
**Relaciones:**  
  Las conexiones entre tablas pueden ser de uno a uno, uno a muchos o muchos a muchos, lo que permite organizar la información de forma eficiente y coherente.

## ORM (Object Relational Mapping)

El **ORM** es una técnica que conecta la base de datos relacional con los objetos del código, permitiendo trabajar con datos usando el lenguaje de programación sin escribir directamente consultas SQL.
Ejemplos: SQLAlchemy (Python), Sequelize (Node.js), Eloquent (Laravel/PHP).

## CRUD desde el backend

**CRUD** significa **Crear, Leer, Actualizar y Borrar** registros en la base de datos.
El backend implementa operaciones CRUD para gestionar los datos:  
  - Crear: agregar nuevos registros  
  - Leer: consultar información  
  - Actualizar: modificar datos existentes  
  - Borrar: eliminar registros
Estas acciones se realizan normalmente mediante funciones o rutas en la API que interactúan con la base de datos.


<ins>**4.-Seguridad básica en aplicaciones web**</ins>
La seguridad es fundamental para proteger los datos y el funcionamiento de una aplicación web.

## Validación de formularios

Verifica que los datos ingresados por el usuario sean correctos y seguros antes de procesarlos.
Evita ataques como la inyección de código o el envío de información inválida.

## Autenticación y autorización

**Autenticación:** Confirma la identidad del usuario (por ejemplo, mediante usuario y contraseña).
**Autorización:** Determina qué acciones y recursos puede acceder cada usuario según su rol o permisos.


Propósito de Aprendizaje 3: Implementar y desplegar una aplicación web funcional

<img width="300" height="168" alt="image" src="https://github.com/user-attachments/assets/88baf15d-1b37-4863-80b7-f5a6d6434067" />

<ins>**1. Integración de frontend y backend**</ins>

La integración del frontend y backend permite que la aplicación web funcione como un sistema completo, conectando la interfaz de usuario con la lógica y los datos del servidor.

## Interfaz de usuario Frontend
La **interfaz de usuario** es la parte visual con la que interactúa el usuario. El frontend captura acciones y muestra información, usando tecnologías como HTML, CSS y JavaScript.

## Manejo de API
El frontend se comunica con el backend a través de **APIs** (normalmente REST), enviando solicitudes y recibiendo respuestas en formato JSON o similar. Esto permite obtener y mostrar datos dinámicos y realizar acciones como registros, búsquedas o actualizaciones.

## Proceso de Solicitud y Respuesta de Backend
Cuando el usuario realiza una acción (como enviar un formulario), el frontend envía una **solicitud** a la API del backend. El backend procesa la petición, accede a la base de datos si es necesario, y envía una **respuesta** al frontend, que actualiza la interfaz en función de los datos recibidos.


<ins>**2. Almacenamiento en Servidor**</ins>

El almacenamiento en servidor es fundamental para guardar archivos, datos y recursos de una aplicación web y hacerlos accesibles a los usuarios.

## Tipos de servidores

**Servidor dedicado:**  
  Hardware exclusivo para una sola aplicación o cliente, ofrece mayor control y rendimiento.
**Servidor compartido:**  
  Varios usuarios comparten el mismo hardware, es más económico pero con recursos limitados.
**Servidor virtual (VPS):**  
  Simula varios servidores en una sola máquina física, combinando flexibilidad y coste moderado.
**Servidor en la nube:**  
  Recursos escalables y accesibles bajo demanda a través de Internet (ej.: AWS, Azure, Google Cloud).

## Servidores y servicios de hosting

**Hosting compartido:**  
  Ideal para pequeños proyectos, muchos sitios comparten recursos de un mismo servidor.
**Hosting dedicado:**  
  Un servidor exclusivo para un solo cliente, recomendable para proyectos grandes.
**Hosting VPS:**  
  Ofrece aislamiento y control con precios intermedios.
**Hosting en la nube:**  
  Permite crecer fácilmente, pagando solo por lo que se usa.

## Proveedores de Servicios de Almacenamiento

**Amazon Web Services (AWS)**
**Microsoft Azure**
**Google Cloud Platform**
**DigitalOcean**
**Heroku**
**Hostinger, GoDaddy, Bluehost** (hosting tradicional)

Estos proveedores ofrecen diferentes opciones para almacenar archivos, bases de datos y recursos, adaptándose a las necesidades de cualquier proyecto web.

<ins>**3. Optimización y rendimiento**</ins>

Mejorar el rendimiento de una aplicación web es clave para una experiencia de usuario fluida y eficaz.

## Optimización de recursos

**Imágenes:** Usar formatos adecuados, comprimir y dimensionar correctamente para reducir el tiempo de carga.
**Scripts:** Minimizar y combinar archivos JavaScript y CSS para reducir peticiones y mejorar la velocidad.

## Despliegue de aplicaciones web

Publicar la aplicación en un servidor o plataforma en la nube.
Configurar el entorno para asegurar accesibilidad y seguridad.

## CI/CD básico

**CI/CD** (Integración y entrega continua) automatiza pruebas y despliegues.
Permite detectar errores rápidamente y publicar nuevas versiones de forma ágil.

## Documentación del proyecto

Explica la estructura, configuración y uso del proyecto.
Facilita la colaboración y el mantenimiento del software.
