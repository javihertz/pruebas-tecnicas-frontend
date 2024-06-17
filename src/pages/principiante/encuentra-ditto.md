---
layout: ../../layouts/NivelLayout.astro
mainText: Encuentra a
strongText: Ditto
level: Principiante
description: "El objetivo de esta prueba es evaluar tus habilidades para identificar elementos específicos en una lista de objetos y devolver el resultado esperado.
En el mundo de Pokémon, cuando un Ditto se transforma en otro Pokémon, puede copiar el 99% de la apariencia del Pokémon original. Sin embargo, existe un rasgo distintivo que permite diferenciar a un Ditto transformado de un Pokémon real: los ojos. Los Ditto transformados siempre tienen los ojos como dos puntos negros (points), a diferencia de los Pokémon originales."

---

# JSON

```ts
const pokemons = [
    {
      "name": "Pikachu",
      "type": "Electric",
      "height": 0.4,
      "weight": 6,
      "eyes": "oval",
    },
    {
      "name": "Bulbasaur",
      "type": "Grass/Poison",
      "height": 0.7,
      "weight": 6.9,
      "eyes": "oval"
    },
    {
      "name": "Charmander",
      "type": "Fire",
      "height": 0.6,
      "weight": 8.5,
      "eyes": "point"
    },
    {
      "name": "Charmander",
      "type": "Fire",
      "height": 0.6,
      "weight": 8.5,
      "eyes": "oval"
    },
    {
      "name": "Squirtle",
      "type": "Water",
      "height": 0.5,
      "weight": 9,
      "eyes": "oval"
    },
    {
      "name": "Pikachu",
      "type": "Electric",
      "height": 0.4,
      "weight": 6,
      "eyes": "point"
    },
    {
      "name": "Bulbasaur",
      "type": "Grass/Poison",
      "height": 0.7,
      "weight": 6.9,
      "eyes": "point"
    },

    {
      "name": "Squirtle",
      "type": "Water",
      "height": 0.5,
      "weight": 9,
      "eyes": "point"
    }
]
```
