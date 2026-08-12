# Raúl Ruiz – Dashboard de un legado

[![Licencia](https://img.shields.io/badge/licencia-MIT-blue)](LICENSE)

Un sitio web estático que presenta la vida, obra y legado del cineasta **Raúl Ruiz**, utilizando datos abiertos y contenido en vivo desde el ecosistema Wikimedia.

---

## Acerca del Proyecto

**Raúl Ruiz – Dashboard de un legado** es un proyecto web diseñado para demostrar cómo reutilizar datos abiertos del ecosistema Wikimedia en una experiencia visual moderna.

El sitio integra contenido actualizado automáticamente desde:

- **Wikipedia** (biografía, obras, reconocimientos)
- **Wikimedia Commons** (galería de imágenes, autoría, licencias)
- **Wikisource** (acceso a textos en dominio público)

Este proyecto sirve como ejemplo de conocimiento como infraestructura, mostrando cómo construir experiencias culturales digitales con fuentes verificables, abiertas y accesibles.

---

## Características Principales

* 📘 **Biografía Dinámica:** Los primeros párrafos de la biografía se cargan en vivo desde la API REST de Wikipedia.
* 🏆 **Reconocimientos:** Premios y distinciones del artista, como el Premio Nacional de Artes de la Representación.
* 🖼️ **Galería desde Wikimedia Commons:** Imágenes recuperadas desde una categoría de Commons.
* 📚 **Obras Fundamentales:** Portadas, descripciones y enlaces directos a Wikipedia para las principales obras de Raúl Ruiz.
* 🗓️ **Hitos:** Cronología de momentos clave en la vida y carrera del cineasta.
* ✍️ **Citas Aleatorias:** Generación dinámica de citas destacadas en cada visita.

---

## Construido Con

Este proyecto está construido completamente sobre tecnologías web abiertas:

**Frontend:**

- HTML5 + CSS3
- [TailwindCSS (CDN)](https://tailwindcss.com/)
- [Google Fonts](https://fonts.google.com/) (Montserrat, Inter)
- JavaScript

**APIs del Ecosistema Wikimedia:**

- [Wikipedia REST API](https://www.mediawiki.org/wiki/REST_API)
- [Wikipedia Action API](https://www.mediawiki.org/wiki/API:Main_page)
- [Wikimedia Commons API](https://commons.wikimedia.org/w/api.php)

---

## Uso Local

Este proyecto no requiere instalación, pero **debe ejecutarse desde un servidor local** (no abrir con doble clic), debido a políticas CORS de las APIs de Wikimedia.

### 1. Clona el repositorio

```sh
git clone https://github.com/tu-usuario/tu-repositorio.git
```

### 2. Entra al proyecto

```sh
cd tu-repositorio
```

### 3. Ejecuta en un servidor local

```sh
python3 -m http.server
```

¡Listo! La aplicación estará corriendo en `http://localhost:8000`.

---

## Licencia

El contenido reutilizado de Wikipedia y Wikimedia Commons está disponible bajo licencias libres (CC BY-SA, CC BY, Dominio Público).
El código del sitio puede liberarse bajo MIT u otra licencia abierta.

---

## Contacto

Jordy Lizana - [jordylizana-ship-it](https://github.com/jordylizana-ship-it)
Carla Toro - [Soylacarli](https://github.com/Soylacarli)
Tomás Bazán - [tromvn](https://github.com/tromvn)
Con el apoyo de **[Wikimedia Chile](https://wikimedia.cl/)**