# PROYECTO: 

(Basado en Repositorio CMI24, incluye card personal)
Proyecto de Creación Multimedia Interactiva de la  Facultad de Bellas Artes de la Univesidad de Granada



# 1 Datos 



**Titulo** : Cooking Yaya

**Web:**   https://github.com/aliciaruizz/aliciaruizz.github.io

Proyecto: https://aliciaruizz.github.io


**Autor:**  Alicia Ruiz Rodríguez

**Resumen** : Serie de minijuegos orientados a niños pequeños.

**Estilo/género:**  Videojuego 

**Logotipo** : (insertar imagen y breve justificación, si  tiene) 
![logo](https://github.com/aliciaruizz/CMI24/blob/main/cara1.png).


**Resolución:** 800x600px 

**Probado en:**    Google Chrome 

**Tamaño proyecto:** 3.5MB 

**Licencia** Este proyecto tiene una Licencia CC Reconocimiento Compartir igual (CC BY-SA)

**Fecha** : 23/05/2024

**Medios** (donde se tiene presencia relacionada):

- Github: https://github.com/aliciaruizz/aliciaruizz.github.io





# 2. Memoria del proyecto 

### 2.1 Storyboard: 

Lo primero que encontramos es el teaser, en el cual se muestras el objetivo del juego. Es un juego para miños en el cual tienen que conseguir todas las piezas del puzzle para completar la receta, por cada mini juego que supere se le dará una pieza

![teaser](https://github.com/aliciaruizz/aliciaruizz.github.io/blob/main/teaser.png).

Esta es una de las varias escenas del teaser, concretamente la que marca el objtetivo. Tras el teaser aparecerá el menú principal:

![menu](https://github.com/aliciaruizz/aliciaruizz.github.io/blob/main/menu.png).

En el menú podemos observar diferentes opciones, si pulsamos galería llegaremos a otra página en la que también se muestran diferentes opciones que ver como son las diferentes localizaciones, el personaje principal (la yaya) o la receta a conseguir; en créditos aparacen algunos datos de quien ha realizado el videojuego y finalmente si pulsamos empezar nos llevará a un segundo menú:

![juegos](https://github.com/aliciaruizz/aliciaruizz.github.io/blob/main/juegos.png).
Como vemos tenemos varios hecos sin piezas, algunos en las mesas y otros en el rectángulo azul.
Los de las mesas son los botones para entrar a los juegos, solo hay uno ya que van apareciendo según superen los niveles; si consigue superar el primer nivel la pieza se desplazará a su sitio en el rectángulo azul, una vez encajada apareceda en otra mesa la del siguiente nivel.
El juego acaba cuando las cuatro piezas están en su sitio.


### 2.2. Esquema de navegación 



(imagen con las distintas pantallas de navegación, usa draw.io o cualquier programa de dibujo)











### Etapa 1: Ideación de proyecto

**Investigación de campo** (propuestas inspiradoras para el proyecto)

- Portfolio [Leonardi Web page](http://www.rleonardi.com/interactive-resume/) para idear cómo organizar el material
- 



**Motivación de la propuesta** 

Este  proyecto es interesante porque no es simplemente una página con distintos jurgos que no tienen relación entre sí, sino que tiene el incentivo de juntar todas las piezas.



**Publico / audiencia**

- Orientado a niños pequeños, ya que son juegos bastante fáciles, pero intenté poner colores vibrantes y sonidos que pudieran llamar su atención





### Etapa 2: Desarrollo / actividades realizadas

En un principio todos los videojuegos serían iguales, pero al ir aprendiendo cosas nuevas decidí que cada uno sería diferente para que también así fuera más entretenido.

Casi todo lo hice a base de condicionales y variables.

El primer videojuego consiste en un juego de cartas, en el cual hay que encontrar las parejas.
Mediante las variables establecí todos los términos que iba a necesitar y con las condicionales el funcionamiento del juego en sí: por ejemplo, si al dar la vuelta las dos son iguales desaparecen del tablero, si no lo son, la carta vuelve a darse la vuelta.
Para poder dar la vuelta a las cartas y que una misma tuviera dos caras utilicé los conmutadores, en un principio todos tienen la misma imagen, la del revés y al clicar sobre ella aparece un alimento, el objetivo es encontrar el que es igual a él.
Si llega a alcanzar las tres parejas habrá superado el nivel y volverá al menú de los mini juegos, donde una pequeña animación hace que aparezca el siguiente nivel.
Hasta que no alcance las tres parejas la escena se reproduce en bucle, usando un GoToandPlay.

Respecto al segundo nivel, me costó un poco más entender el funcionamiento, intenté hacerlo solo por colisiones pero no llegaba a funcionar, así que tuve que añadir más cosas.
Usé varios elementos, primero una plantilla en la que encajarían varias piezas, pero al estar todas juntas no llegaba a entender el proceso a seguir, así que cree una figura (cuadrado) para cada hueco y les bajé la opacidad al máximo, ahora ya tenía cada figura con la que cada pieza entraría en contacto.
Para coger las piezas usé Drag and Drop creando un área caliente para cada pieza, si al soltar la pieza coincidía con su cuadrado correspondiente se encajaría en el lugar, sino quedaría suelta. 
Al no poder usar la línea de tiempo con las piezas, ya que sino no funciona el Drag and Drop lo que hice es que la pieza movible desaparezca y simplemente aparezca su correspondiente en su sitio, para esto simplemente la pieza encajada empieza invisible y con un condicional establecí que si encaja se haga visible.

Al ser nueve piezas , si llega a encajar todas, al igual que antes vuelve a la escena del menú y con otra animación aparece el mini juego siguiente.



### Etapa 3: Problemas identificados

Creo que conseguí que todo funcionara más o menos bien, pero lo que quizás falla un poco más es que a la hora de poner las piezas en el segundo juego si no está lo suficientemente cerca no encaja, lo que puede confundir al jugador y pensar que está encajada pero no, por eso también añadí los sonidos, si no está encajada no sonará.



# 4. Conclusiones 

Al ser la primera vez programando hay cosas que me ha costado mucho entenderlas, algunas por ejemplo ni llegaron a salirme y tuve que cambiar de idea por ejemplo en uno de ellos irían cayendo alimentos y el personaje tendría que esquivarlos pero no conseguí que funcionara y lo cambié por el de las cartas. Otro problema que me costó mucho resolver fue reiniciar los juegos cada vez que entrara. Pero en general estoy contenta con el resultado aunque no esté acabado del todo ya que solo pude hacer dos de los cuatro juegos.







# 5 Referencias 


**Recursos y materiales audiovisuales:**

* Musica:  
* Imágenes:  
* Tipografía

**Herramientas utilizadas**

- Hippani Animator 5.1




