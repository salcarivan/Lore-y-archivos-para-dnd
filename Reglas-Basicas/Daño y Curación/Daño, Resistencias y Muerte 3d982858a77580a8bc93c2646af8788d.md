# Daño, Resistencias y Muerte

# 🔥 1. Tipos de Daño

Imagina que cada tipo de daño es como un "elemento" en un videojuego RPG (piensa en Pokémon o Final Fantasy): fuego, hielo, veneno... cada uno representa una fuente distinta de daño, y algunas criaturas son fuertes o débiles contra ciertos tipos.

En D&D 2024 hay **13 tipos de daño oficiales**. No tienen "número" propio: el tipo de daño no cambia cuánto duele el golpe por sí mismo, solo determina si algo lo resiste, es vulnerable a él, o es inmune.

| Tipo de daño | Origen típico | Analogía rápida |
| --- | --- | --- |
| **Ácido** | Escupitajo de un limo negro, un frasco de ácido | Como el ácido de batería: corroe, no quema |
| **Contundente** | Golpe de maza, caída, puñetazo | El "daño físico romo" de cualquier RPG: mazazos, embestidas |
| **Cortante** | Espadas, hachas, garras | Filo que corta carne y tela |
| **Frío** | Aliento de dragón blanco, hechizo *Cono de frío* | El elemento "hielo" de cualquier JRPG |
| **Fuego** | *Bola de fuego*, antorchas, aliento de dragón rojo | El elemento "fuego" clásico |
| **Fuerza** | *Rayo de fuerza mágica*, un golpe de energía pura | Energía mágica "genérica", como un láser de ciencia ficción |
| **Necrótico** | Toque de un no-muerto, hechizos de la escuela de nigromancia | El "drenaje vital" tipo vampiro o Grim Reaper |
| **Perforante** | Flechas, colmillos, lanzas | Cualquier cosa que empala o muerde |
| **Psíquico** | Ataques mentales, un mind flayer, el hechizo *Onda de trueno mental* | Daño directo a la mente, como un ataque psíquico en Pokémon |
| **Radiante** | Luz divina, hechizos de clérigo, un ángel | El elemento "luz" o "sagrado" en un JRPG |
| **Rayo** | Electricidad | El elemento "eléctrico", tipo Pikachu |
| **Trueno** | Sonido o Explosión | Daño de **sonido/onda expansiva**, no de electricidad (ojo, se confunde mucho con "Rayo") |
| **Veneno** | Mordedura de serpiente, gas tóxico | El clásico "poison damage" de cualquier RPG |

> **Distinción importante:** "Trueno" (sonido/explosión) y "Rayo" (electricidad) son dos tipos *distintos* en inglés también (*Thunder* vs *Lightning*). Es fácil confundirlos porque en español suenan parecidos, pero mecánicamente no tienen nada que ver entre sí.
> 

---

## 🛡️ 2. Vulnerabilidades, Resistencias e Inmunidades

Sigue con la analogía del RPG con elementos: cada criatura tiene una especie de "tabla de tipos" (como la tabla de tipos de Pokémon) que le dice cómo reacciona a cada tipo de daño.

### ¿Cómo funciona cada una?

| Concepto | Qué hace | Analogía |
| --- | --- | --- |
| **Resistencia** | El daño de ese tipo se **reduce a la mitad** (se redondea hacia abajo) | Como llevar puesta una "armadura de fuego" en un juego: el fuego sigue dañando, pero mucho menos |
| **Vulnerabilidad** | El daño de ese tipo se **duplica** | Es el "punto débil elemental": como un enemigo de hielo recibiendo doble daño de fuego |
| **Inmunidad** | Ese tipo de daño **no hace nada, 0 puntos** | Como un esqueleto inmune al veneno porque no tiene sangre ni pulmones: ese "elemento" simplemente no le afecta |

### El orden de cálculo (esto es clave)

Cuando una criatura tiene resistencia **y** vulnerabilidad al mismo tipo de daño a la vez (raro, pero pasa), las reglas de 2024 dicen que primero se suma todo el daño de ese tipo, **luego** se aplica la vulnerabilidad (x2) y **después** la resistencia (÷2) — en la práctica, esto hace que se cancelen entre sí y el daño se aplique normal (sin duplicar ni reducir).

> **Regla de "no se acumulan resistencias del mismo tipo":** si un personaje tiene resistencia al fuego por dos fuentes distintas a la vez (por ejemplo, un hechizo Y un objeto mágico), **no** se aplica ÷2 dos veces. Solo se divide una vez. Piensa en ello como en muchos videojuegos: dos "buffs" del mismo tipo no se multiplican entre sí, solo cuenta el efecto una vez.
> 

### Paso a paso de cómo se calcula el daño final

1. Se tira el dado de daño del ataque o hechizo (por ejemplo, 2d6 de una espada larga a dos manos).
2. Se suman los modificadores (como el modificador de Fuerza).
3. Se compara el **tipo** de ese daño con las características de la criatura que lo recibe.
4. Si tiene **inmunidad** a ese tipo → el daño final es 0, fin del cálculo.
5. Si tiene **resistencia** → se divide el total entre 2 (redondeando hacia abajo).
6. Si tiene **vulnerabilidad** → se multiplica el total por 2.
7. Si tiene ambas (caso raro) → se cancelan, daño normal.
8. Ese número final es el que se resta de los puntos de golpe (HP) de la criatura.

**Ejemplo práctico:** Un mago lanza *Bola de fuego* y el ataque hace 24 puntos de daño de fuego. El objetivo es un diablillo con resistencia al fuego. 24 ÷ 2 = **12 puntos de daño final**. Si en vez de resistencia tuviera vulnerabilidad al fuego, serían 24 x 2 = **48 puntos de daño final**.

# 💀 3. Morir: 0 puntos de golpe y tiradas de salvación de muerte

Aquí es donde D&D se aleja de muchos videojuegos: llegar a 0 HP **no significa morir automáticamente**. Es más parecido a quedar "K.O." en un juego de lucha: estás derribado y en peligro real, pero todavía hay una oportunidad de levantarte.

## 3.1 ¿Qué pasa exactamente al llegar a 0 HP?

- El personaje cae **inconsciente** inmediatamente (suelta lo que tenga en las manos, cae al suelo, no puede actuar ni moverse).
- Entra en estado de **"Moribundo" (Dying)**: está vivo, pero al borde de la muerte.
- A partir de ese momento, **al principio de cada uno de sus turnos**, debe hacer una **tirada de salvación de muerte**.

> Si un personaje recibe daño mientras ya está a 0 HP (por ejemplo, un enemigo le vuelve a golpear estando en el suelo), eso cuenta como **un fallo automático** en su tirada de salvación de muerte (o dos fallos si es un golpe crítico). Es la versión de D&D de "rematar" a alguien caído.
> 

## 3.2 La tirada de salvación de muerte

Es una tirada especial: se lanza **1d20**, sin sumar ningún modificador (ni de Constitución, ni de nada). El resultado se compara así:

| Resultado del d20 | Qué ocurre |
| --- | --- |
| **10 o más** | Cuenta como **éxito** |
| **9 o menos** | Cuenta como **fallo** |
| **Un 20 natural (el dado marca 20)** | El personaje **recupera la consciencia** de inmediato con **1 punto de golpe**. Se levanta directamente, como si hubiera hecho una "resurrección exprés" |
| **Un 1 natural (el dado marca 1)** | Cuenta como **dos fallos** en vez de uno, como si el destino se hubiera reído de él |

El juego lleva la cuenta de estos resultados como si fuera una barra de "vidas": el personaje tiene un contador de **3 éxitos** y otro de **3 fallos**.

- **3 éxitos acumulados** → el personaje queda **Estable** (ver más abajo). Los contadores se resetean.
- **3 fallos acumulados** → el personaje **muere**.

> Piensa en esto como una barra de vida oculta de "tres corazones": cada turno el destino tira una moneda ponderada. Si llenas la barra de corazones verdes antes que la de calaveras, sobrevives.
> 

## 3.3 Quedar Estable

Un personaje moribundo se **estabiliza** (deja de tener que tirar salvaciones de muerte, pero sigue inconsciente a 0 HP) de dos formas:

1. **Consiguiendo 3 éxitos** en las tiradas de salvación de muerte.
2. **Recibiendo ayuda de otro personaje**: cualquiera puede usar su acción para hacer una prueba de Sabiduría (Medicina) CD 10 junto al moribundo. Si tiene éxito, el personaje queda estable sin necesidad de más tiradas.

Un personaje estable **no** despierta automáticamente: sigue a 0 HP e inconsciente hasta que recupere al menos 1 punto de golpe (por curación mágica, una poción, etc.), o hasta que pase 1d4 horas, tras las cuales recupera 1 HP por sí solo si nadie lo ha curado antes.

## 3.4 Muerte instantánea por daño masivo

Hay una regla especial para cuando el golpe es *brutal*: si el daño recibido de una sola vez es tan grande que sobrepasa los HP máximos del personaje (no los HP actuales, los **máximos**), el personaje **muere instantáneamente**, sin tiradas de salvación de muerte ni nada. Es la regla que impide que un dragón adulto le pegue un mordisco a un personaje de nivel 1 y el jugador aún tenga "una oportunidad" de salvarse con un 20 natural: a veces el golpe es simplemente letal.

**Ejemplo:** un personaje tiene 12 HP máximos. Recibe un golpe de 20 puntos de daño de una vez. Como 20 supera los 12 HP máximos, muere en el acto, sin pasar por el estado moribundo.

---

## 🧭 Resumen visual del flujo de "morir"

```
HP llega a 0
     │
     ├─► ¿El daño de una sola vez superó los HP máximos? ──► SÍ ──► Muerte instantánea
     │                                                                (fin)
     └─► NO
          │
          ▼
   Estado: Moribundo (inconsciente)
          │
          ▼
   Cada turno: tirada de salvación de muerte (1d20, sin modificadores)
          │
   ┌──────┼───────────────┬────────────────┐
   │      │               │                │
  20 nat  10+            9 o menos        1 nat
   │      │               │                │
   ▼      ▼               ▼                ▼
 Despierta  Éxito       Fallo          2 Fallos
 con 1 HP     │            │                │
              └─────┬──────┴────────┬───────┘
                     │               │
              3 Éxitos → Estable   3 Fallos → Muerte
```