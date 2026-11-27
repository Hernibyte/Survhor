# Game Design Document

PD: Usar el prefijo Survhor para las clases en C++.

## Initial Design Concept

### Player

Dos tipos de control, clasico (tipo tanque) y moderno (tipo tanque pero de la camara deu).

El jugador puede correr?

Puede realizar un empuje como el de Zomboid, podria ser una carga u otra cosa pero la idea seria permitirle al jugador tener la posibilidad de salvarse incluso sin ningun arma aunque no seria infalible y no podria ser usado contra todos los enemigos.

El jugador no puede pegar a melee sin algun arma equipada.

Podria estar interesante agregar el tipico pisoton para rematar? No estoy tan seguro de darle esa capacidad al jugador igualmente. Depende, en el signalis puedes patearlos en el piso para rematar, pero los enemigos siempre reviven despues de un tiempo (explorar si queremos enemigos que revivan y se necesite una mecanica para matarlos para siempre) -Hernan: Tengamos en cuenta que si pensamos en un diseño de nivel mas lineal no tiene sentido que los enemigos revivan porque nunca vas a volver a pasar por ahi como para que sea significativo.

El inventario es tipo RE2, aunque podria llegar a ser tipo RE4, pero podriamos centrarnos en un inventario como RE2 primero y ver como funciona. Ademas el juego no se va a pausar cuando abras el inventario y ademas te deberia de permitir poder ver algo del juego mientras estan con el inventario abierto.

Mecanica extra de recarga de las armas de fuego similar a los sistemas de recarga de algunos extraction's como el tarkov por ejemplo. Tambien existirian cargadores para solventar este problema. same same.
Un arma podria ser un revolver por ejemplo y eso tambien forzaria al jugador a recargar bala a bala, quiza se podria solventar esta mecanica simplemente con las armas adecuadas. pa pensar.

Las armas melee se pueden romper? No me pareceria mal

Existiria un item que con tenerlo en el inventario puede salvarte la vida una unica vez? como por ejemplo el cuchillo del resident remake.

El jugador podria moverse mientras esta apuntando el arma? Por ahora diria que no, ver en el futuro si se quiere

Podria existir la posibilidad que en contadas situaciones el jugador tenga una camara en primera persona o incluso con vista senital, pero no es prioridad y ademas serian ocaciones especiales.

### Enemigos

Supongo que la idea es que cada enemigo que intentes matar sea un desafio en si mismo, evitar poner muchos enemigos en una misma zona.

Enemigo de toda la vida.

Enemigo que no se puede morir, se puede frenar y solo te persigue. La tipica.

Enemigo que no se puede morir con melee o arma de fuego y necesita un objeto clave.

### Concept

Lista de algunas cosas que podrian funcionar como referencia para el disparador inicial. Preferiblemente que funcione con una sola frase. Solo es para iniciar el concepto en base a esa frase simple.

PD: No es necesario pensar en quedarse con una sola de estas, de hecho no estaria mal si podemos plantear una como la principal y agregar partes de otras como accesorias, o incluso combinar conceptos y ver que sale. Todo esto son meramente opciones.

- IA mala mu mala pasan cosas pum caos muerte destruccion y horror
- Un mundo en los sueños y la mente
- Viviendo una simulacion
- Dios nos abandona
- Nos visita una entidad que no deberia estar en nuestro plano
- Culto religioso haciendo macanerias (JA un clasico)
- El juego "Look Outside" tiene un concepto interesante de entrada para ver

### Puzzles
Diria que vayamos mas por el lado de Silent Hill, en todo caso un punto medio entre resi y sh para la dificultad de resolverlos -Hernan: Prefiero unos mas tirados a sh si, aunque aprovecharse de la simplicidad de los puzzle del re tampoco es una mala idea para algun puzzle que otro, pero si reducimos los puzzles y los hacemos mas dificiles o mas complejos tampoco me pareceria mal, en plan, hacer unos pocos puzzles muy complejos (complejos en el sentido de que se extienden durante gran momento del juego) y meter pequeños mini puzzle muy simples en el medio como transicion simplemente, no se si me estoy explicando bien. Otra cosa importante a plantear, el "Silver Pines" tiene una mecanica donde te permite volver a un lugar en el que hayas hecho una foto previamente, no digo de copiarla porque me pareceria excesivo pero tratar de buscar una alternativa o en su defecto jugar con los shortcut's para facilitar el realizar algunos puzzles o al menos el llegar hasta ellos.

Backtracking para resolver alguno?? -Hernan: Me gustaria la verdad.

### Exploracion

Queremos que sea linear o que te vayas desbloqueando zonas en un area predeterminada a medida que vayas avanzando en la historia? (estilo re2 o metroidvanias) -Hernan: Personalmente me gustan las zonas grandes y bloqueadas donde te vas abriendo camino, aunque tambien es verdad que creo que ningun survival horror depende de eso completamente, la mayoria usa esa estructura en una zona en particular del juego y despues lo combinan con otra zona mas lineal que termina conectando con la siguiente, para resumir, me gustaria que las secciones principales sean como la mansion de re o el hospital del requiem etc. pero no veo lo malo de combinar ambas estructuras, tambien me interesaria ver si algo como dark souls 1 es aplicable a este caso.

### World building

-Hernan: Pense en algo para darle contexto a el mundo en el que transcurre la historia, lo voy a dejar anotado y despues lo revisamos, cambiamos o elegimos otra cosa.

En el mundo en el que transcurre la historia, la humanidad habia abandonado la guia de Dios y entrado en una era sin El, creyendo que simplemente no lo necesitaban (la idea viene de la mitica frase de Nietzsche "Dios ha muerto, nosotros lo hemos matado", que plantea el problema de tener que vivir con valores morales, reglas y leyes que ya no pueden ser sustentados con una base divina y por ende pierden valor, autoridad y legitimidad), y en la busqueda de conocimiento la humanidad observa algo que no debia.

"Cuando la humanidad vio detras del Velo, Eso... nos devolvio la mirada."

Despues de ese suceso empiezan a pasar cosas fuera de lo comun (Aca podriamos incluir cualquier cosa realmente, como el concepto es tan ambiguo las cosas que suceden despues del "Encuentro" podrian ser cualquiera, tampoco hace falta definirlo en este momento solo estoy planteando el contexto del mundo en el que transcurriria la historia principal).
Despues del "Encuentro" la humanidad perdio la razon, entro en panico y obviamente no tardo en surgir cultos religiosos totalmente desviados, asi como escepticos, oportunistas, etc.

"El nunca nos castigaria por encontrarlo, pero cuando lo hicimos ya nos habiamos desviado demasiado."

PD: Es relativamente simple en cierta forma pero supongo que no esta mal para empezar. Lo tire mas que nada por un lado mas religioso aunque la idea es que lo que carajo sea "Eso" no se especifique nada, simplemente es algo y punto, el hecho de pensar que sea Dios seria meramente una interpretacion propia.

