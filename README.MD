# NORKEB: Una app para mejorar la fidelización de clientes mediante estrategias de gamificación por compras

#### Autor: Fabián Catalán
#### Tags: UX Research, Surveys, Agile, Prototype, Wireframes

> Creación: 4 de noviembre de 2025
> Ult. Actualización: 4 de diciembre de 2025 

El desarrollo de una aplicación siguiendo procesos de diseño requiere, tanto en teoría como en práctica, una validación constante con usuarios, clientes y partes interesadas. Este enfoque permite respaldar cada decisión y asegurar que los avances del proyecto estén alineados con las necesidades reales del mercado.

 Se realizó bajo el marco del UX Research, la recopilación de información valiosa a potenciales clientes pertenecientes a un nicho de mercado de artículos desechables -parafernalias- de consumo fumador y de cultivo indoor, testeando bajo encuestas, la idea de **ofrecer descuentos y beneficios por cada compra usando tecnología QR de por medio**. Dado los resultados, se hizo validación de la idea y se construye por iteraciones las estructuras de las pantallas importantes de la aplicación, cuyas percepciones de diseño se recogieron mediante mensajes directos, think aloud (pensar en voz alta) que fueron contrastadas con los modelos de diseño probados en la industria. Actualmente se encuentra finalizando de la fase de investigación y validación de diseño.



## La idea

Desde inicios de noviembre, nace un proyecto piloto colaborativo y comunitario enfocado en la creación de una aplicación web que apoya a una tienda Growshop bajo UX Research, aplicando investigación previa, apoyo social naciendo una hipótesis de diseño: "Norkeb, tu growshop amigo". La propuesta central es utilizar códigos QR en las boletas físicas para vincular la experiencia offline con la digital para aumentar la fidelización de clientes y la mejora de experiencia de marca haciendo de cada compra una bonificación gamificada.

## Validación de la idea y resultados de primera encuesta

De la primera encuesta  se plantearon 10 preguntas de estudio que puedes [ver aquí](./assets/forms/Norkeb_formulario.pdf) cuyo fin es medir variables de decisión de los participantes bajo la hipótesis de comprar en un growshop y los posibles beneficios que se podrían ofrecer, recolectando sus preferencias y estilos de cliente.

Dividido en 3 áreas, la encuesta midió:
- la experiencia de compra & la comunidad
- interés en comunidad & anonimato
- motivación y recompensas.

### Resultados de la encuesta

> Según [los artículos de Jakob Nielsen](https://www.nngroup.com/articles/why-you-only-need-to-test-with-5-users/), manifiesta que con solo 5 encuestados son más que suficientes para tomar decisiones rápidas de diseño. Aunque hay discusiones de la [vigencia de lo anterior](https://medium.com/@anna.y.dickinson/its-not-five-users-c11da404f299) tenemos una muestra interesante con resultados coherentes para esta primera iteración.

El rango de edades de los ocho encuestados está entre los 25 y 44 años, con tendencias a cultivo (62.5%) y consumo.
Declaran guardar siempre o temporalmente las boletas físicas (75%). La novena pregunta agrega un dato interesante: los usuarios manifiestan un interés medio-alto de ganar recompensas bajo esta mecánica de escaneo de QR de boletas (ver imagen #1), obteniendo dos indicadores que respaldan, en primera iteración, que nuestra técnica de fidelización de escaneo de QR de boletas *podría ser viable*.

![Gráfico de barras mostrando la probabilidad de escaneo de QR](./assets/img/qr-win-1.png)
Imagen #1 Probabilidad de escanear el QR una boleta de Norkeb.

Por otro lado, todos manifiestan tener un interés medio-alto en información sobre el uso y cultivo de estos productos. Siguiendo la línea de la comunidad, se testea si están dispuestos a  compartir fotos y consejos de plantas y productos, manifestando interés medio-alto (87.5%) manteniedo una preocupación media-alta de anonimato. Se considera preguntar directamente qué les motiva más a unirse a un programa de fidelización, escogiendo en su gran mayoría el "ganar descuentos directos en productos (5 de 8 usuarios), obtener contenido exclusivo (2 usuarios), y leve interés (1 usuario) por gamificar via reconocimiento por niveles y estatus / insignias.

![Gráfico de motivación por programa de fidelización de este growshop - Norkeb](./assets/img/fidelizacion-1.png)
Imagen #2 Motivación por programa de fidelización

En la última pregunta de gamificación evaluamos el interés de tres posibles misiones (múltiple respuesta)

- Dejar una reseña sobre el producto comprado (5 votos)
- Subir una foto de producto o planta (1 voto)
- Recomendar tienda a un amigo (4 votos)

![Resultados de misiones gamificadas en contexto al growshop](./assets/img/misiones-1.png)
Imagen #3 Misiones y testeo de gamificación.

# Investigación y Definición de Usuarios

El objetivo de esta investigación fue perfilar al usuario principal de Norkeb mediante una encuesta realizada a 8 personas entre el 1 a 4 de noviembre, para validar la tracción de una propuesta de Programa de Fidelización Digital que combina una comunidad web con un sistema de recompensas.

### Resumen del Diseño
- La solución debe ser digital, móvil e incorporar elementos sociales, se infiere que los usuarios pesquisados son adultos jóvenes digitalmente activos.
- La motivación principal es canjear y materializar los puntos - moneda en valor tangible, es decir, la app debe estimular lo transaccional via descuentos directos
- La web es un valor añadido a la tienda, y la sección de comunidad como sección de gamificación debe priorizar la privacidad y anonimato total.
- Escanear la boleta se entiende que es una recompensa y a la vez una misión gamificada debido al beneficio que se obtendrá de esa acción.

## Perfil del Usuario digital Norkeb

### El Cultivador:

- Adulto joven, comprador de temporada (5 de 8 usuarios compra espaciadamente al menos 3 veces al año) relacionado a semillas, equipos como también fertilizantes.  Mencionar que estas preguntas eran de opción única, lo que estamos infiriendo fuera de encuesta que **el que cultiva también consume**, pero por ahora, esta conclusión queda incluida implícitamente dentro de este diseño sin validación explícita.

### El consumidor casual

- Adulto joven, (3 del total de los encuestados) compra al menos dos veces al mes productos ligeramente inclinados a parafernalia. Dado que el porcentaje de consumidores es menor a los cultivadores, asumiremos para este user persona que es un **usuario no cultivador**.

## Mecanismo gamificado de misiones y monedas

Por simplicidad, los puntos Norkeb vs moneda chilena son 1 a 1, es decir, los puntos es dinero real canjeable. La misión más atractiva para ganar puntos son:

- Dejar una reseña sobre el producto comprado (muy valioso para Norkeb)
- Recomendar la tienda a un amigo (muy relevante la opción de referidos).

## Conclusión Estratégica
La estrategia de fidelización es atractiva y viable siempre que se enfoque en el valor transaccional para el usuario.

Se desprenden tres lineas de diseño:

- Diseñar la arquitectura de recompensas
- Diseñar el flujo de adopción (escaneo de QR y compras online)
- Diseñar la comunidad anónima mediante reseñas.

# Arquitectura de Recompensas

El objetivo es incentivar la adopción, la repetición de compra y generación de contenido.

Desde ahora, los puntos Norkeb pueden ser llamados como 'monedas' o simplemente 'puntos'. Dada la paridad 1:1, el sistema es fácil de entender y trasparente para el usuario

### Definición y tasas de ganancias:

Con cada misión ganas puntos base más un porcentaje de lo comprado.

$$Puntos_{Mision} = Base_{misión} + tasa_{misión} * TotalBoleta$$

| Misión|Base   | Tasa  |
|---    |---    |---    |
|Unirse | $100  | 0%    |
|QR Scan| $350  | 1%   |
|Reseña | $450  | 0%    |
|Compra online| $150 | 1% |

Entonces, si un usuario compra $20.000 en tienda física y escanea el QR de la boleta, tenemos ganancia por unirse y por haber escaneado.

$$Puntos += Puntos_{unirse} + Puntos_{Scan QR}$$
$$Puntos += 100 + (350 + 20000*0.01)$$
$$Puntos = \$650$$

Estos puntos pueden ser canjeados en una siguiente boleta.
Si bien los valores son ficticios para efectos de este ejercicio académico, en un escenario real se ajustaría la economía de fichas para asegurar la rentabilidad del negocio

### Limitaciones

Se debe informar que los canjeos o descuentos solo son accionables si los puntos son mayor o igual a una cifra. Definamos ese valor en 2.500.

Estas definiciones deben ser contenidas bajo estructuras de patrones de diseños adecuadas y equilibradas porque es lógico que pueden sufrir cambios.

# Test de Usabilidad bajo escenario
## Validación de Prototipo preliminar usando Figma

La meta de este prototipo es ver si el usuario entiende cómo escanear, porqué escanear y como eso le beneficia. Para ello, a cinco encuestados se les hizo revisar la siguiente imagen, pidiéndoles no enfocarse en detalles visuales. Mencionaron que no les resultaba cómodo ni convincente, los colores e íconos distraían mucho. Después de esas quejas, obtuve que:

- Los botones no son llamativos (poco Call to action)
- Prototipo muy genérico y opaco
- Cambiar la estructura de los botones y sus textos
- No queda claro cómo funciona los descuentos
- Que tenga contrastes más profundos

![Prototipo uno, fondo blanco, poca información, no es llamativa.](./assets/img/norkeb_proto_1.png)

## Iteración dos:

Se toman algunas sugerencias del prototipo uno. Agregamos texturas de fondo y generalicé íconos y botones. Dejé claro el beneficio de cada misión, obteniendo mayor aprobación del diseño, aunque personalmente no me convence del todo.

![Prototipo 2, texturas de fondo asociadas a growshop, colores y contrastes afines, + info](./assets/img/norkeb_proto_2.png)

## Iteración tres de usabilidad
### El recorrido

La idea es que el usuario aprenda intuitivamente a usar la app, en específico, debe aprender la noción de escanear las boletas para su beneficio. Como primera misión, a mis encuestados le contaré un pequeño storytelling introductorio.

> "Mira, necesitamos comprar un bong y papelillos. Solo tenemos 20000 en efectivo así que no podemos comprar online, tu misión es comprar solamente eso en la tienda y ver que tanta maravilla es eso de que escaneando la boleta ganas plata para canjear en la tienda. Ten cualquier boleta en tus manos, veamos como funciona el prototipo."

![Prototipo 2.1 pantalla principal de la web app Norkeb - tu growshop amigo](./assets/img/norkeb-3.png)

![Prototipo 2.2  - pantalla gracias por tu compra con el total de puntos ganados](./assets/img/Norkeb-4.png)

# Prototipo interactivo

[interactuar por acá](https://www.figma.com/proto/GfNHqGwrQjXyZAIueRdXeM/MVP2025)

## 🧪 4. Usabilidad y Validación del Prototipo

Esta fase fue crucial para validar nuestras hipótesis de diseño y asegurar que el sistema de recompensas fuera intuitivo.

### 4.1 Plan de Testeo
* **Metodología:** Testeo moderado presencial, con enfoque en la técnica "Think Aloud" (Pensar en voz alta).
* **Muestra:** 6 participantes, replicando el perfil del "Cultivador" y "Consumidor Casual".
* **Herramienta:** Prototipo interactivo de Figma (link).

#### Tareas a Validar
1.  **Inicio de Sesión:** El usuario debe registrarse y localizar el bono de bienvenida.
2.  **Escaneo de QR:** El usuario debe escanear un código de boleta simulado y confirmar la ganancia de puntos.
3.  **Canje de Recompensa:** El usuario debe encontrar la sección de premios y simular el canje de un producto de $2.500.

---

### 4.2 Resultados Clave (Hallazgos)
Los resultados confirmaron la motivación por el sistema, pero revelaron fricciones importantes en la interfaz de puntos.

| Hallazgo | Tasa de Éxito | Nivel de Fricción |
| :--- | :--- | :--- |
| **Bono de Bienvenida:** Fácil de localizar y claro en su valor. | 100% | Baja |
| **Pantalla de Puntos:** Los usuarios confundieron los "Puntos Norkeb" con un saldo en CLP. | 25% | Alta |
| **Función de Escaneo:** El botón estaba muy escondido en la barra de navegación inferior. | 50% | Media |
| **Proceso de Canje:** Intuitivo, una vez que llegaban a la sección de premios. | 87.5% | Baja |

> **Cita clave de usuario:** *"Me gusta la idea de ganar un 1%, pero no entendía si esos 'puntos' eran plata real o solo fichas de juego."*

### 4.3 Iteración: Antes y Después (Solución de Diseño)
Los hallazgos anteriores nos llevaron a dos iteraciones clave para mejorar la claridad de la arquitectura de la información.

> # Iteraciones de prueba!

#### 🎯 Iteración 1: Claridad de Saldo y Moneda
**Problema:** El texto "1.050 Puntos" no era claro, causando confusión con el saldo bancario.
**Solución:** Se cambió el *copy* y se añadió un icono identificador.

| Antes | Después |
| :---: | :---: |
|  |  |
| **Razón del cambio:** El saldo ahora se presenta como **"1.050 N-Points"** y se explica en un tooltip contextual que son la moneda de canje interna. |

#### 🎯 Iteración 2: Optimización del Flujo de Escaneo
**Problema:** El botón de escanear QR estaba agrupado con otras funciones, lo que aumentaba el tiempo de tarea a 15 segundos en promedio.
**Solución:** Se elevó la jerarquía visual del botón principal de acción (CTA).

| Antes | Después |
| :---: | :---: |
|  |  |
| **Razón del cambio:** Se movió el ícono a un botón flotante central (FAB), reduciendo el tiempo de tarea a **5 segundos** y elevando la tasa de éxito al 100%. |

### 4.4 Métricas Finales y Conclusión
Tras aplicar las correcciones, se realizó una mini-validación rápida (N=4) para obtener un puntaje final.

#### System Usability Scale (SUS) Simplificado
El SUS es una métrica de usabilidad estándar con un puntaje máximo de 100.
* **Puntaje promedio final de Norkeb:** **82/100**
* **Interpretación:** Según la escala de Aaron Bangor, un puntaje de **82** se considera en el rango de **"Excelente"** y supera el promedio de usabilidad (68).

> **Conclusión:** La estrategia de gamificación fue validada. La usabilidad mejoró significativamente en las tareas críticas de acumulación de puntos, asegurando un proceso de fidelización claro y disfrutable.
