# Karaoke Night Manager (Didaxkaraoke)

Karaoke Night Manager es una aplicación web moderna para gestionar sesiones de karaoke, ideal para bares, fiestas o reuniones. Permite buscar canciones de karaoke en YouTube, añadirlas a una cola de reproducción, llevar el control de las canciones más reproducidas y ofrece una experiencia visual atractiva y fácil de usar.

## Características

- 🎤 **Búsqueda de canciones karaoke** en YouTube usando palabras clave y artista.
- 📺 **Reproductor integrado** basado en el IFrame API de YouTube, con soporte de pantalla completa.
- 📋 **Cola de reproducción dinámica**: añade, elimina y reordena canciones fácilmente.
- ⭐ **Estadísticas en tiempo real**: visualiza las canciones más reproducidas de la sesión.
- 🏆 **Interfaz moderna**: diseño responsivo con TailwindCSS y efectos visuales atractivos.
- 🗂️ **Persistencia local**: la cola y las estadísticas se guardan en el navegador.

## Instalación y uso

### 1. Clonar el repositorio

```bash
git clone https://github.com/didapape/Didaxkaraoke.git
cd Didaxkaraoke
```

### 2. Configurar Clave API de YouTube

Para que la búsqueda funcione, necesitas una clave API de YouTube válida.  
Edita el archivo HTML y reemplaza el valor de `YOUTUBE_API_KEY` por tu propia clave:

```js
const YOUTUBE_API_KEY = 'AQUÍ_TU_CLAVE_API';
```
[Guía sobre cómo obtener una clave de API de YouTube](https://developers.google.com/youtube/v3/getting-started)

### 3. Ejecutar

Solo necesitas abrir el archivo `index.html` en tu navegador.

---

## Estructura de la App

- **index.html**: Todo el código de la aplicación (HTML, CSS y JS) se encuentra aquí.
- **TailwindCSS** y **Lucide Icons** se cargan desde CDN.
- La aplicación es completamente frontend y no requiere servidor.

---

## Funcionalidades detalladas

- **Buscar Canción:**  
  Escribe el título y/o artista y haz clic en buscar. Se mostrarán hasta 5 videos de karaoke embebibles.

- **Añadir a la Cola:**  
  Haz clic en el resultado para agregarlo a la cola. Puedes gestionar la cola y eliminar canciones.

- **Reproducir Siguiente:**  
  Usa el botón de micrófono para reproducir la siguiente canción de la cola.

- **Pantalla Completa:**  
  Usa el botón de maximizar para poner el reproductor en pantalla completa.

- **Estadísticas:**  
  Las canciones más reproducidas aparecen en la sección "Top Canciones".

- **Persistencia:**  
  La cola y estadísticas se mantienen aunque recargues la página (usando localStorage).

---

## Captura de pantalla

![Ejemplo de la aplicación Didaxkaraoke](https://images.unsplash.com/photo-1514933651103-005eec06c04b?auto=format&fit=crop&w=800&q=80)

---

## Créditos

- Imagen de fondo: Unsplash
- [TailwindCSS](https://tailwindcss.com/)
- [Lucide Icons](https://lucide.dev/)
- [YouTube Data API](https://developers.google.com/youtube/v3)

---

## Licencia

MIT

---

### Hecho por [didapape](https://github.com/didapape)
