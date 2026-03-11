![[TrainStatus.png]]
  

El entrenamiento es el núcleo del juego. Cada sesión tiene **24 turnos** y un **cooldown de 1 hora** entre sesiones.

  

---

  

## Comandos

  

### `train start` / `!train start`



Inicia una sesión de entrenamiento. Debes elegir un **stat de enfoque** (speed, stamina, power, guts, wit). El stat elegido recibe la mayor ganancia; los secundarios reciben ~20%.

![[Train_01.png]]  

### `train status` / `!train status`

  
Muestra el estado actual: equipo, turnos completados, ánimo, cooldown restante y clima.

![[TrainStatus02.png]]

### `recreation` / `!recreation`

  

Sube el ánimo de todas las Umas del equipo. **Cooldown: 5 horas.**

  

- Sube 1 nivel de ánimo (o 2 con 30% de probabilidad)

  

### `weather` / `!weather`

  

Muestra el clima actual. El clima es **global** para todos los usuarios y cambia cada **3 horas**.

  

---

  

## Stats

  
El stat de enfoque recibe la ganancia principal. Los stats secundarios asociados reciben ~20%:

- Speed → Power

- Stamina → Guts

- Power → Stamina

- Guts → Speed, Power

- Wit → Speed

  

---

  
## Clima

![[weather.png]]

El clima afecta las ganancias y la probabilidad de fallo:

| Clima           | Efecto                                 |
| --------------- | -------------------------------------- |
| Clear / Cloudy  | Sin cambios (75% del tiempo)           |
| Light Rain      | Speed -3%, Guts +3%                    |
| Pleasant Breeze | +5% todos los stats                    |
| Heat Wave       | Stamina -5%, +2% probabilidad de fallo |
| Storm           | Speed -5%, Power -5%, Guts +5%         |
| Light Snow      | Speed -5%, Power +5%                   |

---

## Ánimo

  
Cada Uma tiene un nivel de ánimo (1–5) que afecta el entrenamiento:

| Nivel      | Emoji | Multiplicador ganancia | Fallo |
| ---------- | ----- | ---------------------- | ----- |
| 1 (Awful)  | 😭    | 90%                    | +5%   |
| 2 (Bad)    | 😞    | 95%                    | 0%    |
| 3 (Normal) | 😐    | 100%                   | 0%    |
| 4 (Good)   | 😃    | 105%                   | 0%    |
| 5 (Great)  | 🤩    | 110%                   | 0%    |

  

El ánimo puede subir o bajar después de cada turno. Las cartas Pal reducen la probabilidad de bajada. Puedes usar el comando **/recreation** para subir el ánimo de **todo** tu equipo al mismo tiempo

![[Recreation.png]]

---


## Retiro


Al completar los 24 turnos, la Uma se **retira automáticamente** y pasa a tu lista de veteranas. El rango de retiro depende del crecimiento de stats y las carreras ganadas.

El bot genera una tarjeta de tu Uma, mostrando sus estadísticas finales y el rango final que obtiene. Este se calcula según sus estadísticas y victorias obtenidas

![[Retire.png]]

---


## Consejos

  

1. Usa `recreation` cuando el ánimo esté bajo (1–2) para maximizar ganancias.

2. Entrenar con **Pleasant Breeze** da un buen bonus; evita Heat Wave si puedes.

3. Elige el stat de enfoque según las aptitudes de la Uma y las carreras que quieras correr.