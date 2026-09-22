# Análisis de la clase Bardo (Homebrew — Ankora)

## 🎯 Dificultad general de la clase: **Media-Alta**

El Bardo base ya exige llevar varios "platos" a la vez:
- Gestionar **dados de Inspiración Bárdica** (repartirlos, recuperarlos, saber cuándo el aliado debe usarlos).
- Mantener **Interpretaciones Bárdicas** activas (que no requieren concentración clásica pero sí atención a condiciones de interrupción y a las reglas de "Simultánea" entre varias activas).
- Llevar **maná** y una lista de conjuros limitada a solo 2-5 esferas conocidas.
- Tomar decisiones reactivas constantes (usar reacción para Requiem de la Guardia, gastar maná para recuperar dados, etc.)

No es una clase punitiva si se juega mal, pero **su techo de poder depende directamente de cuántas decisiones tácticas tome el jugador por turno**. Un bardo pasivo es mediocre; un bardo que arbitra bien sus recursos es de los personajes más influyentes de la mesa.

---

## 🛠️ Guía rápida de mecánicas

| Sistema | Qué hace | Frecuencia de uso |
| --- | --- | --- |
| **Inspiración Bárdica** | Moneda universal: repararla, gastarla, recuperarla (mod. CAR usos/descanso largo) | Cada turno |
| **Interpretaciones Bárdicas** | "Auras" activas iniciadas con acción adicional, se mantienen gratis salvo incapacidad | Se inicia 1 vez, se sostiene solo |
| **Lanzamiento de conjuros** | Esferas limitadas (no acceso total), maná como recurso | Media, depende del build |
| **Folklore** | Pericias/competencias narrativas, más social que de combate | Fuera de combate |
| **Fuente de Inspiración (10)** y **Actuación Flexible (7)** | Motores de reciclaje de recursos: convierten maná/descansos cortos en más usos | Optimización a niveles medios-altos |

El diseño empuja a **repartir dados de Inspiración como un director de orquesta reparte entradas**: el bardo raramente "hace" la acción decisiva, la habilita.

---

## 🎭 Guía de subclases

### Colegio del Gran Concierto
- **Dificultad:** Media (pocas decisiones, pero hay que llevar el radio y el modo activo)
- **Rol:** Buffer de área permanente / "director de orquesta"
- **Poder base:** Alto — un aura pasiva que sube a +3 a todo el grupo sin gastar recursos por turno es de las más fuertes del set
- **Fantasía:** Ser el corazón invisible del grupo, el que no brilla pero sin el que nadie gana

### Colegio de la Armonía Perfecta
- **Dificultad:** Alta (mucha gestión de usos limitados y timing de reacciones)
- **Rol:** Seguro anti-azar / soporte de "corrección de errores"
- **Poder base:** Muy alto, especialmente en mesas con tiradas críticas de historia (anular 1 naturales, forzar un 18 fijo)
- **Fantasía:** El erudito que ha vencido al caos mediante conocimiento absoluto

### Colegio de la Forja Viviente
- **Dificultad:** Alta (múltiples "minions" con sus propias estadísticas y acciones)
- **Rol:** Invocador/controlador de campo de batalla mediante objetos animados
- **Poder base:** Alto, sobre todo por multiplicación de la economía de acciones
- **Fantasía:** El artesano-director cuyos instrumentos son las cosas mismas

### Colegio de la Danza de Guerra
- **Dificultad:** Baja-Media (rutina marcial simple, pocas decisiones por turno)
- **Rol:** Golpeador cuerpo a cuerpo / skirmisher
- **Poder base:** Sólido, comparable a un monje temático
- **Fantasía:** El escaldo-guerrero para quien pelear y recitar son el mismo acto

### Colegio del Lienzo Vivo
- **Dificultad:** Media-Alta (requiere conocer bestiario para la Criatura del Lienzo a nivel 15)
- **Rol:** Ilusionista / explorador-espía / invocador tardío
- **Poder base:** Alto, con un pico enorme a nivel 15
- **Fantasía:** El pintor cuya obra respira y engaña por él

### Colegio de la Pirueta
- **Dificultad:** Baja-Media (recursos simples: usos diarios + dados de Inspiración)
- **Rol:** Skirmisher / debuffer por humillación
- **Poder base:** Medio-Alto, más defensivo-utilitario que ofensivo puro
- **Fantasía:** El bufón imposible de atrapar que derrota con vergüenza, no con acero

---

## 👤 Dos ideas de personaje

### El epítome de la clase
**Maestro Belisario, el Batutista de Kalindra** — Bardo del **Colegio del Gran Concierto**, Carisma como característica principal, instrumento (batuta/violín) siempre en mano. Nunca ataca directamente si puede evitarlo: cambia de modo del Concierto según lo que necesite el grupo turno a turno, reparte dados de Inspiración como quien reparte partituras, y su frase de guerra es *"yo no gano batallas, las dirijo"*. Representa la fantasía pura del bardo: el líder social y táctico que hace brillar a los demás.

### La vuelta de tuerca
**Ren, la Pintora Muda** — Bardo del **Colegio del Lienzo Vivo** que **nunca habla ni canta**. Su "instrumento" son sus Herramientas de Pintor, su familiar es su única voz (habla a través de lo que pinta o de gestos), y sus Interpretaciones Bárdicas se manifiestan como pinturas que cobran vida momentáneamente en el aire mientras trabaja en silencio. Subvierte la premisa del bardo-extrovertido: es introvertida, casi antisocial, y genera su magia desde la observación silenciosa en vez de la actuación pública. El gancho de mesa: nadie sabe si sus ilusiones son arte o profecía.

---

## 📝 Plantilla / prompt para diseñar cualquier subclase de Bardo

```
Diseña un "Colegio de Bardo" para una clase homebrew de D&D ambientada en Ankora, siguiendo esta estructura:

1. TÍTULO Y DESCRIPCIÓN BREVE
   - Nombre del colegio + una línea de descripción (estilo CSV: "X que Y, Z que W").

2. TEXTO DE SABOR (1 párrafo)
   - Origen cultural/histórico del colegio dentro de Ankora (ciudades: Ankora, Miravel,
     Kalindra, Dûrkarath, las estepas del norte, etc.)
   - Termina con una pregunta retórica dirigida al jugador sobre el dilema moral/filosófico
     de la subclase.

3. TRES PROMESAS DEL COLEGIO
   - Compromisos de roleplay concretos y accionables en mesa, no solo estéticos.

4. RASGOS MECÁNICOS POR NIVEL:
   - Nivel 3 (dos rasgos): una competencia/pericia temática + un rasgo de identidad
     central que defina el "gimmick" único de la subclase.
   - Nivel 6 (un rasgo): amplía o combina el gimmick del nivel 3 con las
     Interpretaciones Bárdicas o el sistema de conjuros.
   - Nivel 11 (un rasgo): escala el gimmick a un nivel claramente más potente
     (más usos, más alcance, nueva opción táctica).
   - Nivel 15 (rasgo(s) capstone): 1-2 mejoras definitivas que representen el
     dominio absoluto del concepto.

5. REGLAS DE INTEGRACIÓN
   - Todo rasgo que exija salvación usa la CD de conjuros del bardo.
   - Los rasgos deben interactuar con el dado de Inspiración Bárdica y/o el maná
     como recursos centrales (gasto, recuperación, sustitución).
   - Evita duplicar el rol, la dificultad o la fantasía de otro colegio ya existente
     [lista de colegios existentes].

6. CALIBRACIÓN
   - Indica explícitamente: dificultad de juego (baja/media/alta), rol de mesa
     (buffer, striker, controller, support, face, etc.) y nivel de poder base
     relativo a otras subclases del set.
```

---

## 🆕 Tres propuestas de subclases con rol/dificultad/fantasía no cubiertos

### 1. Colegio del Réquiem Eterno
- **Rol:** Sanador dedicado / guardián anti-muerte (no cubierto: ninguna subclase actual es un healer puro)
- **Dificultad:** Baja (disparadores reactivos simples, poca gestión de sub-sistemas)
- **Fantasía:** El psicopompo que canta funerales antes de tiempo, negociando con la muerte para que un aliado se quede un poco más

### 2. Colegio del Nombre Verdadero
- **Rol:** Controlador de conocimiento / debuffer analítico (distinto de la humillación de Pirueta o el "anti-azar" de Armonía Perfecta: aquí el poder viene de **identificar y anular** rasgos concretos del enemigo)
- **Dificultad:** Alta (requiere que el jugador conozca o descubra en vivo resistencias, inmunidades y rasgos de las criaturas para explotarlos)
- **Fantasía:** El erudito que colecciona nombres verdaderos y desata el poder de nombrar aquello que otros temen describir

### 3. Colegio de la Voz Franca
- **Rol:** "Face" social / control mediante diplomacia y carisma bruto (ninguna subclase actual está centrada en resolver conflictos sin combate)
- **Dificultad:** Media (mecánicamente sencillo, pero exige compromiso fuerte con el roleplay social para brillar)
- **Fantasía:** El embajador cuyas palabras terminan guerras antes de que empiecen, convirtiendo enemigos en aliados temporales en vez de cadáveres