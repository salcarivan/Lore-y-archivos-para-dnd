# Análisis de la clase Mago

## Dificultad general de la clase: **Alta**

El Mago es una de las clases con mayor curva de entrada y mayor techo de dominio del sistema. Tres capas de decisiones se apilan constantemente sobre el jugador:

1. **Gestión de recursos dobles** (maná + usos de Fórmulas de Arte, cada uno con su propio ritmo de recuperación entre descanso corto/largo).
2. **Personalización estructural desde el nivel 1** (Esfera de Afinidad + Postura), que no es solo estética sino que reconfigura literalmente qué rasgos recibe el personaje en niveles 7/11/15.
3. **Riesgo de agotamiento mágico** en círculo 6+, que obliga a leer tablas de consecuencias y jugar con probabilidad, no solo con daño.

A esto se suma que cada Tradición arcana introduce un **subsistema propio** (Puntos de Inercia, runas, pergaminos, refracciones, Guías Espirituales, sacrificio de vigor), por lo que dominar "el Mago" en la práctica implica dominar seis minijuegos distintos según la elección de nivel 3.

---

## Guía breve de mecánicas

- **Maná**: recurso principal para lanzar conjuros; escala con nivel, se recupera con Recuperación Arcana (nivel 2) y descansos.
- **Círculo máximo**: techo de poder disponible por nivel; lanzar círculo 6+ arriesga **agotamiento mágico** (tabla d100 + dado de agotamiento que se degrada).
- **Grimorio**: banco de conjuros conocidos (los trucos van aparte, fijados en memoria); se prepara un subconjunto diario según INT + nivel.
- **Esfera de Afinidad + Postura**: elección de nivel 1 que define identidad mágica de por vida — especialista (*Maestro de Esfera*), generalista (*Aprendiz de Todo*) o híbrido (*Erudito Equilibrado*) — y determina beneficios en niveles 1/7/11/15.
- **Fórmulas de Arte**: "adjetivos" reutilizables que modifican cualquier conjuro/truco en el momento de lanzarlo (alcance, daño, tiempo de lanzamiento, componentes, etc.), limitados por usos independientes del maná.
- **Tradición arcana (nivel 3)**: subclase que añade un recurso o mecánica central propia y reescribe cómo el mago se relaciona con el maná y el agotamiento.

---

## Guía de subclases (Tradiciones)

| Tradición | Dificultad | Rol en mesa | Poder base | Fantasía que llena |
|---|---|---|---|---|
| **Hemomancia** | Alta | Daño sostenido / nuke autosuficiente | Alto, pero con coste real y permanente (PG máximos) | El hereje que paga la magia con su propia sangre y no necesita maná para seguir golpeando |
| **Cronomancia** | Alta | Control de tempo / manipulación de iniciativa | Medio-alto, muy dependiente de la planificación | El manipulador del instante que roba turnos y reescribe fallos |
| **Runoforjador** | Media | Control de terreno / trampas de área | Medio, explota en burst si el enemigo pisa mal | El artesano paciente que convierte el campo de batalla en una trampa |
| **Escribas** | Media-Alta | Soporte / utilidad para el grupo | Medio, su fuerza es multiplicativa (equipo), no personal | El bibliotecario cuyo grimorio piensa por sí mismo y comparte su saber |
| **Prismatismo** | Media-Alta | Daño versátil + mitigación reactiva | Medio-alto, muy fuerte en manos expertas por el timing de reacciones | El cristal viviente que descompone cualquier magia en sus colores puros |
| **Espiritista** | Media | Versatilidad / buff adaptativo por turno | Medio, escala en flexibilidad más que en números brutos | El médium poseído por un coro de voces arcanas ajenas |

---

## Dos ideas de personaje

### 1. Epítome de la clase
**"El Archivero de Ykalon", Mago Erudito Equilibrado (Cinética) con Tradición Escribas.**
Encarna exactamente lo que el Mago promete: control metódico, memorización precisa, un grimorio como extensión de su identidad y una Postura que reparte el poder entre profundidad y amplitud sin comprometerse a un extremo. Su Tradición (Escribas) refuerza la fantasía central de "el mago como estudioso": no lanza magia, la *transcribe, reescribe y comparte*. Es el personaje que un jugador nuevo debería probar para entender de qué va la clase.

### 2. Vuelta de tuerca
**"Sien Rota", Mago Maestro de Esfera (Ruina) con Tradición Hemomancia.**
En lugar de la imagen del erudito frío y calculador, este personaje convierte al Mago en un fanático físico: su cuerpo, no su biblioteca, es el verdadero grimorio. Renuncia a la amplitud (Maestro de Esfera) y renuncia también a la seguridad del maná (Hemomancia), apostando todo a un único campo de destrucción pagado con su propia vitalidad. Es un Mago que se juega la vida cada combate, invirtiendo la fantasía habitual de "el que estudia desde la distancia" por "el que sangra en primera línea".

---

## Prompt / instrucciones para crear cualquier Tradición arcana

```
Crea una Tradición arcana para la clase Mago del sistema Ankora siguiendo esta estructura:

1. NOMBRE + DESCRIPTOR MECÁNICO (5-10 palabras que resuman la fantasía en una frase, 
   ej: "Ancla conjuros de área en runas-trampa detonables en el terreno").

2. PÁRRAFO DE LORE (uno solo, en tono literario, conectado a la cosmología de Ankora: 
   Tapiz, Ruptura, Custodios, Ecos, Cápsulas, Vestigios, Doce Esferas). 
   Debe terminar en una pregunta dirigida al jugador que invite a definir su personaje.

3. MECÁNICA CENTRAL (opcional pero recomendable): si la tradición necesita un recurso 
   propio (Puntos de Inercia, Cargas Cromáticas, Reserva Sanguínea, etc.), defínelo aquí 
   con: cómo se gana, cómo se recupera (descanso corto/largo) y para qué se gasta.

4. PROGRESIÓN EN 5 NIVELES FIJOS — 3, 6, 10, 14, 18:
   - Nivel 3: el rasgo definitorio de la tradición (la mecánica que la hace reconocible) 
     + a veces un segundo elemento menor de apoyo.
   - Nivel 6: expande el rasgo de nivel 3 (más usos, más opciones, nuevas condiciones) 
     y suele introducir la primera interacción con el agotamiento mágico (círculo 6+), 
     normalmente dando ventaja, desventaja o aplazando la tirada.
   - Nivel 10: profundiza la interacción con el agotamiento mágico o añade una nueva 
     capa de sinergia con el rasgo de nivel 3 (nuevo uso, nuevo recurso derivado).
   - Nivel 14: escala el poder de forma notable (duplica límites, añade una tercera 
     opción, permite combinar rasgos anteriores entre sí).
   - Nivel 18: rasgo de firma, usable normalmente 1/descanso largo, que culmina la 
     fantasía de la tradición y suele anular por completo el riesgo de agotamiento 
     mágico en, al menos, una circunstancia.

5. REGLAS DE DISEÑO OBLIGATORIAS:
   - Reutiliza conjuros existentes de Ankora como base mecánica siempre que sea posible; 
     si se necesita un conjuro nuevo, indica su equivalencia de círculo (Truco a 9º).
   - Ningún chispa o disparador de la tradición puede ser una acción, acción adicional 
     o reacción estándar sin más — debe tener una condición o coste narrativo propio 
     (igual que en el resto de la clase, los "gastos" son de maná, PG, usos o recursos 
     nuevos, no de economía de acciones genérica).
   - Cada tradición debe tener una relación clara y distinta con el agotamiento mágico 
     (mitigarlo, posponerlo, transferirlo, ignorarlo bajo condición) — es el eje que 
     conecta mecánicamente a todas las tradiciones entre sí.
   - Evita solapar el rol de tradiciones ya existentes (revisa la lista de Tradiciones 
     antes de proponer una nueva).

6. CIERRE: escribe una frase o mini-diálogo en cursiva (tipo "flavor quote") que 
   ejemplifique cómo se ve/siente lanzar magia con esta tradición.

Formato de salida: Markdown, en español, con encabezados de nivel (#, ##) igual que 
las tradiciones existentes.
```

---

## 4 propuestas de Tradiciones con rol, dificultad y fantasía no cubiertos aún

| Tradición propuesta | Dificultad | Rol en mesa | Fantasía |
|---|---|---|---|
| **Nigromante de Enjambre** | Alta (gestión de múltiples secuaces a la vez) | Invocador / comandante de un ejército de constructos-eco menores | El mago que no lucha solo, sino a través de un enjambre de fragmentos del Tapiz que él dirige como una mente colmena |
| **Oniromante** | Media | Control mental / debilitación (miedo, sueño, confusión) sobre objetivos concretos | El mago que invade sueños ajenos y arrastra pesadillas al mundo despierto para incapacitar a un único enemigo de alto valor |
| **Contramago (Disruptor Arcano)** | Media-Baja (reglas claras, poca gestión de recursos, pero exige buen timing de reacción) | Anti-lanzador / disruptor que anula o roba magia enemiga, débil ante enemigos no mágicos | El duelista arcano cuya única guerra es contra otros magos: existe para que la magia ajena nunca llegue a completarse |
| **Alquimista de Campo** | Baja-Media (accesible, pensada como punto de entrada sencillo a la clase) | Soporte versátil mediante objetos consumibles preparados fuera de combate (pociones, bombas, brebajes) | El mago práctico que trata la magia como artesanía embotellada, dando a cada aliado una herramienta distinta antes de que empiece la pelea |

Estas cuatro cubren huecos claros: **invocación/gestión de secuaces**, **control mental puro**, **anti-magia dirigida** y **soporte basado en objetos preparados**, ninguno de los cuales ocupa actualmente Hemomancia, Cronomancia, Runoforjador, Escribas, Prismatismo o Espiritista. También aportan el rango de dificultad **Baja-Media** que hoy no existe entre las tradiciones ya escritas.