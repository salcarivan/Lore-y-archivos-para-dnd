# Sistema de Artesanía

> Piensa en esto como el **banco de trabajo de un RPG de supervivencia** (tipo *Fallout 4*, *Monster Hunter* o la alquimia de hollín de *Bloodborne*). Para fabricar algo necesitas tres cosas: **saber cómo** (la receta), **tener las herramientas** y **reunir los materiales**.
> 

# La Idea Central: Cómo se Mezcla con el Inventario

El sistema de inventario y el de artesanía comparten **un único idioma**: el **Volumen** (cuánto estorba algo) y los **Espacios de Inventario** (cuánto puede guardar algo).

| Concepto de artesanía | Se mide en… | Su equivalente en el inventario |
| --- | --- | --- |
| Una **medida** de material | Volumen (depende de su *formato*, ver 2.2) | Un objeto que ocupa casillas en tu inventario |
| Una **recompensa** (el objeto terminado) | Volumen del objeto (tabla de volumen del inventario) | El objeto ya fabricado, que cargas como cualquier otro |
| Un **taller o almacén** | Espacios de Inventario (categorías de *Espaciado*) | Un edificio o vehículo con capacidad |
| Un **nodo** de recursos | Medidas disponibles | Un "cofre" del que sacas medidas hasta vaciarlo |
| El **transporte** | Capacidad de criaturas, animales y vehículos | Cargar, arrastrar, vehículos y animales de transporte |

> **Regla de oro:** cada medida de material ocupa Volumen. Si no te cabe en el inventario, no es un fallo del sistema: es un **problema de logística**, y resolverlo (contratar una carreta, escoltar una caravana, construir un taller cerca de la mina) es aventura.
> 

# Las Tres Patas de la Artesanía

Para fabricar cualquier cosa hacen falta **las tres**. Si falta una, no puedes fabricarla.

1. **📖 Conocimiento (la receta):** sabes qué materiales lleva y cómo se combinan. Se descubre experimentando, o en un papel, o se aprende de un mentor (normalmente pagando).
2. **🔧 Herramientas:** la competencia adecuada **y** el kit físico. El kit **ocupa espacio en tu inventario** (ver 3.5).
3. **🧱 Materiales:** las cantidades y tipos que pide la receta (ver capítulo 2).

> **Analogía:** es como el crafteo de *Resident Evil*. Necesitas saber que la hierba verde + la roja hacen algo mejor (receta), pero además tienes que **llevar** las dos hierbas en un inventario con casillas limitadas.
> 

# Materiales

## ¿Qué es un material?

Un **material de crafteo** es un recurso genérico que sirve para **todas** las formas de artesanía: preparar pociones, forjar armas, construir barcos o levantar edificios.

Cada material se define con **tres propiedades**:

| Propiedad | Pregunta que responde | Analogía de videojuego |
| --- | --- | --- |
| **Rareza** | ¿Cómo de común es en el mundo? Cuanto más raro, más difícil de encontrar, recolectar y reunir. | El **color del objeto** (gris, verde, azul, morado, naranja) |
| **Sustancia** | ¿De qué está hecho? | El **tipo de ingrediente** (hueso, metal, planta…) |
| **Elemento** | ¿Qué propiedades mágicas puede potenciar, si tiene alguna? La mayoría tiene afinidad elemental aunque no sea mágico. | La **afinidad** de un arma de fuego, hielo o rayo |

## Medida y Volumen (la parte que conecta con el inventario)

Una **medida** es la unidad básica de material: la cantidad que una receta cuenta como "1". **Cada medida lleva incluido su envase básico**: el frasco del fluido, el cilindro del gas, el fardo de la tela. No tienes que gastar Volumen aparte en envases.

Según su **Sustancia**, una medida tiene uno de estos tres **formatos** (cuánto Volumen ocupa):

| Formato | Volumen por medida | Medidas por espacio | Sustancias | Ejemplo |
| --- | --- | --- | --- | --- |
| **Compacto** | 0.2 (Diminuto) | 5 | Tela, Planta, Extraplanario | Un fardo de tela enrollada, hierbas secas, un frasquito de esencia |
| **Estándar** | 1 (Pequeño) | 1 | Hueso, Cerámica, Carne, Fluido, Gas, Vidrio, Piel | Un frasco de aceite, un cilindro de gas, un colmillo |
| **Pesado** | 2 (Mediano) | ½ (una medida ocupa 2 espacios) | Metal, Piedra, Madera | Un lingote de acero, un bloque de piedra, un tablón grueso |

> **Cómo sumar:** suma el Volumen de todo lo que llevas y **redondea hacia arriba solo al final** (no objeto por objeto). Así 5 medidas Compactas (5 × 0.2 = 1) ocupan exactamente 1 espacio.
> 

> **Regla del DJ:** el formato por Sustancia es la regla general. Un material concreto puede saltársela si la narrativa lo pide (un polvo de metal muy fino podría ser Compacto; un hueso de dragón enorme podría ser Pesado).
> 

**Ejemplo:** Crackle (mago kobold, 13 espacios de inventario) lleva a la espalda:

- 4 × Acero de caldera (Pesado, 2 c/u) = **8**
- 3 × Aceite de lámpara (Estándar, 1 c/u) = **3**
- 5 × Hongo de cripta (Compacto, 0.2 c/u) = **1**

Total: **12 espacios de inventario** de 13. Le queda 1 libre.

### Ejemplo: el Sable de la Furia Elemental

Un DJ introduce un objeto mágico nuevo, el **Sable de la Furia Elemental**. Necesita estos materiales:

| Cant. | Material | Propiedades | Volumen |
| --- | --- | --- | --- |
| 2 | Barra de acero de caldera | Poco común, Metal, Fuego | 2 × 2 = 4 |
| 1 | Piel de sabueso de ceniza | Poco común, Piel, Fuego | 1 |
| 1 | Núcleo de elemental de fuego | Rara, Piedra, Fuego | 2 |

**Volumen total de los materiales: 7.** El sable terminado ocupa solo **2** (objeto Mediano). Es normal: al fundir, forjar y curtir se pierde mucho volumen (escoria, virutas, humo, recortes).

> **No hace falta que el Volumen de los materiales cuadre con el del objeto final.** Los materiales están pensados para generar misiones ("necesito 5 lingotes de acero de caldera"), no para simular la física de una fundición. *Fiction first*.
> 

### Sustituir Materiales

Al fabricar desde una receta, muchas veces puedes usar **otros materiales distintos** a los indicados, siempre que las propiedades encajen. Si quieres usar materiales con propiedades diferentes, se aplica esto:

| Propiedad | Regla de sustitución |
| --- | --- |
| **Rareza** | El material sustituto debe tener **igual o mayor** rareza. Nunca menor. |
| **Sustancia** | Puedes cambiarla si tiene sentido para el objeto y se puede justificar. |
| **Elemento** | Puedes cambiarlo si tiene sentido para el objeto y se puede justificar. Si el objeto tiene un tema elemental muy marcado, quizá tengas que cambiar el elemento de **varios** materiales. |

> **Sustituir también cambia el Volumen que cargas.** Si cambias de Sustancia, cambia el formato (Compacto / Estándar / Pesado), y con él los espacios que ocupan los materiales al transportarlos. El Volumen del objeto **terminado** no cambia: sigue la tabla del inventario.
> 

**Ejemplos con el Sable de la Furia Elemental:**

- **Krazak** tiene una Piel de salamandra (Rara, Piel, Fuego). La usa en lugar de la Piel de sabueso de ceniza (Poco común, Piel, Fuego). Rareza mayor y mismas Sustancia y Elemento: **permitido**. Volumen igual (1).
- **Brakken** prefiere los huesos para sus armas. Sustituye las 2 barras de acero por 2 Huesos de dragón rojo joven (Poco común, Hueso, Fuego) y fabrica un **sable de hueso**. Rareza igual, Sustancia cambiada y justificada: **permitido**. Sus materiales pasan de Volumen 4 (Metal, Pesado) a **2** (Hueso, Estándar).
- **Crackle** quiere un Núcleo de elemental de relámpago (Rara, Piedra, Relámpago) para hacer un sable de descarga. Pero entonces también tiene que cambiar el Elemento de los otros materiales para que el tema sea coherente.

### Nombres de Materiales

Los nombres pueden ser **únicos de tu campaña**: mecánicamente solo importan las tres propiedades. Usa el nombre como sabor y **deja que los jugadores propongan los suyos**, sobre todo al despiezar monstruos.

### Tablas de Propiedades (d100)

Usa estas tablas para inventar materiales al vuelo. Tira un d100 en cada una.

**Rareza**

| d100 | Rareza | Descripción | Analogía de loot |
| --- | --- | --- | --- |
| 01–16 | Común | Lo encuentras casi en cualquier parte del mundo. | ⚪ Gris |
| 17–32 | Infrecuente | Lo encuentras casi en cualquier parte, pero es difícil de reunir o conseguir. | 🟢 Verde |
| 33–48 | Rara | Es limitada (por lugar, cantidad o tiempo). | 🔵 Azul |
| 49–64 | Epico | Es limitada y además difícil de reunir o conseguir. | 🟣 Morado |
| 65–80 | Legendaria | Un material mítico, en los lugares más peligrosos del mundo. | 🟠 Naranja |
| 81–96 | Única | Solo existe **una** unidad en todo el mundo. | 🟡 Artefacto |
| 97–00 | — | Repite la tirada. | — |

**Sustancia**

| d100 | Sustancia | Descripción | Formato |
| --- | --- | --- | --- |
| 01–07 | Hueso | Hueso de una criatura que estuvo viva. | Estándar |
| 08–14 | Cerámica | Barro, porcelana, ladrillo, loza. | Estándar |
| 15–21 | Tela | Lana, algodón, tweed, seda, lona… | Compacto |
| 22–28 | Carne | Trozo de carne u órganos de una criatura que estuvo viva. | Estándar |
| 29–35 | Fluido | Un líquido: sangre, agua, aceite, ácido… | Estándar |
| 36–42 | Gas | Una sustancia gaseosa. | Estándar |
| 43–49 | Vidrio | Sustancia transparente o translúcida, normalmente hecha de arena. | Estándar |
| 50–56 | Metal | Mineral o mena metálica: hierro, oro, acero, latón… | Pesado |
| 57–63 | Extraplanario | Una sustancia indescriptible, de otro mundo. | Compacto |
| 64–70 | Planta | Material de una planta: fibras, flores, polen, hongos… | Compacto |
| 71–77 | Piel | Piel o cuero de una criatura que estuvo viva. | Estándar |
| 78–84 | Piedra | Roca dura usada en construcción. | Pesado |
| 85–91 | Madera | Material duro que sale de los árboles. | Pesado |
| 92–00 | — | Repite la tirada. | — |

**Elemento**

| d100 | Elemento | Sensación / temática |
| --- | --- | --- |
| 01–10 | Aire | Viento, sonido, flexible, veleidoso. |
| 11–20 | Tierra | Tierra, naturaleza, terco, fiable. |
| 21–30 | Fuego | Llama, calor, pasión, furia. |
| 31–40 | Fuerza | Magia, inmaterial, distante, espectral. |
| 41–50 | Relámpago | Rayos, electricidad, impulsivo, energía. |
| 51–60 | Necrótico | Oscuridad, descomposición, morboso, fatalista. |
| 61–70 | Ninguno | Sin elemento apreciable. |
| 71–80 | Psíquico | Mente, sobrenatural, perspicaz, de otro mundo. |
| 81–90 | Radiante | Luz, purificar, calmante, ordenado. |
| 91–00 | Agua | Agua, frío, tempestuoso, caótico. |

## Materiales de Ejemplo

**Industria y ciudad**

| Nombre | Propiedades | Volumen por medida |
| --- | --- | --- |
| Latón de relojería | Común, Metal, Ninguno | 2 |
| Hierro de fundición | Común, Metal, Ninguno | 2 |
| Carbón de hulla | Común, Piedra, Fuego | 2 |
| Madera de olmo ahumada | Común, Madera, Ninguno | 2 |
| Gas de alumbrado | Común, Gas, Fuego | 1 |
| Aceite de lámpara | Común, Fluido, Fuego | 1 |
| Cuero de rata de cloaca | Común, Piel, Necrótico | 1 |
| Lona alquitranada | Común, Tela, Ninguno | 0.2 |
| Musgo de cloaca | Común, Planta, Tierra | 0.2 |
| Acero de caldera | Poco común, Metal, Fuego | 2 |
| Ácido de curtidor | Poco común, Fluido, Necrótico | 1 |
| Cristal de lente pulido | Poco común, Vidrio, Radiante | 1 |
| Engranaje de autómata | Rara, Metal, Fuerza | 2 |
| Placa de golem de vapor | Rara, Metal, Fuego | 2 |
| Resina de niebla | Rara, Fluido, Necrótico | 1 |
| Seda de araña de campanario | Rara, Tela, Aire | 0.2 |

**Monstruos y criaturas góticas**

| Nombre | Propiedades | Volumen por medida |
| --- | --- | --- |
| Sangre de necrófago | Poco común, Fluido, Necrótico | 1 |
| Hongo de cripta | Poco común, Planta, Psíquico | 0.2 |
| Ala de gárgola | Poco común, Piedra, Tierra | 2 |
| Piel de licántropo | Rara, Piel, Tierra | 1 |
| Ectoplasma embotellado | Rara, Extraplanario, Necrótico | 0.2 |
| Bruma psíquica destilada | Rara, Gas, Psíquico | 1 |
| Núcleo de gárgola | Muy rara, Piedra, Tierra | 2 |
| Colmillo de vampiro | Muy rara, Hueso, Necrótico | 1 |
| Lágrima de banshee | Muy rara, Fluido, Psíquico | 1 |

# Recetas

Las **recetas** te enseñan a convertir materiales en **recompensas**. Puedes descubrirlas experimentando o aprenderlas de un mentor dispuesto (normalmente a cambio de dinero).

## Qué lleva una receta

| Campo | Qué responde |
| --- | --- |
| **Recompensa** | ¿Qué obtienes al fabricarla? |
| **Materiales** | ¿Cuántos y de qué tipo hacen falta? |
| **Tiempo** | ¿Cuánto se tarda en fabricarla? |
| **Requisitos** | ¿Hay algo más? (competencias, herramientas, taller…) |
| **Volumen del resultado**  | Cuánto ocupa el objeto terminado, según la tabla de volumen del inventario. |
| **Volumen de los materiales**  | La suma del Volumen de todos los materiales. Te dice cuánto hay que cargar y guardar. |

Para crear tus propias recetas, sigue estos **4 pasos**.

### 3.2 Paso 1: Elige una Recompensa

La recompensa puede ser **cualquier cosa**: una espada, una armadura mágica, una casa, un barco, un castillo.

### 3.3 Paso 2: Elige los Materiales

Elige el **tamaño de la recompensa** en esta tabla. Cuanto más grande, más material necesita.

| Tamaño de recompensa | Materiales | Descripción | Cómo se maneja en el inventario |
| --- | --- | --- | --- |
| Diminuto | 1–5 | Más pequeño que una persona. | Un objeto normal de la tabla de volumen (0.2 a 6). Va en la mochila. |
| Pequeño | 10 | Grande como una persona. | Un objeto voluminoso (6 a 9), o algo que hay que arrastrar. |
| Mediano | 100 | Grande como un elefante. | Ya no se carga: se arrastra, se conduce o se instala. Suele ser un vehículo (Reducido a Compacto). |
| Grande | 1.000 | Grande como una casa. | Fijo o vehículo grande (Amplio o Grande). |
| Enorme | 10.000 | Grande como una mansión. | Construcción fija o vehículo Vasto. |
| Gargantuesco | 100.000 | Grande como un fuerte. | Construcción fija. |
| Astronómico | 1.000.000+ | Grande como un castillo. | Construcción fija. |

**Regla general de reparto:** elige **tres tipos** de material para la receta:

| Tipo de material | Porcentaje |
| --- | --- |
| **Primario** | 50 % |
| **Secundario** | 30 % |
| **Terciario** | 20 % |

Elige rarezas, sustancias y elementos que encajen con el tipo y el tema de la recompensa.

> **Recompensas Diminutas (1–5 materiales):** con tan pocas medidas no se puede repartir en tres tipos. Usa **uno o dos** tipos y ya está.
> 

> **Fiction First:** las recetas son una forma divertida de sacar a los personajes al mundo a buscar materiales raros. Sé evocador y con sabor, y no te obsesiones con simular la realidad. Usa trazos gruesos para crear ganchos de misión. En tu mundo, entre ciudades estado la espesura es peligrosa: **cada material raro es una excusa para salir de la ciudad**.
> 

### Paso 3: Elige un Tiempo de Crafteo

El tiempo se mide en **días**: cuántos días tardaría **una persona media** en fabricar la recompensa una vez tiene todos los materiales.

| Escala | Días | Ejemplos |
| --- | --- | --- |
| Días | 1–5 | Una poción, una comida, un cuadro. |
| Semanas | 10 | Una espada, un gran banquete. |
| Meses | 100 | Una armadura, una casa diminuta. |
| Años | 1.000 | Una casa grande, un templo. |
| Décadas | 10.000 | Una mansión, una iglesia. |
| Siglos | 100.000 | Un fuerte, una catedral. |
| Milenios | 1.000.000+ | Un castillo, una pirámide gigante. |

#### Trabajo en equipo

Algunas recompensas tardarían meses, años o siglos para una sola persona. Para esas, recluta ayuda con esta regla:

1. **Artesano cualificado** (tiene la competencia con la herramienta) = cuenta como **1 artesano**.
2. **Ayudante sin competencia** = cuenta como **½ artesano**.
3. **Tiempo real** = días de la receta ÷ artesanos efectivos. Redondea hacia arriba. Mínimo **1 día**.
4. **Límite por taller:** el espacio manda. Cabe **1 artesano por cada 10 espacios de inventario** del taller (ver 5.6).

**Ejemplo:** una receta de 100 días con 4 artesanos cualificados y 2 ayudantes = 4 + (2 × ½) = 5 artesanos efectivos → 100 ÷ 5 = **20 días**.

### 3.5 Paso 4: Aplica Restricciones

Piensa qué restricciones (si las hay) tiene la receta:

- **Competencias:** habilidades o herramientas en las que hay que ser competente.
- **Herramientas físicas:** el kit, que ocupa espacio en el inventario.
- **Taller:** una fragua de vapor, una mesa de alquimia, un banco de relojero…
- **Alineamiento, costes adicionales, permisos de gremio…**

**Volumen de las herramientas de artesano** (propuesta coherente con la tabla de volumen del inventario):

| Herramienta | Volumen | Categoría |
| --- | --- | --- |
| Herramientas de herrero | 3 | Grande |
| Herramientas de albañil | 3 | Grande |
| Herramientas de carpintero | 3 | Grande |
| Suministros de alquimista | 3 | Grande |
| Herramientas de manitas (relojería y mecanismos) | 3 | Grande |
| Herramientas de soplador de vidrio | 3 | Grande |
| Herramientas de peletero | 2 | Mediano |
| Herramientas de tejedor | 2 | Mediano |
| Utensilios de cocinero | 2 | Mediano |
| Kit de herboristería | 2 | Mediano |
| Herramientas de joyero | 1 | Pequeño |

> Estos volúmenes son una propuesta. Si tu tabla de volumen del inventario dice otra cosa para alguna herramienta, manda la tuya.
> 

> **Llevar varios kits pesa mucho.** Un artesano viajero con herramientas de herrero y suministros de alquimista ya gasta 6 espacios. Por eso en tu mundo existen los **carros-taller** (ver 5.6).
> 

### 3.6 Ejemplo Completo: Coraza de Placas de Hollín

Valiant, el clérigo, quiere una armadura pesada mágica. El DJ crea una receta nueva siguiendo los 4 pasos.

1. **Recompensa:** una armadura pesada completa para una persona → tamaño **Pequeño** (10 materiales).
2. **Materiales (50 / 30 / 20 %):** 5 + 3 + 2 = 10.
3. **Tiempo:** una armadura es cosa de **Meses** → 100 días.
4. **Restricciones:** Herramientas de herrero + fragua de vapor.

**Receta: Coraza de Placas de Hollín**

| Campo | Valor |
| --- | --- |
| **Recompensa** | 1 × Coraza de Placas de Hollín (armadura pesada, criatura Mediana) |
| **Tiempo de crafteo** | 100 días |
| **Requisitos** | Herramientas de herrero (competencia) + fragua de vapor |
| **Volumen del resultado** | 9 (armadura pesada, criatura Mediana) |
| **Volumen de los materiales** | 17 |

| Cant. | Material | Propiedades | Volumen |
| --- | --- | --- | --- |
| 5 | Acero de caldera | Poco común, Metal, Fuego | 5 × 2 = 10 |
| 3 | Resina de niebla | Rara, Fluido, Necrótico | 3 × 1 = 3 |
| 2 | Núcleo de gárgola | Muy rara, Piedra, Tierra | 2 × 2 = 4 |

### 3.7 Ejemplo Pequeño: Tónico Reconstituyente

Una receta Diminuta (3 materiales, solo dos tipos).

| Campo | Valor |
| --- | --- |
| **Recompensa** | 1 × Poción de curación |
| **Tiempo de crafteo** | 1 día |
| **Requisitos** | Kit de herboristería o Suministros de alquimista (competencia) |
| **Volumen del resultado** | 1 |
| **Volumen de los materiales** | 1.4 (se redondea a 2 si los llevas solos) |

| Cant. | Material | Propiedades | Volumen |
| --- | --- | --- | --- |
| 2 | Musgo de cloaca | Común, Planta, Tierra | 2 × 0.2 = 0.4 |
| 1 | Agua de lluvia destilada | Común, Fluido, Agua | 1 |

### 3.8 Plantilla para Copiar

```
Receta: [Nombre]

Recompensa: [cantidad] × [objeto]
Tiempo de crafteo: [días]
Requisitos: [competencias, herramientas, taller]
Volumen del resultado: [según tabla de volumen]
Volumen de los materiales: [suma]

| Cant. | Material | Propiedades | Volumen |
|---|---|---|---|
| [n] | [nombre] | [Rareza, Sustancia, Elemento] | [n × formato] |
```

# 4. Nodos

Para reunir un material, primero tienes que encontrar una **fuente**. Son los **nodos de recursos**, y pueden ser de cualquier forma y tamaño: árboles, minas, ríos, ciudades, criaturas, canteras, chatarrerías, mercaderes…

> **Analogía:** un nodo es como una **veta de mineral en *Skyrim* o *Minecraft***: está en un sitio concreto, tiene una cantidad de recurso y necesitas la herramienta y la habilidad para sacarlo. La diferencia aquí es que **lo que sacas te llena la mochila**.
> 

Para crear un nodo, sigue estos **5 pasos**.

## 4.1 Paso 1: Elige los Materiales

Elige qué materiales se pueden sacar de este nodo. Un nodo básico da **un solo tipo**, pero algunos pueden tener **dos o tres**.

## 4.2 Paso 2: Fija la Cantidad

Elige la **riqueza** del nodo: cuanto más rico, más materiales puedes sacar antes de que se agote.

| Riqueza | Cantidad (medidas) | Descripción | Ejemplos Gaslamp |
| --- | --- | --- | --- |
| Agotado | 0 | El nodo se ha secado. | Una mina vacía |
| Escaso | 1–5 | Una criatura o un recurso básico. | Un cadáver de necrófago, una farola rota |
| Simple | 10 | Un árbol, una veta, una criatura enorme. | Un filón de acero, una bolsa de gas de pantano |
| Rico | 100 | Un árbol gigante, una criatura gargantuesca. | Un cementerio, una chimenea colosal |
| Abundante | 1.000 | Una aldea pequeña, una granja cultivada. | Una chatarrería del muelle, una granja de hongos |
| Copioso | 10.000 | Del tamaño de un fuerte. | Una fundición abandonada |
| Ilimitado | 100.000 | Una ciudad, una gran cantera. | Un puerto industrial, una ciudad estado |

**Cantidad limitada:** algunos nodos tienen una cantidad fija de materiales concretos: un corazón, dos núcleos, 2d6 escamas de rubí… Asigna esos límites como te convenga.

**Regeneración:** algunos nodos **recuperan** sus materiales con el tiempo: una granja produce cosechas nuevas, los peces se reproducen en un estanque, los árboles echan ramas. Si un nodo va a ser importante a largo plazo, añade una **tasa y velocidad de regeneración** (por ejemplo: "1d4 medidas cada 10 días").

## 4.3 Cadáveres como Nodos

Cuando derrotas a una criatura, su cuerpo es un nodo **Escaso** (o mayor si es enorme):

| Tamaño de la criatura | Riqueza | Medidas de material |
| --- | --- | --- |
| Diminuto | Escaso | 1 |
| Pequeño | Escaso | 1d3 |
| Mediano | Escaso | 1d4 |
| Grande | Escaso | 1d4 + 1 (2–5) |
| Enorme | Simple | 10 |
| Gargantuesco | Rico | 100 |

> **Ojo con el Volumen del botín.** Despiezar un monstruo Enorme deja 10 medidas: si son de hueso o piedra (Pesado), son **20 espacios de inventario**. El botín grande necesita carro, animal de carga o varios viajes.
> 

### 4.4 Paso 3: Elige un Tiempo de Recolección

Elige cuánto tarda **un intento** de recolección en este nodo.

| Escala | Tiempo mínimo |
| --- | --- |
| Segundos | 1 segundo |
| Minutos | 1 minuto |
| Horas | 1 hora |
| Días | 1 día |
| Semanas | 1 semana |
| Meses | 1 mes |
| Años | 1 año |
| Décadas | 10 años |

### 4.5 Paso 4: Fija las Habilidades de Recolección y la CD

Elige una o más **habilidades** que tengan sentido para el nodo, y una **CD** (si la hay) para poder sacar el material.

**Habilidades de recolección habituales**

| Habilidad | Cómo se usa |
| --- | --- |
| Trato con Animales | Recoges materiales de animales. |
| Arcanos | Interactúas con lo arcano. |
| Atletismo | Recoges materiales a base de fuerza bruta. |
| Intimidación | Intimidas y extorsionas materiales a una persona o lugar. |
| Naturaleza | Recoges materiales de plantas. |
| Persuasión | Convences y regateas materiales a una persona o lugar. |
| Religión | Interactúas con lo divino. |

**Habilidades añadidas para tu mundo Gaslamp**

| Habilidad | Cómo se usa |
| --- | --- |
| Investigación | Rebuscas entre chatarra, ruinas y archivos. |
| Medicina | Extraes órganos y fluidos de una criatura con precisión. |
| Supervivencia | Localizas y recoges recursos en la espesura (pantanos, bolsas de gas). |
| Sigilo | Sustraes materiales de almacenes y fábricas sin que te vean. |

**CD de recolección**

| Dificultad | CD |
| --- | --- |
| Muy fácil | 5 |
| Fácil | 10 |
| Media | 15 |
| Difícil | 20 |
| Muy difícil | 25 |
| Imposible | 30 |

Cuando un jugador gasta el tiempo necesario en recolectar, hace la prueba de habilidad correspondiente:

| Resultado | Qué pasa |
| --- | --- |
| **Éxito crítico** (20 natural en el dado) | Recolectas **2 medidas** de material. |
| **Éxito** | Recolectas **1 medida** de material. |
| **Fallo** | No recolectas nada. |
| **Fallo crítico** (1 natural en el dado) | No recolectas nada y el nodo **pierde 2 medidas**. |

> **Regla clara:** un 20 natural siempre es éxito crítico y un 1 natural siempre es fallo crítico, aunque el total sea mayor o menor que la CD.
**Variante opcional:** éxito crítico si superas la CD por 10 o más; fallo crítico si fallas por 10 o más.
> 

### 4.6 Paso 5: Aplica Restricciones

Piensa qué restricciones tiene el nodo: herramientas (un pico, un cilindro vacío), habilidades, conocimientos, permisos, peligros del entorno…

### 4.7 Recolectar con el Inventario Lleno

Cada medida que recolectas **entra en tu inventario en el momento**. Si no cabe:

1. **Puedes pasarte de tu capacidad** hasta el límite absoluto (capacidad + la mitad), pero quedas **Agobiado**.
2. **Si ya no puedes cargar más**, la medida **se queda en el nodo** (no se pierde). Queda apilada a merced de ladrones y monstruos.
3. **Puedes soltar algo** para hacer sitio, pero lo que sueltes queda en el suelo.

> **Ejemplo:** Krazak (21 espacios, 13 usados) mina en un **Filón de acero de caldera**. Cada medida de Acero es Pesada (2 espacios). Con sus 8 espacios libres carga **4 medidas** y queda en 21/21. Una quinta medida lo dejaría en 23/21: **Agobiado** (velocidad a la mitad, desventaja en FUE/DES/CON). Su límite absoluto es 31 (21 + 10). Lo más inteligente: la quinta medida se la lleva Crackle.
> 

### 4.8 Nodos de Ejemplo para tu Mundo Gaslamp

**Nodo: Filón de acero de caldera**

| Campo | Valor |
| --- | --- |
| **Riqueza** | Simple (10 medidas en total) |
| **Materiales** | Acero de caldera (1d4 + 4 medidas, es decir 5–8) y Carbón de hulla (el resto hasta 10) |
| **Tiempo de recolección** | 1 hora por intento |
| **Habilidad y CD** | Atletismo, CD 15 |
| **Restricciones** | Un pico o herramienta de minero |

**Nodo: Gárgola caída**

| Campo | Valor |
| --- | --- |
| **Riqueza** | Escaso (1 medida) |
| **Materiales** | Núcleo de gárgola |
| **Tiempo de recolección** | 1 día |
| **Habilidad y CD** | Arcanos o Atletismo, CD 15 |
| **Restricciones** | Herramientas de albañil o similares |

**Nodo: Chatarrería del muelle**

| Campo | Valor |
| --- | --- |
| **Riqueza** | Abundante (1.000 medidas) |
| **Materiales** | Hierro de fundición, Latón de relojería, Engranaje de autómata (poco) |
| **Regeneración** | Llegan 10 medidas nuevas al día |
| **Tiempo de recolección** | 1 hora por intento |
| **Habilidad y CD** | Investigación, CD 10 (Engranaje de autómata: CD 20) |
| **Restricciones** | Puede haber bandas de chatarreros que reclamen la zona |

**Nodo: Cripta cubierta de hongos**

| Campo | Valor |
| --- | --- |
| **Riqueza** | Rico (100 medidas) |
| **Materiales** | Hongo de cripta, Sangre de necrófago (raro) |
| **Regeneración** | 1d4 medidas cada 10 días |
| **Tiempo de recolección** | 1 hora por intento |
| **Habilidad y CD** | Naturaleza, CD 15 |
| **Restricciones** | Los necrófagos rondan la cripta |

**Nodo: Bolsa de gas de pantano**

| Campo | Valor |
| --- | --- |
| **Riqueza** | Simple (10 medidas de Gas de alumbrado) |
| **Tiempo de recolección** | 1 hora por intento |
| **Habilidad y CD** | Supervivencia o Arcanos, CD 15 |
| **Restricciones** | Un cilindro vacío por cada medida. **Fallo crítico:** el gas se enciende (2d6 de daño de fuego al recolector) |

**Nodo: Mercader del mercado negro**

| Campo | Valor |
| --- | --- |
| **Riqueza** | Escaso (3 medidas de Resina de niebla) |
| **Tiempo de recolección** | 1 hora |
| **Habilidad y CD** | Persuasión, CD 15 |
| **Restricciones** | Hay que conocer la contraseña de la puerta trasera |

---

# 5. Logística: Cargar, Guardar y Transportar Materiales

Esta es la parte donde **se mezclan del todo** el crafteo y el inventario.

### 5.1 Dónde guardas los materiales

Divide tus espacios libres en contenedores igual que con el resto del equipo:

| Contenedor | Sirve para materiales… | Velocidad para sacarlos |
| --- | --- | --- |
| 🎒 **Bolsa** | De cualquier formato (Compacto, Estándar, Pesado) | Acción completa |
| 🧵 **Cinturón** | Solo Compactos y Estándar pequeños (frascos, ampollas, fardos) | Acción gratuita |
| 🏹 **Carcaj** | No aplica | — |
| 🗡️ **Funda** | No aplica | — |
| 👕 **Puesto** | No aplica | — |

> **Truco de artesano:** lleva los materiales delicados y valiosos (esencias, ampollas, resinas) en el **cinturón**, como una bandolera de reactivos, y los pesados (lingotes, piedra) en la **bolsa** o en un vehículo.
> 

### 5.2 Sobrecarga

Se aplican las reglas normales de sobrecarga:

> **Condición: Agobiado**
> 
> - Tu velocidad se reduce a la mitad.
> - Tienes desventaja en pruebas de habilidad, tiradas de ataque y salvaciones que usen Fuerza, Destreza o Constitución.
> 
> **Límite absoluto:** no puedes superar tu capacidad en más de la mitad de tus espacios máximos (redondeando hacia abajo).
> 

### 5.3 Arrastrar y Ruedas

Si en lugar de cargar los materiales los **arrastras**:

| Situación | Reducción de Volumen |
| --- | --- |
| Arrastrar o tirar de un montón de materiales | Mitad del total (redondeado hacia abajo) |
| Transporte con ruedas (carro, carreta, trineo) | Un cuarto del volumen |

**Ejemplo:** 20 espacios de material arrastrados cuentan como 10. Sobre un carro de mano, como 5.

### 5.4 Vehículos y Animales de Transporte

Los vehículos usan la tabla de **Espaciado** del inventario:

| Espaciado | Ejemplos | Espacios de inventario |
| --- | --- | --- |
| Reducido | Carro de mano, trineo de mano | 20 |
| Ajustado | Carro de caballo, cuadriga, bote de remos | 60 |
| Compacto | Carreta, carruaje, botequilla | 180 |
| Amplio | Carruaje de tren | 540 |
| Grande | Drakkar, barco de vela | 1.620 |
| Vasto | Galera, buque de guerra | 4.860 |

Las **mulas, caballos y otros animales** calculan su capacidad como un personaje: por su tamaño y su modificador de Fuerza.

> **Gancho de aventura:** una recompensa de 100 materiales (Mediana) ya necesita varios carros. Entre ciudades estado, la espesura es peligrosa: **una caravana cargada de metal es un objetivo**. Escoltarla, protegerla o asaltarla es una aventura entera.
> 

### 5.5 Contenedores Mágicos

| Objeto | Volumen propio | Espacios que otorga |
| --- | --- | --- |
| Bolsa de Contención | 1 | 6 |
| Agujero Portátil | 1 | 9 |
| Mochila Práctica | 2 | 12 |

Son el sueño de cualquier recolector: una Bolsa de Contención da 5 espacios netos extra para materiales.

### 5.6 Talleres y Almacenes

Un taller también es un "edificio con capacidad": tiene **espacios de inventario** para guardar materiales, y determina **cuántos artesanos** pueden trabajar a la vez.

| Espaciado | Ejemplo Gaslamp | Espacios (almacén) | Artesanos máximos (1 por cada 10 espacios) |
| --- | --- | --- | --- |
| Reducido | Rincón de taller, carro-taller | 20 | 2 |
| Ajustado | Taller de barrio, herrería | 60 | 6 |
| Compacto | Taller-almacén, forja de gremio | 180 | 18 |
| Amplio | Fábrica pequeña | 540 | 54 |
| Grande | Fundición | 1.620 | 162 |
| Vasto | Complejo industrial, astillero | 4.860 | 486 |

**Reglas:**

1. Los **materiales de la receta** deben caber en el almacén del taller. Si el Volumen total de los materiales supera su capacidad, necesitas un taller mayor.
2. **Alternativa por fases:** divide los materiales en tandas. Cada tanda avanza el tiempo de crafteo en proporción a los materiales que use. Un taller pequeño puede levantar algo grande, pero muy despacio.
3. El **límite de artesanos** de la tabla es un máximo, no un mínimo: puedes trabajar con menos.

> [!NOTE]
**Fiction first:** los números son una guía. Un DJ puede decidir que un taller no tiene el equipo adecuado (la fragua correcta, una grúa) y exigirlo como requisito de la receta.
> 

### 5.7 Ejemplo: Fabricar una Carreta

**Receta: Carreta reforzada** (Mediana, 100 materiales)

| Campo | Valor |
| --- | --- |
| **Recompensa** | 1 × Carreta (vehículo Compacto, 180 espacios de inventario) |
| **Tiempo de crafteo** | 100 días (Meses) |
| **Requisitos** | Herramientas de carpintero y de herrero (competencia) |
| **Volumen de los materiales** | 164 |

| Cant. | Material | Propiedades | Volumen |
| --- | --- | --- | --- |
| 50 | Madera de olmo ahumada | Común, Madera, Ninguno | 50 × 2 = 100 |
| 30 | Hierro de fundición | Común, Metal, Ninguno | 30 × 2 = 60 |
| 20 | Lona alquitranada | Común, Tela, Ninguno | 20 × 0.2 = 4 |

**Logística:**

- **Transporte:** 164 espacios de material. Cargando a mano es imposible (un personaje de 20 espacios llega a 30 como máximo), así que hacen falta **3 carros de caballo** (3 × 60 = 180 espacios).
- **Taller:** necesita un taller **Compacto** o mayor (180 espacios ≥ 164).
- **Tiempo:** con 10 artesanos cualificados, 100 ÷ 10 = **10 días** (el taller admite hasta 18).

### 5.8 Opcional: Materiales Perecederos

Para más realismo y tensión:

- Los materiales **orgánicos frescos** (Carne, Fluidos biológicos, Plantas frescas) **se echan a perder a los 3 días** si no se conservan.
- **Conservarlos** exige Suministros de alquimista y 1 medida de un Fluido conservante (Común) por cada 5 medidas conservadas. Duran **30 días**.
- Una **cámara frigorífica** (en ciudades) los mantiene indefinidamente.

## 6. Ejemplo de Campaña: La Coraza de Valiant

**Situación:** Valiant (clérigo, 20 espacios) quiere la **Coraza de Placas de Hollín** (receta 3.6). Necesita **17 espacios** de materiales. Krazak tiene **8 libres** y Crackle tiene **13 libres**.

1. **Conseguir el acero:** Krazak mina en el **Filón de acero de caldera** (Atletismo CD 15, 1 hora por intento). Tras varias horas consigue **5 medidas** de Acero de caldera. Carga 4 (8 espacios, queda en 21/21). **Crackle** carga la quinta (2 espacios).
2. **Conseguir la resina:** Crackle regatea con el mercader del mercado negro (Persuasión CD 15) y compra **3 medidas** de Resina de niebla (3 espacios).
3. **Conseguir los núcleos:** el grupo derrota a dos gárgolas y las despieza (Arcanos o Atletismo CD 15, 1 día cada una). Consiguen **2 Núcleos de gárgola** (4 espacios).
4. **Cargar todo:** Crackle lleva 2 + 3 + 4 = **9 espacios** de sus 13. Nadie está Agobiado. No hacía falta ni carro.
5. **Fabricar:** en un taller Reducido (20 espacios ≥ 17) con fragua de vapor. Krazak (enano, competente con herramientas de herrero) trabaja junto a un herrero PNJ: 2 artesanos → 100 ÷ 2 = **50 días**.
6. **Resultado:** una armadura pesada de **9 volumen**. Al ponérsela, Valiant baja su espacio libre según las reglas del inventario.

---

## 📋 Resumen Rápido (Cheat Sheet)

1. Fabricar necesita **receta + herramientas + materiales**.
2. Cada material tiene **Rareza, Sustancia y Elemento**.
3. Una **medida** ocupa Volumen según su **formato**: Compacto (0.2), Estándar (1) o Pesado (2).
4. **Suma todo y redondea hacia arriba solo al final.**
5. Sustituir materiales: **igual o mayor rareza**, y justifica cambios de sustancia o elemento. Cambia el Volumen que cargas.
6. Una receta se crea en **4 pasos**: recompensa, materiales (50/30/20), tiempo, restricciones.
7. Un nodo se crea en **5 pasos**: materiales, cantidad, tiempo de recolección, habilidad y CD, restricciones.
8. Recolección: **20 natural** = 2 medidas, **éxito** = 1, **fallo** = nada, **1 natural** = nada y el nodo pierde 2.
9. Lo que recolectas **entra en tu inventario al instante**. Si no cabe, te Agobias o se queda en el nodo.
10. Los **talleres** tienen almacén (Espaciado) y admiten **1 artesano por cada 10 espacios**.
11. **Equipo:** cada kit de artesano ocupa Volumen (1 a 3).
12. Para lo grande, **piensa en logística**: carros, caravanas, escoltas.