# Legends Arena - Eventos de LoL & Warcraft

Este proyecto es una simulación de una plataforma de eventos para juegos como League of Legends y Warcraft. Los usuarios pueden enviar mensajes de contacto que son visualizados por un administrador desde un panel interno. Todo el sistema se conecta a una API falsa simulada con JSON Server.

## ✨ Funcionalidades

- Formulario de contacto para visitantes.
- Visualización de mensajes en tiempo real en el panel de administrador.
- Filtrado de mensajes por correo electrónico.
- Confirmación y eliminación de mensajes.
- Estilos responsivos utilizando Bulma y CSS personalizado.

## 🗂 Estructura del Proyecto

Eventos lol/
├── index.html # Página principal (formulario de contacto)
├── admin.html # Panel del administrador
├── db.json # Base de datos falsa (JSON Server)
├── css/
│ └── styles.css # Estilos personalizados
├── js/
│ ├── contacto.js # Lógica del formulario de contacto
│ └── admin-mensajes.js # Lógica del panel de administración

markdown
Copiar
Editar

## ⚙️ Instalación y uso

1. Clona el repositorio o descarga el archivo ZIP.

2. Asegúrate de tener instalado JSON Server:
   ```bash
   npm install -g json-server

# 🎮 Legends Arena - Eventos de LoL & Warcraft

Este proyecto simula una plataforma web donde los usuarios pueden enviar mensajes relacionados con eventos de videojuegos como **League of Legends** y **Warcraft**. Un panel de administrador permite visualizar y gestionar esos mensajes, todo conectado mediante una API falsa con **JSON Server**.

---

## ✨ Funcionalidades principales

### Para usuarios (página `index.html`)
- 📝 Formulario de contacto con validaciones.
- 📤 Envío de mensajes al administrador (nombre, correo, mensaje).
- ✅ Confirmación visual al enviar.

### Para administrador (página `admin.html`)
- 👁 Ver todos los mensajes recibidos.
- 📧 Filtro por correo electrónico.
- 🗑 Eliminar mensajes individualmente con confirmación.
- 📱 Diseño responsivo sin uso de modales.

---

## 📬 ¿Cómo enviar un mensaje?

1. Abre el archivo `index.html` en tu navegador.
2. Llena el formulario con:
   - Tu **nombre**
   - Tu **correo electrónico**
   - Tu **mensaje**
3. Haz clic en el botón `Enviar`.

Si todos los campos son válidos, el mensaje se enviará correctamente y se almacenará en `db.json` usando `fetch()` y método `POST`.

---

## 🛠 ¿Cómo se ve en el panel de administrador?

1. Abre el archivo `admin.html` en el navegador.
2. Verás una lista con todos los mensajes enviados por los usuarios, con:
   - 🧍 Nombre
   - 📧 Correo
   - 💬 Mensaje completo
   - 🗑 Botón para eliminar cada mensaje

También puedes usar el campo de búsqueda para **filtrar por correo electrónico** o **filtrar por correo nombre** en tiempo real.

