Estudio: Infinite Horizon Studios 
Nombre del juego: The Cursed Return 
Género del juego: Roguelite de acción/perspectiva top-down 
Clases: Mago, arquero y guerrero 
Ecosistemas: Desierto, bosque, nieve 
 
Game Design Document 
Logo del juego 
 
Resumen del juego 
Desarrollado  por  Infinite  Horizon  Studios,  "The  Cursed  Return"  es  un roguelite 
top-down de acción, aventura y supervivencia, que contiene elementos de RPG´s, 
en el que eres un soldado atrapado en un loop temporal creado por una hechicera 
que busca venganza. La guerra entre los reinos del Norte y del Sur ha terminado, 
pero a un costo terrible. Tras años de lucha, estás listo para regresar a casa, pero 
algo  no  está  bien:  el  mundo  a  tu  alrededor  comienza  a  cambiar  de  maneras 
extrañas. 
 
Explora  niveles  aleatorios, lucha contra enemigos desafiantes y toma decisiones 
que  definirán  el  destino  de  tu  personaje.  Al  principio  de  la partida elige entre 
guerrero,  arquero  y  hechicero,  cada  uno  con  armas  únicas y  especiales, pero 
recuerda que cada elección tiene un costo, ya sea bueno o malo. La maldición no 

solo te persigue, sino que también altera la realidad, creando peligros impredecibles 
y enemigos cada vez más poderosos. 
 
La maldición es el elemento distintivo de nuestro juego. La barra se agota con cada 
segundo que pasa, si esta llega a cero el destino está sellado, morir y empezar de 
nuevo. La maldición no solo te limita, genera desafíos impredecibles por lo que es 
indispensable adaptar tu estrategia en cada partida. 
 
Gameplay 
El  objetivo del juego es completar diferentes niveles, mientras el jugador intenta 
romper su maldición y derrotar a enemigos. En el juego, el jugador elige al inicio una 
de las siguientes clases: mago, arquero y guerrero. Mientras mata a los enemigos, 
el jugador podrá obtener ventajas como reducir el impacto de la barra de maldición o 
aumentar  esta  el tamaño de la  barra. Pero, también podrá obtener desventajas 
como reducción de daño, reducción de vida, etc. El juego recuerda mucho a un 
Role-Play Game debido a que el jugador asume el papel de un personaje y avanza 
a través de una historia, combates y exploración. En este caso el combate es en 
tiempo real y el juego incluirá un sistema de progresión para cada clase. 
 
Mindset 
Queremos hacer que el jugador se sienta poderoso de manera progresiva, mientras 
se mantiene alerta de los riesgos que su personaje corre. Queremos provocar este 
mindset colocando al jugador en situaciones donde deberán decidir si aumentar su 
poder (a un costo) o mantenerse con su poder original. 
También buscamos que los jugadores se sientan aventureros mientras avanzan por 
los  niveles  en búsqueda de una manera de romper la maldición. Los diferentes 
entornos  provocarán un sentido  de aventura para el jugador, ya que explorarán 
zonas que siempre serán completamente diferentes. 
Finalmente, queremos provocar una sensación de precaución, con la que el jugador 
deberá decidir de manera estratégica las acciones que realizará, para llegar lo más 
lejos posible antes de que la maldición lo elimine. Además deberán elegir su clase 
considerando los posibles peligros que se presentarán en cada nivel. 
 
Elementos Técnicos 
Pantallas 
El juego contará con varias pantallas clave, cada una diseñada con una interfaz 
clara y funcional para mejorar la experiencia del usuario. Cada pantalla tendrá su 
propio propósito y navegación bien definida. A continuación se explican las pantallas 
más importantes, además, se mostrará un concepto muy básico de lo que se espera 
diseñar. 
 
 
 

I.  Title Screen (Pantalla de Inicio) 
A.  Propósito: Servir como la primera impresión del juego y ofrecer acceso 
a las opciones principales de navegación y configuración. 
 
Se incluirá: 
1.  Logo del juego: Posicionado en el centro superior de la 
pantalla, acompañado de una animación que lo hará destacar 
visualmente. 
2.  Botón de "Nueva Partida": Permite iniciar una nueva aventura 
desde el principio. 
3.  Botón de "Cargar Partida": Disponible sólo si existe un 
progreso guardado previamente. 
4.  Menú de Opciones: Acceso a configuraciones avanzadas de 
sonido y controles. 
5.  Sección de Créditos: Un apartado para reconocer al equipo de 
desarrollo y colaboradores. 
6.  Animaciones dinámicas en el fondo: Se integrarán efectos 
visuales. 
7.  Música de fondo: Un tema de introducción envolvente que 
refuerce la atmósfera del juego. 
8.  Botón de "Salir": Opción para cerrar el juego de manera 
inmediata. 
A continuación se muestra un boceto de cómo se vería: 
 
 NOTA: (falta un botón que diga “cargar una partida”) 
 

II.  Menú de opciones 
A.  Propósito: Permite modificar configuraciones del juego para adaptarlo 
a las preferencias del jugador.  
 
Se incluirá:  
1.  Volumen de efectos: Ajuste específico para los sonidos de 
combate y ambiente. 
2.  Volumen de música: Permite ajustar el nivel de la banda 
sonora. 
3.  Botón de "Regresar": Para volver al menú principal. 
 
III.  Juego Principal 
A.  Propósito: Es la pantalla donde ocurre la jugabilidad, con la interfaz del 
usuario (UI) mostrando información relevante.  
 
Se incluirá: 
1.  Área central del juego: Representa el mundo en el que el 
jugador se moverá e interactuará con personajes y enemigos. 
2.  Interfaz de usuario del jugador: 
a)  Barra de salud: Indica la vida restante del personaje. 
b)  Barra de maldición: Representa el tiempo disponible 
antes de que la maldición afecte al jugador. 
3.  Iconos de estado: Notificaciones visuales que informan sobre 
mejoras temporales o penalizaciones activas. 
4.  Menú de pausa: Permite acceder a configuraciones, controles 
y otras opciones sin salir del juego. 
 
 
 
 
 
 
 
 
A continuación se muestra una secuencia de bocetos: 

 
Las tres clases para nuestro juego, Mago, Arquero y Soldado. En ese orden 
 
 
Al inicio se tenían en cuenta otros sprites, pero esos sprites limitaban el movimiento 
que queríamos implementar, por lo que optamos por rediseñar nuestros sprites para 
facilitarnos el proceso de animación. 
 
 
Sprites originales (no íbamos a usar todos) 
 

 
Boceto de cómo se verían los personajes respecto a un pedazo del mapa 
 
 
Boceto de cómo se vería un personaje en relación a un nivel, con su heads-up 
display que muestra la barra de maldición (corazón morado), la barra de vida 
(corazón rojo) y dos apartados, uno muestra los enemigos derrotados y otro muestra 
el nivel de dificultad. 
  
 
 
 

IV.  Créditos del juego 
A.  Propósito: Mostrar el equipo de desarrollo y agradecer a los jugadores.  
 
Se incluirá: 
1.  Nombres del equipo. 
2.  Música de fondo. 
3.  Opción para regresar al menú principal. 
4.  Acreditaciones de elementos externos. 
 
Controles 
El sistema de controles define cómo el jugador va a interactuar con el juego, 
permitiendo movimientos, ataques y acciones esenciales para la jugabilidad. A 
continuación se enlistan los controles para “The Cursed Return”. 
 
I.  Movimiento del Jugador 
A.  Teclas de dirección (WASD) 
1.  W → Moverse hacia arriba. 
2.  S → Moverse hacia abajo. 
3.  A → Moverse hacia la izquierda. 
4.  D → Moverse hacia la derecha. 
5.  L o click derecho → Dash 
 
II.  Ataques y Combate 
A.  Ataque principal 
1.  K o click izquierdo → Ataque con el arma equipada. 
2.  Diferentes armas tienen diferentes animaciones y efectos. 
3.  Si se deja presionada la tecla/click, se hará un ataque cargado, 
que hará más daño. 
 
III.  Interacción: Se utiliza la misma tecla porque tiene una función de interacción 
en circunstancias específicas. 
A.  Interacción con Curandero, Armero y con Cofres 
1.  Tecla F → Permitirá interactuar con los personajes que le 
proporcionarán ayuda al jugador, al igual que podrán abrir 
cofres que encuentren a lo largo de su run. 
B.  Recoger objetos (armas, pociones, llaves, etc.): 
1.  Tecla F → Recoger los objetos del escenario. 
 
 
 
 
 

Mecánicas 
Nuestro  juego  introduce  una  mecánica  en  específico  que  consideramos  muy 
innovadora,  que  refuerza  la  temática  de  la  maldición  y  el  loop temporal. Pero 
algunas de las principales mecánicas son: 
 
1.- Barra de maldición 
  i. La barra de maldición representa el tiempo que el jugador tiene para pasar 
las salas antes de ser víctima de la maldición y reiniciar su partida.  
ii. Esta barra se agota de forma constante a lo largo del tiempo, pero puede 
regenerarse al derrotar enemigos. 
iii. La barra de maldición comienza llena y se vacía completamente en 
10 minutos si no se regenera. 
v. Derrotar enemigos permite regenerar un porcentaje de la barra, 
dependiendo del nivel y tipo de enemigo. 
vi. Su implementación está basada en un temporizador en segundo plano. 
 
Ejemplo en el Gameplay 
El jugador inicia con su barra de maldición llena y debe moverse rápidamente para 
empezar a derrotar enemigos, si tarda demasiado en el combate, el jugador morirá y 
reiniciará su partida. Si derrota a un jefe final en el nivel 1, su barra se extenderá y 
regenerará parte de su barra, permitiéndole seguir avanzando.  
 
La siguiente tabla ilustra el tiempo total de la barra al inicio del juego (sin aumentos) 
 
    Minutos  Segundos 
 
Tiempo total  10  600 
 
 
 
Los siguientes bocetos ilustran el progreso de cómo es que la barra de maldición va 
bajando con el tiempo. En el boceto, diferenciamos la barra de vida de la barra de 
maldición por el color del corazón al inicio de la barra, la barra de maldición tiene un 
corazón morado, mientras que la barra de vida tiene un corazón rojo.  
 
Boceto de la barra de maldición al 100% 

 
Boceto de la barra de maldición entre el 50% y 75% 
 
 
Boceto de la barra de maldición entre el 25% y 50% 
 
 
Boceto de la barra de maldición entre el 0% y 25% 
 
 
Boceto de la barra de vida entre al 100% 
 
2.- Generación aleatoria de Niveles 
i. Cada partida será diferente gracias a la generación aleatoria de mapas. 
ii. Los niveles del juego están compuestos por habitaciones conectadas, 
generadas de manera aleatoria a partir de un conjunto de salas predefinidas. 
iii. Cada nivel tiene un ecosistema temático (desierto, bosque o nieve) y 
contiene enemigos, cofres y elementos únicos. 
iv. Existen 12 salas en total, divididas en 4 por ecosistema. 

v. Cada partida selecciona aleatoriamente salas de cualquier ecosistema 
para construir el nivel. 
vi. Las salas se bloquean hasta que el jugador elimine a todos los enemigos  
dentro. 
vii. El jefe del nivel siempre estará al final y será el último desafío antes de 
avanzar. 
viii. Cofres y recompensas aparecen en una sala específica sin enemigos, 
elegida aleatoriamente dentro del nivel. 
ix. Al iniciar la partida, el jugador tiene tres formas de salir de la sala: ganar 
derrotando a todos los enemigos, perder si su barra de vida llega a cero, ser 
eliminado por la maldición si su barra llega a cero 
 
Ejemplo en el Gameplay 
El jugador entra a la sala de un nivel, observa que hay enemigos de corto y largo 
alcance. Decide primero atacar a los enemigos de largo alcance para evitar recibir 
daño constante de lejos, derrota a todos los enemigos y desbloquea la siguiente 
sala. El jugador continúa así hasta llegar a la sala del jefe. 
 
3.- Progresión de las clases con mejoras y desventajas 
i. El jugador podrá obtener diferentes mejoras y desventajas que afectarán su 
desempeño durante la partida. 
ii. Pueden ser temporales o permanentes, y afectan tanto el combate como la 
barra de maldición. 
iii. Existe un arma secundaria temporal, que se obtiene durante la partida 
y tiene una duración de 1 minuto. 
iv. Existen mejoras temporales, que se obtienen durante la partida y sólo 
duran esa partida. 
v. Existe un aumento del tamaño de la barra de maldición, que se obtiene al 
derrotar a un jefe y se mantiene por el resto de partidas. 
 
4.- Combate rápido y estratégico 
  i. El combate es en tiempo real, con una mecánica de “dash” que permite 
a los jugadores esquivar ataques y adaptarse a diferentes tipos de 
enemigos. 
ii. El jugador puede realizar una evasión rápida en cualquier dirección para  
evitar ataques enemigos. Se implementará con una animación de 
desplazamiento. 
iii. Cada clase comienza con un ataque básico. 
iv. Al obtener un arma secundaria, el ataque básico se mantiene, pero se 
vuelve más fuerte. 
v. No existen efectos de estado como quemaduras o veneno, centrándose  
en el combate directo. 
 
 

 
Cada clase tiene un estilo de combate único: 
i. El guerrero tiene ataques cuerpo a cuerpo con gran daño. 
ii. El arquero tiene disparos a distancia con la mecánica de cargar el tiro para 
causar más daño. 
iii. El mago tiene la habilidad de lanzar hechizos desde lejos. 
 
A continuación se presenta una tabla ilustrativa de las diferencias de estadísticas 
entre las clases: 
 
  Guerrero  Arquero  Hechicero 
Arma  Espada  Arco  Báculo/bola de fuego 
Ataque básico  35  15  20 
Ataque cargado  60  40  50 
Distancia  Cuerpo a cuerpo  40  20 
 
Se utilizará un  sistema de detección de  colisiones y físicas  para hacer que los 
ataques sean precisos y satisfactorios. 
 
Además  de  la  generación  aleatoria  de  niveles,  la  cantidad  de  enemigos  será 
aleatoria, sin embargo hay unas restricciones por bioma: 
-  Los esqueletos solo aparecerán en el desierto. 
-  Los duendes y lagartos sólo aparecerán en el bosque 
-  Los minotauros y lobos sólo aparecerán en la nieve. 
 
A continuación se muestra una tabla con las vidas de los enemigos. 
 
  Vida  Enemigo común  Enemigo fuerte  Jefes 
 
Nivel 1  70  200  1000 
 
  Nivel 2  100  350  1500 
  Nivel 3  150  500  2000 
 
Aquí se asumirá que: 
-  Los esqueletos sin armadura serán comunes. 
-  Los esqueletos con armadura serán fuertes. 
 
-  Los duendes sin armas y poca armadura serán comunes. 
-  Los duendes con armas y armadura serán fuertes. 
 
-  Los lobos serán fuertes por defecto. 
-  Los minotauros serán fuertes por defecto. 

-  Los lagartos sin armadura serán comunes. 
-  Los lagartos con armadura serán fuertes. 
 
*Nota: se hablará de los personajes más a fondo en las siguientes secciones. 
 
5.- Curandero, Armero y Cofres 
  i. A lo largo del run del jugador, este podrá encontrarse con salas que  
contengan uno de los siguientes: 
-  Armero: le dará un arma secundaria aleatoria al jugador. 
-  Curandero: le dará una pócima al jugador que le curará 25% de la 
barra de vida. 
-  Cofre: le dará al jugador una pócima o un arma secundaria aleatoria. 
ii. Estos elementos servirán como ventajas para el jugador ya que, el arma  
secundaria podrá causar más daño que el arma base de cada clase. Habrá 4  
armas secundarias diferentes:  
-  Hacha de guerra: Un hacha que provocará gran daño, pero reduce la 
velocidad del jugador. 
-  Lanza: Una lanza que tendrá mucho daño, pero tendrá un corto 
alcance. 
-  Ballesta: Una ballesta que tendrá el daño de un arco cargado, pero un 
rango menor. 
-  Daga: Una daga que permitirá que las clases de rango lejano puedan 
acercarse a combate cuerpo a cuerpo. 
 
iii. En cuanto al armero, este podrá aparecer en una sala única que no tendrá  
enemigos, en el momento en el que el jugador interactúe con él, se asignará  
un arma temporal aleatoria al jugador. 
iv. En cuanto a la curandera, también aparecerá en una sala única que no  
tendrá enemigos, en el momento en el que el jugador interactúe con ella, se  
le asignará una pócima al jugador, la cuál le regenerará vida, más no  
maldición. 
 
 
 
 
 
 
 
 
 
 
 
 
 

A continuación se muestran bocetos de la Curandera y del Armero: 
 
 
 
Boceto de la curandera 
 
 
Boceto del Armero 
 
 
Boceto de cómo se verán los cofres abiertos y cerrados respectivamente 

 
5.- Armas secundarias 
  i. Como se mencionó previamente, a lo largo del run, el jugador encontrará  
armas secundarias que le darán una ventaja por cierto tiempo. 
ii. Previamente ya mencionado, habrá 4 armas secundarias diferentes:  
-  Hacha de guerra 
-  Lanza 
-  Ballesta 
-  Daga 
iii. Estas armas se activarán en el momento en el que el jugador la recoja, 
con una duración de 1 minuto y al terminar ese tiempo, el jugador regresará al arma 
que le corresponde a la clase que eligió. 
iv. Esto permitirá que el jugador pueda crear nuevas maneras para pasar 
niveles y derrotar a enemigos, pero también lo obligará a que piense de 
manera más crítica. 
v. Si el jugador ya cuenta con un arma secundaria temporal, y encuentra a 
otros npc o cofre que le dé otra arma secundaria temporal, el jugador deberá 
considerar su estrategia para lo que le queda del run y escoger el arma con la 
cual continuar su camino (es decir, si recoger el arma o no). 
 
 
A continuación se muestra una tabla que contiene información sobre cada arma 
secundaria: 
 
 
Arma  Daño básico  Distancia 
Ballesta  40  30 
Hacha de guerra  45 Cuerpo a cuerpo 
Lanza  40  10 
Daga  Mismo que la clase  Cuerpo a cuerpo 
 
 
6.- Puntuación 
  i. Con la finalidad de mostrar estadísticas que inciten al jugador a continuar  
haciendo runs, implementaremos un sistema de puntuación, a cada enemigo 
se le asignará determinada puntuación. 
ii. En el momento en el que acabe el run del jugador, ya sea porque murió por  
daño, murió por la maldición o terminó el juego, se desplegará una pantalla 
de estadísticas del run en general, donde se mostrarán estadísticas como: 
-  Enemigos derrotados en el run 
-  Jefes derrotados en el run 

-  Con qué clase se jugó 
-  Cuánto duró el run 
-  Puntuación del run 
  iii. La puntuación se asignará de la siguiente manera: 
-  Enemigo común: 1 punto 
-  Enemigo fuerte: 3 puntos 
-  Jefe: 10 puntos 
iv. Para fomentar la rejugabilidad y la competencia entre jugadores, se 
añadirá un sistema de records personales donde el jugador podrá ver sus 
mejores runs en distintas categorías: 
-  Run más largo (en tiempo).  
-  Mayor cantidad de enemigos derrotados en un solo run.  
-  Mayor puntuación obtenida en un run.  
 
Diseño de Niveles 
Temas 
1.  Desierto 
i.  Atmósfera 
a.  Incómoda, Calurosa y Árida 
b.  Se ambienta en una aldea olvidada con ruinas antiguas y restos 
de civilizaciones. 
ii.  Objetos 
a.  Ambientales 
a.  Cactus 
b.  Ruinas cubiertas con arena 
c.  Esqueletos y restos de armaduras. 
b.  Interactivo 
a.  Esqueletos (enemigo - 3 variaciones) 
b.  Cofres 
c.  Armas Secundarias 
d.  Curandero 
e.  Armero 
 
 
 
 
 
 
 

Boceto de un nivel del desierto: 
 
 
2.  Bosque 
i.  Atmósfera 
a.  Misteriosa, Oscura, Tranquila 
ii.  Objetos 
a.  Ambiente 
a.  Árboles grandes y matorrales densos 
b.  Raíces 
c.  Troncos caídos 
b.  Interactivo 
a.  Duendes (enemigo - 2 variaciones) 
b.  Lobos (enemigo - 1 variación) 
c.  Cofres 
d.  Armas Secundarias 
e.  Curandero 
f.  Armero 
Boceto de un nivel del bosque: 
 

 
3.  Nieve 
i.  Atmósfera 
a.  Fría, Hostil, Invernal 
ii.  Objetos 
a.  Ambiente 
a.  Paisaje cubierto de nieve 
b.  Vistas de montañas lejanas y valles helados. 
c.  Nieve cubriendo el suelo, sin afectar la movilidad del 
jugador. 
d.  Rocas congeladas 
e.  Piedras de hielo 
b.  Interactivo 
a.  Minotauros (enemigo - 1 variación) 
b.  Lagartos (enemigo - 2 variaciones) 
c.  Cofres 
d.  Armas Secundarias 
e.  Curandero 
f.  Armero 
Boceto de un nivel de la nieve: 
 
 
Game Flow 
1.  Inicio del juego 
1.1.  Aparece un breve texto que da contexto a la historia del juego. 
1.2.  El jugador comienza en un bioma aleatorio (bosque, desierto o nieve). 
1.3.  HUD aparece: barra de vida, barra de maldición, indicador de clase 
seleccionada, etc. 
 

2.  Exploración inicial 
2.1.  El jugador se encuentra en la primera sala con enemigos aleatorios. 
2.2.  El jugador se da cuenta que la puerta a la siguiente sala está cerrada. 
2.3.  El jugador observa el tipo de enemigos (corta o larga distancia) y toma 
decisiones sobre cómo proceder. 
2.4.  El jugador observa que la barra de maldición está comenzando a bajar. 
2.5.  La batalla comienza, el jugador comienza a atacar estratégicamente. 
 
3.  Movimiento entre Salas 
3.1.  Una vez derrotados los enemigos, la puerta o entrada a la siguiente 
sala se desbloquea. 
3.2.  El jugador se mueve hacia la siguiente sala aleatoria (bioma aleatorio), 
encontrando cofres y enemigos en cada una. 
3.3.  Las mecánicas como esquivar y ataques básicos se emplean 
constantemente durante el avance. 
 
4.  Encuentro con el Jefe 
4.1.  El jugador lleva a la cuarta sala, donde se encontrará a un Jefe. 
4.2.  La barra de maldición está a la mitad o menos, lo que genera presión 
adicional para completar el nivel. 
4.3.  Se activa un corte de sonido o transición para indicar la llegada al jefe. 
 
5.  Fase del Combate Final 
5.1.  El jugador se enfrenta al jefe final en una batalla emocionante. 
5.2.  El jefe tiene mecánicas especiales, como fuerza mucho mayor o 
spawnear enemigos básicos,  el jugador debe adaptarse a su patrón 
de ataque para sobrevivir. 
5.3.  El combate sucede bajo la presión de la maldición, con el jugador 
viendo cómo la barra disminuye constantemente. 
 
6.  Finalización del nivel 
6.1.  Si el jugador derrota al jefe, se aumenta el tamaño y capacidad 
máxima de la barra de maldición, además, se desbloquea la puerta 
para avanzar al siguiente nivel. 
6.2.  Si el jugador pierde debido a la barra de maldición vacía o morir, se 
muestra una pantalla de derrota y el jugador es regresado al inicio del 
nivel. 
 
7.  Reiniciar o Continuar 
7.1.  Al reiniciar, el jugador comienza de nuevo, pero con una nueva 
generación de niveles. 

7.2.  Además, el jugador conserva el tamaño alcanzado de la barra (en 
dado caso de que haya eliminado a un jefe en cierto nivel). 
A continuación, mostraremos unas tablas que simulan los valores de enemigos y 
tiempo en cada nivel (estos valores están sujetos a cambios de ser necesario y se 
usaron para visualizar el tiempo de sobra que le quedaría al usuario si se dedicara 
únicamente a eliminar enemigos): 
Nivel 1:  
●  Parte a): Es necesario recordar que se parte de un tiempo total inicial de 
600 segundos: 
○  En esta tabla se estima un tiempo que toma en eliminar a los 
enemigos por su fuerza para el primer nivel. 
○  Posteriormente, se pone el número de enemigos máximo del nivel 
(este es el mismo en todos los niveles). 
○  Después se obtiene el tiempo total que toma eliminarlos. 
●  Parte b) 
○  Tiempo base por eliminación: Posteriormente, se calcula el tiempo 
base que se va a recuperar por eliminación de cada enemigo (un 30% 
del tiempo que toma eliminarlo) 
○  Tiempo extra porcentaje: En esta parte se calcula un umbral (aleatorio) 
de recuperación extra de energía, que va desde el 0.1%-0.3% del valor 
inicial de la barra al iniciar el nivel (en este caso, de 600 segundos). 
■  Es importante mencionar que se estimó con el mejor caso 
(0.3%) y el peor caso (0.1%) para ver ambos escenarios. 
●  Parte c) y d) 
○  Tiempo agotado: Aquí se calcula el tiempo que se perdió en el mejor y 
el peor caso (restando el tiempo recuperado) 
○  Tiempo restante total: Aquí se calcula el tiempo restante (tiempo 
inicial-tiempo perdido) al terminar el nivel, con los dos escenarios. 
●  Tiempo restante promedio: Se calcula un promedio de ambos 
escenarios, para utilizarlo como referencia en el calculo del siguiente nivel. 
Enemigo 
    común  Fuertes  Jefes  Total  Total 2 
Tiempo en eliminar  3  10  90    
Número de enemigos  15  3  1    
Tiempo total en eliminar  45  30  90  165  
Nivel 1 
           
Tiempo base por 
eliminación (30%)  0.9  3  27  49.5  

Tiempo extra porcentaje 
(mín)  0.6  2.4  21.6  24.6  74.1 
Tiempo extra porcentaje 
(máx)  1.8  7.2  64.8  73.8  123.3 
           
Tiempo agotado mín (Lo 
que se pierde)  90.9        
Tiempo restante total  509.1        
Tiempo promedio 
      restante  533.7 
Tiempo agotado máx (Lo 
que se pierde)  41.7        
Tiempo restante total  558.3        
 
Nivel 2: 
●  En esta sección se hace el mismo proceso partiendo de 533.7 segundos, lo 
único que cambia es: 
○  El tiempo de eliminación de los enemigos aumenta, debido a que se 
vuelven más fuertes. 
○  El tiempo base de recuperación pasa de 30% a 20% 
●  El tiempo restante final (promedio) de recuperación es de 361 segundos. 
 
Enemigo 
    común  Fuertes  Jefes  Total  Total 2 
Tiempo en eliminar  5  15  150    
Número de enemigos  15  3  1    
Tiempo total en eliminar  75  45  150  270  
           
Tiempo base por 
eliminación (20%)  1  3  30  54  
Tiempo extra porcentaje 
Nivel 2  (mín)  0.5337  2.1348  19.2132  21.8817  75.8817 
Tiempo extra porcentaje 
(máx)  1.6011  6.4044  57.6396  65.6451  119.6451 
           
Tiempo agotado mín (Lo 
que se pierde)  194.1183        
Tiempo restante total  339.5817        

Tiempo promedio 
      restante  361.4634 
Tiempo agotado máx (Lo 
que se pierde)  150.3549        
Tiempo restante total  383.3451        
 
Nivel 3: 
●  Los cambios son: 
○  El tiempo de eliminación de los enemigos 
○  El tiempo base de recuperación pasa de 20% a 10% 
●  El tiempo restante estimado al terminar el juego sería de 80 segundos. 
 
Enemigo 
    común  Fuertes  Jefes  Total  Total 2 
Tiempo en eliminar  7  20  180    
Número de enemigos  15  3  1    
Tiempo total en eliminar  105  60  180  345  
           
Tiempo base por 
eliminación (10%)  0.7  2  18  34.5  
Tiempo extra porcentaje  0.361463 1.445853 13.01268 14.81999 49.31999
(mín)  4  6  24  94  94 
Tiempo extra porcentaje  1.084390 4.337560 39.03804 44.45999 78.95999
(máx)  2  8  72  82  82 
Nivel 3 
           
Tiempo agotado mín (Lo  295.6800
que se pierde)  006        
65.78339
Tiempo restante total  94        
Tiempo promedio  80.60339
      restante  88 
Tiempo agotado máx (Lo  266.0400
que se pierde)  018        
95.42339
Tiempo restante total  82        
 
Desarrollo del Juego 

El  desarrollo  del  juego  se  estructurará  en  una  serie  de  clases  base  y  clases 
derivadas que encapsulan las mecánicas principales del juego. 
Clases Abstractas 
Estas  clases  proporcionan la estructura más fundamental y básica del juego, se 
definirán  las  propiedades  y métodos que van a ser  heredados  por clases más 
específicas. 
 
Clases abstractas / Componentes 
1.  PersonajeBase 
i.  JugadorBase (Tiene movimiento, ataques y ataque cargado) 
ii.  EnemigoBase (Ataca al jugador con distinto daño dependiendo del 
tipo) 
iii.  NPCBase (Ofrecen objetos al jugador) 
2.  ObjetoBase 
i.  ObjetoArmaSecundaria (Son temporales y ofrecen ventajas) 
3.  ObstaculoBase 
4.  ElementosUIBase 
Clases derivadas / Composiciones de componentes 
1.  JugadorBase 
i.  Soldado (Cuerpo a cuerpo y daño alto) 
ii.  Arquero (Rango de ataque alto y daño bajo) 
iii.  Hechizero (Rango de ataque moderado y daño moderado) 
2.  EnemigoBase 
i.  EnemigoEsqueleto (Comunes y fuertes) 
ii.  EnemigoDuende (Comunes y fuertes) 
iii.  EnemigoLagarto (Comunes y fuertes) 
iv.  EnemigoMinotauro (Fuertes) 
v.  EnemigoLobo (Fuertes) 
3.  NPCBase 
i.  NPCCurandera (Ofrece una poción al jugador) 
ii.  NPCCArmero (Ofrece un arma secundaria al jugador) 
4.  ObjetoBase 
i.  ObjectoCofre (Ofrece un arma secundaria o una poción al jugador) 
ii.  Objeto pócima (Regenera vida al jugador) 
5.  ObjetoArmaSecundaria 
i.  ArmaHacha (Daño, alcance, velocidad) 
ii.  ArmaLanza(Daño, alcance, velocidad) 
iii.  ArmaBallesta (Daño, alcance, velocidad) 

iv.  ArmaDaga (Daño, alcance, velocidad) 
6.  ObstaculoBase 
i.  ObstaculoPared (Previene que el jugador salga del nivel) 
ii.  ObstaculoPuerta (Previene que el jugador salga de la sala hasta que 
mate a todos los enemigos) 
7.  UIBase 
i.  BarraMaldicion (Muestra el tiempo restante antes de que la maldición 
consuma al jugador) 
ii.  BarraVida (Muestra la vida del jugador) 
iii.  Iconos (Muestran la clase del jugador y si es el caso el arma 
secundaria) 
iv.  Puntaje (Muestra los enemigos eliminados) 
v.  BotonMenu (Pausa el juego y abre los ajustes) 
 
 
Gráficos 
El  juego utiliza  una  paleta  de colores variada  pero  que al final del día permite 
diferenciar biomas y personajes sin dejar de tener sentido en cuanto a lo visual. A 
pesar de que no seguiremos una paleta de colores limitada, los tonos terrosos, fríos, 
o cálidos se emplean según el entorno para mantener una ambientación correcta y 
cómoda. Los colores presentan sombreados y contrastes que aportan profundidad 
pero mantienen un estilo pixel art característico. No aplicaremos un post-procesado 
HSV, pero los escenarios estarán diseñados para ser reconocibles sin necesidad de 
aplicar filtros o correcciones adicionales. 
 
Algunos colores que utilizaremos son los siguientes: 
-  Para el soldado: #726b7e y #867e7f 
-  Para el arquero: #64a42c y #0b5c2f 
-  Para el hechicero: #3c49ad y #322d6a 
-  Para el bioma del bosque: #a0b12a y #4d8051 
-  Para el bioma del desierto: #d7bd4e y #ba8b4a 
-  Para el bioma de nieve: #a6b5b5 y #8cadb4 
 
El estilo gráfico es en pixel art en 2D, con una resolución aproximada de 32x32 
píxeles por  personaje. Queremos  que las armas y vestimentas tengan un toque 
semi-realista. Para  los personajes vamos a utilizar contornos negros además de 
contrastes  de  color  para  definir  las  siluetas  y  sombras.  Para  tener  una 
retroalimentación visual efectiva, incorporaremos diferentes efectos, por ejemplo, 
cuando el jugador o un enemigo recibe daño, se mostrará un frame rojo en el sprite. 
Al igual que con el jugador, los enemigos también mostrarán un frame rojo en su 
sprite.  Los  cofres  y  armas  secundarias  contarán  con  sus  propios  efectos  y 
animaciones,  también  se  implementarán  animaciones  en  la  barra  de  vida  y 
maldición, al igual que colocar íconos por si el jugador obtiene el arma secundaria. 

 
Gráficos Necesarios 
I.  Personajes 
A. Humanos (Jugador) 
1.  Arquero: No tendrá variación y solo cambiará de arma en caso 
de encontrar un arma secundaria temporal. 
a)  Idle (cuatro direcciones) 
b)  Caminar (cuatro direcciones) 
c)  Atacar con arma principal (cuatro direcciones) 
d)  Atacar con arma secundaria (cuatro direcciones) 
e)  Dash (cuatro direcciones) 
f)  Recibir daño (cuatro direcciones) 
g)  Morir (una dirección) 
 
 
2.  Soldado: No tendrá variación, y solo cambiará de arma en caso 
de encontrar un arma secundaria temporal. 
a)  Idle (cuatro direcciones) 
b)  Caminar (cuatro direcciones) 
c)  Atacar con arma principal (cuatro direcciones) 
d)  Atacar con arma secundaria (cuatro direcciones) 
e)  Dash (cuatro direcciones) 
f)  Recibir daño (cuatro direcciones) 
g)  Morir (una dirección) 
 
3.  Mago: No tendrá variación, y solo cambiará de arma en caso de 
encontrar un arma secundaria temporal. 
a)  Idle (cuatro direcciones) 
b)  Caminar (cuatro direcciones) 
c)  Atacar con arma principal (cuatro direcciones) 
d)  Atacar con arma secundaria (cuatro direcciones) 
e)  Dash (cuatro direcciones) 
f)  Recibir daño (cuatro direcciones) 
g)  Morir (una dirección) 
 
4.  Curandero y Armero: No tendrá variación, y su diseño será 
diferente a todos los demás personajes, a su vez, este diseño 
será exclusivo para cada personaje 
a)  Idle (una dirección) 
b)  Interacción con el jugador (una dirección) 
 
 

B. Enemigos Semi-Humanos 
1.  Esqueletos: Habrá tres variaciones en el diseño, que serán 
cambios en su armadura, los que tienen más armadura harán 
más daño y tendrán más vida, los que tienen menos armadura 
son los “comunes” con menos fuerza y menos vida. 
a)  Idle 
b)  Caminar 
c)  Atacar 
d)  Recibir daño 
e)  Morir (única animación sin variación de dirección) 
 
2.  Duendes: Habrá dos variaciones en el diseño, que serán 
cambios en su armadura, los que tienen más armadura harán 
más daño y tendrán más vida, los que tienen menos armadura 
son los “comunes” con menos fuerza y menos vida. 
a)  Idle 
b)  Caminar 
c)  Atacar 
d)  Recibir daño 
e)  Morir (única animación sin variación de dirección) 
 
3.  Minotauro: No tendrá variación, el daño que tiene es fijo. 
a)  Idle 
b)  Caminar 
c)  Atacar 
d)  Recibir daño 
e)  Morir (única animación sin variación de dirección) 
 
C. Enemigos No Humanos 
1.  Lagartos: habrá dos variaciones en el diseño, que serán 
cambios en su armadura, los que tienen más armadura harán 
más daño y tendrán más vida, los que tienen menos armadura 
son los “comunes” con menos fuerza y menos vida. 
a)  Idle 
b)  Caminar 
c)  Atacar 
d)  Recibir daño 
e)  Morir (única animación sin variación de dirección) 
 
2.  Lobo: No tendrá variación y el daño que hace es fijo. 
a)  Idle 
b)  Caminar 

c)  Atacar 
d)  Recibir daño 
e)  Morir (única animación sin variación de dirección) 
 
II.  Tiles y Bloques 
Cada bioma tendrá su propio tileset, organizados en 12 salas distribuidas en 
3 niveles. Los tilesets estarán prehechos y se generarán aleatoriamente. 
Cabe aclarar que todos los tilesets tendrán bordes en los extremos del nivel, 
para funcionar como muro de colisión para el jugador 
 
A. Bosque 
1.  Pasto 
2.  Camino de tierra 
3.  Rocas 
4.  Flores 
5.  Árboles 
6.  Lagunas (zonas con agua) 
 
B. Desierto 
1.  Arena 
2.  Ruinas de piedra 
3.  Restos de estructuras 
4.  Cactus 
5.  Armaduras tiradas 
6.  Esqueletos (decoración) 
 
C. Nieve 
1.  Suelo Nevado 
2.  Bloques de hielo 
3.  Rocas cubiertas de nieve 
4.  Árboles nevados 
5.  Huellas 
6.  Lagos Congelados 
 
Además de estos elementos en los tilesets, planeamos agregar decoraciones que 
no tengan ningún otro propósito más que ser utilizados como decoración para 
ayudar a ambientalizar la zona. No tendrán interacción alguna con el personaje. 
 
III.  Ambiente 
A.  Hierba Alta 

B.  Huesos en el suelo 
C. Picos de hielo 
D. Columnas rotas (ruinas) 
E.  Estatuas dañadas (ruinas) 
F.  Raíces que salen de los árboles 
G. Árboles 
H. Arbustos 
 
IV.  Other 
A.  Cofres 
B.  Camino que indica la salida al siguiente nivel 
C. Zonas donde estarán los NPC´s (Curandero y Armero) 
 
Música y Sonidos 
La banda sonora de “The Cursed Return” se basará en un estilo orquestal ambiental 
que  evoque  una  sensación  de  estar  en  una  aventura  legendaria,  pero  sin 
encasillarse  en  una  interpretación  medieval  o  similar  al  género  de  nuestros 
personajes e historia. Deseamos utilizar instrumentos orquestales como cuerdas, 
metales, percusión, y coros para reforzar la sensación de grandeza y peligro, por lo 
que también es prudente utilizar un tempo que sea rápido, uno ideal sería 165 BPM, 
que puede dar pauta a coros sombríos o armonías épicas. 
 
El  tono  general de  la música será tenso y opresivo, ya que  la mecánica de la 
maldición genera una presión constante sobre el jugador, esto se puede reflejar con 
composiciones que tengan: 
 
-  Ritmos y progresiones armónicas que transmiten urgencia y peligro 
-  Crescendos dinámicos en combate para aumentar la tensión 
-  Uso  de  cuerdas  en  secciones más  tranquilas para dar un respiro y una 
sensación de “calma” antes de regresar a los combates.  
-  Capas  musicales  progresivas,  que  vayan  añadiendo  más  instrumentos 
conforme el jugador va llegando más lejos. 
 
A la hora de decidir una generación de biomas aleatoria, se deben evitar choques 
en la música de los biomas, por ello, se optará utilizar una banda sonora unificada, 
osea, una misma base musical que se reproduzca en todos los niveles, pero que 
progresivamente  vaya  evolucionando  conforme  el  jugador  también  evoluciona, 
haciéndose más épica con la incorporación de más instrumentos. 
 
 
Efectos de Sonido 

Los efectos de sonido serán retros y estilizados, en lugar de ser realistas, para que 
así puedan encajar con la identidad visual del juego, ya que si se agregan efectos 
realistas,  el  diseño  visual  del  juego  no  encajará  con  el  realismo que  el audio 
proporciona. Los efectos tendrán una estética similar a los sonidos clásicos de 16 
bits, con un diseño de audio claro y fácil de identificar, de esta manera, la inmersión 
que se proporcionará será mucho mejor a una donde los efectos y sonidos no 
encajan con lo que uno ve. 
 
I.  Efectos de sonidos por interacción 
A. Movimientos 
1.  Paso sobre tierra 
2.  Paso sobre piedra 
3.  Paso sobre pasto 
4.  Paso sobre nieve 
5.  Paso sobre arena 
6.  Desplazamiento rápido (dash) 
 
B. Interacción 
1.  Cofre abriéndose 
2.  Sonido de alguien bebiendo (pócima) 
3.  Armadura chocando contra el suelo 
 
C. Armas 
1.  Espada cortando 
2.  Hacha impactando 
3.  Lanza perforando 
4.  Daga apuñalando 
5.  Cargando tiro de arco 
6.  Flecha disparada desde un arco 
7.  Cargando tiro con ballesta 
8.  Ballesta disparando 
9.  Báculo canalizando energía 
10. Disparo de energía 
 
D. Combate 
1.  Sonido de impacto al golpear un enemigo 
2.  Sonido de impacto al recibir daño 
3.  Sonido de muerte de enemigos 
4.  Sonido de muerte del jugador 
 
II.  Feedback Auditivo 

Para reforzar el feedback sin depender de elementos visuales únicamente, 
implementaremos sonidos como golpes secos para indicar que el jugador fue 
golpeado. Al morir, se reproducirá un sonido impactante y fuerte, seguido de 
un breve silencio para recalcar la derrota antes del reinicio del loop. Al 
derrotar al jefe final, habrá un sonido especial para resaltar el suceso. 
 
Música Necesaria en el Juego 
Como los niveles serán generados de manera aleatoria, conforme el jugador avanza 
y cambiarán entre biomas, también aleatorios, la música será unificada, con una 
sola pista general que va escalando conforme el juego avanza, hasta llegar a un 
punto máximo donde es una canción con una intensidad muy grande 
 
 
I.  Estructura musical 
A. Inicio (exploración temprana) 
1.  Sonidos de cuerdas y vientos suaves. 
2.  Bajo volumen y una sensación de inseguridad. 
 
B. Media partida (mayor dificultad) 
1.  Se añaden percusiones para aumentar la tensión. 
2.  La melodía base evoluciona con la inclusión de nuevos 
instrumentos. 
 
C. Final (Zona de mayor peligro y jefe final) 
1.  Uso de coros épicos y metales pesados. 
2.  Ritmo más acelerado para representar la urgencia y tensión del 
momento final del juego. 
 
II.  Sonidos Ambientales 
Los sonidos ambientales serán mínimos, con una ligera presencia de sonidos 
como viento en ciertas áreas para reforzar la atmósfera. No se planea incluir 
efectos de sonidos adicionales en los escenarios, para evitar una saturación 
de efectos. 
 
Por el momento no sabemos de dónde obtendremos la música y los efectos pero se 
están tomando en cuenta las referencias y sitios que el Profesor Gilberto nos 
proporcionó: 
○  http://www.freesound.org/ 
○  https://www.freesfx.co.uk/ 
○  http://dig.ccmixter.org/ 
○  https://www.playonloop.com/ 
○  https://www.bensound.com/ 

○  http://www.newgrounds.com/audio 
○  https://felgo.com/game-resources/free-music-for-games 
○  https://www.dl-sounds.com/ Not free 
○  https://www.youtube.com/audiolibrary/music?nv=1 
 
 
Cronograma del desarrollo
 
El desarrollo del juego estará organizado en 7 sprints de una semana cada uno, 
comenzando con el primer sprint la semana del 10 de Abril, y terminando en un 
deadline  de  7  semanas.  Cada  sprint  estará  enfocado  en  áreas  específicas 
dependiendo de los issues que se realicen en GitHub Projects, para así construir 
progresivamente  todos  los  sistemas  del  juego,  asegurando que  las mecánicas, 
gráficos, sonidos, bases de datos, scripts y todos los aspectos del proyecto sean 
implementados de manera eficiente. 
Dado que el equipo está conformado por tres estudiantes que no tienen experiencia 
previa  en  el  desarrollo  de  videojuegos,  es  muy  importante  que el cronograma 
mantenga  una  estructura  clara  y  organizada,  asignando  mayor  prioridad  a  los 
elementos esenciales y dejando fases de pulido y ajuste para las últimas semanas. 
En el equipo buscamos siempre realizar pruebas y ajustes durante los sprints para 
así evitar una acumulación de errores al final del desarrollo. 
 
A continuación se detalla el cronograma del desarrollo, es importante aclarar y hacer 
mucho  énfasis  en  que  este  cronograma  NO  es  el  oficial  y  que  se  puede  ir 
cambiando durante el proceso de desarrollo del proyecto. 
 
¿Qué falta? 
 Leer el GDD completo y verificar que hace sentido 
 Terminar cronograma 
 Pasarlo a Markdown 
 Hacerle commits a todo 
 Y ya 😀 

