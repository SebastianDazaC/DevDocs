# 🌐 DESARROLLO WEB

La Web es todo lo que vemos e interactuamos a través de un navegador (como Chrome, Edge, Firefox, etc). Funciona gracias a una **arquitectura cliente-servidor**, dividida en dos grandes partes:

- **Cliente (Front-end):** Es el dispositivo desde donde se visualiza la página web. Se desarrolla principalmente con HTML, CSS y JavaScript.
- **Servidor (Back-end):** Es el lugar donde vive y se almacena la página web (sus archivos, bases de datos y lógica). Se puede programar con JavaScript (Node.js), Python, Java, Go, entre otros.

## 🕸 ¿Qué es la Web?

Cuando abres un archivo (imagen, texto, video, etc.) en tu computadora, este se reproduce localmente. Pero si quieres compartirlo con el mundo, necesitas subirlo a un servidor y hacerlo accesible mediante un **enlace (link)**. Así nació la **World Wide Web (WWW)**: un sistema global para compartir archivos en forma de páginas web accesibles desde cualquier lugar.

Una **página web** es un tipo especial de archivo que necesita un **navegador web** para ser visualizado correctamente. Un conjunto de páginas web enlazadas entre sí se llama **sitio web**.

### 🔗 Links y URLs

Los **links** o **hipervínculos** conectan páginas entre sí. Internamente, usan **URLs** (Uniform Resource Locators), que son direcciones únicas que identifican recursos (documentos, imágenes, videos, etc.) en la web.

> En desarrollo web, "recurso" es cualquier elemento disponible en la red.
> 

## 🧱 HTML: Lenguaje de Marcado

**HTML (HyperText Markup Language)** permite estructurar los contenidos en una página: títulos, párrafos, imágenes, videos, enlaces, tablas, listas, etc. "Markup" se refiere a "marcar" el contenido indicando su función.

## 📡 Protocolos de Comunicación

Para que una página web viaje desde el servidor hasta tu navegador, se siguen ciertas reglas llamadas **protocolos**:

- **TCP/IP:** Para enviar y recibir datos por internet.
- **HTTP / HTTPS:** Protocolo específico para páginas web. El navegador y el servidor se comunican mediante **peticiones** y **respuestas** siguiendo este protocolo.

---

# ⚙️ ¿Cómo Funciona la Web?

La Web se basa en una arquitectura **cliente/servidor**. El cliente (tu navegador) hace una **petición** al servidor pidiendo ver una página. Si el servidor lo permite, devuelve una **respuesta** con los datos solicitados.

- **Petición (Request):** Lo que tu dispositivo envía para solicitar un recurso.
- **Respuesta (Response):** Lo que el servidor envía de vuelta (la página web, imagen, etc.).

### 🌐 Web vs Internet

- **Internet** es la infraestructura física: cables, antenas, redes.
- **Web** es un servicio que funciona sobre internet, basado en páginas enlazadas mediante hipertexto.

> Ejemplo: WhatsApp (app) usa Internet pero no la Web. WhatsApp Web sí es parte de la Web.
> 

---

# 🧰 Tecnologías Web

Las tecnologías web se agrupan en tres pilares esenciales:

### 1. HTML (Estructura)

Define el contenido y la estructura de la página web.

### 2. CSS (Diseño)

Estiliza la estructura: colores, tamaños, márgenes, animaciones, y también permite diseño responsivo (adaptado a cualquier pantalla).

### 3. JavaScript (Funcionalidad)

Agrega lógica e interactividad: formularios, menús dinámicos, validaciones, efectos, etc.

> Un diseñador web trabaja más con HTML y CSS. Un programador front-end domina JavaScript y entiende HTML y CSS.
> 

---

# 🛠 Herramientas para Desarrollar

## Editores de Código

Son programas ligeros para escribir código, como:

- **Visual Studio Code**
- **Sublime Text**

Son fáciles de usar, personalizables con plugins y perfectos para empezar.

## IDEs (Entornos de Desarrollo Integrados)

Son herramientas más complejas y completas como:

- **Android Studio**
- **IntelliJ IDEA**

Traen depuradores, compiladores, simuladores, etc. Recomendados para proyectos grandes.

## Navegador Web

Es donde se prueba el resultado del código. Algunos ejemplos:

- Chrome, Edge, Firefox, Safari, Opera, Brave.

Además, los navegadores manejan **cookies**, que almacenan datos del usuario para reconocerlo y personalizar su experiencia.

---

# 🧾 Git y Control de Versiones

**Git** es una herramienta que registra todos los cambios hechos en un proyecto de software.

- Permite volver a versiones anteriores.
- Facilita el trabajo en equipo con **ramas**.
- Se puede usar junto a servicios como **GitHub**, **GitLab** o **BitBucket** para guardar tus proyectos en la nube.

> Las 4 tecnologías esenciales del front-end son: HTML, CSS, JavaScript y Git.

---

# 🗃 Bases de Datos

Si una página muestra siempre la misma información, es **estática**. Si cambia según el usuario o el contexto, es **dinámica**, y necesita conectarse a una **base de datos**.

Una **base de datos** es un sistema donde se almacena información que se puede consultar, modificar y organizar.

### Tipos de bases de datos

1. **Relacionales (SQL):** Usan tablas (MySQL, PostgreSQL, SQLite...).
2. **No relacionales (NoSQL):** Usan documentos u otros formatos más flexibles (MongoDB, Redis...).

El encargado de diseñar, administrar y mantener bases de datos se llama **DBA (Database Administrator)**.

---

# 🖼 SPA (Single Page Application)

Un **SPA** es una aplicación web que carga una sola página HTML y actualiza su contenido dinámicamente sin recargarla por completo. Esto mejora la velocidad y experiencia del usuario. Se logra gracias a JavaScript.

---

# ⚙️ SSR vs CSR

- **SSR (Server-Side Rendering):** El servidor envía la página ya construida al navegador.
- **CSR (Client-Side Rendering):** El navegador recibe datos sin formato y construye la página con JavaScript.

> Un sitio puede usar ambos métodos para mejorar rendimiento y experiencia.

---

# 👥 Roles en el Desarrollo Web

En el ecosistema web, los proyectos suelen dividirse según la **arquitectura cliente-servidor**. La conexión entre estos dos mundos se logra mediante una **API (Interfaz de Programación de Aplicaciones)**.

- El **lado del cliente** (navegador) **consume** la API.
- El **lado del servidor** **crea** y **responde** a la API.

A partir de esto, surgen tres roles principales en el desarrollo web:

## 👨‍🎨 Front-end Developer

Trabaja en el **lado del cliente**. Se encarga de:

- Crear la interfaz visual (UI).
- Desarrollar la experiencia de usuario (UX).
- Usar tecnologías como HTML, CSS, JavaScript.
- Consumir datos de la API para mostrarlos al usuario.

> Un buen Front-end debe entender diseño, interactividad y accesibilidad.

## 🛠 Back-end Developer

Trabaja en el **lado del servidor**. Se encarga de:

- Procesar lógica de negocio.
- Gestionar bases de datos.
- Crear y exponer las APIs.
- Implementar seguridad y autenticación.

> Usa lenguajes como Node.js, Python, Java, PHP o Go. Trabaja con bases de datos como MySQL, PostgreSQL, MongoDB.

## 🔁 Full Stack Developer

Conoce y trabaja tanto en el **Front-end como en el Back-end**. Tiene una visión completa del sistema:

- Puede construir interfaces visuales.
- También puede desarrollar y conectar con servidores y bases de datos.

> No siempre se especializa a fondo en cada parte, pero comprende y puede trabajar en todo el flujo de una aplicación web.

---

# 🚀 Deploy (Despliegue a Producción)

El **Deploy** es el proceso de poner tu sitio web en línea, accesible para el público. Para ello necesitas:

- **Nombre de dominio** (ejemplo.com)
- **Servidor web** (para alojar tu sitio)

## Etapas del ciclo de desarrollo

1. **Desarrollo:** Escribes el código.
2. **Pruebas:** Simulas situaciones reales para detectar errores.
3. **Producción:** El código probado se lanza al público general.

---