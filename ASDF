# **The Cursed Return**

## _Game Design Document_

---

##### **© 2025 Infinite Horizon Studios. Todos los derechos reservados.**

**"The Cursed Return"** y todos los contenidos relacionados, incluyendo pero no limitado a: diseño del juego, personajes, historia, arte, música, código fuente y documentación, son propiedad intelectual de **Infinite Horizon Studios**.

Queda estrictamente prohibida la reproducción, distribución, modificación o uso no autorizado de cualquier parte de este documento o del juego sin el consentimiento previo por escrito de **Infinite Horizon Studios**.

**Autores**
- Valentina Castilla
- Diego de la Vega Saishio
- Luis Emilio Veledíaz

##
## _Índice_

---

1. [Índice](#index)
2. [Game Design](#game-design)
    1. [Logo del juego](#logo)
    2. [Resumen del juego](#summary)
    3. [Gameplay](#gameplay)
    4. [Mindset](#mindset)
3. [Elementos Técnicos](#technical)
    1. [Pantallas](#screens)
    2. [Controles](#controls)
    3. [Mecánicas](#mechanics)
4. [Diseño de Niveles](#level-design)
    1. [Temas](#themes)
    2. [Game Flow](#game-flow)
5. [Desarrollo del Juego](#development)
    1. [Clases Abstractas](#abstract-classes--components)
    2. [Clases Derivadas](#derived-classes--component-compositions)
6. [Gráficos](#graphics)
    1. [Atributos del Estilo](#style-attributes)
    2. [Gráficos Necesarios](#graphics-needed)
7. [Sonidos/Música](#soundsmusic)
    1. [Atributos del Estilo](#style-attributes-1)
    2. [Sonidos Necesarios](#sounds-needed)
    3. [Música Necesaria](#music-needed)
8. [Cronograma](#schedule)

## _Game Design_

---

### **Logo**

Subir logo a GitHub y poner el .md

### **Summary**

Desarrollado por Infinite Horizon Studios, "The Cursed Return" es un roguelite top-down de acción, aventura y supervivencia, que contiene elementos de RPG´s, en el que eres un soldado atrapado en un loop temporal creado por una hechicera que busca venganza. La guerra entre los reinos del Norte y del Sur ha terminado, pero a un costo terrible. Tras años de lucha, estás listo para regresar a casa, pero algo no está bien: el mundo a tu alrededor comienza a cambiar de maneras extrañas. 

Explora niveles aleatorios, lucha contra enemigos desafiantes y toma decisiones que definirán el destino de tu personaje. Al principio de la partida elige entre guerrero, arquero y hechicero, cada uno con armas únicas y especiales, pero recuerda que cada elección tiene un costo, ya sea bueno o malo. 

La maldición no solo te persigue, sino que también altera la realidad, creando peligros impredecibles y enemigos cada vez más poderosos. La maldición es el elemento distintivo de nuestro juego. La barra se agota con cada segundo que pasa, si esta llega a cero el destino está sellado, morir y empezar de nuevo. La maldición no solo te limita, genera desafíos impredecibles por lo que es indispensable adaptar tu estrategia en cada partida.

### **Gameplay**

El objetivo del juego es completar diferentes niveles, mientras el jugador intenta romper su maldición y derrotar a enemigos. En el juego, el jugador elige al inicio una de las siguientes clases: mago, arquero y guerrero. Mientras mata a los enemigos, el jugador podrá obtener ventajas como reducir el impacto de la barra de maldición o aumentar esta el tamaño de la barra. Pero, también podrá obtener desventajas como reducción de daño, reducción de vida, etc. El juego recuerda mucho a un Role-Play Game debido a que el jugador asume el papel de un personaje y avanza a través de una historia, combates y exploración. En este caso el combate es en tiempo real y el juego incluirá un sistema de progresión para cada clase.

### **Mindset**

Queremos hacer que el jugador se sienta poderoso de manera progresiva, mientras se mantiene alerta de los riesgos que su personaje corre. Queremos provocar este mindset colocando al jugador en situaciones donde deberán decidir si aumentar su poder (a un costo) o mantenerse con su poder original.
También buscamos que los jugadores se sientan aventureros mientras avanzan por los niveles en búsqueda de una manera de romper la maldición. Los diferentes entornos provocarán un sentido de aventura para el jugador, ya que explorarán zonas que siempre serán completamente diferentes.
Finalmente, queremos provocar una sensación de precaución, con la que el jugador deberá decidir de manera estratégica las acciones que realizará, para llegar lo más lejos posible antes de que la maldición lo elimine. Además deberán elegir su clase considerando los posibles peligros que se presentarán en cada nivel.
