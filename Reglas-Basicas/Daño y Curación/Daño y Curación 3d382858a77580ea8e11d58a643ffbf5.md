# Daño y Curación

[Estados Alterados](Da%C3%B1o%20y%20Curaci%C3%B3n/Estados%20Alterados%203d682858a7758038bf71c28ac0233565.md)

[Daño, Resistencias y Muerte](Da%C3%B1o%20y%20Curaci%C3%B3n/Da%C3%B1o,%20Resistencias%20y%20Muerte%203d982858a77580a8bc93c2646af8788d.md)

[Estrés y Trastornos Mentales](Da%C3%B1o%20y%20Curaci%C3%B3n/Estr%C3%A9s%20y%20Trastornos%20Mentales%203d982858a77580d5b91fef6d86be7474.md)

# Puntos de Golpe (PG)

Los Puntos de Golpe (PG) representan tu durabilidad y tus ganas de seguir en pie. Cuantos más PG tiene una criatura, más difícil es matarla.

- Tu **PG máximo** es cuánto tienes sin heridas.
- Tus **PG actuales** pueden ir desde el máximo hasta 0 — nunca bajan de ahí.
- Perder PG **no afecta a tus capacidades** hasta llegar a 0. No hay "penalización por vida baja" tipo barra de vida de un shooter arcade: estás perfectamente operativo con 1 PG... hasta que dejas de estarlo.

> **Herido** es un estado *pasivo* aparte de tu sistema de Ensangrentado: si tienes la mitad de tus PG o menos, estás "Bloodied". Por sí solo no hace nada, pero algunos rasgos de clase, hechizos o monstruos pueden reaccionar a esta condición. No lo confundas con el **Ensangrentado**, que es un sangrado activo con sus propias reglas — puedes estar Herida sin estar Ensangrentado, y viceversa (por ejemplo, tras un golpe masivo con muchos PG de sobra).
> 

# Daño básico y Golpes Críticos

Cada arma, hechizo o habilidad dañina especifica qué dados de daño usa.

1. Tiras los dados de daño indicados.
2. Sumas los modificadores que correspondan.
3. Aplicas el resultado a tu objetivo (si hay penalizadores, el daño mínimo es 0, nunca negativo).

| Origen del daño | ¿Sumas modificador de característica? |
| --- | --- |
| Ataque con arma | Sí — el mismo modificador que usaste para el ataque |
| Hechizo con dado de daño | Solo si el hechizo lo indica |
| Daño fijo sin tirada (ej. cerbatana) | No, salvo que una regla diga lo contrario |

## Golpe Crítico

Cuando aciertas un Golpe Crítico:

- Tiras **todos** los dados de daño del ataque **dos veces** y sumas el resultado (no se duplica el modificador, solo los dados).
- Ejemplo: una Daga (1d4) en crítico tira **2d4**, y le sigues sumando tu modificador de característica normal.
- Si el ataque añade dados extra (como el Ataque Furtivo del Pícaro), esos dados **también** se tiran por duplicado.

> Un Golpe Crítico no solo duele más — en tu sistema casero, es también uno de los disparadores que puede meterte de lleno en el sangrado grave (ver sección 4) o reabrir una herida ya tratada (ver sección 7). Guárdate esto en la manga como DM: el crítico es la "casilla de evento especial" del tablero.
> 

# Umbral de Herida

Antes de entrar en el sangrado, necesitas un número clave: el **Umbral de Herida**. Es el listón que decide si un golpe es "solo daño" o si empieza a abrirte una herida de verdad.

> El Umbral de Herida de un personaje es igual a su **puntuación de Constitución** (no el modificador). Un personaje con CON 14 tiene Umbral de Herida 14 — es justo el ejemplo que ya usabas en tus propias notas, así que no hace falta inventar una fórmula nueva: cuanto más aguantas por naturaleza, más golpe hace falta para que empieces a desangrarte.
> 

| Concepto | Valor |
| --- | --- |
| Umbral de Herida | = Puntuación de Constitución del personaje |
| Golpe masivo | Daño > **2 ×** Umbral de Herida en un solo golpe |

# Heridas: del sangrado a la cicatriz

Aquí es donde se fusionan tu Ensangrentado con el sistema de heridas persistentes. El Ensangrentado es la "barra de sangrado en tiempo real"; una **Herida** es lo que queda grabado en tu ficha cuando esa barra se pone seria.

## Cuándo ganas una Herida

Ganas una **Herida** (marca persistente en la hoja de personaje) cuando ocurra cualquiera de estos casos:

- Tu Ensangrentado alcanza el **Nivel 3 (Grave)** o superior.
- Te reducen a 0 PG mediante un ataque **violento/vicioso** (ver sección 9, Lesiones Permanentes) — en ese caso la Herida viene acompañada de una Lesión Permanente.

## Estados de una Herida

Piensa en la Herida como un pequeño sub-personaje con tres estados, tipo semáforo:

| Estado | Descripción | Efecto |
| --- | --- | --- |
| 🔴 **Abierta** | Sangra activamente | Sigue las reglas de Ensangrentado (sección 4); mientras esté en nivel 1+ también aplica 1 nivel de Agotamiento Leve (sección 10) por vida difícil |
| 🟡 **Tratada** | Alguien la ha vendado/cosido | Ya no aplica Agotamiento ni sigue empeorando sola, pero sigue "ahí" hasta curar del todo — y puede **reabrirse** (sección 7) |
| 🟢 **Cerrada** | Curada del todo | Sin efecto alguno, salvo que un golpe fuerte la reabra (sección 7) |

## Tratar una Herida

Pasar de 🔴 Abierta a 🟡 Tratada:

- Cuesta **1 hora** de trabajo con conocimientos y suministros de primeros auxilios.
- Tirada de **Inteligencia (Medicina)** o **Sabiduría (Medicina)**, **CD 10**.
- Esto detiene el sangrado activo (baja el Ensangrentado a 0 si no lo habías estabilizado antes) y quita el Agotamiento Leve asociado a esa herida, pero la herida en sí permanece en tu ficha hasta curar del todo.

## Curar una Herida (de Tratada a Cerrada)

- **Curación natural:** al terminar un descanso largo, tira **Constitución (Medicina)**, **CD 15**, por cada herida Tratada que tengas. Algunas actividades de tiempo libre (como simplemente descansar) pueden darte ventaja en esta tirada.
- **Curación mágica:** cualquier efecto mágico dedicado a curar la herida la cierra directamente — pero **no recuperas PG** por ese hechizo, toda su potencia se gasta en cerrar la herida.

# Estabilización y curación en pleno combate

Estas son tus herramientas de "urgencias" para frenar el Ensangrentado *durante* la escena, antes de llegar siquiera a tratar la Herida con calma:

| Acción | Coste | Tirada | Efecto |
| --- | --- | --- | --- |
| Estabilización básica | Acción completa, sin magia | CD 12 Medicina | Detiene el empeoramiento durante 1 minuto (no baja de nivel, solo evita la tirada de empeoramiento) |
| Estabilización con Kit | Acción completa | CD 15 Medicina + Kit de Sanador | Reduce el nivel de Ensangrentado en 1 |
| Curación mágica | Según el hechizo | — | Reduce el nivel de Ensangrentado en 1 por cada 5 PG que el hechizo cure |
| *Restablecer menor* | Según el hechizo | — | Estabiliza automáticamente: no baja de nivel, pero evita que empeore durante 1 hora |
| Cirugía (solo niveles 4–5) | 10 minutos, Kit de cirugía | CD 20 Medicina | Éxito: baja **2** niveles. Fallo: sube **1** nivel |

> La cirugía es tu jugada de "todo o nada": en niveles 4 o 5 de Ensangrentado ya no hay margen para intentos flojos. Un fallo empeora las cosas, así que resérvala para cuando tengas un buen bonificador o no te quede otra.
> 

# Reapertura de una Herida

Una vez tienes una Herida 🟡 Tratada o 🟢 Cerrada, hay dos formas distintas de que vuelva a abrirse — una para golpes críticos en pleno combate, otra para golpes normales sobre una herida recién cerrada.

## Reapertura por Golpe Crítico (herida Tratada)

Cuando recibes daño crítico y tienes al menos una Herida en estado 🟡 Tratada, tira **1d20 por cada herida tratada** que tengas:

| d20 | Efecto |
| --- | --- |
| 1 | La herida se reabre **y** pierdes un dado de golpe |
| 2–8 | La herida se reabre |
| 9–20 | La herida se mantiene cerrada |

Al reabrirse, la herida vuelve a estado 🔴 Abierta con **Ensangrentado Nivel 1** y vuelve a aplicar Agotamiento Leve hasta que la trates de nuevo.

> Una herida **sin tratar** (🔴 Abierta) falla esta tirada automáticamente, como si hubieras sacado un 1: pierdes un dado de golpe también. Moraleja para tus jugadores: vendarse las heridas no es opcional si piensan seguir peleando.
> 

## Reapertura por daño físico (herida Cerrada recientemente)

Si una herida 🟢 Cerrada (curada del todo desde hace al menos un descanso largo) recibe daño **contundente o perforante** antes de que hayan pasado más descansos:

1. Vuelve automáticamente a **Ensangrentado Nivel 1**.
2. Sufres una Herida crítica adicional.
3. Tirada de salvación de **Constitución, CD 15**:
    - Éxito: no pasa nada más.
    - Fallo: el nivel de Ensangrentado sube **1 nivel adicional** (es decir, directamente a Nivel 2).

# Lesión Supurante (infección)

Si terminas un **descanso largo (8 horas)** sin haber detenido el sangrado (Ensangrentado en Nivel 1 o superior), la herida se infecta. Es el "efecto de veneno acumulativo" del sistema: si ignoras el problema, empeora solo con el paso del tiempo, no hace falta que nadie te vuelva a golpear.

## Síntomas automáticos

- **Fiebre:** desventaja en todas las tiradas.
- **Daño continuo:** 1 punto de daño necrótico por hora.
- **Propagación:** cada día sin tratamiento, el nivel de Ensangrentado **sube 1 automáticamente**, sin tirar dado.

## Curar la supuración

- Tirada de **Medicina, CD 15** (requiere Kit de Sanador o kit de herborista).
- **Éxito:** detiene la infección; si el sangrado estaba por encima del Nivel 1, baja a Nivel 1.
- **Fracaso:** la herida empeora un grado de severidad (leve → moderada → severa → mortal).

# Lesiones Permanentes

Algunos monstruos —dragones, gigantes, ogros— no solo hacen daño, **rompen cosas**. Cuando el golpe es tan bestial que no basta con "perder PG", entra en juego la Lesión Permanente.

## Cuándo se activa

Si te reducen a **0 PG** mediante un ataque marcado como **vicioso** (*vicious*), sufres una Lesión Permanente.

> [Como DM, marca de antemano qué monstruos o ataques llevan la etiqueta *vicioso* y **avísalo claramente a la mesa** antes del combate — es una regla de tensión narrativa, no una trampa oculta. Tus jugadores deben poder decidir con esa información si cargan de frente o se lo piensan dos veces.
> 

## Efectos

1. Tira en tu tabla de lesiones (a definir según el mundo/campaña; vuelve a tirar cualquier resultado sin sentido para la situación).
2. Ganas además **1 nivel de Agotamiento** (sección 10), permanente hasta tratar la lesión.
3. DM y jugador comentáis brevemente qué efecto narrativo concreto tiene la lesión más allá del Agotamiento (perder un dedo, cojear, cicatriz que asusta a la gente del pueblo, etc.).

## Tratar una Lesión Permanente

| Método | Cuándo se puede usar |
| --- | --- |
| **Prótesis** | En cualquier momento, si sustituye la parte del cuerpo perdida |
| **Atención médica / cirugía** | Solo durante un descanso largo, en un lugar seguro (aldea, pueblo o ciudad) |
| **Magia** | *Restablecimiento Mayor* o un efecto de potencia equivalente |

Una vez tratada, el nivel de Agotamiento asociado desaparece y el personaje vuelve a actuar con normalidad.

> **Filosofía de mesa:** las lesiones deben doler, no arruinar la partida. Úsalas para generar momentos de drama puntuales, pero evita castigar a un personaje durante demasiadas sesiones seguidas. Una vez tratada —con prótesis, cirugía o magia— no sigas aplicando penalizadores salvo que encaje especialmente bien con la historia.
> 

# Resumen rápido del flujo completo

Para tenerlo todo junto en un vistazo (ideal para pegar como referencia rápida en la mesa):

1. **Recibes daño** → se aplican las reglas de la sección 2 (dados, modificador, crítico si procede).
2. Según cuánto daño y de qué tipo, puede que entres en **Ensangrentado** (sección 4): leve (d12), grave (d8) o masivo (d6), comparando contra tu **Umbral de Herida = tu Constitución**.
3. Si el Ensangrentado llega a **Nivel 3** o si te reducen a **0 PG con un golpe vicioso**, ganas una **Herida** (sección 5) — y si es lo segundo, además tiras en la tabla de **Lesión Permanente** (sección 9).
4. Mientras la Herida esté 🔴 Abierta, sufres Agotamiento Leve y sigues las tiradas de empeoramiento del Ensangrentado cada turno/minuto.
5. Alguien te trata (Medicina CD 10, 1 hora) → pasas a 🟡 Tratada: se acaba el Agotamiento por esa herida, pero sigue "en tu ficha".
6. Con el tiempo (descanso largo, CD 15 Constitución/Medicina) o con magia → pasas a 🟢 Cerrada.
7. Ojo con los **críticos** sobre heridas Tratadas (tabla d20, sección 7.1) y con los golpes contundentes/perforantes sobre heridas recién Cerradas (CD 15 Constitución, sección 7.2): ambos pueden reabrirte la herida.
8. Si dejas pasar un descanso largo entero con sangrado activo, cuidado con la **infección** (sección 8): fiebre, daño por hora y empeoramiento automático diario.
9. En paralelo, vigila tu **Agotamiento** general (sección 10): heridas sin tratar, sobreesfuerzo y privación te empujan por la escalera Leve → Severo.

> En resumen: el Ensangrentado es tu reloj de "estoy sangrando ahora mismo"; la Herida es la marca que queda cuando ese reloj llega demasiado lejos; la Lesión Permanente es lo que pasa cuando un golpe es tan bestia que rompe algo de verdad; y el Agotamiento es el hilo que conecta todo esto con tu rendimiento día a día. Cuatro sistemas, un solo cuerpo aguantando el golpe.
>