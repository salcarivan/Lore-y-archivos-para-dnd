# Análisis de la clase Guerrero

## 🎯 Dificultad general de la clase

**Media.**

El núcleo (atacar y dejar que las "Chispas" disparen técnicas) es intuitivo y accesible para un jugador novato, pero la clase premia fuertemente a quien:
- Lleva la cuenta de qué condiciones de "Chispa" se están cumpliendo turno a turno (posición, rondas en combate, vigor propio/ajeno, etc.)
- Gestiona dos economías de recursos en paralelo (**Puntos de Técnica** para preparar y **Dados de Técnica** para empoderar)
- Decide cuándo gastar dados de técnica vs. guardarlos

El techo de habilidad es alto (optimizar combos de chispas encadenadas), pero el suelo es bajo (siempre puedes "solo atacar"). El **Herrero de Batalla** eleva la dificultad general de la clase al introducir gestión de maná y conjuros.

---

## ⚙️ Guía breve de mecánicas

| Mecánica | Qué hace |
|---|---|
| **Técnicas Marciales** | Maniobras pasivas/reactivas que se activan solas cuando se cumple su "Chispa" (condición de disparo). No son "hechizos que lanzas", son reacciones entrenadas al fragor del combate. |
| **Básicas / Avanzadas / Maestras** | Las básicas están siempre disponibles; las avanzadas cuestan Puntos de Técnica (14 al máximo, el mayor de todas las clases); las maestras se desbloquean en nivel 11. |
| **Dados de Técnica** | Recurso limitado (empieza en 2d6, escala a 6d12) para "empoderar" cualquier técnica y hacerla más fuerte. Es la moneda de decisiones tácticas: ¿lo gasto ahora o espero el momento perfecto? |
| **Arma Favorita** | Cada descanso corto, un arma designada gana un dado de técnica al ataque y un ataque extra como acción adicional. |
| **Ataque Adicional / Indomable / Superioridad Marcial** | Escalado clásico de daño y resiliencia a las tiradas de salvación, con regeneración parcial de dados de técnica al iniciar cada combate desde nivel 11. |
| **Arquetipo (nivel 3)** | Define la fantasía real del personaje: el resto de la clase es "chasis", el arquetipo es "alma". |

---

## 🛡️ Guía de subclases (Arquetipos)

### Cuerpo de Hierro
- **Dificultad:** Baja–Media (pocas decisiones activas, casi todo pasivo y reactivo)
- **Rol en mesa:** DPS melee de riesgo/recompensa — brilla cuanto más sangra
- **Poder base:** Alto (picos de daño enormes a bajo vigor, resiliencia genuina)
- **Fantasía:** El bruto imparable al que el dolor no detiene, sino que alimenta

### Francotirador de Cápsula
- **Dificultad:** Media–Alta (requiere gestionar posicionamiento e inmovilidad turno a turno)
- **Rol en mesa:** DPS a distancia de objetivo único / control de reacciones enemigas
- **Poder base:** Alto (daño de precisión brutal, pero frágil si lo fuerzan a moverse)
- **Fantasía:** El calculador frío que no falla el disparo que decide la batalla

### Callejero
- **Dificultad:** Baja–Media
- **Rol en mesa:** Skirmisher melee/desarmado, muy móvil, resistente al castigo
- **Poder base:** Medio–Alto (daño constante + resistencia física; escala con condiciones enemigas)
- **Fantasía:** El peleador de callejón sin honor ni reglas, que simplemente no pierde

### Guardián
- **Dificultad:** Media (juego reactivo constante: cuándo interponerse, priorizar aliados)
- **Rol en mesa:** Tanque puro / protector de grupo
- **Poder base:** Medio (poco daño propio, pero indispensable para la supervivencia del grupo)
- **Fantasía:** El muro viviente que recibe el golpe que iba a matar a otro

### Corazón de Tormenta
- **Dificultad:** Media–Alta (gestión de Carga, decisiones de cuándo detonarla)
- **Rol en mesa:** Skirmisher móvil / daño en área elemental
- **Poder base:** Alto (movilidad + daño en área + control con aturdimiento)
- **Fantasía:** El guerrero que es literalmente la tormenta encarnada

### Herrero de Batalla
- **Dificultad:** Alta (medio-lanzador: maná, círculos, lista de conjuros Cinética/Origen)
- **Rol en mesa:** Controlador de campo de batalla / híbrido daño-utilidad (gish)
- **Poder base:** Alto (mucha versatilidad táctica, empuje/atracción/anclaje a voluntad)
- **Fantasía:** El ingeniero arcano que reescribe el espacio de combate con su cuerpo como foco mágico

---

## 🧙 Dos ideas de personaje

### 1. El epítome de la clase — "El Duelista Metódico"
Un guerrero **sin arquetipo mágico ni gimmick elemental**: solo técnicas marciales básicas y avanzadas puras, estilo de pelea equilibrado, arma favorita constante. Juega el "ajedrez de chispas" al máximo nivel: cuenta rondas, posición y condiciones enemigas para encadenar Lectura de Apertura → Golpe Sostenido → Rompimiento de Guardia en una sola pelea. Representa la fantasía original de la clase sin distracciones: el maestro de armas que gana por lectura de combate, no por magia ni por gimmicks.

### 2. Una vuelta de tuerca — "El Ingeniero que Nunca Desenvaina"
Un **Herrero de Batalla** que rara vez ataca directamente: usa Distorsión Local, empujones y su Arsenal Comprimido para mover enemigos y aliados como piezas en un tablero, dejando que otros den los golpes finales. Es, mecánicamente, un guerrero — tiene ataque adicional, dados de técnica, técnicas marciales — pero narrativamente juega como un **controlador táctico casi no-combatiente**, subvirtiendo la idea de "el guerrero pega fuerte" por "el guerrero decide dónde pelea todo el mundo".

---

## 📝 Prompt genérico para crear cualquier arquetipo de Guerrero

```
Crea un Arquetipo de Guerrero para un sistema homebrew de D&D con las
siguientes reglas de diseño:

1. ESTRUCTURA OBLIGATORIA
   - Descripción corta (una frase evocadora, tipo tagline)
   - Un párrafo de lore ambientado en el mundo de Ankora (cápsulas de
     realidad, Hilos Ley, Custodios, Ecos) que explique el origen del
     arquetipo, terminando con una pregunta retórica dirigida al jugador.
   - Rasgos en niveles 3, 7, 10, 15 y 18 (siguiendo la tabla del guerrero).

2. NIVEL 3 — Técnica de Arquetipo
   - Debe tener: Chispa (condición de disparo clara y verificable en mesa,
     no ambigua), Efecto (base, sin gastar dados), Empoderado (mejora al
     gastar un dado de técnica), y opcionalmente un "Ejemplo en juego".
   - La Chispa debe reforzar la fantasía única del arquetipo y no solaparse
     con las chispas de las técnicas marciales genéricas ya existentes.

3. NIVEL 3 — Rasgo pasivo de identidad
   - Un segundo rasgo de nivel 3 (no técnica) que dé una herramienta
     permanente y temática (resistencia, sentido especial, competencia,
     mecánica de recurso propio del arquetipo).

4. NIVEL 7 — Expansión táctica
   - Amplía lo que el personaje puede hacer en su turno (movilidad,
     ataques extra condicionales, opciones de reacción).

5. NIVEL 10 — Escalada de poder
   - Un salto de poder notable que combine varios rasgos anteriores o
     introduzca una nueva mecánica de recurso.

6. NIVEL 15 — Rasgo de alto impacto
   - Algo que cambie cómo juega el personaje en combates largos o
     situaciones extremas (casi siempre un "permanente" fuerte).

7. NIVEL 18 — Capstone
   - 2–4 beneficios permanentes de nivel épico que definan al personaje
     como la máxima expresión de la fantasía del arquetipo, incluyendo
     idealmente una habilidad de "una vez por descanso largo" de gran
     impacto narrativo y mecánico.

8. RESTRICCIONES DE DISEÑO
   - No debe pisar el espacio de rol/dificultad/fantasía de arquetipos
     existentes: [Cuerpo de Hierro, Francotirador de Cápsula, Callejero,
     Guardián, Corazón de Tormenta, Herrero de Batalla].
   - Define explícitamente: dificultad de juego, rol en la mesa
     (tanque/dps melee/dps distancia/control/soporte), poder base
     relativo, y qué fantasía de jugador satisface.
   - Usa CDs con la fórmula estándar: 8 + bonificación de competencia +
     modificador de característica relevante.
   - El tono de la prosa debe ser directo, algo poético en las citas
     entre comillas, sin exceso de adjetivos.
```

---

## 🆕 Tres subclases nuevas (rol/dificultad/fantasía no cubiertos)

### 1. Comandante de Escuadra
- **Dificultad:** Media (gestión de acción economy ajena, no propia)
- **Rol:** Soporte/buffer puro — su daño personal es secundario, multiplica el de sus aliados
- **Fantasía:** El oficial que nunca lucha solo; gana batallas dando la orden correcta en el instante correcto (extensión real de "Cadena de Mando" a arquetipo completo, con ordenes de reacción, marcado de objetivos y bonificadores de iniciativa grupal)

### 2. Duelista de Honor
- **Dificultad:** Alta (mecánicas de amago/parada/lectura de intención, ventanas de reacción muy ajustadas)
- **Rol:** Asesino/control de objetivo único en combate 1 contra 1 — anula reacciones y huida del enemigo marcado
- **Fantasía:** El espadachín que reta a un único rival y hace que el resto del campo de batalla deje de importar

### 3. Cazador-Ingeniero (trampas y artefactos mundanos)
- **Dificultad:** Alta (requiere trackear objetos desplegados, cargas de trampas, posicionamiento previo)
- **Rol:** Control de área / denegación de terreno **sin magia** (contraparte no-arcana del Herrero de Batalla)
- **Fantasía:** El veterano que prepara el campo de batalla antes de que empiece la pelea, convirtiendo el terreno mismo en su arma