
![[DTL.png]]

Dream Trophy es una **liga semanal** donde compites con tus veteranos contra otros jugadores.

  

---

## Calendario

| Fase                   | Cuándo                     |
| ---------------------- | -------------------------- |
| Inscripciones abiertas | Lunes 00:00 – Sábado 23:59 |
| Inscripciones cierran  | Sábado 23:59               |
| Carreras               | Domingo 12:00 (automático) |
  
---

  
## Comandos


### `dreamtrophy view` / `!dt view` / `!dt`


Muestra el estado de la temporada actual: carreras disponibles, tus inscripciones y fechas.

![[DTL02.png]]

### `dreamtrophy register` / `!dt register`
  
Inscribes un veterano en una carrera. Elige la carrera y luego el veterano de tu lista.

![[DTL_Register.png]]

### `dreamtrophy results` / `!dt results`

Muestra los resultados de tu última temporada.

![[DTL_Results.png]]

---

  

## Carreras por temporada

  

Cada temporada tiene **8 carreras** con combinaciones fijas:

  
| #   | Superficie | Distancia | Nombre                                 |
| --- | ---------- | --------- | -------------------------------------- |
| 1   | Turf       | Sprint    | Dream Sprint Trophy                    |
| 2   | Turf       | Mile      | Dream Mile Trophy                      |
| 3   | Turf       | Medium    | Dream Middle Trophy                    |
| 4   | Turf       | Long      | Dream Long Trophy                      |
| 5   | Dirt       | Sprint    | Dream Dirt Sprint Trophy               |
| 6   | Dirt       | Mile      | Dream Dirt Mile Trophy                 |
| 7   | Dirt       | Medium    | Dream Dirt Middle Trophy               |
|     | _Dirt_     | _Long_    | _Dream Dirt Long Trophy_<br>(Temporal) |


---


## Matchmaking

  

Los participantes se agrupan en **heats** (grupos de 6–12) según su **rating** de veterana. El matchmaking usa una ventana de ±175 puntos de rating.

  

---

## Sistema de recompensas


### Flujo general

  

1. **Inscripciones** (lunes–sábado): Inscribes 1 veterano por carrera con `/dreamtrophy register`.

2. **Matchmaking** (domingo 12:00): Se crean heats agrupando inscritos por rating (±175).

3. **Carreras** (domingo 12:00): Se simulan las carreras de cada heat. Las recompensas se guardan pero **no se entregan** hasta que uses el comando.

4. **Reclamar recompensas**: Usa `!dt results` o `/dreamtrophy results` para ver tus resultados y **recibir** las coins y carats en tu wallet.

  

---

  

### Cálculo de recompensas

  

Cada carrera Dream Trophy tiene valores base por temporada:

  

| Recompensa | Base |
| ---------- | ---- |
| Coins      | 150  |
| Carats     | 42   |
| Exp        | 35   |

### Multiplicador por rango del veterano

El rango (G, C, B, A, SS+, UG, UF...) multiplica las recompensas:

| Rango     | Multiplicador |
| --------- | ------------- |
| UF        | 2.0           |
| UG        | 1.6           |
| SS / S    | 1.4           |
| A / B     | 1.2           |
| C / D / E | 1.0           |
| F / G     | 0.8           |
  
### Multiplicador por posición

| Posición | Coins | Carats | Exp |
| -------- | ----- | ------ | --- |
| 1º       | 1.5   | 1.2    | 1.2 |
| 2º       | 1.3   | 1.1    | 1.1 |
| 3º       | 1.1   | 1.0    | 1.0 |
| 4º       | 1.0   | 0.8    | 0.8 |
| 5º       | 0.9   | 0.8    | 0.8 |
| 6º       | 0.8   | 0.8    | 0.8 |
| 7º+      | 0.5   | 0.4    | 0.4 |
  

**Fórmula final:** `base × multRango × multPosición` (redondeado).


### Ejemplo


Veterano rango **UF** (×2.0), posición **1º** en Dream Sprint Trophy:

- Coins: 150 × 2.0 × 1.5 = **450**

- Carats: 42 × 2.0 × 1.2 = **100** (máximo por carrera)

- Exp: 35 × 2.0 × 1.2 = **84**


Veterano rango **A** (×1.2), posición **1º**:

- Carats: 42 × 1.2 × 1.2 = **60**

  
---

## NPCs en heats

Si un heat tiene menos de 4 participantes reales, se rellenan con **NPCs** (nombres de Umas de la base de datos). Los NPCs no reciben recompensas; solo los usuarios inscritos.

Con 1 solo usuario inscrito en una carrera, el heat tendrá 1 real + 3 NPCs. El usuario compite y puede ganar recompensas según su posición.

---

## Restricciones
  

- Solo puedes inscribir **un veterano por carrera** (no el mismo en dos carreras de la misma temporada)

- El veterano debe estar **retirado** (no en entrenamiento)

- Las inscripciones no se pueden modificar una vez cerradas

  

---

## Consejos

  
1. Inscribe veteranos con **aptitud A o B** para la superficie y distancia de cada carrera.

2. Los veteranos con **rango UG/UF** suelen rendir mejor.

3. Revisa `!dt view` al inicio de la semana para planificar tus inscripciones.