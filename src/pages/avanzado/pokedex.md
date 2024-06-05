# Prueba Técnica para Programador Frontend: Pokédex

## Introducción

Te damos la bienvenida a esta prueba técnica para la posición de Programador Frontend. El objetivo de esta prueba es evaluar tus habilidades para desarrollar una aplicación web interactiva y dinámica utilizando tecnologías modernas de frontend. En esta ocasión, te pedimos que desarrolles una Pokédex.

## Requisitos del Proyecto

### Funcionalidades Básicas

1. **Fetch de Datos**:
   - Utiliza la [API pública de PokéAPI](https://pokeapi.co/) para obtener una lista de Pokémon y detalles específicos de cada uno.
   - Implementa una funcionalidad para cargar más Pokémon al hacer scroll hacia abajo (infinite scroll).

2. **Añadir y Eliminar Favoritos**:
   - Permite a los usuarios añadir Pokémon a una lista de favoritos.
   - Permite a los usuarios eliminar Pokémon de la lista de favoritos.
   - La lista de favoritos debe persistir aunque el usuario recargue la página (puedes usar localStorage).

3. **Buscador**:
   - Implementa una barra de búsqueda que permita a los usuarios buscar Pokémon por nombre.

4. **Filtros por Tipo**:
   - Implementa un sistema de filtrado que permita a los usuarios filtrar los Pokémon por su tipo (agua, fuego, planta, etc.).

### Funcionalidades Avanzadas (Opcional)

1. **Paginación**:
   - Además del infinite scroll, permite a los usuarios navegar entre páginas de resultados.

2. **Detalles del Pokémon**:
   - Al hacer clic en un Pokémon, muestra una vista detallada con información adicional (estadísticas, habilidades, evoluciones, etc.).

3. **Interfaz Responsiva**:
   - Asegúrate de que la aplicación sea completamente responsiva y funcione bien en dispositivos móviles.

4. **Animaciones**:
   - Añade animaciones para mejorar la experiencia de usuario, por ejemplo, al añadir/eliminar favoritos o al cargar más Pokémon.

### Pruebas Unitarias

1. **Pruebas de Componentes**:
   - Escribe pruebas unitarias para al menos tres componentes principales de tu aplicación (por ejemplo: el componente de la lista de Pokémon, el componente de detalles de Pokémon, y el componente de favoritos).

2. **Pruebas de Funcionalidades**:
   - Escribe pruebas unitarias para las funciones clave, como la búsqueda de Pokémon y el filtrado por tipo.

## Pautas de Desarrollo

1. **Tecnologías**:
   - Puedes utilizar cualquier framework de frontend moderno, aunque se recomienda React.js o Vue.js.
   - Usa CSS, SASS o algún framework de CSS para el estilo (ej. TailwindCSS, Bootstrap).

2. **Gestión del Estado**:
   - Puedes usar soluciones como Redux, Vuex, o el contexto de React para la gestión del estado global.

3. **Testing**:
   - Utiliza bibliotecas como Jest, Testing Library o Cypress para las pruebas unitarias y funcionales.

## Entrega

1. **Repositorio**:
   - Publica tu código en un repositorio público de GitHub y proporciona el enlace.
   - Incluye un archivo README.md con instrucciones claras sobre cómo instalar y ejecutar tu aplicación, así como cómo ejecutar las pruebas.

2. **Demostración**:
   - (Opcional) Si es posible, despliega tu aplicación en una plataforma de hosting como Vercel, Netlify o GitHub Pages y proporciona el enlace.

## Evaluación

Serás evaluado en base a los siguientes criterios:
- Correcta implementación de las funcionalidades requeridas.
- Calidad y claridad del código.
- Uso adecuado de tecnologías y herramientas.
- Eficiencia y rendimiento de la aplicación.
- Calidad de las pruebas unitarias.
- Diseño y experiencia de usuario.

¡Buena suerte y esperamos ver tu creatividad y habilidades en acción!
