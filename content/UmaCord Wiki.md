
> Bot de Discord inspirado en *Uma Musume Pretty Derby*. Colecciona Umas, cartas de apoyo y entrena a tus corredoras.

---

## ¿Qué es UmaCord?

UmaCord es un bot que recrea la experiencia de coleccionar personajes y cartas de Uma Musume. Puedes hacer gacha para conseguir Umas y cartas, entrenarlas y formar equipos.

---

## Empezar

1. **Recompensas diarias** — Usa `/daily` para obtener monedas cada día. La racha aumenta las recompensas.
2. **Tu balance** — `/balance` muestra tus Coins, Carats y Clovers.
3. **Primer gacha** — Usa `/pulluma` o `/pullcard` para conseguir tu primera Uma o carta.

---

## Monedas

| Moneda | Uso principal |
|--------|----------------|
| Coins | Gacha de Umas y Cartas |
| Carats | Alternativa para gacha |
| Clovers | (En desarrollo) |

---

## Gacha

### Gacha de Umas

- **Rarezas:** Common → Uncommon → Rare → Epic → Legendary
- **Pity:** Si no sacas Legendary en 100 tiradas, la siguiente es Legendary. Epic garantizado cada 30 tiradas.
- **Coste:** 150 por pull

### Gacha de Cartas

- **Rarezas:** R → SR → SSR → UR
- **Pity:** UR garantizada a las 100 tiradas, SSR a las 30.
- **Coste:** 150 por pull

### Consejos

- Los pulls múltiples (`/multiuma`, `/multicard`) muestran varias unidades en una sola imagen.
- Las Umas pueden tener estrellas y duplicados; las cartas tienen Limit Break (0–5).

---

## Colección

### Mis Umas (`/myumas`)

- Lista paginada de tus Umas.
- Muestra rareza, estrellas y duplicados.
- Cada Uma tiene su perfil visual.

### Mis Cartas (`/mycards`)

- Lista paginada de tus cartas.
- Muestra rareza, personaje asociado y Limit Break.
- Las cartas dan bonificaciones en entrenamiento.

---

## Entrenamiento

### El equipo

- **3 slots** de entrenamiento.
- Cada slot: **1 Uma** + **3 cartas**.
- Las cartas dan bonos a stats según su tipo (Speed, Power, Stamina, etc.).

### Cómo entrenar

1. **Montar equipo** — `/team add` para añadir Umas a los slots.
2. **Asignar cartas** — Desde la vista del equipo, selecciona las cartas para cada slot.
3. **Entrenar** — `/train` para completar turnos de entrenamiento.

### Progreso

- Cada Uma debe completar **24 turnos** para graduarse.
- El clima y el ánimo afectan las ganancias de stats.
- **Stats:** Speed, Stamina, Power, Guts, Wit.

### Vista del equipo

`/team view` genera una imagen con tu equipo actual: Umas y cartas por slot.

---

## Personajes y cartas

### Umas

Hay 41 Umas disponibles, desde Common hasta Legendary. Cada una tiene stats base, tipo de distancia preferido y habilidad única.

> Ver [[Lista de Umas]] para el listado completo

### Cartas de apoyo

Hay 52 cartas (R, SR, SSR, UR). Cada carta está ligada a un personaje y da bonos a stats concretos en condiciones específicas (distancia, estrategia, superficie, etc.).

> Ver [[Lista de Cartas]] para el listado completo
---

## FAQ

**¿Cómo consigo más monedas?**  
Principalmente con `/daily`. Mantén la racha para mejores recompensas.

**¿Qué hace el pity?**  
Si no sacas la rareza más alta en X tiradas, la siguiente pull la garantiza (Legendary/UR a 100, Epic/SSR a 30).

**¿Puedo quitar una Uma del equipo?**  
Sí, con `/team remove` y el número de slot (1, 2 o 3).

**¿Las cartas se consumen al usarlas?**  
No. Las cartas se asignan al equipo y se pueden reutilizar.

---

## Comandos

> Ver [[Comandos]] para la lista completa.