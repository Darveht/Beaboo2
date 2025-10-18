# Zenvio - Plataforma de Historias

## Descripción General
Zenvio es una aplicación web estilo TikTok para leer y compartir historias. Los usuarios pueden descubrir historias, seguir autores, y disfrutar de contenido narrativo en diferentes géneros.

## Estructura del Proyecto
- `index.html` - Aplicación completa de una sola página
- Tecnologías: HTML5, TailwindCSS, Firebase (Auth, Database, Storage)
- Estilo: Diseño inspirado en TikTok con tema rosa pastel

## Características Principales

### Autenticación
- Inicio de sesión con email/contraseña
- Autenticación con Google y Apple
- Recuperación de contraseña
- Registro de nuevos usuarios

### Navegación Principal
- **Inicio**: Feed de historias destacadas y nuevos lanzamientos
- **Búsqueda**: Buscar historias y autores
- **Perfil**: Ver y editar perfil de usuario
- **Notificaciones**: Sistema de notificaciones en tiempo real

### Menú de Categorías (NUEVO - Octubre 2025)
Ubicación: Esquina superior izquierda de la pantalla principal

**Características:**
- Botón con ícono de menú hamburguesa (3 líneas) + ícono de libro
- Panel lateral deslizante con categorías de historias
- Filtrado dinámico de historias por categoría

**Categorías disponibles:**
- Todas las Historias ✨
- Fan Fiction ⭐
- Romance 💕
- Comedia 😂
- Terror 👻
- Aventura 🗺️
- Fantasía 🔮
- Ciencia Ficción 🚀
- Drama 🎭
- Misterio 🔍
- Acción 💥
- Histórico 📜

### Funcionalidades Adicionales
- Transmisión en vivo
- Sistema de regalos virtuales
- Historias leídas recientemente
- Membresía premium
- Calendario de actualizaciones
- Chat entre usuarios
- Sistema de monedas virtuales (BCI)

## Cambios Recientes

### Octubre 18, 2025
- ✅ Agregado menú de categorías en la esquina superior izquierda
- ✅ Panel lateral con 12 categorías diferentes
- ✅ Sistema de filtrado de historias por categoría
- ✅ Interfaz visual mejorada con íconos y gradientes
- ✅ Animaciones suaves para apertura/cierre del menú
- ✅ Corrección de error de Font Awesome CDN

## Configuración de Firebase
La aplicación utiliza Firebase para:
- Autenticación de usuarios
- Base de datos en tiempo real
- Almacenamiento de imágenes
- Notificaciones

## Servidor de Desarrollo
- Puerto: 5000
- Comando: `python3 -m http.server 5000`

## Notas Técnicas
- La aplicación es responsive y funciona en dispositivos móviles y desktop
- Utiliza Tailwind CSS para estilos (CDN)
- Firebase versión 9.22.2 (modo compat)
- Diseño inspirado en TikTok con colores rosa pastel (#FE2C55, #25F4EE)
