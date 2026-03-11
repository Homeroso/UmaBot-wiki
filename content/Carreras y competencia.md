*De que serviría entrenar Umas si no van a competir en carreras?*

Las carreras son la forma principal de ganar recompensas experiencia y subir las stats de tus Umas durante el entrenamiento. El resultado depende de las stats, aptitudes, estrategia, skills y algo de azar.

Puedes correr una carrera por turno con cada Uma de tu equipo de entrenamiento. Hay un cooldown global de 30 minutos entre carreras.

## Tipos de carreras

Existen tres tipos de carreras principales:

| Tipo              | Comando / Acceso | Descripción                                                                                        | Oponentes                                        |
| ----------------- | ---------------- | -------------------------------------------------------------------------------------------------- | ------------------------------------------------ |
| Carreras normales | /race            | Carreras durante el entrenamiento. Disponibles según el turno actual de la uma.                    | Pre-Op y Op: NPCs. G3, G2 y G1: jugadores reales |
| Friendly Race     | /friendlyrace    | Carreras creadas por jugadores. El creador elige superficie, distancia y grado.                    | Otros jugadores inscritos (hasta 10)             |
| Dream Trophy      | /dreamtrophy     | Torneo semanal con umas veteranas (retiradas). Inscripciones hasta el sábado; carreras el domingo. | Jugadores con rating similar                     |
- - -
## Estructura de una carrera

Cada carrera se define por tres atributos:

### Superficie

- Turf (césped): pista de hierba.

- Dirt (arena): pista de tierra.

La aptitud de la Uma para cada superficie afecta su rendimiento.

### Distancia

- Sprint (~1200 m): carreras cortas.

- Mile (~1600 m): carreras medias-cortas.

- Medium (~2000 m): carreras medias.

- Long (~2400 m): carreras largas.

A mayor distancia, más importante la stamina y menos la velocidad pura.

- - -
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
- - -
## Skills

Las skills dan bonos temporales durante la carrera. Hay dos tipos:

### Skills de cartas (equipo)

Las cartas asignadas a la uma pueden tener skills que se activan por fase:

- Condiciones: always, distance_sprint, surface_turf, strategy_front, etc.

- Efectos:

- Planos: speed_+50 → +50 a velocidad.

- Porcentuales: stamina_+10% → +10% de stamina.

- Todas las stats: all_+15 → +15 a cada stat.

- Probabilidad de activación: 70% por fase cuando la condición se cumple.

### Skill única de la uma

Cada uma tiene una skill única:

- Fases: late y final.

- Probabilidad: 60% en una de esas fases.

- Efecto: +30 al stat objetivo (por defecto velocidad).

- Activaciones: solo una vez por carrera.
### Carreras Para Umas activas
Mientras entrenas tus Umas, puedes hacer que compitan en diferentes carreras, distribuidas de la siguiente manera:

| Grado  | Dificultad | Oponentes                        | Premios                    |
| ------ | ---------- | -------------------------------- | -------------------------- |
| Pre-Op | Baja       | NPCs                             | 50–60 monedas, 10–14 exp   |
| Op     | Media      | NPCs                             | 75–90 monedas, 16–22 exp   |
| G3     | Alta       | Jugadores (75–95% de tu poder)   | 120–135 monedas, 28–32 exp |
| G2     | Muy alta   | Jugadores (90–110% de tu poder)  | 170–185 monedas, 38–42 exp |
| G1     | Máxima     | Jugadores (105–125% de tu poder) | 250–265 monedas, 55–60 exp |
> [!WARNING]
> Solo puedes hacer que tu Uma corra en una carrera por cada turno de entrenamiento

Según el desempeño de la Uma en la carrera, obtendrás **coins** como recompensa, ademas de un pequeño aumento de stats 
### Dream Trophy League

