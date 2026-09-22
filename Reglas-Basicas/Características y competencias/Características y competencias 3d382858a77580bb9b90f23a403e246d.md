# Características y competencias

[Habilidades](Caracter%C3%ADsticas%20y%20competencias/Habilidades%203d482858a77580c7b2ddeab3a9b67d63.md)

[Suerte](Caracter%C3%ADsticas%20y%20competencias/Suerte%203d482858a775800688f6dcb6fb068951.md)

[Competencia y Pericia](Caracter%C3%ADsticas%20y%20competencias/Competencia%20y%20Pericia%203d482858a77580f5b303fc33ca47e817.md)

# 1. ¿Qué son las Pruebas d20?

Una **Prueba d20** es el nombre general que las reglas de 2024 dan a **cualquier momento en el que el juego necesita saber si algo que intentas hacer tiene éxito o fracasa, y ese resultado depende del azar**.

Piensa en ello como una "tirada de comprobación" universal. En términos de videojuego, imagina que cada vez que tu personaje intenta algo incierto (saltar un abismo, convencer a un guardia, esquivar una bola de fuego, golpear a un enemigo), el juego "lanza los dados internos" para decidir si el intento sale bien. En D&D, ese "dado interno" es literal: **un dado de 20 caras (d20)**.

Existen **tres tipos** de Pruebas d20, y los tres funcionan con la misma estructura matemática de fondo:

| Tipo de Prueba d20 | ¿Para qué sirve? |
| --- | --- |
| **Prueba de Característica** | Intentar hacer algo con tu habilidad natural (trepar, persuadir, recordar un dato) |
| **Tirada de Ataque**  | Intentar golpear a un objetivo en combate |
| **Tirada de Salvación** | Intentar resistir o evitar un efecto peligroso (veneno, hechizo, trampa) |

Todas comparten la misma "fórmula madre":

```
Resultado de la Prueba = 1d20 + modificadores relevantes
```

Ese resultado se compara luego contra un número objetivo para saber si tienes éxito.

# 2. Los pasos para hacer una Prueba d20

Cuando el Director de Juego (DJ) te pide una Prueba d20, siempre sigues la misma secuencia de pasos, sea cual sea el tipo de prueba:

> **Analogía:** piensa en esto como un "flujo de ejecución" fijo, como una función que siempre se llama igual pero recibe distintos parámetros según el contexto (característica, arma, tipo de salvación...).
> 

### Paso 1 — El DJ describe la situación y pide la prueba

El DJ te dice qué tipo de prueba necesitas hacer (por ejemplo: "haz una prueba de Destreza" o "tira tu salvación de Sabiduría").

### Paso 2 — Determinas los modificadores que aplican

Sumas los números fijos que corresponden a tu personaje para ese tipo de prueba concreta (esto varía según si es Característica, Ataque o Salvación — lo verás en detalle en las secciones siguientes).

### Paso 3 — Tiras 1d20

Lanzas un dado de 20 caras. El resultado va de 1 a 20, cada número con la misma probabilidad (5%) de salir.

> **1 y 20 son especiales en algunos casos** (por ejemplo, en Tiradas de Ataque, un 1 natural siempre falla y un 20 natural siempre acierta e inflige daño crítico). En Pruebas de Característica y Salvaciones normales, un 1 o un 20 natural **no** tienen ese efecto especial automáticamente — solo importa el total final, salvo que una regla concreta diga lo contrario.
> 

### Paso 4 — Sumas el resultado del dado + los modificadores

```
Total = número del d20 + modificadores del Paso 2
```

### Paso 5 — Comparas el total contra el número objetivo

- Si es una **Prueba de Característica** o **Salvación** → comparas contra una **CD (Clase de Dificultad)**, un número fijado por el DJ o por el efecto que causa la prueba.
- Si es una **Tirada de Ataque** → comparas contra la **CA (Clase de Armadura)** del objetivo.

Si tu total **iguala o supera** el número objetivo → **éxito**.
Si tu total **es menor** → **fracaso**.

# 3. Pruebas de Característica

Se usan cuando tu personaje intenta hacer algo que depende de su **capacidad física o mental innata**, y el resultado es incierto: forzar una puerta, recordar historia, mentir de forma convincente, mantener el equilibrio, etc.

### Fórmula

```
1d20 + modificador de Característica + bonificador de Competencia (solo si eres competente en la habilidad relevante)
```

| Elemento | Tipo | Explicación detallada |
| --- | --- | --- |
| `1d20` | Dado | El dado de 20 caras que tiras |
| Modificador de Característica | Número fijo | Depende de tu puntuación de Fuerza, Destreza, Constitución, Inteligencia, Sabiduría o Carisma. Se calcula así: `(puntuación - 10) / 2`, redondeando hacia abajo |
| Bono de Competencia | Número fijo | Solo se suma si tu personaje tiene entrenamiento (competencia) en la **habilidad** concreta que se está usando (ej. Sigilo, Persuasión, Investigación). Aumenta con el nivel de tu personaje |

> **Diferencia clave:** la "Característica" es el atributo base (Fuerza, Destreza...). La "Habilidad" (ej. Atletismo, Persuasión) está *asociada* a una Característica pero es donde declaras si tienes competencia o no. Puedes hacer una prueba de una Característica sin usar ninguna habilidad concreta (ej. "tira Fuerza a secas" para forzar una puerta), en cuyo caso no sumas el bonificador de competencia salvo que tengas alguna herramienta o rasgo especial que lo permita.
> 

### Ejemplo detallado

Tu personaje tiene Destreza 16 (modificador +3) y es competente en Sigilo (bonificador de competencia +2 a nivel bajo). Intentas escabullirte sin ser visto:

```
1d20 (sale un 11) + 3 (Destreza) + 2 (competencia en Sigilo) = 16
```

Si la CD para no ser detectado era 14, tu 16 supera esa CD → **éxito**, pasas desapercibido.

# 4. Tiradas de Ataque

Se usan cuando tu personaje intenta **golpear a un objetivo** en combate, ya sea con un arma cuerpo a cuerpo, a distancia, o con un ataque de conjuro.

### Fórmula

```
1d20 + modificador de Característica relevante + bonificador de Competencia (si eres competente con esa arma/conjuro)
```

| Elemento | Tipo | Explicación detallada |
| --- | --- | --- |
| `1d20` | Dado | El dado que tiras para el ataque |
| Modificador de Característica | Número fijo | **Fuerza** para armas cuerpo a cuerpo normales; **Destreza** para armas a distancia o armas "sutiles"; **modificador de característica de lanzamiento de conjuros** (Inteligencia, Sabiduría o Carisma, según tu clase) para ataques de conjuro |
| Bono de Competencia | Número fijo | Se suma si eres competente con el tipo de arma usada, o siempre en el caso de ataques de conjuro (los lanzadores de conjuros siempre son competentes con sus propios ataques de conjuro) |

El resultado se compara contra la **Clase de Armadura (CA)** del objetivo.

> **Fallo Crítico y Golpe Crítico:** en una Tirada de Ataque, si el **d20 muestra un 1 natural**, el ataque **falla automáticamente**, sin importar los modificadores. Si el **d20 muestra un 20 natural**, el ataque **acierta automáticamente** y además es un **golpe crítico** (se duplican los dados de daño). Esto es exclusivo de las Tiradas de Ataque.
> 

### Ejemplo detallado

Tu personaje tiene Fuerza 14 (modificador +2) y es competente con espadas largas (bonificador de competencia +2). Atacas con tu espada larga:

```
1d20 (sale un 15) + 2 (Fuerza) + 2 (competencia) = 19
```

Si la CA del enemigo es 16, tu 19 la supera → **impacto**, ahora tiras el daño del arma.

## 5. Tiradas de Salvación

Se usan cuando tu personaje intenta **resistir, esquivar o sobrevivir a un efecto dañino o peligroso**: el aliento de un dragón, un hechizo enemigo, veneno, una trampa que se activa, etc.

### Fórmula

```
1d20 + modificador de Característica relevante + bonificador de Competencia (solo si eres competente en esa salvación concreta)
```

| Elemento | Tipo | Explicación detallada |
| --- | --- | --- |
| `1d20` | Dado | El dado que tiras para intentar resistir el efecto |
| Modificador de Característica | Número fijo | Depende de qué Característica pide el efecto (ej. Destreza para esquivar una explosión, Constitución para resistir veneno, Sabiduría para resistir un hechizo mental) |
| Bono de Competencia | Número fijo | Solo se suma si tu **clase** te da competencia en esa salvación concreta (ej. los Guerreros suelen ser competentes en salvaciones de Fuerza y Constitución) |

El resultado se compara contra la **CD** que fija el efecto o quien lo causa (por ejemplo, la CD de conjuro de un hechicero enemigo).

### Ejemplo detallado

Un hechicero enemigo te lanza un hechizo que requiere salvación de Sabiduría, CD 15. Tu personaje tiene Sabiduría 12 (modificador +1) y no es competente en salvaciones de Sabiduría:

```
1d20 (sale un 16) + 1 (Sabiduría) + 0 (sin competencia) = 17
```

17 supera la CD 15 → **éxito**, resistes el efecto (normalmente sufres menos o ningún efecto, según describa el hechizo).

# 6. Ventaja y Desventaja

La Ventaja y la Desventaja son formas de reflejar que las circunstancias favorecen o perjudican tu intento, **sin tener que inventar modificadores numéricos nuevos** cada vez.

> **Analogía:** imagina que normalmente lanzas un solo dado para decidir tu suerte. Con Ventaja, el juego te dice "lanza dos veces y quédate con el mejor resultado" — como tener una segunda oportunidad automática. Con Desventaja, es lo contrario: "lanza dos veces y quédate con el peor" — como si algo te estuviera saboteando la tirada.
> 

**Mecánicamente:**

- **Con Ventaja:** tiras **2d20** y te quedas con el **más alto** de los dos resultados.
- **Con Desventaja:** tiras **2d20** y te quedas con el **más bajo** de los dos resultados.

En ambos casos, sigues sumando tus modificadores normales **solo al dado que te quedas** (no sumas los modificadores dos veces).

### ¿Cómo se aplican?

| Situación | Regla |
| --- | --- |
| Solo tienes Ventaja (una o varias fuentes) | Tiras 2d20, te quedas con el más alto |
| Solo tienes Desventaja (una o varias fuentes) | Tiras 2d20, te quedas con el más bajo |
| Tienes **Ventaja Y Desventaja** al mismo tiempo | Se **anulan entre sí**: tiras un solo d20 normal, como si no tuvieras ninguna de las dos |

> **Punto importante que mucha gente confunde:** la Ventaja y la Desventaja **no se acumulan**. Si tienes tres fuentes distintas de Ventaja a la vez, sigue siendo solo Ventaja (tiras 2d20, no 4). Es un estado de "sí/no", no un contador.
> 

### Ejemplo detallado

Intentas trepar un muro resbaladizo (normalmente Prueba de Fuerza, CD 12) mientras llueve (Desventaja por terreno resbaladizo) pero tu compañero te está ayudando a sujetar la cuerda (Ventaja por ayuda). Ambas se anulan → tiras **un solo d20 normal** + tu modificador de Fuerza + competencia si aplica.