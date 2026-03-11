El entrenamiento permite subir las estadísticas de tus Umas usando un equipo de hasta 3 Umas, dependiendo de las cartas de apoyo y condiciones aleatorias. Cada sesión tiene un cooldown de 1 hora, y una Uma puede entrenar un máximo de 24 turnos.

## El equipo de entrenamiento
Un equipo de entrenamiento cuenta con 3 slots. En cada uno de ellos puedes tener:
- 1 Uma de tu colección, no puedes tener Umas repetidas en el equipo
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
## Sistema de herencias
Cuando agregas una Uma al equipo usando /team add, el bot te dará la opción de seleccionar dos Umas de herencia. Hacer esto otorgará un bonus de estadísticas a tu nueva Uma, basado en el rango de las que selecciones como herencia.
![[Inheritance.png]]

El porcentaje de estadísticas que te otorga una herencia, se calcula de la siguiente manera:

- Las umas veteranas transmiten entre 7% y 12% de sus estadísticas según su rango de retiro. Rangos bajos (G–C) dan 7%; rangos altos (C+–UF1) dan más, hasta 12% en UF1. Cuanto mejor rango tenga la veterana, más stats hereda la nueva Uma.

| G–C | C+–B+ | A–SS+ | UG     | UF      |
| --- | ----- | ----- | ------ | ------- |
| 7%  | ~7–8% | ~8–9% | ~9–11% | ~11–12% |
> [!INFO]
> No puedes usar a la misma Uma que intentas entrenar como herencia

## Entrenar (/train)
Para poder realizar una sesión de entrenamiento, debes cumplir las siguientes condiciones:
- Tener al menos una Uma en el equipo
- Cooldown de una hora completado

Durante una sesión de entrenamiento, podrás decidir que entrenar para cada una de tus Umas con los selectores que te proporciona el bot. Cada uno de estos corresponde a una Uma de tu equipo, por orden de slot
![[Train_01.png]]
>[!TIP]
>En estos selectores aparece por defecto la última estadística que entrenaste, por lo que si deseas repetir una sesión, solo debes dar click en confirmar inmediatamente

Antes de realizar un entrenamiento, el bot te mostrará las condiciones del clima, y el mood de cada una de tus Umas. Esta información es importante, pues afecta los resultados del entrenamiento.
### Clima
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

### Mood
Afecta la ganancia general de estadísticas de la siguiente manera:

| **Clima** |      **Efecto**      |
| :-------: | :------------------: |
|   Great   | +10% de estadísticas |
|   Good    | +5% de estadísticas  |
|  Normal   |     Ninguno<br>      |
|    Bad    | -5% de estadísticas  |
|   Awful   | -10% de estadísticas |
#### /recreation

El mood tiene una pequeña probabilidad de subir o bajar al finalizar una sesión de entrenamiento. Sin embargo, también cuentas con el comando **/recreation**, que mejora el mood de todo tu equipo

> [!WARNING]
> Este comando puedes usarlo una vez cada 5 horas, piensa bien cuando es el momento de hacerlo

## Estado de entrenamiento
Para ver los detalles de tu equipo, puedes usar el comando /train status. De esta manera, el bot te mostrará las estadísticas de todas tus umas, su estado de ánimo y la cantidad de turnos de entrenamiento que han usado
![[TrainStatus.png]]
- - -
## Retiro de umas y rango de carrera
Cuando una Uma alcanza los 24 turnos de límite establecido, se retira y pasa a ser veterana. En ese momento, el bot genera una carta con la información final de la Uma: Sus estadísticas finales y su rango, que es una muestra del desempeño del entrenamiento

![[Retire.png]]
#### ¿Cómo se calcula el rango?

El rango depende de un puntuación:

> Puntuación = Crecimiento de stats + (Victorias × 50)

- Crecimiento de stats: suma de stats finales − suma de stats iniciales (velocidad, stamina, poder, guts, wit).

- Victorias: cada victoria en carrera suma 50 puntos.

#### Tipos de rangos

1. Letras (G → SS+): 18 rangos, desde G (más bajo) hasta SS+ (más alto).

2. UG (UG10 → UG1): 10 rangos por encima de SS+.

3. UF (UF10 → UF1): 10 rangos máximos.
- - -
