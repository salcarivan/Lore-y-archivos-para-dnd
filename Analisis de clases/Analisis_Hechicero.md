# Análisis de clase: Hechicero

## Dificultad general: **Alta**

El Hechicero combina en una sola clase varios subsistemas que deben gestionarse simultáneamente: maná, esferas de magia restringidas, conjuros conocidos, un estado activable con condición de mantenimiento (Encarnación Arcana), y un pool independiente de Signos de poder con usos propios ligados a Carisma. A esto se suma que su subclase (Origen) no solo añade rasgos, sino que *modifica* la Encarnación Arcana, obligando al jugador a entender cómo interactúan ambos sistemas. Es una clase pensada para jugadores que ya dominan el lanzamiento de conjuros y quieren una capa adicional de optimización y toma de decisiones en cada turno.

---

## Guía breve de mecánicas

- **Lanzador basado en Carisma**, con modelo de **conjuros conocidos** (no preparados) y acceso restringido a **esferas de magia** (empieza con 2, va ganando más).
- **Maná** como recurso de lanzamiento, con círculo máximo creciente hasta 9º.
- **Encarnación Arcana**: estado activable (Acción Adicional, usos limitados por descanso largo) que otorga ventaja en ataques de conjuro y +CD de salvación. Tiene una condición de mantenimiento pasado el primer minuto (concentración, lanzar conjuro de nivel 1+, o gastar Acción Adicional para extenderla), lo que introduce tensión táctica.
- **Signos de poder (Metamagia)**: un catálogo amplio de rasgos pasivos y activos (Acción, Acción Adicional o Reacción) desbloqueados por nivel, con usos igual al modificador de Carisma por descanso largo. Son intercambiables al subir de nivel, lo que da flexibilidad de build sin rehacer el personaje.
- **Origen de hechicero** (nivel 3): define de dónde viene el poder, añade lista de conjuros de origen (no cuentan como conocidos) y una mejora temática a la Encarnación Arcana en los niveles 3, 6, 14 y 18.
- Rasgos de apoyo como **Esencia desbordante** (trucos potenciados), **Guardia mística** (relanzar salvaciones contra magia estando Encarnado) y **Perturbación Arcana** (disipación al activar Encarnación) refuerzan la fantasía de un poder que se desborda del propio cuerpo.
- Capstone (**Realización Arcana**): estando Encarnado, todos los conjuros suben un círculo de potencia efectivo.

---

## Guía de subclases (Orígenes)

### Linaje del Vestigio Viviente
- **Dificultad:** Media-Alta (gestionar el arma viviente, sus propiedades y a quién se la entregas)
- **Rol:** Gish de soporte / potenciador de aliados marciales
- **Poder base:** Alto — convertirte (o convertir a un aliado) en un arma mágica competente es fuerte desde el nivel 3
- **Fantasía:** Ser, literalmente, un arma consciente; el vínculo entre objeto y persona

### Linaje del Caos Primigenio
- **Dificultad:** Alta (tirada de magia salvaje en tabla d100, gestión de riesgo/recompensa)
- **Rol:** Blaster/soporte errático, alto variance
- **Poder base:** Medio-Alto pero muy swingy; mejora en consistencia según sube de nivel
- **Fantasía:** Canalizar el caos anterior al Tapiz, ser una grieta ambulante hacia lo indomable

### Linaje del Genio Elemental
- **Dificultad:** Media (elección de elemento clara, efectos consistentes)
- **Rol:** Blaster elemental con opción de tanque ligero según elemento
- **Poder base:** Alto y muy consistente, sin picos de aleatoriedad
- **Fantasía:** El sorcerer "clásico" de sangre elemental

### Linaje Negador
- **Dificultad:** Media-Alta (rasgos reactivos y condicionales, muy situacional)
- **Rol:** Control anti-lanzadores / supresor de magia
- **Poder base:** Muy alto contra otros lanzadores, mediocre contra marciales puros
- **Fantasía:** Un vacío viviente que aterra a otros hechiceros

### Linaje Cósmico
- **Dificultad:** Alta (múltiples interacciones únicas: teletransporte por conjuro, redirección de efectos, capstone de área)
- **Rol:** Control mental / utilidad de alto nivel
- **Poder base:** Alto en utilidad y control, más débil en daño directo
- **Fantasía:** Fragmento de una conciencia cósmica atrapada en un cuerpo mortal

### Linaje Feérico
- **Dificultad:** Media-Alta (mezcla de sigilo, encantamiento y utilidad social)
- **Rol:** Trickster / soporte social y utilidad
- **Poder base:** Medio-Alto en control social, moderado en combate directo
- **Fantasía:** Un alma progresivamente poseída por un espíritu feérico ancestral

---

## Dos ideas de personaje

**El epítome — "Sangre en llamas" (Genio Elemental, Fuego)**
Un hechicero que abraza sin reservas la fantasía central de la clase: poder mágico incontrolable que se desborda del cuerpo. Prioriza Carisma y Constitución, activa su Encarnación en cuanto empieza el combate, y usa signos vistosos (Lanza deslumbrante, Estatura terrible) como acentos de una identidad de bomba de daño teatral e impredecible. Es la versión "de manual" del hechicero: llamativo, ofensivo, centrado en su propia presencia mágica.

**La vuelta de tuerca — "El silencio antes del vacío" (Negador)**
Un hechicero que casi nunca ataca directamente. En vez de deslumbrar, se dedica a apagar la magia ajena: protege a sus aliados anulando conjuros enemigos, marca a los lanzadores rivales y rara vez activa su Encarnación de forma ofensiva. Reflavoriza sus Signos de poder como fenómenos de "ausencia" en vez de manifestaciones flamígeras (una luz que se apaga en vez de brillar, un sonido que desaparece en vez de aparecer). Subvierte la fantasía habitual del hechicero-espectáculo con una identidad callada, casi anti-mágica, que funciona mejor como guardián que como artillero.

---

## Prompt / instrucciones para crear cualquier Origen de hechicero

```
Crea un nuevo Origen de hechicero para Ankora siguiendo esta estructura exacta:

1. NOMBRE: "Linaje [adjetivo o sustantivo temático]"

2. DESCRIPCIÓN MECÁNICA: una frase de 5-10 palabras que resuma
   el rol y la fantasía del origen (ej. "Manipulas magia caótica
   pre-arcana con riesgo de efectos salvajes impredecibles").

3. LORE: un párrafo narrativo en segunda persona que conecte el
   origen con la cosmología de Ankora (el Tapiz, los Hilos Ley,
   los Custodios, los Ecos, los Jirones, el Consorcio Luminar u
   otras facciones/conceptos relevantes). El párrafo debe terminar
   con una pregunta en cursiva dirigida al jugador, que invite a
   definir la relación de su personaje con su propio poder.

4. CONJUROS DE ORIGEN: una tabla con conjuros adicionales en los
   niveles 3, 5, 7 y 9 (2-4 conjuros por nivel). Estos conjuros
   NO cuentan para el límite de conjuros conocidos. Prioriza
   reutilizar conjuros ya existentes de Ankora que encajen con la
   temática; solo crea conjuros nuevos si es imprescindible, y en
   ese caso indica su círculo equivalente explícito (Truco a 9º).

5. RASGOS POR NIVEL:
   - Nivel 3: uno o dos rasgos. Al menos uno debe ser una mejora
     temática de la Encarnación Arcana (un efecto que solo se
     activa o mejora mientras el personaje está Encarnado); el
     segundo (si existe) puede ser un rasgo permanente o pasivo
     que no dependa de la Encarnación.
   - Nivel 6: un rasgo pasivo o reactivo de complejidad media,
     normalmente con usos igual al modificador de Carisma (mínimo
     1) por descanso largo o corto.
   - Nivel 14: un rasgo más potente, a menudo de Reacción o que
     interactúa con el maná/economía de conjuros del personaje.
   - Nivel 18: un rasgo culminante que transforma o reemplaza los
     efectos normales de la Encarnación Arcana por una versión
     mucho más poderosa y temática, activable en su lugar.

6. CONSISTENCIA: todas las CD de salvación deben usar la fórmula
   estándar (8 + bono de competencia + modificador de Carisma).
   Todos los usos limitados deben expresarse como "modificador de
   Carisma (mínimo 1)" salvo que haya una razón mecánica explícita
   para usar otra característica o un número fijo.

7. Indica al final: dificultad estimada (Baja/Media/Media-Alta/Alta),
   rol en la mesa, nivel de poder base, y qué fantasía de jugador
   cumple este origen, en una frase cada uno.
```

---

## 4 subclases nuevas (rol, dificultad y fantasía no cubiertos aún)

### Linaje de la Marea Viva
- **Rol:** Sanador/soporte de vitalidad (no cubierto: los orígenes actuales no tienen un healer dedicado)
- **Dificultad:** Media (rasgos mayormente reactivos y directos, sin tablas ni gestión de compañeros)
- **Poder base:** Medio-Alto en sostenibilidad de grupo, bajo en daño
- **Fantasía:** Tu sangre lleva un eco de renovación y ciclos vitales; rediriges vitalidad entre los tuyos como si la vida fuera un río que puedes desviar

### Linaje del Vínculo Espectral
- **Rol:** Invocador/comandante — actúas a través de un aliado espectral ligado a ti (no cubierto: ningún origen actual gestiona una criatura vinculada)
- **Dificultad:** Alta (gestión de una entidad con acciones propias, sincronizada con tu propia economía de turno)
- **Poder base:** Alto pero condicionado a mantener con vida/activo al vínculo
- **Fantasía:** Un antepasado, guardián o entidad incompleta camina contigo, actuando como extensión de tu voluntad

### Linaje del Pliegue
- **Rol:** Controlador de campo de batalla / manipulador de espacio y terreno (distinto del control mental del Cósmico y del engaño social del Feérico)
- **Dificultad:** Media-Alta (requiere pensar en posicionamiento propio y ajeno cada turno)
- **Poder base:** Medio-Alto en control posicional, bajo en daño directo
- **Fantasía:** Tu sangre dobla sutilmente la geometría a tu alrededor; el espacio no es del todo fiable cerca de ti

### Linaje del Estallido Latente
- **Rol:** Nuke de daño puro, simple y directo (no cubierto: ningún origen actual es de baja complejidad)
- **Dificultad:** Baja (pocos rasgos, decisiones simples, casi todo se resume en "cuándo detonar")
- **Poder base:** Muy alto en picos de daño, muy frágil el resto del tiempo
- **Fantasía:** Tu cuerpo es una carga mágica inestable que podría, literalmente, matarte a ti también si la sueltas mal