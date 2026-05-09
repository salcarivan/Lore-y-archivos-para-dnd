# 🧪 Condición: Envenenado

La condición **Envenenado** representa el avance de un tóxico en el cuerpo. Es **progresiva**: al final de cada turno (o cada cierto tiempo, según la situación), el afectado tira un dado. Si saca **1 o 2**, el nivel de envenenamiento aumenta.

El dado usado para la tirada depende del nivel actual de envenenamiento.

---

### 📊 Tabla de niveles de Envenenado

| Nivel | Dado de empeoramiento | Efecto |
|-------|----------------------|--------|
| **0** (Sano) | — | Sin efectos. |
| **1** (Leve) | d12 | Desventaja en pruebas de Constitución para resistir venenos o enfermedades. |
| **2** (Moderado) | d10 | Desventaja en **todas** las pruebas de Constitución. |
| **3** (Grave) | d8 | Desventaja en Constitución + **desventaja en ataques cuerpo a cuerpo** por temblores. |
| **4** (Severo) | d6 | Desventaja en Constitución y ataques + **velocidad reducida a la mitad**. |
| **5** (Crítico) | d4 | Todos los anteriores + **daño automático de 1d4 al inicio de cada turno** (ácido interno). |
| **6** (Muerte) | — | El personaje **muere**. Solo puede ser revivido con magia poderosa (ej. *Resurrección*). |

---

## 🎲 Mecánica de empeoramiento

Al final de cada turno del personaje (o cada minuto/ronda fuera de combate):

1. Tira el dado correspondiente a su nivel actual.
2. Si saca **1 o 2**, el nivel de envenenamiento **aumenta en 1** (hasta nivel 6 = muerte).
3. Si el nivel aumenta, el dado para futuras tiradas cambia al del nuevo nivel.

> ⚠️ El empeoramiento solo ocurre si no se recibe tratamiento (antídoto, conjuro *Purificar comida y bebida*, etc.).

---

## 🧴 Formas de contraerlo

### Envenenamiento **leve** (dado inicial d12)
- Fallar una salvación contra veneno débil.
- Comida en mal estado.
- Picadura de insecto venenoso menor.
- Exposición prolongada a toxinas ambientales leves.

### Envenenamiento **grave** (dado inicial d8)
- Muerdedura de criatura letal (ej. serpiente enorme).
- Fracaso crítico en salvación contra veneno potente.
- Veneno de asesino aplicado directamente.
- Toxina mágica o alquímica concentrada.

---

## 🩹 Curar el envenenamiento

- **Nivel 1 a 3:** Antídoto común o conjuro de 1° nivel (*Purificar comida y bebida*, *Restablecer menor*) reduce 1 nivel.
- **Nivel 4 a 5:** Requiere *Restablecer mayor* o antídoto raro (reduce 1 nivel por dosis).
- **Nivel 6 (Muerte):** Solo *Resurrección*, *Deseo*, o un *Toque de la muerte revertido* (CD 20 en Sanación).

> 🎲 También se puede intentar una prueba de **Constitución CD 15** al recibir tratamiento para bajar 2 niveles de una vez.

---
Perfecto. Tomando tu sistema de **progresión de dados** (d12 → d10 → d8 → d6 → d4 → muerte) y adaptándolo al concepto de **Ensangrentado** (pérdida activa de sangre), más las reglas de heridas críticas que me has proporcionado, aquí tienes la condición completa.

---

## 🩸 Condición: Ensangrentado

**Ensangrentado** representa una hemorragia activa no controlada. Es **progresiva**: al final de cada turno del afectado, tira un dado. Si saca **1 o 2**, el nivel de sangrado aumenta.

El dado de empeoramiento depende del nivel actual de Ensangrentado.

---

### 📊 Niveles de Ensangrentado

| Nivel | Dado | Efecto |
|-------|------|--------|
| **0** (Normal) | — | Sin sangrado. |
| **1** (Leve) | d12 | Al final de tu turno, recibes **daño necrótico = 1d4** (pérdida de sangre). |
| **2** (Moderado) | d10 | Daño necrótico = **1d6** al final del turno. Desventaja en pruebas de Constitución. |
| **3** (Grave) | d8 | Daño necrótico = **1d8** + desventaja en Constitución y **ataques**. |
| **4** (Severo) | d6 | Daño necrótico = **1d10** + desventaja + **velocidad reducida a la mitad**. |
| **5** (Crítico) | d4 | Daño necrótico = **1d12** + todos los efectos anteriores + **no puedes recuperar vida** hasta detener la hemorragia. |
| **6** (Muerte) | — | Mueres por exanguinación al inicio de tu turno si no te han estabilizado antes. |

> 💡 El daño necrótico es **acumulativo por ronda** y no requiere ataque; es automático al final del turno.

---

## 🎲 Mecánica de empeoramiento

Al final del turno del personaje (en combate) o cada minuto fuera de combate:

1. Tira el dado de su nivel actual de Ensangrentado.
2. Si saca **1 o 2**, el nivel **aumenta en 1** (hasta 6 = muerte).
3. Al subir de nivel, el dado para futuras tiradas cambia al del nuevo nivel.

> 🛑 Si el personaje recibe **curación mágica** o un **Kit de Sanador** (acción completa, CD 15 Medicina), el nivel baja en 1.

---

## ⚔️ Cómo se adquiere Ensangrentado

No todo sangrado empieza igual. Según el tipo de daño recibido, el **dado inicial** cambia:

### 🩸 Inicio leve (dado d12)
- Recibir daño superior a la **mitad de tus puntos de golpe restantes** (pero sin llegar a 0).
- Herida menor no tratada.
- Ejemplo: Tienes 30 PG, recibes 16 de daño → empiezas con sangrado leve (d12).

### 🩸 Inicio grave (dado d8)
- Sufrir una **herida crítica** (según tus reglas: daño restante tras llegar a 0 supera Umbral de Herida).
- Recibir un **ataque crítico** mientras estás **Ensangrentado** o con menos del 50% PG.
- Ejemplo: Umbral 14, recibes 18 daño con 0 Vigor → herida crítica + sangrado grave (d8).

### 🩸 Inicio masivo (dado d6)
- Sufrir un **golpe masivo** (daño superior al doble de tu Umbral de Herida aunque tengas PG).
- Sufrir un **fallo crítico en tirada de muerte** (1 natural o fallo por 5+).
- Ejemplo: Umbral 14, recibes 30 daño de un solo golpe → sangrado masivo (d6).

---

## 🧬 Deriva a lesión supurante (infección)

Si el personaje termina un **descanso prolongado** (8 horas) sin haber detenido el sangrado (nivel 1 o superior), la herida **supura**:

1. **Síntomas automáticos**:
   - Fiebre: desventaja en todas las tiradas.
   - Daño continuo: 1 punto de daño necrótico por hora.
   - Propagación: cada día sin tratamiento, el nivel de Ensangrentado **sube 1 automáticamente** (sin tirar dado).

2. **Curación de la supuración**:
   - Tirada de Medicina CD 15 (requiere Kit de Sanador o kit de herborista).
   - Éxito: detiene la infección, el sangrado baja a nivel 1 si estaba superior.
   - Fracaso: la lesión empeora un grado de severidad (según tus tablas: leve → moderada → severa → mortal).

---

## 🩹 Curación y estabilización

### Estabilización básica (acción completa, sin magia)
- **CD 12 Medicina**: detiene el empeoramiento durante 1 minuto (no baja nivel, solo evita tirar dado).
- **CD 15 Medicina con Kit de Sanador**: reduce el nivel de Ensangrentado en 1.

### Curación mágica
- Cualquier conjuro que cure vida (ej. *Curar heridas*) reduce el nivel de Ensangrentado en 1 por cada 5 PG curados.
- *Restablecer menor* estabiliza automáticamente (no baja nivel, pero evita empeorar 1 hora).

### Cirugía (para niveles 4 o 5)
- Necesaria si el sangrado supera nivel 3.
- Tirada de Medicina CD 20, 10 minutos, Kit de cirugía.
- Éxito: baja 2 niveles.
- Fracaso: sube 1 nivel.

---

## 🔁 Reapertura de lesión sangrante

Si una herida **ya cerrada** (nivel 0 durante al menos un descanso largo) recibe daño contundente o perforante antes de curar completamente:

1. Vuelve al nivel de sangrado **1** automáticamente.
2. Recibe 1 herida crítica adicional.
3. Tirada de Constitución CD 15:
   - Éxito: solo eso.
   - Fracaso: el nivel de sangrado **sube 1 adicional** (nivel 2 directamente).

---

## 📝 Ejemplo práctico

> **Grok** (CON +2, Umbral 14, PG 30) recibe un golpe masivo de 30 daño → empieza con **Ensangrentado nivel 1 (d12)**.
>
> - Ronda 1: tira d12 → saca 2 → sube a nivel 2. Recibe 1d6 daño necrótico.
> - Ronda 2: tira d10 → saca 1 → sube a nivel 3. Recibe 1d8.
> - Ronda 3: un aliado usa Kit de Sanador (CD 15, éxito) → baja a nivel 2.
> - Ronda 4: tira d10 → saca 6 → no empeora.
> - Descanso largo sin curar → la herida supura: desventaja + daño por hora.

---
Perfecto. Partiendo de la mecánica de **progresión por dados** (d12 → d10 → d8 → d6 → d4) que ya usaste para *Envenenado* y *Ensangrentado*, más la información de *Heridas críticas* (PDF) y la descripción en inglés que me diste, aquí tienes la condición **Quemado** completamente adaptada.

---

## 🔥 Condición: Quemado

**Quemado** representa el daño por fuego en la piel, tejidos y sistemas corporales. Es **progresivo**: al final de cada turno (o cada hora fuera de combate), tiras un dado. Si sacas **1 o 2**, el nivel de quemado aumenta.

El dado usado depende de tu nivel actual.

> ⚠️ **Inmunidad al fuego:** Inmune a esta condición.  
> **Resistencia al fuego:** Necesitas recibir **1/4 más** de daño por fuego para alcanzar cada nivel (ver tabla al final).

---

## 📊 Niveles de Quemado

| Nivel | Nombre | Dado de empeoramiento | Efectos |
|-------|--------|----------------------|---------|
| **0** | Sin quemaduras | — | Sin efectos. |
| **1** | **Primer grado** (leve) | d12 | Piel enrojecida o rosada intensa. <br> • Desventaja en tu **próxima tirada de ataque**. <br> • Desventaja en **pruebas de Carisma**. |
| **2** | **Segundo grado** (moderado) | d10 | Piel roja con **ampollas**. <br> • Desventaja en **tiradas de salvación de Destreza**. <br> • Desventaja en **pruebas de Destreza**. <br> • **Velocidad reducida a la mitad**. |
| **3** | **Tercer grado** (grave) | d8 | Piel **carbonizada negra**. <br> • Todos los efectos anteriores. <br> • Al recibir este nivel: tira **Constitución CD 15** (o CD del hechizo/fuente). <br> &nbsp;&nbsp; → **Fallo:** Caes **inconsciente** durante 1 hora (tumbado boca abajo). <br> &nbsp;&nbsp; → **Éxito:** No quedas inconsciente, pero tienes desventaja en todas las tiradas mientras tengas este nivel. |
| **4** | **Cuarto grado** (severo) | d6 | Daño a **músculo y hueso**. <br> • Todos los efectos anteriores. <br> • **Desventaja en todas las tiradas de salvación**. <br> • **No puedes recuperar PG por descanso corto**. |
| **5** | **Quinto grado** (crítico) | d4 | Carbonización profunda, riesgo de shock sistémico. <br> • Todos los efectos anteriores. <br> • **Daño automático de 1d6 de fuego al inicio de tu turno** (tejido necrosado). <br> • **Desventaja en tiradas de muerte**. |
| **6** | **Sexto grado** (muerte por fuego) | — | El personaje **muere** carbonizado. Solo puede revivir con magia poderosa (*Resurrección*, *Deseo*). |

---

## 🎲 Mecánica de empeoramiento

Al final de cada **turno** (en combate) o cada **hora** (fuera de combate):

1. Tira el dado correspondiente a tu nivel actual.
2. Si sacas **1 o 2**, subes 1 nivel de quemado (hasta nivel 6).
3. Si subes de nivel, el dado cambia al del nuevo nivel.

> 🔥 **Fuentes externas de empeoramiento:** Si recibes **daño de fuego adicional** mientras ya estás quemado, tira el dado de empeoramiento inmediatamente (sin esperar al final del turno).

---

## 🧨 Cómo se adquiere la condición Quemado

Se basa en el **porcentaje de tus PG máximos** perdidos **solo por daño de fuego** en un solo ataque o acumulado en menos de 1 minuto.

### Ejemplo con 100 PG máximos:

| Daño por fuego recibido | Nivel de quemado |
|------------------------|------------------|
| 25 (1/4) | Nivel 1 (d12) |
| 50 (1/2) | Nivel 2 (d10) |
| 75 (3/4) | Nivel 3 (d8) |
| 100 (total) | Nivel 4 (d6) |
| 125 (más del total) | Nivel 5 (d4) |

> ⚠️ Si recibes suficiente daño para saltarte niveles, empiezas directamente en el nivel más alto correspondiente.  
> *Ejemplo:* 100 PG, recibes 60 de fuego → empiezas en **nivel 2** (porque 50 es 1/2), pero con el dado de nivel 2 (d10).

---

## 🧴 Subtipos de inicio según gravedad (opcional)

| Tipo de quemadura | Dado inicial | Condición equivalente | Daño recibido |
|------------------|--------------|----------------------|----------------|
| **Quemadura leve** | d12 | Primer grado | 1/4 de PG máximos |
| **Quemadura mediana** | d8 | Segundo grado | 1/2 de PG máximos |
| **Quemadura grave** | d6 | Tercer grado o más | 3/4 o más de PG máximos |

---

## 🩹 Curación del estado Quemado

### Por magia:
- Cada **1/4 de tus PG máximos** que cure un hechizo de curación **reduce 1 nivel de quemado**.
- *Ejemplo:* 100 PG máximos, curas 30 PG → reduces 1 nivel (porque 25 = 1/4).
- *Restablecer menor* → elimina 1 nivel.
- *Restablecer mayor* → elimina **todos** los niveles.

### Por medios naturales:
- **Descanso largo** + haber comido y bebido → reduces 1 nivel por cada descanso.

### Por cuidados médicos (del PDF de Heridas críticas):
- **Medicina CD 15** + kit de sanador → detiene la progresión durante 1 día.
- **Cirugía** necesaria para niveles 4 o 5.

---

## 🧟‍♂️ Si no tratas las quemaduras → Lesiones (según tu PDF)

| Quemadura no tratada | Deriva en (del PDF) |
|---------------------|----------------------|
| Nivel 1 (leve) sin tratar 24h | **Lesión leve** (infección local) |
| Nivel 2 (mediana) sin tratar 24h | **Lesión moderada** (supuración) |
| Nivel 3+ (grave) sin tratar 12h | **Lesión grave o mortal** (necrosis, sepsis) |

> 🔁 Esto conecta directamente con tu sistema de *Heridas críticas*: una quemadura mal curada puede abrirse, infectarse o requerir cirugía.

---

## 🔥 Resistencia al fuego (regla especial)

Si una criatura tiene **resistencia al daño de fuego**, necesita **1/4 más de daño** para alcanzar cada nivel.

### Ejemplo con 100 PG máximos y resistencia al fuego:

| Daño por fuego recibido | Nivel de quemado real |
|------------------------|----------------------|
| 25 (1/4) | **Ninguno** (necesitas 31 para nivel 1) |
| 31 | Nivel 1 |
| 62 | Nivel 2 |
| 93 | Nivel 3 |

> 🛡️ **Inmunidad al fuego:** Ignora completamente la condición.

---
# Agotamiento
Es progresivo
## Agotamiento leve

Representa fatiga temporal que se acumula fácilmente pero también se recupera con descansos breves.

**Causas:**

- Combate prolongado (después de cierto número de rondas).
- Falta de descanso adecuado.
- Acciones físicas exigentes, como escalar o correr largas distancias.

| **Nivel**  | **Efectos** |
| --- | --- |
| 1 | [Desventaja] en tiradas de habilidad de habilidad de FUE y DES
No puedes usar la acción [Correr] |
| 2 | [Desventaja] en todas las tiradas de habilidad.
Tu [velocidad] se reduce a la mitad.  |
| 3 | [Desventaja] en tiradas de ataque y salvación. |

## Agotamiento severo

Representa un estado crítico de desgaste que es difícil de revertir.

**Causas:**

- Ignorar el agotamiento leve y continuar con actividades extenuantes.
- Falta de comida, agua o sueño por períodos prolongados.
- Condiciones ambientales extremas.

| Nivel  | Efecto |
| --- | --- |
| 4 | Solo puedes realizar una [acción] o una [acción bono] por turno (no ambas).
No puedes tomar [reacciones].
Capacidad reducida para [concentrarte]en tareas. |
| 5 | [Velocidad] reducida a 5 pies 
No puedes [concentrarte] en hechizos o habilidades.
Visión borrosa, vértigo o alucinaciones (a discreción del DM). |
| 6 | Estás [Inconsciente] y comienzas a realizar [salvaciones de muerte] |

## Ignorar el Agotamiento

Si decides ignorar los efectos del agotamiento leve y continuar exigiéndote físicamente. **Haces una tirada de salvación de Constitución (CD 10 + niveles de agotamiento):**

- **Éxito:** Puedes completar la tarea, pero ganas 1 nivel adicional de agotamiento leve.
- **Fallo:** Ganas 1 nivel de agotamiento severo.



Un guerrero con 2 niveles de agotamiento leve quiere correr durante el combate. La CD es 12 (10 + 2). Si falla, pasa al nivel 4 (agotamiento severo).


## Exceso de agotamiento leve

Cuando alcanzas el **máximo nivel de agotamiento leve (Nivel 3)** y continúas exigiéndote. Cada nivel adicional de agotamiento leve:

- Se convierte en **agotamiento severo (Nivel 4+).**
- Esto refleja que tu cuerpo está más allá de sus límites.

---

### **Asustado (Leve)**  

- **Pruebas de característica y ataques afectados.** Una criatura asustada tiene desventaja en las tiradas de Ataque y de Pruebas de Característica mientras la fuente de su miedo esté a la vista.  
- **No se puede acercar.** La criatura no puede acercarse voluntariamente a la fuente de su miedo.  

---

### **Aterrorizado**  
Una criatura **aterrorizada** sufre todos los efectos de **Asustado**, más los siguientes:

- **Parálisis por miedo.** Al inicio de su turno, debe superar una tirada de salvación de SAB (CD igual a la del efecto original) para poder actuar. Si falla, solo puede usar su movimiento para huir (sin acciones).  
- **No puede hablar ni realizar acciones complejas.** Solo puede gritar, correr o temblar.  
- **Vulnerable a ataques mentales.** Tiene desventaja en tiradas de salvación contra efectos que causen miedo o psíquico.  

---

### **Ofuscado**  
- **Visión reducida.** Tienes desventaja en las pruebas de Sabiduría (Percepción) que dependen de la vista.  
- **No puedes ver con claridad.** Cualquier efecto que requiera ver un detalle fino (como leer o identificar un rostro) tiene desventaja o es imposible a criterio del DM.  

---

### **Cegado**  
Una criatura **cegada** sufre todos los efectos de **Ofuscado**, más los siguientes:

- **No puedes ver.** Fallas automáticamente las pruebas de característica que requieren visión.  
- **Velocidad reducida.** Tu velocidad se reduce a la mitad.  
- **Ataques contra ti con ventaja.** Las tiradas de ataque contra ti tienen ventaja si tu oponente puede verte.  
- **Tus ataques con desventaja.** Tus tiradas de ataque tienen desventaja.  
- **Sin magia visual.** No puedes lanzar hechizos ni usar efectos que requieran que veas al objetivo.  
- **No puedes detectar escondidos.** No puedes seleccionar activamente criaturas que se hayan escondido de ti (como con la acción de Esconderse).  

---

### **Estupefacto**  
- **Mente nublada.** Tienes desventaja en las tiradas de salvación de Inteligencia.  
- **Reflejos lentos.** No puedes realizar ataques de oportunidad.  

---

### **Desquiciado**  
Una criatura **desquiciada** sufre todos los efectos de **Estupefacto**, más los siguientes:

- **Confusión mental.** Al inicio de tu turno, tira un d6 para determinar tu acción:
  - **1-2:** No realizas ninguna acción ni reacción en este turno. Balbuceas sin sentido.
  - **3-4:** Usas tu acción para atacar a la criatura más cercana a ti (elige al azar si hay empates).
  - **5-6:** Actúas con normalidad, pero con desventaja en todas las tiradas de ataque y salvación.
- **Pérdida de concentración.** Fallas automáticamente cualquier tirada de salvación de Constitución para mantener la concentración.

---

### **Enloquecido**  

Una criatura **enloquecida** sufre todos los efectos de **Desquiciado**, más los siguientes:

- **Pérdida de identidad.** No recuerdas quién eres ni quiénes son tus aliados. Consideras a todas las criaturas como potenciales amenazas o irrelevantes (el DM determina tu comportamiento básico, típicamente errático o agresivo aleatorio).
- **No puedes lanzar hechizos ni usar habilidades que requieran concentración o pensamiento lógico.** Solo puedes realizar acciones instintivas (golpear, huir, gritar).
- **Vulnerabilidad psíquica.** Tienes desventaja en todas las tiradas de salvación de Sabiduría e Inteligencia.
- **Al final de tu turno**, si recibiste daño psíquico durante el turno, debes superar una tirada de salvación de SAB (CD igual a la del efecto original) o quedas **inconsciente** durante 1 minuto (o hasta recibir daño).

---

### Incapacitado
*(Condición escalonada previa)*

- **Inactivo.** No puedes realizar ninguna acción, acción de bonificación ni reacción.
- **Sin concentración.** Tu concentración se ha roto.
- **Sin palabras.** No puedes hablar.
- **Sorprendido.** No puedes ir primero en la iniciativa de combate.

---

### Aturdido
Una criatura **aturdida** sufre todos los efectos de **Incapacitado**, más los siguientes:

- **Movimiento restringido.** Tu velocidad se reduce a la mitad (redondeando hacia abajo al múltiplo de 5 más cercano).
- **Percepción borrosa.** Tienes desventaja en las pruebas de Sabiduría (Percepción) y en las tiradas de salvación de Destreza.
- **Solo acciones instintivas.** Puedes moverte (con la velocidad reducida), pero no puedes realizar ninguna acción que requiera pensamiento complejo (como lanzar hechizos, usar objetos mágicos, o realizar ataques especiales).
- **Sin reacciones.** No puedes realizar reacciones (esto ya está incluido en Incapacitado, pero se refuerza).

---

### Inconsciente
*(Escalón 2: cuando fallas la tirada de salvación de CON estando ya Aturdido)*

Una criatura **inconsciente** sufre todos los efectos de **Aturdido**, más los siguientes:

- **Postrado.** Caes al suelo, quedando tumbado y soltando todo lo que tengas en las manos.
- **Indefenso.** Las tiradas de ataque contra ti tienen ventaja. Si un atacante está a 5 pies de ti, cualquier golpe que impacte es un crítico (si el atacante no está también incapacitado).
- **Sin percepción.** No eres consciente de tu entorno. Fallas automáticamente cualquier prueba de característica que requiera percepción o consciencia.
- **No puedes moverte.** Tu velocidad es 0 y no puedes levantarse hasta que la condición termine.
- **Despertar.** La condición termina si recibes daño o si una criatura usa su acción para sacudirte o darte una poción curativa (u otro efecto similar a criterio del DM).

---

### Marchito
*(Condición pasajera)*

- **Cicatrización detenida.** No puedes recuperar puntos de vida ni recibir curación de ningún tipo (mágica o no mágica) mientras dure esta condición.
- **Herida supurante.** Cualquier efecto que intente restaurarte puntos de vida falla automáticamente y el recurso (como el espacio de conjuro o la poción) se gasta sin efecto.
- **Sin estabilización automática.** Si caes a 0 puntos de vida mientras estás marchito, no te estabilizas por medios naturales; debes superar tus tiradas de salvación contra la muerte normalmente.

**Duración.** La condición marchito es pasajera y termina automáticamente después de un descanso prolongado (8 horas) o si la criatura recibe el beneficio de un hechizo de *Restablecimiento menor* o similar.

**Cómo terminar la condición (formas no mágicas).** Existen métodos simples para poner fin a esta condición sin necesidad de magia:
- **Esparcir plata molida sobre la herida.** Una criatura puede usar su acción para aplicar plata en polvo (valor de al menos 5 po) sobre la herida que causa la condición. Al hacerlo, la condición marchito termina inmediatamente.
- **Aplicar fuego cauterizante.** Si una criatura recibe al menos 1 punto de daño por fuego en la zona afectada (como con un hierro al rojo vivo o una llama directa), la condición termina al recibir el daño.
- **Lavado con agua bendita.** Verter un frasco de agua bendita (25 po) sobre la herida termina la condición sin necesidad de tirada.
---

### Corroído
*(Condición pasajera)*

- **Armadura debilitada.** La criatura u objeto corroído tiene una penalización de -1 a su Clase de Armadura (CA).
- **Acumulable.** Si una criatura u objeto recibe la condición Corroído múltiples veces, la penalización se acumula (hasta un máximo de -5 a la CA). Cada aplicación tiene su propia duración, pero todas terminan simultáneamente si se neutraliza la corrosión.

**Duración.** La condición Corroído es pasajera y termina automáticamente después de 1 minuto (10 rondas) si no se ha neutralizado antes.

**Cómo terminar la condición (formas simples no mágicas).** Existen métodos sencillos para poner fin a esta condición sin necesidad de magia:
- **Rodar por el suelo.** Como acción, puedes neutralizar la corrosión tirándote al suelo y rodando. Al hacerlo, adquieres la condición **Tumbado** (Prone) y la condición Corroído termina inmediatamente.
- **Estar mojado.** Si ya estás mojado (por ejemplo, por agua, lluvia, o haber estado en un líquido) al recibir la condición, esta se neutraliza automáticamente. Sumergirse en agua o mojarse a propósito también termina la condición.
- **Arenado o frotamiento con tierra.** Como acción, puedes frotarte con arena, tierra o un paño áspero para eliminar la corrosión, sin necesidad de tumbarte (a discreción del DM).

---

### Mojado
*(Condición pasajera)*

- **Vulnerabilidad energética.** Tienes desventaja en las tiradas de salvación contra daño por Relámpago y Frío.
- **Conductor de electricidad y frío.** Las criaturas que te infligen daño por Relámpago o Frío tienen ventaja en sus tiradas de ataque contra ti.
- **Daño mínimo asegurado.** Las tiradas de daño por Relámpago o Frío que obtengan un resultado de 1, 2 o 3 contra ti se tratan como un 4.
- **Protección contra el fuego.** Eres resistente al daño por Fuego mientras estás mojado.

**Duración.** La condición Mojado es pasajera y termina automáticamente después de 1 minuto (10 rondas) si no se ha neutralizado antes, o antes si entras en un entorno especialmente seco o cálido a criterio del DM.

**Cómo terminar la condición (formas simples no mágicas).** Existen métodos sencillos para poner fin a esta condición:
- **Secarse como acción.** Como acción, puedes secarte con una toalla, un paño, o frotándote con arena o tierra, terminando la condición inmediatamente.
- **Daño por fuego intenso.** Si recibes 10 o más puntos de daño por Fuego en un solo turno, el calor te seca por completo y la condición termina.
- **Exposición a calor extremo.** Permanecer junto a una fuente de calor intenso (como una hoguera grande o una fragua) durante 1 ronda completa también termina la condición, a discreción del DM.

---
Here is the description for the **Enfriado** condition, following the same format as **Asustado** and taking into account that it is temporary with simple, non-magical ways to end it.

---

### Enfriado
*(Condición pasajera)*

- **Entumecimiento corporal.** Tu velocidad se reduce a la mitad (redondeando hacia abajo al múltiplo de 5 más cercano).
- **Falta de coordinación.** Tienes desventaja en las tiradas de salvación de Fuerza y Destreza, así como en las pruebas de característica basadas en Fuerza o Destreza.
- **Tiritona incontrolable.** Cualquier movimiento o acción que requiera precisión física tiene desventaja (a criterio del DM, como realizar tareas de equilibrio, escalar o esquivar).

**Inmunidades.** Las criaturas inmunes o resistentes al daño por Frío y a los efectos de frío extremo no se ven afectadas por esta condición. Del mismo modo, las criaturas que no necesitan resistencia física para sus movimientos o acciones (como los seres incorpóreos o los constructos sin articulaciones) tampoco la padecen.

**Duración.** La condición Enfriado es pasajera y termina automáticamente después de 1 minuto (10 rondas) si no se ha neutralizado antes, o antes si entras en un ambiente cálido.

**Cómo terminar la condición (formas simples no mágicas).** Existen métodos sencillos para poner fin a esta condición sin necesidad de magia:
- **Calentarse como acción.** Como acción, puedes abrazarte a ti mismo envolviéndote los brazos alrededor del torso y frotándote para generar calor. Al hacerlo, adquieres la condición **Inmovilizado** (Grappled) contigo mismo (tu velocidad se reduce a 0 y no puedes realizar movimientos voluntarios) hasta el inicio de tu siguiente turno, pero la condición Enfriado termina inmediatamente.
- **Daño por fuego intenso.** Si recibes 10 o más puntos de daño por Fuego en un solo turno, el calor te reconforta y la condición termina.
- **Entorno cálido.** Entrar en un ambiente cálido (como junto a una chimenea, una fogata, o bajo el sol abrasador) durante 1 ronda completa también termina la condición.

---

### Agarrado
*(Condición pasajera)*

- **Velocidad 0.** Tu velocidad se vuelve 0 y no puedes beneficiarte de ninguna bonificación a tu velocidad.
- **Ataques entrantes con desventaja.** Los ataques que tengan como objetivo al agarrado tienen desventaja a menos que se use un arma Ligera o Natural.
- **Ataques salientes limitados.** Un agarrado tiene desventaja para atacar a criaturas que no lo estén agarrando.

**Cómo terminar la condición.** La condición termina automáticamente si:
- El agarrador queda **Incapacitado**.
- Un efecto retira al agarrado del alcance del agarrador o del efecto de Agarrar (como ser empujado, teletransportado o movido por la fuerza).
- El agarrado usa su acción para realizar una prueba de Fuerza (Atletismo) o Destreza (Acrobacias) contra la CD de agarre del agarrador, terminando la condición si tiene éxito.

**Inmovilizar (opción para el agarrador).** Si el agarrador tiene una Fuerza de 13 o más, puede gastar uno de sus ataques para hacer una prueba de Agarrar para **inmovilizar** a la criatura agarrada. Si tiene éxito, la criatura queda **Inmovilizada** por el agarrador. Si falla, el agarre se rompe y la criatura agarrada puede usar su reacción para realizar un ataque de oportunidad contra el agarrador.

---
## Electrificado
*(Condición pasajera)*
- **Parálisis muscular.** Tu velocidad se reduce a la mitad (redondeando hacia abajo al múltiplo de 5 más cercano).
- **Espasmos incontrolables.** Tienes desventaja en las pruebas de característica, tiradas de ataque y tiradas de salvación que utilicen Fuerza, Destreza o Constitución.
- **Objetos metálicos peligrosos.** Si sostienes un objeto metálico (como un arma o armadura), cualquier criatura que te toque o te golpee con un arma metálica debe superar una tirada de salvación de Constitución (CD 12) o recibir 1d4 de daño por Eléctrico y quedar Electrificada hasta el final de su siguiente turno.

**Duración.** La condición Electrificado es pasajera y termina automáticamente después de 1 minuto (10 rondas) si no se ha neutralizado antes.

**Cómo terminar la condición (formas simples no mágicas).** Existen métodos sencillos para poner fin a esta condición:

- **Ponerse a tierra.** Como acción, puedes tocar el suelo con ambas manos o soltarte el contacto con el metal. La condición termina inmediatamente al inicio de tu siguiente turno si permaneces en contacto con el suelo.
- **Sumergirse en agua.** Sumergirte completamente en agua no conductora (como agua destilada o pura) termina la condición. Sin embargo, sumergirte en agua normal puede transmitir la electricidad a otras criaturas cercanas (a discreción del DM).
- **Recibir daño por frío o tierra.** Recibir al menos 5 puntos de daño por Frío o por impacto de tierra (como una avalancha o un golpe de roca) neutraliza la electricidad estática y termina la condición.

**Inmunidades.** Las criaturas inmunes al daño por Relámpago, las que no tienen un sistema nervioso (como los constructos o no muertos sin músculos) y las que flotan o no tocan el suelo no se ven afectadas por esta condición.
---
## Encantado
*(Condición pasajera)*

- **No puedes dañar al encantador.** No puedes atacar al encantador ni utilizar habilidades dañinas o efectos mágicos que tengan como objetivo al encantador.
- **Ventaja social.** El encantador tiene ventaja en cualquier prueba de habilidad para interactuar socialmente contigo (como Persuasión, Engaño o Intimidación).

**Duración.** La condición Encantado es pasajera y termina automáticamente después de 1 minuto (10 rondas) si no se ha neutralizado antes, o antes si el encantador o sus aliados te atacan o te infligen daño.

**Cómo terminar la condición (formas simples no mágicas).** Existen métodos sencillos para poner fin a esta condición sin necesidad de magia:

- **Recibir daño del encantador o sus aliados.** Si el encantador o cualquier aliado suyo te ataca o te inflige daño, la condición termina inmediatamente.
- **Daño autoinfligido.** Como acción, puedes infligirte daño a ti mismo (como morderte el labio o clavarte una aguja). Si te infliges al menos 1 punto de daño, superas el encantamiento y la condición termina.
- **Estímulo extremo.** Ser salpicado con agua fría, recibir un fuerte azote o cualquier otro estímulo violento a discreción del DM puede terminar la condición.

**Inmunidades.** Las criaturas inmunes al estado encantado (como los elfo por su ascendencia feérica o ciertos no muertos) no se ven afectadas por esta condición.
---
## Estable
*(Condición pasajera)*

- **Sin peligro inmediato.** Tienes 0 puntos de golpe, pero no estás obligado a realizar tiradas de salvación de muerte.
- **Incapacitado pero vivo.** Permaneces **Incapacitado** y no puedes realizar acciones, reacciones ni moverte, pero no empeorarás tu estado por ti mismo.
- **No empeora.** No pierdes tiradas de salvación de muerte ni corres riesgo de morir a menos que recibas daño nuevamente.

**Cómo termina la condición.** La condición Estable termina automáticamente si ocurre cualquiera de las siguientes situaciones:

- **Recibir daño.** Si recibes cualquier cantidad de daño mientras estás Estable, vuelves a tener 0 puntos de golpe y debes retomar las tiradas de salvación de muerte desde cero (con cualquier fallo acumulado previamente si el DM lo determina).
- **Recibir curación.** Si recuperas al menos 1 punto de golpe (por magia, una poción, o la habilidad de estabilización de otro), la condición termina y recuperas el conocimiento si tus puntos de golpe superan 0.
- **Descanso breve.** Tras 1d4 horas de estar Estable sin recibir daño, recuperas 1 punto de golpe naturalmente y la condición termina (aunque sigues **Incapacitado** hasta que completes un descanso corto o tengas más de 0 PG).
- **Atención médica.** Una criatura puede usar su acción para realizar una prueba de Sabiduría (Medicina) CD 10. Si tiene éxito, puede despertarte inmediatamente con 1 punto de golpe (una vez por descanso corto por criatura)
---
## Inmovilizado
*(Condición pasajera)*

- **Velocidad 0.** Tu velocidad se convierte en 0 y no puedes beneficiarte de ninguna bonificación a tu velocidad.
- **Ataques entrantes con ventaja.** Las tiradas de ataque contra ti tienen ventaja.
- **Ataques salientes con desventaja.** Tus tiradas de ataque tienen desventaja.
- **Reflejos afectados.** Tienes desventaja en las tiradas de salvación de Destreza.

**Cómo terminar la condición.** La condición Inmovilizado termina automáticamente si ocurre cualquiera de las siguientes situaciones:

- **El inmovilizador queda incapacitado.** Si la criatura o efecto que te inmoviliza queda **Incapacitado**, la condición termina.
- **Movimiento forzado.** Si un efecto te mueve fuera del alcance o de la sujeción que te inmoviliza (como ser empujado o teletransportado), la condición termina.
- **Prueba de fuerza o destreza.** Como acción, puedes realizar una prueba de Fuerza (Atletismo) o Destreza (Acrobacias) contra la CD de inmovilización de la fuente. Si tienes éxito, la condición termina.
- **Ayuda externa.** Otra criatura puede usar su acción para ayudarte a liberarte, permitiéndote realizar una nueva prueba de Fuerza o Destreza con ventaja para terminar la condición.

**Inmunidades parciales.** Las criaturas que no pueden ser agarradas o inmovilizadas por medios físicos (como seres incorpóreos, elementales de aire, o criaturas con forma amorfa) no se ven afectadas por esta condición a menos que el efecto especifique lo contrario.
---
## Invisible
*(Condición pasajera)*
- **Sorpresa.** Si eres invisible cuando empiezas un combate, empiezas primero en la iniciativa.
- **Oculto.** No te afecta ningún efecto que requiera que su objetivo sea visto, a menos que el creador del efecto pueda verte de alguna manera. Cualquier equipo que lleves puesto o que lleves contigo también está oculto.
- **Ataques entrantes con desventaja.** Las tiradas de ataque contra ti tienen desventaja.
- **Ataques salientes con ventaja.** Tus tiradas de ataque tienen ventaja.
- **Limitación.** Si una criatura puede verte de alguna manera (como mediante visión verdadera, vista ciega, o habilidades especiales), no obtienes los beneficios de esta condición contra esa criatura.

**Duración.** La condición Invisible es pasajera y termina automáticamente si ocurre cualquiera de las siguientes situaciones:

- **Atacar o lanzar un hechizo.** Si realizas una tirada de ataque o lanzas un hechizo que afecte a un objetivo, la invisibilidad termina inmediatamente después del ataque o del lanzamiento.
- **Recibir daño.** Si recibes daño de cualquier tipo, la invisibilidad termina.
- **Realizar una acción que rompa la invisibilidad.** Algunas acciones específicas (como agarrar a alguien o abrir una puerta de forma ruidosa) pueden terminar la invisibilidad a criterio del DM.

**Cómo terminar la condición (formas adicionales).** Existen métodos para poner fin a esta condición sin necesidad de magia:

- **Ser salpicado.** Si te arrojan un líquido (agua, tinta, aceite, etc.) y este se adhiere a ti, la invisibilidad termina mientras permanezcas cubierto.
- **Cubrirse de polvo o harina.** Ser cubierto por una fina capa de polvo, harina o cualquier sustancia que se adhiera a tu cuerpo revela tu silueta y termina la condición.
- **Contacto con superficies reveladoras.** Pisar barro, nieve, pintura fresca o cualquier superficie que deje rastro visible puede terminar la invisibilidad a discreción del DM.
## Paralizado
*(Condición pasajera)*

- **Incapacitado.** Tienes la condición de **Incapacitado**. No puedes realizar acciones, acciones de bonificación ni reacciones.
- **Velocidad 0.** Tu velocidad es 0 y no puede aumentar.
- **Fallas automáticas.** Fallas automáticamente las tiradas de salvación de Fuerza y Destreza.
- **Ataques entrantes con ventaja.** Las tiradas de ataque contra ti tienen ventaja.
- **Golpes críticos automáticos.** Cualquier tirada de ataque que te impacte es un **golpe crítico** si el atacante está a 5 pies (1 casilla) o menos de ti.

**Duración.** La condición Paralizada es pasajera y termina automáticamente después de 1 minuto (10 rondas) si no se ha neutralizado antes.

**Cómo terminar la condición (formas simples no mágicas).** Existen métodos sencillos para poner fin a esta condición sin necesidad de magia:

- **Recibir daño contundente.** Si recibes al menos 10 puntos de daño contundente de un solo golpe, el impacto puede sacudir tu sistema nervioso y terminar la parálisis inmediatamente (a discreción del DM).
- **Estimulación extrema.** Ser salpicado con agua muy fría, recibir una descarga eléctrica leve (al menos 1 punto de daño por Relámpago), o ser quemado por fuego (al menos 1 punto de daño por Fuego) puede restaurar el movimiento.
- **Sacudida violenta.** Una criatura adyacente puede usar su acción para sacudirte violentamente. Debes superar una tirada de salvación de Constitución CD 15; si tienes éxito, la condición termina.
- **Masaje o frotamiento.** Como acción, una criatura puede frotar vigorosamente tus extremidades durante 1 minuto completo, terminando la condición al final de ese minuto.
---
## Cargado
*(Condición pasajera)*

- **Movimiento lastrado.** Tu velocidad se reduce a la mitad (redondeando hacia abajo al múltiplo de 5 más cercano).
- **Fatiga física.** Tienes desventaja en las pruebas de característica, tiradas de ataque y tiradas de salvación que utilicen Fuerza, Destreza o Constitución.
- **Sobresfuerzo.** Cualquier acción que requiera esfuerzo físico sostenido (como correr, nadar, escalar o saltar) requiere un gasto de movimiento doble del normal, a criterio del DM.

**Duración.** La condición Cargado es pasajera y termina automáticamente después de 1 minuto (10 rondas) si no se ha neutralizado antes.

**Cómo terminar la condición (formas simples no mágicas).** Existen métodos sencillos para poner fin a esta condición:

- **Soltar peso.** Como acción, puedes soltar o depositar el objeto o la carga que te está causando la condición. Si la fuente es una criatura que te está sujetando o una acumulación de objetos, terminas la condición inmediatamente al aligerar tu carga.
- **Descanso breve.** Si permaneces inmóvil y sin realizar acciones extenuantes durante 1 ronda completa (6 segundos), la condición termina al inicio de tu siguiente turno.
- **Recibir ayuda.** Una criatura adyacente puede usar su acción para ayudarte a redistribuir o aliviar tu carga. Si tiene éxito en una prueba de Fuerza (Atletismo) CD 12, la condición termina.
- **Hidratación o estímulo.** Beber agua fresca o recibir un estímulo frío (como agua helada o un viento fresco) puede aliviar la fatiga temporal y terminar la condición a discreción del DM.
---
## Tumbado
*(Condición pasajera)*

- **Movimiento restringido.** Tus únicas opciones de movimiento son arrastrarte (gastando 2 pies de movimiento por cada 1 pie que te mueves) o gastar una cantidad de movimiento igual a la mitad de tu velocidad (redondeada hacia abajo) para enderezarte y así terminar con la condición. Si tu velocidad es 0, no puedes enderezarte.
- **Ataques salientes con desventaja.** Tienes desventaja en las tiradas de ataque.
- **Ataques cuerpo a cuerpo entrantes con ventaja.** Una tirada de ataque contra ti tiene ventaja si el atacante está a 5 pies (1 casilla) o menos de ti.
- **Ataques a distancia entrantes con desventaja.** Si el atacante está a más de 5 pies de ti, la tirada de ataque contra ti tiene desventaja.

**Duración.** La condición Tumbado es pasajera y termina automáticamente cuando te enderezas usando tu movimiento, o si algún efecto te pone de pie (como la ayuda de otra criatura o magia).

**Cómo terminar la condición (formas simples).** Existen métodos sencillos para poner fin a esta condición:

- **Enderezarse.** Gastas una cantidad de movimiento igual a la mitad de tu velocidad. No requiere acción, solo movimiento.
- **Ayuda externa.** Una criatura adyacente puede usar su acción para ayudarte a ponerte de pie, terminando la condición sin que gastes movimiento.
- **Impulso o tirón.** Una criatura puede usar su acción para tirar de ti o empujarte a una posición erguida. Esto también termina la condición.
- **Rodar por una pendiente.** Si estás en una superficie inclinada, puedes rodar cuesta abajo y terminar la condición al final del movimiento, aunque posiblemente termines en otra ubicación (a discreción del DM).
---
## Ensordecido
*(Condición pasajera)*
- **Silencio total.** No puedes oír ningún sonido.
- **Fallo automático en pruebas auditivas.** Fallas automáticamente cualquier prueba de habilidad que requiera audición (como Percibir un susurro, identificar una dirección por el sonido, o escuchar una conversación a escondidas).
- **Limitación social.** No puedes comunicarte verbalmente de forma efectiva en entornos ruidosos o a distancia, ya que no puedes escuchar las respuestas ni calibrar tu propio volumen. Tienes desventaja en pruebas de Carisma que dependan de la comunicación oral (como Persuasión o Engaño) si la otra persona no se acerca lo suficiente o usa gestos.

**Duración.** La condición Ensordecido es pasajera y termina automáticamente después de 1 minuto (10 rondas) si no se ha neutralizado antes, o antes si la causa es un efecto temporal como una explosión cercana que desaparece gradualmente.

**Cómo terminar la condición (formas simples no mágicas).** Existen métodos sencillos para poner fin a esta condición:

- **Tapones o protección.** Si la sordera fue causada por un ruido extremo, usar tapones para los oídos o cubrirse los oídos firmemente durante 1 minuto puede permitir que el oído se recupere, terminando la condición.
- **Sonido de compensación.** Exponerte a un sonido constante y de baja intensidad (como un zumbido o un tono puro) durante 1 minuto puede "reiniciar" tu audición, terminando la condición a criterio del DM.
- **Limpieza de oídos.** Si la sordera es por obstrucción (cera, agua, suciedad), limpiarte los oídos con un paño suave o inclinar la cabeza para drenar líquidos termina la condición.
- **Masaje en la mandíbula.** Masajear suavemente la zona detrás de las orejas y la mandíbula durante 1 minuto puede aliviar la presión en el conducto auditivo y restaurar la audición.
- **Bostezar o tragar.** Realizar movimientos como bostezar forzadamente o tragar saliva repetidamente puede abrir las trompas de Eustaquio y terminar la sordera temporal.
---
## Petrificado
*(Condición persistente)*
- **onvertido en sustancia inanimada.** Te transformas, junto con cualquier objeto no mágico que lleves puesto o que lleves encima, en una sustancia inanimada sólida (normalmente piedra). Tu peso aumenta diez veces y dejas de envejecer.
- **Incapacitado.** Tienes la condición de **Incapacitado**. No puedes realizar acciones, acciones de bonificación ni reacciones.
- **Velocidad 0.** Tu velocidad es 0 y no puede aumentar.
- **Ataques entrantes con ventaja.** Las tiradas de ataque contra ti tienen ventaja.
- **Fallas automáticas.** Fallas automáticamente las tiradas de salvación de Fuerza y Destreza.
- **Resistencia al daño.** Tienes resistencia a todo daño.
- **Inmunidad al veneno.** Tienes inmunidad a la condición de **Envenenado**.

**Duración.** La condición Petrificado es **persistente**. No termina por sí sola con el paso del tiempo ni mediante métodos simples o descansos. Una vez aplicada, permanece indefinidamente hasta que sea eliminada por medios específicos.
---
## Moribundo
*(Condición persistente)*
- **Inerte.** Tienes las condiciones **Incapacitado** y **Tumbado**, y dejas caer todo lo que estés sosteniendo. Cuando esta condición termina, permaneces **Tumbado**.
- **Parcialmente consciente.** Estás consciente de lo que sucede a 15 pies (3 casillas) a tu alrededor. Puedes percibir sonidos, luces y movimientos en ese radio, pero no más allá.
- **Pocas palabras.** Puedes hablar un máximo de dos palabras por ronda (por ejemplo, "Ayuda" o "No...").
- **Debilitado.** Fallas automáticamente las tiradas de salvación de Fuerza y Destreza.
- **Tiradas de muerte.** Debes realizar una **tirada de muerte** al comienzo de tu turno. Si fallas tres tiradas de muerte, mueres. Si tienes éxito en tres, la condición **Moribundo** termina y pasas a estar **Estable** (pero sigues **Inconsciente**). Los éxitos y fracasos se reinician cuando te estabilizas o recuperas puntos de golpe.

**Duración.** La condición Moribundo es **persistente**. No termina por sí sola con el paso del tiempo ni mediante descansos. Una vez aplicada (al caer a 0 puntos de golpe sin estabilizarse), permanece activa hasta que ocurra una de las siguientes situaciones.