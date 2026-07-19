# Lanzamiento de conjuros

# 1- ¿Qué es un conjuro?

Un **conjuro** es una manifestación de energía mágica que produce un efecto sobrenatural en el mundo. Puede curar heridas, invocar llamas, manipular mentes o abrir portales a otros planos. Para lanzar un conjuro, el lanzador debe canalizar su **maná** (su reserva de energía mágica interna) y cumplir los requisitos del conjuro: su tiempo de lanzamiento, sus componentes y estar dentro del rango adecuado.

Cada conjuro tiene un **círculo** (del 0 al 9) que indica su potencia. Cuanto mayor es el círculo, más maná cuesta y más poderoso es su efecto.

## 🔮 Esferas de conjuro

Las **esferas** son categorías temáticas que agrupan los conjuros según el tipo de magia que representan. Cada lanzador aprende conjuros de las esferas que corresponden a su clase o a las que tiene acceso.

Existen **12 esferas** en total:

| Nombre | Temática |
| --- | --- |
| **Simbiosis** | Plantas, animales y capacidades bestiales |
| **Restauración** | Curación, mejora física y purificación |
| **Ruina** | Enfermedad, venenos, drenaje vital y no-muertos |
| **Cinética** | Energía pura, fuerza, glifos y efectos comodín |
| **Catálisis** | Líquidos, transmutación y cambios de estado |
| **Mente** | Control mental, daño psíquico y manipulación interna |
| **Espejismo** | Luz, oscuridad, ilusiones e invisibilidad |
| **Cénit** | Tierra, minerales, metales y gravedad |
| **Energía** | Fuego, electricidad, sonido y elementos violentos |
| **Destino** | Adivinación, suerte, protección y causalidad |
| **Origen** | Invocación de criaturas y creación de objetos |
| **Realidad** | Teletransporte, espacio, tiempo y dimensiones |

<aside>
💡

**Ejemplo:** Un clérigo centrado en curación usará principalmente la esfera de **Restauración**. Un mago destructor probablemente prefiera **Energía** o **Ruina**.

</aside>

## 🌀 Círculos de conjuro

Los **círculos de conjuro** representan la potencia de un hechizo. Funcionan como anillos concéntricos: los más exteriores son los más poderosos y requieren más nivel y más maná para lanzarse.

- El **Círculo 0** corresponde a los **trucos** (sin coste de maná).
- Los **Círculos 1 al 9** son conjuros que consumen maná.
- Los **Círculos 6 al 9** además conllevan riesgo de **agotamiento mágico**.

### Coste de maná por círculo

| Círculo | Coste de maná | Nivel mínimo para usarlo |
| --- | --- | --- |
| **Trucos (0)** | 0 | 1 |
| **1º** | 2 | 1 |
| **2º** | 3 | 3 |
| **3º** | 5 | 5 |
| **4º** | 6 | 7 |
| **5º** | 8 | 9 |
| **6º** | 9 | 11 |
| **7º** | 11 | 13 |
| **8º** | 12 | 15 |
| **9º** | 14 | 17 |

<aside>
💡

**Ejemplo:** Un mago de nivel 5 con 14 puntos de maná puede lanzar dos conjuros de 3er círculo (5 maná cada uno = 10) y dos de 1er círculo (2 maná cada uno = 4). Total: 14 maná, justo lo que tiene.

</aside>

## ✨ Puntos de maná

El **maná** es la energía mágica interna de un lanzador. Cada vez que lanza un conjuro, gasta una cantidad de maná según el círculo del hechizo. Cuando se queda sin maná, no puede lanzar más conjuros (salvo trucos, que son gratuitos).

### ¿Cómo se calcula el maná máximo?

```
Maná máximo = (Nivel de lanzador × 2) + Modificador del atributo de lanzamiento
```

<aside>
💡

**Ejemplo:** Un Mago de nivel 5 con Inteligencia 18 (modificador +4) tiene: (5 × 2) + 4 = **14 puntos de maná**.

</aside>

### Recuperación de maná

| Tipo de descanso | Maná recuperado |
| --- | --- |
| **Descanso corto** | La mitad del maná máximo (redondeado hacia abajo). El brujo lo recupera todo. |
| **Descanso largo** | Todo el maná |

## ⚠️ Agotamiento mágico

El **agotamiento mágico** es un sistema de riesgo que se activa cuando un lanzador utiliza conjuros de **Círculo 6 o superior**. Representa el peligro de canalizar energías mágicas extremadamente poderosas.

### ¿Cuándo ocurre?

| Círculo del conjuro | ¿Hay riesgo? |
| --- | --- |
| 1 al 5 | ❌ No |
| 6 al 9 | ✅ Sí |

### ¿Cómo funciona el dado de agotamiento?

Cada lanzador tiene un **dado de agotamiento** que empieza siendo un **d12**. Cuando lanza un conjuro de Círculo 6+, sigue estos pasos:

1. Gasta el maná del conjuro normalmente.
2. Tira su dado de agotamiento.
3. Si el resultado es **1 o 2** → ocurre agotamiento (tira en la tabla d100 para ver el efecto).
4. Si el resultado es **3 o más** → lanzamiento normal, sin consecuencias.

### El dado se degrada con el uso

Cada vez que sufres agotamiento, tu dado de agotamiento **baja un paso**:

```
d12 → d10 → d8 → d6 → d4
```

Esto hace que los futuros lanzamientos de alto círculo sean cada vez **más peligrosos**.

<aside>
💡

**Ejemplo:** Con un d12, tienes un ~16,7% de probabilidad de sufrir agotamiento. Con un d4, tienes un 50%.

</aside>

### Tabla de efectos del agotamiento (d100)

Cuando el dado de agotamiento da 1 o 2, tiras 1d100 y aplicas el resultado:

| d100 | Efecto |
| --- | --- |
| 01–05 | Pierdes (círculo del hechizo) dados de golpe permanentemente |
| 06–15 | Pierdes (círculo del hechizo ÷ 2) dados de golpe |
| 16–40 | Pierdes (círculo del hechizo × 4) puntos de golpe |
| 41–88 | Pierdes (círculo del hechizo × 2) puntos de golpe |
| 89–93 | Desventaja al lanzar conjuros durante (círculo del hechizo) rondas |
| 94 | Tu dado de agotamiento cae a d4 |
| 95 | Recuperas el coste de maná del conjuro |
| 96 | Recuperas (círculo del hechizo) dados de golpe |
| 97 | Ganas (círculo del hechizo × 4) puntos de golpe |
| 98 | Ganas (círculo del hechizo × 4) puntos de golpe temporales |
| 99 | Ventaja al lanzar conjuros durante (círculo del hechizo) rondas |
| 100 | Tu dado de agotamiento se restablece a d12 |

### ¿Cómo se recupera el dado de agotamiento?

| Método | Efecto |
| --- | --- |
| Descanso largo | **No** recupera el dado automáticamente |
| Resultado 100 en la tabla | Restablece el dado a d12 |
| Objetos mágicos raros | Pueden restaurar el dado |

## 🔄 Variantes de conjuros

Algunos conjuros tienen **versiones mejoradas** llamadas **variantes automáticas**. Estas versiones se desbloquean solas cuando el lanzador alcanza ciertos niveles. **No hace falta aprenderlas por separado.**

### ¿Cómo funcionan?

| Característica | Regla |
| --- | --- |
| **Desbloqueo** | Automático al alcanzar el nivel requerido |
| **Aprendizaje** | No requieren aprenderse por separado |
| **Coste** | Cuestan más maná según su círculo |
| **Disponibilidad** | Siempre disponibles si conoces el conjuro base |
| **Efecto** | Añaden efectos adicionales o mejoras al conjuro base |

### Ejemplo: El conjuro *Orbe de Escarcha*

| Versión | Nivel requerido | Coste | Efecto |
| --- | --- | --- | --- |
| Truco base | 1 | 0 maná | 1d8 de frío a un objetivo + reduce velocidad 10 pies |
| Variante 1er Círculo (*Bomba de Escarcha*) | 1 | 2 maná | 2d10 a todos en radio 5 pies (salvación de DES) |
| Variante 3er Círculo (*Tormenta de Escarcha*) | 5 | 5 maná | 4d8 a todos en radio 15 pies + terreno difícil + posible prone |
| Variante 5º Círculo (*Corazón de Invierno*) | 9 | 8 maná | 6d10 a todos en radio 20 pies + posible congelación |

<aside>
💡

**Regla clave:** Conocer un truco base te da acceso a todas sus variantes automáticamente cuando alcanzas el nivel necesario. Elegir cuál usar es una decisión táctica en cada combate.

</aside>

## 📚 Conjuros conocidos

Los **conjuros conocidos** son los hechizos que un personaje tiene "grabados en la memoria" de forma permanente y puede lanzar en cualquier momento sin necesidad de prepararlos.

El número de conjuros conocidos es **limitado y fijo** para cada nivel. Si un personaje quiere aprender un conjuro nuevo, normalmente debe **olvidar uno antiguo** al subir de nivel.

<aside>
💡

**Ejemplo:** Un bardo de nivel 3 puede conocer 6 conjuros. Si sube al nivel 4 y quiere aprender uno nuevo, puede sustituir uno de sus 6 conjuros actuales por el nuevo.

</aside>

## 📖 Conjuros preparados

Los **conjuros preparados** funcionan diferente a los conocidos. Los lanzadores que usan este sistema tienen acceso a una **lista completa** de hechizos de su clase, pero solo pueden usar cada día los que hayan preparado durante su descanso largo.

Este sistema es propio de clases que estudian o rezan para acceder a la magia, como:

- **Clérigo** (reza a su deidad cada mañana)
- **Druida** (sintoniza con la naturaleza)
- **Mago** (estudia su grimorio)
- **Paladín** (recibe sus conjuros mediante devoción)

### ¿Cuántos conjuros pueden prepararse?

El número de conjuros preparados suele calcularse así:

```
Conjuros preparados = Modificador del atributo de lanzamiento + Nivel de lanzador
```

<aside>
💡

**Ejemplo:** Un Clérigo de nivel 4 con Sabiduría 16 (modificador +3) puede preparar: 3 + 4 = **7 conjuros** al día.

</aside>

Cada día puede cambiar qué conjuros tiene preparados, lo que da mucha **flexibilidad** para adaptarse a las situaciones.

## ✨ Trucos

Los **trucos** son conjuros de Círculo 0: hechizos menores que un lanzador puede ejecutar **sin gastar maná** y **sin límite de veces al día**. Representan la magia más básica y practicada, tan integrada en el lanzador que fluye de forma casi instintiva.

| Aspecto | Regla |
| --- | --- |
| **Coste** | 0 maná |
| **Preparación** | No se necesita prepararlos cada día |
| **Conocimiento** | Se fijan en la mente con la práctica |
| **Cantidad** | Depende de la clase |

<aside>
💡

**Consejo:** Los trucos son tu "ataque básico mágico". Úsalos cuando quieras conservar el maná para situaciones más importantes.

</aside>

## 🕯️ Rituales

Los **rituales** son conjuros especiales que requieren más tiempo para lanzarse, pero tienen la gran ventaja de que **no consumen maná**. Son perfectos para usar fuera del combate.

| Característica | Regla |
| --- | --- |
| **Tiempo de lanzamiento** | 1 minuto como mínimo (nunca 1 acción) |
| **Coste de maná** | 0 |
| **Componentes** | A menudo requieren componentes materiales costosos |
| **Escalado** | Algunos mejoran automáticamente al acceder a círculos superiores |
| **Interrupción** | Si el ritual se interrumpe (por daño o ruido extremo), falla y se pierden los componentes |

## 🛡️ Lanzar en armadura

Según las reglas estándar de D&D 5.5e, un lanzador que **no sea competente** con la armadura que lleva puesta **no puede lanzar conjuros** mientras la vista. Esto afecta principalmente a clases mágicas como el mago, el hechicero o el brujo, que no tienen competencia con armaduras.

| Situación | ¿Puede lanzar conjuros? |
| --- | --- |
| Sin armadura | ✅ Sí |
| Con armadura ligera (y competencia) | ✅ Sí |
| Con armadura media (y competencia) | ✅ Sí |
| Con armadura pesada (y competencia) | ✅ Sí |
| Con armadura **sin** competencia | ❌ No |

## 🔗 Combinar efectos mágicos

Cuando dos o más conjuros activos afectan al mismo objetivo al mismo tiempo, se aplican las siguientes reglas generales de D&D 5.5e:

- **Efectos distintos se acumulan:** Si un conjuro otorga +1d4 a ataques y otro otorga +1 a ataques, ambos se suman.
- **El mismo efecto NO se acumula:** Si dos conjuros distintos otorgan ventaja en ataques, la ventaja no se duplica; sigue siendo una sola ventaja.
- **Concentración:** La mayoría de los conjuros poderosos y duraderos requieren concentración. Solo puedes mantener **un conjuro de concentración** a la vez. Si lanzas otro, el anterior termina automáticamente.
- **Los trucos no requieren concentración** y pueden usarse libremente junto a conjuros activos.

<aside>
💡

**Ejemplo:** Tienes activo *Bendición* (que da +1d4 a tiradas de ataque) y lanzas *Agrandar* sobre un aliado (que da ventaja en ataques de fuerza). Ambos efectos se aplican porque son de tipo diferente. Pero si ya tenías activo *Acelerar* (concentración) y lanzas *Volar* (también concentración), *Acelerar* termina de inmediato.

</aside>

# 2- Elementos de un conjuro

Cada conjuro tiene una ficha técnica con los siguientes elementos. Entenderlos te permitirá saber exactamente cómo y cuándo puedes usar cada hechizo.

---

## ⏱️ Tiempo de lanzamiento

El **tiempo de lanzamiento** indica cuánto tarda en ejecutarse el conjuro. Los tipos más comunes son:

| Tipo | Descripción | Uso típico |
| --- | --- | --- |
| **1 acción** | El tiempo estándar en combate | La mayoría de conjuros ofensivos y de utilidad |
| **1 acción adicional (bonus action)** | Rápido, permite lanzar otro conjuro en el mismo turno (con restricciones) | Conjuros de mejora o defensa rápida |
| **1 reacción** | Fuera de tu turno, como respuesta a algo | *Escudo*, *Contrahechizo* |
| **1 minuto o más** | Fuera de combate; suele ser un ritual | *Detectar Magia*, *Oración de Sanación* |
| **8 horas** | Conjuros muy poderosos | Algunos encantamientos permanentes |

<aside>
⚠️

**Regla importante:** Si lanzas un conjuro como acción adicional, el único otro conjuro que puedes lanzar ese turno es un **truco** (con tu acción normal). No puedes combinar dos conjuros "completos" en el mismo turno.

</aside>

## 🎯 Rango

El **rango** es la distancia máxima a la que puede llegar el conjuro desde el lanzador.

| Tipo de rango | Significado |
| --- | --- |
| **Personal** | Solo te afecta a ti |
| **Toque** | Debes tocar al objetivo (o a ti mismo) |
| **X casillas** | El objetivo debe estar dentro de esa distancia |
| **Ilimitado** | Puede funcionar en cualquier lugar (conjuros de plano o dimensión) |

<aside>
💡

**Ejemplo:** *Bola de fuego* tiene un rango de 30 casillas, lo que significa que puedes lanzarla a cualquier punto a menos de 30 casillas de ti. El punto de explosión, sin embargo, puede estar más lejos si hay área de efecto.

</aside>

## 💥 Área de efecto

El **área de efecto** define qué zona o cuántos objetivos alcanza el conjuro. Los tipos básicos son:

| Forma | Ejemplo | Descripción |
| --- | --- | --- |
| **Objetivo único** | *Proyectil mágico* | Afecta solo a un personaje o criatura |
| **Esfera / Radio** | *Bola de fuego* (radio 20 pies) | Afecta todo dentro de un círculo centrado en un punto |
| **Cono** | *Aliento de dragón* (cono 30 pies) | Se expande en forma de triángulo desde el lanzador |
| **Línea** | *Rayo de relámpago* | Una franja recta de cierta anchura y longitud |
| **Cubo** | *Nube de dagas* | Un cubo de cierto tamaño centrado en un punto |
| **Cilindro** | *Columna de fuego* | Un cilindro vertical de cierto radio y altura |

<aside>
💡

**Cobertura total:** Si un objetivo tiene cobertura total (está completamente oculto detrás de un muro, por ejemplo), los conjuros que requieren línea de visión **no pueden afectarle**.

</aside>

## 🧪 Componentes

Los **componentes** son los requisitos físicos necesarios para lanzar un conjuro. Hay tres tipos:

| Tipo | Letra | Descripción |
| --- | --- | --- |
| **Verbal (V)** | V | Debes pronunciar palabras o frases en voz alta. No puedes lanzar este conjuro si estás silenciado o no puedes hablar. |
| **Somático (S)** | S | Debes hacer gestos o movimientos con las manos. Si tienes las manos inmovilizadas no puedes lanzarlo. |
| **Material (M)** | M | Necesitas un objeto físico concreto. Puede ser sustituido por un **foco de casteo** (ver sección siguiente) salvo si el componente tiene un coste específico o es consumible. |

### Tipos de componentes materiales

| Tipo | Ejemplo | ¿Consumible? | ¿Tiene coste? |
| --- | --- | --- | --- |
| **Simple** | Una pluma, arcilla | No | No |
| **Con coste específico** | Polvo de rubí (50 PO) | No | Sí |
| **Consumible** | Una gota de alcohol | Sí | No |
| **Costoso + consumible** | Jacinto (1000 PO) + barra de plata (100 PO) | Sí | Sí |

### ¿Qué pasa si no tienes el componente material?

| Situación | Consecuencia |
| --- | --- |
| Componente con coste que no tienes | El conjuro falla + pierdes toda capacidad de lanzar conjuros hasta el próximo descanso largo |
| Componente consumible que no tienes | El conjuro falla + tiras el dado de agotamiento (como si fuera un conjuro de Círculo 6+) |
| Componente costoso **y** consumible que no tienes | El conjuro falla + pierdes capacidad de lanzar conjuros + no puedes lanzar ese conjuro durante 1d12 días |

# Foco de lanzamiento de conjuros

Un **foco de casteo** es un objeto especial que canaliza la energía mágica y puede **sustituir a componentes materiales** que no tengan coste ni sean consumibles.

- [Foco arcano](https://app.notion.com/p/Foco-arcano-15782858a77580519604ee6a58ea0550?pvs=21)
- [Foco de conocimiento](https://app.notion.com/p/Foco-de-conocimiento-36f82858a77580378d61fee82a335636?pvs=21)
- [Foco primario](https://app.notion.com/p/Foco-primario-15e82858a775802484bef25af610722a?pvs=21)
- [Foco sombrío](https://app.notion.com/p/Foco-sombr-o-15e82858a775801284dbf7ea2ddd30b0?pvs=21)
- [Símbolo sagrado](https://app.notion.com/p/S-mbolo-sagrado-15a82858a775808188bdde2913e257a5?pvs=21)

### Rareza de focos y sus beneficios

| Rareza | Nivel sugerido | Espacios para componentes | Bonificaciones |
| --- | --- | --- | --- |
| **Común** | 1 | 2 | Ninguna |
| **Infrecuente** | 3 | 3 | +1 a tiradas de ataque de conjuro |
| **Raro** | 6 | 4 | +1 a CD de salvación |
| **Épico** | 11 | 5 | +1 a ataque y CD, recupera 1d4 maná 1/día |
| **Legendario** | 14 | 6 | +2 a ataque y CD, recupera 1d6+1 maná 1/día |
| **Único** | 17 | 8 | +3 a ataque y CD, recupera 1d8+2 maná 1/día |

### Guardar componentes en el foco

Un foco puede **almacenar** componentes materiales en sus "espacios". Esto permite tener listos componentes costosos sin necesidad de sacarlos durante el combate.

| Tipo de componente | ¿Se puede guardar? |
| --- | --- |
| Simple (sin coste) | Sí, sin gastar espacio |
| Con coste (no consumible) | Sí, ocupa 1 espacio |
| Consumible (sin coste) | Sí, ocupa 1 espacio (se consume al usar) |
| Costoso + consumible | Sí, ocupa 1 espacio (se consume al usar) |

> **Cargar un componente:** Toca el componente con el foco durante 1 minuto mientras canalizas energía. El componente "desaparece" dentro del foco y queda almacenado hasta que lo necesites.
> 

## ⏳ Duración

La **duración** indica cuánto tiempo permanece activo el efecto de un conjuro una vez lanzado.

[Tiempos de duración](Lanzamiento%20de%20conjuros/Tiempos%20de%20duraci%C3%B3n%2014882858a7758059b142fba1ad0278ca.csv)