## Simulación de una carrera
### Stats y pesos por distancia

Las cinco stats (velocidad, stamina, poder, guts, wit) no pesan igual en todas las distancias. El juego usa pesos para calcular el rendimiento:

| Distancia | Velocidad | Stamina | Poder | Guts | Wit |
| --------- | --------- | ------- | ----- | ---- | --- |
| Sprint    | 40%       | 10%     | 25%   | 20%  | 5%  |
| Mile      | 30%       | 25%     | 20%   | 15%  | 10% |
| Medium    | 20%       | 35%     | 20%   | 15%  | 10% |
| Long      | 15%       | 40%     | 20%   | 15%  | 10% |

Ejemplo: En sprint, 100 puntos de velocidad aportan más que 100 de stamina. En long, ocurre al revés.

### Aptitudes

Las aptitudes son grados (A–G) que indican qué tan buena es la Uma en superficie, distancia y estrategia. Se aplican como multiplicadores al rendimiento:

_(Sujeto a cambios)_

| Grado aptitud | Modificador | Efecto           |
| ------------- | ----------- | ---------------- |
| A             | ×1.10       | +10% rendimiento |
| B             | ×1.05       | +5% rendimiento  |
| C             | ×1.00       | Sin cambio       |
| D             | ×0.95       | -5% rendimiento  |
| E             | ×0.90       | -10% rendimiento |
| F             | ×0.85       | -15% rendimiento |
| G             | ×0.80       | -20% rendimiento |

Superficie y distancia se multiplican entre sí. Ejemplo: A en turf y B en mile → ×1.10 × 1.05 ≈ ×1.16.
### Estrategias de carrera

Antes de correr eliges una estrategia:

|Estrategia|Descripción|
|---|---|
|Best|Usa la estrategia con mejor aptitud de la uma|
|Front|Ir al frente desde el inicio|
|Pace|Mantener ritmo medio|
|Late|Acelerar en la recta final|
|End|Sprint muy fuerte al final|

La estrategia influye en qué skills de cartas pueden activarse (por ejemplo, strategy_front, strategy_late).


