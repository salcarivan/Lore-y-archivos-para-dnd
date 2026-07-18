# Análisis de la clase: Bárbaro

## 🎯 Dificultad general

**Media** (más alta que el bárbaro estándar de otros sistemas).

El *loop* básico —entrar en Furia y pegar fuerte— es simple, pero esta versión homebrew añade una capa de complejidad real: el sistema de **Técnicas salvajes** funciona como maniobras de Maestro de Batalla con detonantes ("Cuándo") constantes que hay que vigilar en cada turno (¿me han golpeado? ¿he empujado a alguien? ¿he fallado una salvación mental?). Eso convierte al bárbaro en una clase que exige **atención reactiva constante**, no solo "declaro ataque y tiro dados".

---

## ⚙️ Guía rápida de mecánicas

- **Furia**: recurso limitado por descanso, activable como Acción adicional. Da resistencia física, un bonificador de daño creciente, ventaja en FUE y bloquea la magia. Se mantiene atacando, forzando salvaciones o gastando Acción adicional.
- **Ataque temerario**: ventaja ofensiva a cambio de dar ventaja a quien te ataque; es el "interruptor de riesgo" que habilita varias Técnicas Maestras.
- **Técnicas salvajes**: el corazón táctico de la clase.
  - *Básicas*: gratis, siempre disponibles (ej. Golpe Brutal, Piel de Hierro).
  - *Avanzadas*: se compran con Puntos de Técnica, más específicas y potentes.
  - *Maestras* (nivel 11+): condicionadas a estados concretos (Furia + Temerario + quietud), muy potentes y limitadas a una vez por Furia.
  - Todas usan una **CD de técnica fija** (8 + competencia + FUE o DES), elegida en la creación del personaje.
- **Progresión pasiva**: ataques extra, crítico ampliado, inmunidad a la muerte por Furia (Imparable), resistencia a control mental, hasta terminar en un semidiós físico (Campeón primigenio).

En resumen: el bárbaro decide **qué técnicas comprar** según su estilo (control, daño, supervivencia) y luego juega reaccionando a los detonantes en mesa. Es una clase de "domador de gatillos", no de botón único.

---

## 🛤️ Guía de subclases (Sendas)

### 🗿 Senda del Titán
- **Dificultad**: Media-baja. Pocas decisiones por turno, efectos directos.
- **Rol**: Tanque/control de área — controla el campo por tamaño y empujones.
- **Poder base**: Alto y constante; el crecimiento de tamaño y los puños 1d8→1d12 dan daño y presencia fiables desde el nivel 3.
- **Fantasía**: "Me convierto literalmente en un coloso que aplasta." Pura escalada física, sin sutileza.

### 🌩️ Senda de la Tormenta Viva
- **Dificultad**: Media. Hay que elegir tipo de tormenta y gestionar un aura activa con efectos secundarios acumulativos.
- **Rol**: Controlador de área / DoT — castiga a quien se acerca, sin necesidad de atacar.
- **Poder base**: Alto en combates con múltiples enemigos agrupados; flojo contra un único objetivo.
- **Fantasía**: "Soy el ojo de un desastre elemental andante."

### 👻 Senda del Espíritu Invocado
- **Dificultad**: Media-alta. Eliges espíritu al entrar en Furia, cada uno con efectos, marcas y sinergias distintas.
- **Rol**: Híbrido flexible — según el espíritu, tanque-guardián, skirmisher, controlador de miedo o explorador/vigía.
- **Poder base**: Medio-alto, pero muy dependiente de elegir bien el espíritu para la situación.
- **Fantasía**: "No lucho solo: algo ancestral pilota mi cuerpo, y no siempre soy yo quien decide cómo."

### 🐗 Senda de las Púas
- **Dificultad**: Baja. Casi todo pasivo y automático, mínima toma de decisiones.
- **Rol**: Tanque de castigo — quien te pega, sufre.
- **Poder base**: Medio; escala bien en combates largos de desgaste, menos vistoso en combates cortos.
- **Fantasía**: "Acercarte a mí es la peor decisión que vas a tomar hoy."

### ⚔️ Senda del Coloso
- **Dificultad**: Alta. Mecánica de dos fases (cargar/golpear) con ventana de vulnerabilidad real; requiere planificación de turno.
- **Rol**: Nova striker — un solo golpe devastador, alto riesgo/alta recompensa.
- **Poder base**: Muy alto en el golpe, pero frágil durante la carga (CA -3, sin moverte).
- **Fantasía**: "Preparo el golpe que termina el combate, y el mundo contiene la respiración conmigo."

### 🩸 Senda del Desgarro
- **Dificultad**: Alta. Gestión activa de un dado que degrada, riesgo creciente de atacar a tus aliados, curva de decisiones sobre cuánto tiempo aguantar en Furia.
- **Rol**: Glass cannon de daño creciente con riesgo para el propio grupo.
- **Poder base**: El más alto en daño puro a partir del 3er-4º turno, pero con coste real de mesa (puedes atacar a tu equipo).
- **Fantasía**: "Cuanto más dura mi furia, más peligroso me vuelvo para todos, incluidos los míos."

---

## 🧑‍🎨 Dos ideas de personaje

### El epítome de la clase
**Grondir Piedra-Puño**, enano de las Fracturas del Norte, Senda del Titán. FUE por encima de todo, sin sutileza ni plan B: entra en combate, crece, agarra, empuja y rompe. No tiene traumas ocultos ni dilemas morales con su furia — simplemente es lo que es, y lo acepta con orgullo. Perfecto si quieres jugar la fantasía de fuerza bruta sin vueltas de tuerca.

### Una vuelta a la clase
**Yssara**, ex-diplomática de una corte caída, Senda del Espíritu Invocado (espíritu Clarividente). Fuera de la Furia es calculadora, formal y evita el conflicto directo; dentro de la Furia, un ancestro sereno y observador toma el timón y la convierte en una combatiente casi quirúrgica, que ve huecos en la formación enemiga antes que nadie. Subvierte el estereotipo de "bruto irracional": su furia no es caos, es la única vez que su mente funciona a máxima claridad. El conflicto interesante: ¿le preocupa perder su identidad diplomática, o secretamente prefiere el ancestro a sí misma?

---

## 🧾 Prompt reutilizable para crear cualquier Senda de bárbaro

```
Crea una nueva Senda de bárbaro para este sistema homebrew de D&D con las
siguientes reglas de formato y contenido:

1. ESTRUCTURA OBLIGATORIA:
   - Nombre: "Senda de/del [Concepto]"
   - Descripción: una frase-tagline de la fantasía central.
   - Párrafo de lore (150-250 palabras): origen cultural o metafísico dentro
     del mundo de Ankora, mencionando un pueblo/clan/región concreto y un
     evento o tradición específica. Debe terminar con una pregunta retórica
     dirigida al jugador sobre el precio o la naturaleza de su poder.

2. RASGOS POR NIVEL (usa exactamente esta progresión):
   - Nivel 3 — Rasgo pasivo de Furia: efecto(s) automático(s) que se activan
     SIEMPRE que el personaje entra en Furia. Si tiene daño o números, deben
     escalar con el nivel usando una tabla o menciones a niveles posteriores.
   - Nivel 3 — Técnica de senda (avanzada o maestra): con un "Cuándo"
     detonante concreto y verificable en mesa (no ambiguo), un efecto
     mecánico claro con salvación (Fuerza, Destreza o Constitución, "CD de
     técnica") y una consecuencia de estado existente (derribado, aturdido,
     empujado, agarrado, ardiendo, ensangrentado, etc.).
   - Nivel 6 — Expansión del rasgo de nivel 3: nuevo efecto, opción o
     bifurcación (ideal: una elección tipo "tipo de X" o "espíritu/senda
     secundaria" si aporta variedad de juego).
   - Nivel 10 — Rasgo permanente fuera de combate + escalada de daño/área
     del rasgo de Furia. Debe dar algo útil incluso sin estar en Furia.
   - Nivel 14 — Capstone dramático: un efecto de "una vez por Furia" o "una
     vez por descanso largo" que cambie el combate, con coste narrativo o
     mecánico (agotamiento, aturdimiento propio, pérdida de control, etc.)
     coherente con el lore.

3. PARA CADA RASGO NUEVO (no para las pasivas de nivel 6/10 que solo
   escalan números): añade un "Ejemplo en juego" con nombre de PJ, números
   de dados reales, una CD concreta y un resultado narrado en 3-5 frases.

4. RESTRICCIONES DE BALANCE:
   - Usa exclusivamente los términos de estado ya definidos en el sistema
     (no inventes estados nuevos sin definirlos).
   - La CD de técnica siempre se refiere a la fórmula ya fijada
     (8 + competencia + FUE o DES).
   - No dupliques el rol, la dificultad o la fantasía de las Sendas ya
     existentes (Titán, Tormenta Viva, Espíritu Invocado, Púas, Coloso,
     Desgarro) — especifica antes de escribir cuál es tu ángulo distinto.

5. Al final, resume en una línea: dificultad, rol en la mesa y fantasía
   que cumple, para verificar que no se solapa con las Sendas existentes.
```

---

## 🆕 3 subclases con rol / dificultad / fantasía no cubiertos

### 1. Senda de la Manada
- **Dificultad**: Baja — casi todo son reacciones automáticas de protección, sin dados que gestionar ni elecciones complejas por turno.
- **Rol**: Tanque activo de protección (no de castigo como Púas): se interpone, redirige ataques y cura/escuda a aliados cercanos con daño temporal absorbido.
- **Fantasía**: "Soy el líder que se pone entre la manada y el peligro" — el bárbaro como guardián instintivo, no como castigador ni como bestia de daño.

### 2. Senda del Cazador Silente
- **Dificultad**: Alta — depende de posicionamiento, sigilo y ventanas de oportunidad; el jugador debe planear su ruta de movimiento y momento de ataque con precisión.
- **Rol**: Skirmisher/asesino de hit-and-run — entra, ataque letal contra objetivo aislado, sale antes de que puedan reaccionar.
- **Fantasía**: "No rujo antes de atacar: mi furia es silenciosa y quirúrgica, como la de un depredador que ya eligió a su presa." Rompe la imagen del bárbaro ruidoso.

### 3. Senda del Precio de Sangre
- **Dificultad**: Media — gestión de recursos propios (PG máximos, niveles de daño autoinfligido) como coste de poder, requiere calcular riesgos pero sin tablas degradantes complejas.
- **Rol**: Soporte de sacrificio / nova de emergencia — cede sus propios PG o vitalidad para curar, potenciar o salvar aliados en momentos críticos.
- **Fantasía**: "Mi furia no se alimenta de rabia hacia el enemigo, sino de lo que estoy dispuesto a perder por los míos." Un bárbaro mártir, en las antípodas del egoísmo brutal habitual de la clase.