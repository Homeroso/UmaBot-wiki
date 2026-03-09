El entrenamiento permite subir las estadísticas de tus Umas usando un equipo de hasta 3 Umas, dependiendo de las cartas de apoyo y condiciones aleatorias. Cada sesión tiene un cooldown de 1 hora, y una Uma puede entrenar un máximo de 24 turnos.

### El equipo de entrenamiento
Un equipo de entrenamiento cuenta con 3 slots. En cada uno de ellos puedes tener:
- 1 Uma de tu colección
- Hasta 3 Cartas de apoyo equipadas
![[Team.png]]

> [!WARNING]
 > No puedes equipar cartas de apoyo de la Uma que deseas entrenar, ni repetir cartas en el equipo

Para administrar el equipo, cuentas con los siguientes comandos:

| Comando               | Descripción                                                       |
| --------------------- | ----------------------------------------------------------------- |
| /team view            | Ver el equipo actual con imagen y **botones para asignar cartas** |
| /team add <*uma_id*>  | Añadir una Uma al primer slot libre (ej: tokai_teio)              |
| /team remove <*slot*> | Quitar la Uma del slot 1, 2 o 3                                   |

### Entrenar (/train)
Para poder realizar una sesión de entrenamiento, debes cumplir las siguientes condiciones:
- Tener al menos una Uma en el equipo
- Cooldown de una hora completado

Durante una sesión de entrenamiento, podrás decidir que entrenar para cada una de tus Umas con los selectores que te proporciona el bot. Cada uno de estos corresponde a una Uma de tu equipo, por orden de slot
![[Train_01.png]]
>[!TIP]
>En estos selectores aparece por defecto la última estadística que entrenaste, por lo que si deseas repetir una sesión, solo debes dar click en confirmar inmediatamente

Antes de realizar un entrenamiento, el bot te mostrará las condiciones del clima, y el mood de cada una de tus Umas. Esta información es importante, pues afecta los resultados del entrenamiento.
#### Clima
Modificador global, afecta a todos los usuarios y cambia de manera aleatoria cada 3 horas. Los posibles climas son los siguientes:

|     **Clima**      |                                      **Efecto**                                      |
| :----------------: | :----------------------------------------------------------------------------------: |
|    ☀️ Despejado    |                                       Ninguno                                        |
|     ☁️ Nublado     |                                       Ninguno                                        |
| 🌧️ Lluvia Ligera  |             -3% de ganancia de **Speed**<br>+3% de ganancia de **Guts**              |
| 🍃 Brisa Agradable |                     +5% de ganancia a **Todas** las estadísticas                     |
|   🔥Ola de Calor   | -5% de ganancia de **Stamina**<br>+2% de **probabilidad de fallar** el entrenamiento |
|    ⛈️ Tormenta     |     -5% de ganancia de **Speed** y **Power**<br>+5% de ganancia de **Guts**<br>      |
|  ❄️ Nieve Ligera   |           -5% de ganancia de **Speed**<br>+5% de ganancia de **Power**<br>           |

#### Mood
Afecta la ganancia general de estadísticas de la siguiente manera:

| **Clima** |      **Efecto**      |
| :-------: | :------------------: |
|   Great   | +10% de estadísticas |
|   Good    | +5% de estadísticas  |
|  Normal   |     Ninguno<br>      |
|    Bad    | -5% de estadísticas  |
|   Awful   | -10% de estadísticas |
El mood tiene una pequeña probabilidad de subir o bajar al finalizar una sesión de entrenamiento. Sin embargo, también cuentas con el comando /recreation, que mejora el mood de todo tu equipo

> [!WARNING]
> Este comando puedes usarlo una vez cada 5 horas, piensa bien cuando es el momento de hacerlo
