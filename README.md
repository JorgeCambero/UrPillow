# UrPillow
# Game Development Document

## 1. INTRODUCCIÓN

### 1.1. Descripción del concepto
El juego es un JRPG clásico ambientado en un instituto donde las armas y magias han
sido cambiadas por almohadas, cojines y colchones, las barras de vida y energía por unas
barras de sueño y cafeína respectivamente y al derrotar enemigos no mueren si no que
se quedan dormidos.

### 1.2. Historia y Personajes
Se cuenta la historia de 4 personajes, Jack, Lele, Karen y Sephiroth. Los cuales se
encuentran en un bucle infinito (como el día de la marmota), en el que han de derrotar
al Director del instituto para salir de él, para ello han de subir piso tras piso del instituto
derrotando al resto de estudiantes.

### 1.3. Propósito, Público objetivo y plataformas
Propósito general: darle una vuelta de tuerca a los JRPGs con una temática e historia
menos seria y más relajada.
Público objetivo: Jóvenes amantes de los RPGs por turnos que buscan una experiencia
más relajada.
Plataformas: PC y móvil.



## 2. MONETIZACIÓN

### 2.1. Tipo de modelo de monetización
El videojuego tiene un precio fijo, con el que se obtiene todo el contenido. No consta
de monetización por micropagos ni expansiones o contenido adicional.

### 2.2. Tablas de productos y precios
El producto se venderá digitalmente para ordenador, en la plataforma de videojuegos
Steam. El precio íntegro es de 30€, y con este y 894 copias vendidas se suplirán todos
los gastos y comenzaría la generación de beneficios.



## 3. PLANIFICACIÓN Y COSTES

### 3.1. El equipo humano

El equipo está compuesto por cinco miembros con diferentes perfiles para cumplir con
las necesidades del proyecto. Los integrantes y sus roles serían los siguientes:

- Violeta: Artista gráfico, programadora.

- Alejandro: Productor.

- Jorge: Scrum master, creador de mundo(Writer), Programación.

- Jordan: Programador, diseñador.

- Javier: Diseñador de mecánicas y programador.

Las habilidades que escasean serían el arte y la música, donde aparecen miembros
irremplazables. Sin embargo, en el resto de áreas hay expertise previo por parte de
todos los miembros, suficientes para no alargar innecesariamente el proyecto en caso
de baja.

### 3.2. Estimación temporal de desarrollo

En cuanto a la estimación total del proyecto, se prevé según once tareas en las que se
ha descrito una duración de aproximadamente nueve semanas. Sin embargo, se podría
inyectar presupuesto en personal y horarios para acelerar un poco el proyecto.
La mayoría de tareas son paralelizables, por lo que la mayor parte del equipo está
ocupado cerca de la mitad del tiempo estimado del proyecto, salvo el testing y
publicación que requerirán una finalización de todo lo anterior.


## 4. MECÁNICAS DE JUEGO Y ELEMENTOS DE JUEGO

### 4.1. Concepto de juego

Juego similar a Chrono Trigger pero con una estética de instituto donde los personajes
no portan armas si no que empuñan almohadas, cojines o colchones donde el objetivo
es subir el mayor número de plantas del instituto antes de que se acabe el día (tiempo
o cansancio) para derrotar al Director del centro y terminar así con el bucle infinito.

### 4.2. Mecánicas

- **Bucle infinito:** Similar en funcionamiento al bucle de Majora's Mask donde al
decidir reiniciar el bucle perdemos el progreso de puzzles y piso en el instituto,
pero el jugador se queda con los objetos que ha conseguido y el nivel de los
personajes. ¿Posible banco para guardar cosas?

- **Sueño:** La barra de sueño hace la función de una barra de vida pero inversa
donde si la barra llega al máximo el personaje se dormirá y quedará fuera de
combate. Si todos los personajes del jugador se duermen, terminará ese día y el
bucle comienza de nuevo.

- **Cafeína:** La barra de cafeína hace la función de una barra de energía, con la cual
el personaje podrá usar habilidades especiales a cambio de puntos de la barra,
pero cuando esta llegue a cero el jugador podrá seguir usando las habilidades a
cambio de aumentar su valor de sueño.

- **Combates:** Enfrentamientos contra el resto de alumnos, organizados por
turnos, con distintas habilidades por personaje, así como distintos tipos de
habilidades como de ataque, eliminación de sueño o recuperación de energía, uso
de objetos...

### 4.3. Niveles y Misiones

El instituto cuenta con 5 niveles, donde la dificultad de los enfrentamientos aumenta
según subes los diferentes niveles, además es posible que cada nivel incluya al menos un
puzzle junto a un Jefe al que habrá que derrotar para subir al siguiente nivel.

### 4.4. Objetos

- Objetos equipables:

  * **Almohadas:** Al golpear a un enemigo con ellas les genera sueño.

  * **Cojines:** Utilizadas para conjurar hechizos que pueden generar/quitar
sueño u otros estados alterados.

  * **Colchones:** Bloquean/Reducen el sueño que los enemigos intentan
generar en los personajes.


- Objetos usables:

  * **Regeneran Cafeína:**

    + **Refresco de cola:** Regeneración baja de cafeína.

    + **Doble Espresso:** Regeneración media de cafeína.

    + **Bebida Energética:** Regeneración alta de cafeína.

  * Reducen Sueño:

    + **Zumo de Naranja:** Reducción baja del sueño.

    + **Donut glaseado:** Reducción media del sueño.

    + **Tabasco:** Reducción alta del sueño y aumenta la velocidad del
usuario durante 3 turnos.

  * **Efectos extra:**

    + **Anti-narcolepsia:** Despierta al personaje en el que es utilizado y
aumenta su defensa durante 2 turnos.



## 5. TRASFONDO

### 5.1. Historia y trama
Cuatro amigos de toda la vida, alumnos de una misma clase, se encuentran un día ante
la tesitura de no querer dormir, pues todos acuerdan que es una pérdida de tiempo en
la vida. Así pues, se proponen no volver a dormir nunca más.

Los cuatro amigos están tan orgullosos de su idea y decisión, que al principio de la
siguiente clase se lo comunican al resto de alumnos, y hacen una declaración en voz alta:
“A PARTIR DE AHORA, NUNCA MÁS DORMIREMOS”.

Pasan algunos días y los cuatro amigos sobreviven a base de cafeína, pero se encuentran
en un estado tan deplorable que no son capaces de mantener una conversación
coherente o atender a las lecciones. Durante una de las clases, uno de los chicos golpea
su cabeza contra el pupitre por no poder mantenerse despierto. El profesor de turno
decide llevar a los cuatros ante el director para que solvente el problema.

En el despacho del director, éste les ordena que vengan a clase descansados, pero los
cuatro amigos exponen su punto de vista y se niegan rotundamente. Al director no le
queda otra que obligarlos a dormir a la fuerza, e intenta dormirlos con pastillas para el
sueño. Sin embargo, los cuatro amigos consiguen escapar del despacho.

Al poco, suena por megafonía:
“ATENCIÓN, ATENCIÓN, SE OFRECE RECOMPENSA A QUIEN CONSIGA
DORMIR A LOS SIGUIENTES ALUMNOS: JACK, LELE, KAREN Y SEPHIROTH.”

Los cuatro amigos se reúnen y planean cómo lidiar con la situación. Al final todos
concuerdan:

“SI TANTO LE GUSTA DORMIR, SEREMOS NOSOTROS LOS QUE PONGAMOS A
DORMIR A TODOS, INCLUIDO EL DIRECTOR”.

Los protagonistas se abren paso hasta la oficina del director, no sin antes enfrentarse a
almohadones con todos los alumnos y profesores que se encuentran en el camino,
poniéndolos a dormir.

Por último, tienen un épico enfrentamiento final contra el director, y al vencerlo y
celebrarlo, de repente, todos despiertan. El director ya lo había conseguido. Todo se
trataba de un sueño.

### 5.2. Personajes

- Protagonistas

  * **Jack:** Chico gracioso y amable. Aunque en los últimos años como jugar a
videojuegos e ir al gimnasio le quitan tanto tiempo, ha desarrollado una
pseudo-adicción a la cafeína ya que necesita pasar las noches despierto
para ponerse al día con el instituto. Es el “pegamento” del grupo gracias
a sus gustos variados y carisma.

  * **Lele:** Amiga de la infancia de Jack, si bien han tenido sus más y sus menos
a lo largo de los años, terminaron muy unidos y son prácticamente
inseparables. Tiene problemas de sueño a causa de ayudar a Jack a seguir
con sus estudios.

  * **Karen:** Antes conocida como John, es la compañera de gimnasio de Jack,
es una chica tímida pero agradable. Por su tratamiento con hormonas es
propensa a las migrañas, que derivan en problemas para conciliar el sueño.

  * **Sephiroth:** Amigo online de Jack. Ambos juegan los mismos videojuegos
online, y se hicieron amigos a través de internet jugando videojuegos
antes de darse cuenta que iban al mismo instituto. Se pasa las noches
jugando ayudado de bebidas energéticas por lo cual duerme bastante
poco.

- Antagonistas

  * **Director:** Señor de avanzada edad que solo busca el bien de sus alumnos
y vela por su bienestar.

  * **Bosses (profesores):** Jefes de los diferentes departamentos de las
asignaturas que imparte el instituto. Hay un departamento por planta del
edificio.

- Extras

  * **Tenderos:** Algunos alumnos empatizan con los protagonistas y a cambio
de la moneda del instituto, venden o compran objetos al jugador.

  * **Recepcionista de objetos perdidos:** Señor al mando de los objetos
perdidos. Como cada día se empieza por el principio, el jugador tiene la
posibilidad de dejar parte de sus objetos y dinero en objetos perdidos
para recuperarlos a la mañana siguiente.

  * **El conserje:** El conserje simpatiza con los personajes por el mero hecho
de que odia al director por haberle reducido el sueldo. Permite al jugador
salir del instituto y terminar el día.



### 5.3. Entornos y lugares
El juego ocurrirá completamente dentro de un instituto, por ello, los lugares a los que
se podrá acceder estarán relacionados con este mismo entorno, algunos ejemplos son:
Los pasillos del instituto, la sala de profesores, el cuarto del conserje, el gimnasio del
instituto y el patio, la clase de música, la clase de arte, los laboratorios de tecnología,
biología y química...



## 6. ARTE

### 6.1. Estética general del juego
Respecto al arte nuestro proyecto tiene una estética amigable y acogedora, donde los
principales escenarios y encuentros tendrán una temática graciosa, debido a la historia
del videojuego, al estar basado en una historia algo surrealista y divertida, la estética
tiene que acompañar de la misma forma a la ambientación.

### 6.2. Apartado visual
El apartado visual, al ser un rpg por turnos, se ha pensado que sea principalmente basado
en el pixelart, tanto assets, escenarios y el diseño de interfaces por igual.

### 6.3. Música
La mayoría de la música de nuestro videojuego es música puramente ambiental donde
tiene que ser música enérgica y divertida que acompañe a la serie de escenas y
situaciones surrealistas y divertidas, especialmente la música de combate tiene que ser
muy enérgica e intensa, para reflejar la tensión y dificultad que va a experimentar el
jugador.



## 7. INTERFAZ

### 7.1. Diseño básico de los menús
El diseño básico de los menús es algo bastante simple, pero ha de tener (mediante
estética pixel Art) una serie de principios básicos de usabilidad; Al empezar el videojuego
estará el menú principal, donde existirán los dos siguientes botones:

- **JUGAR**

- **OPCIONES**

Después una vez el jugador haya podido disfrutar de la introducción al videojuego, tendrá
una serie de opciones dentro del menú:

- **EQUIPO**

- **INVENTARIO**

- **HABILIDADES**

- **GUARDAR Y CARGAR PARTIDA**

- **OPCIONES**

En el inventario podrá observar la cantidad de objetos consumibles que tiene para
beneficiarse (curaciones, ventajas de daño, etc...)
En las habilidades simplemente es un breve menú para que el jugador pueda observar
cuales son las cantidades habilidades posee.



### 7.2. Diagrama de flujo
Nuestro videojuego va tener pocas pantallas principales, y son las siguientes:

- **MENÚ PRINCIPAL**

- **MENÚ DE OPCIONES**

- **MENÚ DE INVENTARIO**

- **MENÚ DE HABILIDADES**

- **MENÚ DE EQUIPO**

- **MENÚ DE GUARDAR Y CARGAR**

- **PANTALLA DURANTE EL COMBATE**

- **MAPA PARA COMPROBAR DONDE SE ENCUENTRA EL JUGADOR**

- **PANTALLA DE JUEGO, DONDE SE DESARROLLAN LOS EVENTOS DEL
VIDEOJUEGO**

- **CINEMÁTICAS DE INTRODUCCIÓN DE HISTORIA**

- **PANTALLA “GAME OVER”**

- **PANTALLA FINAL DE JUEGO**
