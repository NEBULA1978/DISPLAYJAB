# DISPLAYJAB

Qué vamos a APRENDER en este vídeo
display a fondo
ahora sin hub en este vídeo un poquito
más especial vamos a hacer homenaje a la
propiedad de ese display super
importante y que tenemos que conocer
para hacer cualquier cosa ya sea con
html css javascript view o cualquier
otro lenguaje de web ya que define cómo
se van a comportar los diferentes
elementos imágenes cajas titulares
etcétera en nuestros proyectos y para
ello vamos a ver las cuatro propiedades
display por defecto que hay más algunas
que salieron en años posteriores para
mejorar nuestros proyectos también
veremos barbaridades usos indebidos del
display de gente que no conoce cómo
funcionan y bueno pues intentan
solucionar los problemas y limitaciones
que tienen de manera poco inteligente y
luego también veremos el caso de el
display none que es muy útil pero que
tiene algunas características un poco
negativas que hay otras propiedades
eficaces alternativas que nos ayudan a
complementar nuestros proyectos muy
potente el display una auténtica pasada
antes de ver la parte práctica de
display quiero explicar dos cosas que
son súper importantes que es por una
Los display por defecto de las etiquetas HTML
parte que con nosotros creamos cualquier
etiqueta html cualquier tipo de caja de
imagen de titular de lo que sea por
defecto cuando lo creamos ya tiene su
propio display y por tanto funciona de
una determinada manera por ejemplo
cualquier tipo de caja que nosotros
creemos cualquier tipo de deep section
header etcétera párrafos o por ejemplo
titulares h1 h2 etcétera tienen son
cajas y por tanto tienen el display
block por defecto que luego veremos qué
significa luego también por ejemplo
cuando creamos imágenes botones o por
ejemplo inputs bueno pues éstos tienen
su inline blog que tiene sus
peculiaridades y algunas limitaciones
que veremos cómo solucionarlo y luego
también por ejemplo si creamos enlaces o
bien etiquetas de tipo spam o strong u
otras bueno pues son de tipo inline que
tienen muchas más limitaciones que
beneficios pero que se pueden solucionar
utilizando a algunos otros displays como
por ejemplo son display o display grid
que veremos que no hay ningún elemento
html que al crearlos sea display flex o
display grid pero que es súper útil
utilizarlos porque nos facilitan mucho
la vida y luego hay un cuarto tipo de
display que parece que nadie reconoce
que es el display table que cuando
creamos cualquier tipo de tabla que si
ya no se utilizan para lo que se
utilizaban antes que era para distribuir
el contenido pero bueno para hacer
tablas lo que sea una lista de tornillos
que nosotros vendemos en una ferretería
se utiliza una tabla pues bien cuando
creamos cualquier tipo de table
cualquier tipo de tabla por defecto
tiene el display table que no se utiliza
pero que existe y estos son los cuatro
tipos de display que hay más el display
flex y el display grid que veremos en
funcionamiento a continuación
suscríbete al canal para no perderte
nada
vamos a ver el display en acción
bien para ver la parte práctica tenemos
un único fichero index html que tiene su
interior tanto la parte de html como los
estilos css para ver un poquito la
relación que tienen entre ellos y tener
que tener abierto varias pestañas en
display: block; (las cajas)
este caso vamos a ver primero el
representante máximo del display blog
que son las cajas cualquier tipo de
cajas pueden ser cajas de tipo de tipo
section de tipo a site cualquier tipo de
caja tienen las mismas características
de display evidentemente si no le pongo
algún tipo de borde o fondo no voy a
poder ver ni las dimensiones ni tampoco
la extensión por lo tanto vamos a darles
un borde en color el fondo
y ya vemos un poco aquí las primeras
características en un principio los
elementos que son de tipo blog acaparan
todo el ancho posible aunque el
contenido sea pequeñito ocupan todo el
máximo posible del ancho otra de las
características es que a nivel de altura
tienen la altura del contenido que
tienen si tienen un contenido muy alto
también serán muy altas otra de las
características es que los diferentes
elementos de tipo blog están totalmente
juntos se pueden separar evidentemente
con margen pero si no no hay ningún tipo
de espacio entre ellos y la siguiente
característica es que aquí porque tienen
el 100% pero si yo por ejemplo les digo
que tengan una anchura más pequeñita
aquí aunque pudieran caber los dos
siempre siempre siempre siempre se
colocan uno debajo del otro aunque
puedan caber más si yo por ejemplo aquí
creo otro tipo de cajas como podrían ser
por ejemplo los h1 h2 h3 que también son
cajas o bien por ejemplo los párrafos
que evidentemente también son cajas y
aquí los añado el h1 y también el pe que
tienen las mismas características y ahí
me puede decir oye ja pero es que ya no
están separados bueno sí porque los hace
uno aparte de ser cajas también tienen
otras propiedades como por ejemplo pues
que las letras son más grandes tienen un
margen por arriba y por abajo igual que
los párrafos que tienen por arriba y por
abajo algún tipo de margen si yo quiero
quitarle ese margen y poner de un margen
para todos de los nichos por ejemplo lo
pondré de esta manera son elementos ya
lo digo de tipo block en que se
diferencian con los de tipo inline por
ejemplo que serían totalmente la
display: inline (enlaces, span...)
antítesis los elementos de tipo inline
por ejemplo los enlaces y por ejemplo un
spot que sería otra etiqueta que también
tendría el display inline se pone de
aquí y los vemos aquí en la parte
inferior dos enlaces y un espacio bien
ahora mismo yo aquí voy a aplicarle
estas mismas características tanto a los
dos enlaces como al spam que son de tipo
in line y vemos que funcionan de manera
diferente por una parte los elementos de
tipo
ocupan el ancho que necesitan
estrictamente para el contenido quiere
decir que si aquí pongo por ejemplo tres
veces este elemento es más ancho porque
el contenido también lo es por lo cual
sólo utilizan el ancho que necesitan
pero cuidado no se puede modificar ni el
ancho ni el alto porque yo aquí tengo
que ocupen 200 píxeles y aquí no se les
añade los 200 píxeles por lo cual es así
la altura la que necesiten pero si yo
por ejemplo aquí le añadiera a todos en
200 clics de altura las cajas se adaptan
a esta altura pero los in line no los
inline no permiten fijar la anchura y la
altura son como son por eso nadie quiere
ser inline voy a poner aquí un poquito
menos nota característica los inline
como veis también tienen una separación
entre ellos de separación no es un
margin es natural ese espacio no se
puede quitar con css no es un margen la
única manera para que se suscribirá
juntos sería venir aquí y escribir de
manera seguida sin ningún tipo de
espacios en el html y ahora si este
espacio es el espacio del margin pero si
yo quitar aquí el margin y lo suprimiera
aparecerían aquí juntos aquí están los
margin del h 1 y el margin del del
párrafo voy a añadir otra vez el marco
bien y luego tenemos a los otros
elementos que son lo voy a dejar como
estaba porque realmente la escritura
todo juntos un poquito difícil de
display: inline-block; (imágenes, input, botones...)
después de editar el tercer tipo son las
etiquetas que son de nacimiento ya de
tipo inline blog como pueden ser por
ejemplo los botones como pueden ser por
ejemplo los imputan y en la verde nada
más o como puede ser las imágenes aquí
le voy a poner una imagen que tengo en
mi web perfecto maravilloso genial muy
bien pues bien estas tres etiquetas son
de tipo inline blog si yo le añado aquí
añado los botones añado también el input
y añado también la imagen vemos cómo se
forman un poquito aquí los elementos de
tipo inline block se les puede añadir el
ancho y también se puede modificar el
alto también al igual que los elementos
de tipo inline tienen una separación por
defecto entre ellos además tienden a
colocarse en la misma línea y cuando
evidentemente ya no caben pues bajan a
la línea de abajo pero se les puede dar
cualquier tipo de propiedad aquí
evidentemente está deformada porque
claramente una imagen de todo el cuadro
de 200 x 50 y esta imagen pues tiene un
tamaño determinado no pero siguió por
ejemplo quito la altura adoptarán todas
la altura que necesite bien y ahora
Usos indebidos de display
venimos a la parte interesante que son
dos usos del display que son totalmente
incorrectos voy a hacer lo siguiente voy
a la imagen que está aquí suelta y
normalmente las imágenes pues van
alimento de cajas claro voy a sustituir
la por ésta con lo cual nuestro div
ahora contiene una imagen evidentemente
está influenciado por esto voy a excluir
de fs a nuestro día y también a nuestra
imagen para que no tengan borde
y nada de aquí conozco a la imagen y la
caja no tiene ningún tipo de css ahora
el dip y la imagen les voy a dar un css
o una parte le voy a dar un borde pero
más pequeñito del implan para poder
verlos y aquí veo el problema que al ser
una caja ocupa todo el ancho y yo quiero
que ocupe el ancho del contenido
evidentemente lo que podría hacer para
solucionar este problema es a nuestro
bip a la imagen no hace falta porque la
imagen ya lo es a nuestro bip le daría
un display inline glock
le cambiaría el display y de esta manera
a la caja pues adoptaría el ancho de su
contenido y además si hubiera otro dip
con otra imagen iba a tener la misma se
colocaría a la derecha vale tiene varios
problemas esto hay un problema que es el
espacio que hay entre una imagen y la
otra a nivel horizontal y la otra el
espacio y por abajo
para el espacio horizontal una solución
muy cutre pero salchichera pero que no
funcionaría sería añadirlo así y de esta
manera eliminaríamos los espacios que
hay entre los elementos que es el
problema de inline blog y para
solucionar este espacio de abajo lo que
podríamos hacer de manera incorrecta del
todo sería cambiar el display de la
imagen para convertirlo en una caja en
vez de que sea inline blog y de esta
manera estaría todo pegado pero esta
solución como vemos es muy complicada es
muy poco lógico porque esto aquí pues
aquí me interesa que está pegado y
nombre pues seguir cambiando todos los
enlaces todos los blogs sería un poquito
complicado entonces la solución para
esto sería la siguiente primero para el
espacio de trabajo
no cambiamos el display de una imagen lo
que hacemos es utilizar la propiedad
vertical online y le damos cualquier
valor por ejemplo todo esta manera
solucionamos este espacio sin tocar el
display bien el otro problema el de la
separación de las imágenes que ahora se
ve correctamente porque he convertido
sus cajas en inline block claro pues
bien tampoco le pondríamos un display
inline blog por tanto lo que haríamos
sería eliminar esto el display de las
cajas que sean cajas igualmente y si
Solución: display: flex
queremos que estas dos imágenes estén en
la misma fila lo que haremos sería crear
aquí otra caja puede ser un sexo puede
ser otro día inclusive pero para hacerlo
más sencillo le ponemos un sección aquí
que engloba a las dos y a este sexo le
damos un display flex para que todos los
hijos que tiene este section coloquen en
la misma fila y se ponen juntos y además
al ancho que necesiten etcétera etcétera
el display flex no hay ningún elemento
que a la hora de crear lo sea display
flex pero nosotros lo podemos añadir
también podríamos añadir aquí
pero entonces lo que haríamos sería nada
en concreto lo que necesitaríamos con el
display flex y también con el display
grid es añadir nuevas propiedades que no
vamos a ver en este vídeo porque si no
sería muy largo para poder hacer lo que
quisiéramos en este caso porque el
display flex y el display grid es otro
mundo que si alguien tiene interés aquí
arriba os dejo la descripción pues ha
inquirido a la lista de reproducción
donde lo explico a la perfección y con
todo lujo de detalles otro de los usos
El caso display:none
este si útil es el display no vamos a
hacer por ejemplo de todos los elementos
que tenemos aquí vamos a ocultar este
por ejemplo el h1 bien yo el h1 lo
podría ocultar lo voy a poner al final
para que se aplique al final aunque aquí
también le aplicó a la h1 unas
propiedades aquí le voy a añadir otras
diferentes si yo por ejemplo aquí le
digo display none a laxe 1 el h 1 ya no
se me ve y el resto de elementos que
habían debajo se han movido para ocupar
su lugar sí evidentemente si yo no
quiero un elemento lo mejor es no
escribirlo aquí pero normalmente esto lo
que haríamos sería hacerlo pues con
javascript o bien con la pseudo clase
alguna pseudo clase de fs como por
ejemplo yo aquí lo que hay muy bien pero
voy a ponerle aquí un púber para que
solamente ejecute el display none cuando
el cursor se coloque encima del h 1 por
lo tanto al colocarme encima el h 1
desaparece y evidentemente cuando saco
el cursor de su interior vuelve a
aparecer pero qué ocurre que si os dais
cuenta cuando esto se oculta el resto de
elementos no dejan el hueco sino que se
coloque para arriba si yo quiero que
La alternativa: visibility: hidden
deje el hueco para que no esté todo
moviéndose todo el rato lo que haría
sería sustituir el display por la
propiedad visibility que evidentemente
es otra y por tanto no tiene el valor no
sino que visibility lo que hace es
ocultar un elemento con el valor hayden
con lo cual dejaría el hueco hago clic y
deja el hueco el resto de elementos no
se mueven y yo creo saco el cursor de
encima vuelve otra vez a aparecer pero
el resto de elementos no tienen ningún
tipo de movimientos y hasta a veces nos
puede interesar o a veces no y esto nos
lleva también a otra posibilidad que es
Cambio automático del display
que hay veces que diferentes propiedades
modifica el display sin que nosotros lo
hagamos como por ejemplo el difunto
float que nos faltan y que lo miréis
porque ya los utiliza para nada aunque
existe y también flex en este caso por
ejemplo si nosotros los enlaces de aquí
vamos por ejemplo a los enlaces y
los meteremos dentro del lápiz sería lo
más lógico para los nab bueno pues tal
aquí hizo una caja entre otra caja vamos
a quitar todo esto de aquí aquí tenemos
los enlaces y aunque yo aquí le dijera
que la sas que la hemos visto antes
tuvieran un ancho de 200 pixels
evidentemente no hace ningún tipo de
caso porque son elementos de tipo inline
pero si yo a la caja que lo contiene es
decir al nab que lo borrado este es el
borrado
le doy un display flex lo que hace es
convertir los hijos que hay dentro del
nab que son los enlaces le convierte el
display y en vez de inline lo pone en
blog y esto hace que el tema de la
automática porque si fueran inline no sé
posible cambiar muchas de sus
propiedades y esto lo hace flex por
tanto a la metodología de añadir los
enlaces dentro de una lista como se
hacía antes es cosa del pasado lo
metemos dentro de una caja de tipo now y
ya está y no hay que hacer absolutamente
nada y es más por ejemplo para ver la
Ejemplo del uso de flex (con mediaqueries)
potencia de flex si yo me voy a los
enlaces aquí
añado unos cuantos más voy a cambiar un
poquito
se colocan aquí bien en la parte
superior aquí le digo que tengan como
hay cuatro que tengan el 25 por ciento
cada uno y podría modificar a la hora de
añadir display flex podría añadir algún
tipo de más de características pero la
potencia está en que cuando yo por
ejemplo aquí añado que cuando la
pantalla del navegador sea como máximo
600 es decir de ser a 600 yo le podría
cambiar a este nadie aquí a la hora de
ponerle un display flex automáticamente
se añaden otras propiedades pero una de
ellas del nap el display flex se
mantiene pero aquí como explicó en un
vídeo que podéis ver pueda utilizar la
propiedad flex direction que es de
display flex para cambiar la disposición
para que los elementos estén en columna
pero únicamente cuando el ancho del
navegador sea menos de 600 y además de
esto yo le puedo decir con el display
flex
uno de ellos por ejemplo esta vez que yo
quiero por ejemplo que sea la primera le
puedo decir que la a que se el hijo
número uno primero de ellos
bueno pues quiero que tenga un orden
diferente en vez de ser el orden 1234 lo
puedo poner por ejemplo al principio
para que tenga un orden y está en primer
lugar esto sólo se puede hacer con
display flex luego grid tiene otras
características para todo el tema de
media queries y demás yo os recomiendo
un vídeo que dejaré en la descripción
también por hacia arriba en las que
podéis ver esto de una manera mucho más
detallada pero aquí en este vídeo lo que
le interesa básicamente es indicar que
el display flex modifica el display de
los hijos que tiene su interior igual
que el grid y exactamente igual aunque
ya no se utiliza que el difunto flow
Consejo personal de JAB
aconsejo que veas este vídeo accedas a
este completo curso de javascript y te
suscribas al canal para estar al tanto
de todas las novedades
[Música]

