# 🛸 Rick & Morty Portal Finder

Aplicación web modular que consume la [API de Rick & Morty](https://rickandmortyapi.com/) y permite buscar, filtrar, marcar favoritos, paginar y ver la ficha de cada personaje.

## Funcionalidades

- Tres estados de pantalla: **cargando** (spinner), **error** (con botón Reintentar) y **éxito** (tarjetas o "sin resultados").
- Búsqueda por nombre en tiempo real.
- Filtro por estado (Alive, Dead, unknown) combinado con el buscador.
- Aviso cuando el estado elegido no existe en la página cargada.
- Favoritos con contador, que se conservan al cambiar de página.
- Paginación con botones desactivados en los extremos.
- Modal con la ficha del personaje: foto, estado, especie, origen, género y número de episodios.

## Tecnologías

- HTML5
- CSS3 + Bootstrap 5
- JavaScript (módulos ES, `fetch`, `async/await`)

## Estructura del proyecto

## Conceptos aplicados

- `fetch` con `async/await`, validación de `respuesta.ok` y `try / catch / finally`.
- Módulos ES: `export`, `export default`, `import` y `type="module"`.
- Métodos de arreglos: `map`, `filter`, `find`, `some`, `includes` y `join`.
- Desestructuración y spread para actualizar favoritos **sin mutar** el estado.
- Delegación de eventos con un solo listener en el contenedor de tarjetas.
- `escaparHTML` para evitar inyección de código al usar `innerHTML`.

## Cómo ejecutarlo

1. Clona el repositorio:
   ```bash
   git clone https://github.com/Kath51/rick-morty-finder.git
   ```
2. Abre la carpeta en VS Code.
3. Instala la extensión **Live Server**.
4. Clic derecho en `index.html` → **Open with Live Server**.

> Los módulos ES no funcionan abriendo el archivo con doble clic (`file://`), por eso se necesita Live Server.

## Autora

Kath51