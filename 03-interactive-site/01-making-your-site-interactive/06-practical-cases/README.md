# Casos prácticos (videos)
- Tipo: `lectura`
- Formato: `self-learning`
- Duración: `60min`

## Objetivos

- Entender, a través de casos prácticos, cómo aplicar los conceptos de navegar
y manipular el DOM, y a responder a eventos.

***

## Enunciados

Al igual que hemos hecho antes, es hora de aplicar los conceptos aprendidos
para resolver problemas.

A continuación tendrás varios problemas que debemos resolver. Intenta
resolverlos primero por tu cuenta. Más abajo encontrarás las soluciones
de Michelle. Después de haberlo intentado, compara tus soluciones
con las de Michelle.   

#### 1. Reserva de puestos aerolínea

Una pequeña aerolínea acaba de comprar una computadora para su nuevo sistema de reservaciones automatizada. Se te ha pedido que desarrolles el nuevo sistema. Escribirás una aplicación para asignar asientos en cada vuelo del __único__ avión de la aerolínea (capacidad: 10 asientos).

![GitHub Logo](https://image.ibb.co/eMz26v/avion_2.jpg)

Tu aplicación debe mostrar las siguientes alternativas:

Por favor escriba 1 para Primera Clase y Por favor escriba 2 para Económico.

![GitHub Logo](https://image.ibb.co/mh9PKF/avion_3.jpg)

Si el usuario escribe 1, tu aplicación debe asignarle un asiento en la sección de primera clase (asientos 1 a 4). Si el usuario escribe 2, tu aplicación debe asignarle un asiento en la sección económica (asientos 5 a 10).

Tu aplicación deberá entonces imprimir un pase de abordar, indicando el número de asiento de la persona y si se encuentra en la sección de primera clase o clase económica.

![GitHub Logo](https://image.ibb.co/d8gtDa/avion_4.jpg)


### Tips para la solución

A continuación, encontrarás tips que podrían ayudarte con la solución, ¡mucha suerte!

#### [Tip. | Diagrama de flujo]

![GitHub Logo](https://image.ibb.co/bQ86Ya/untitled_8.jpg)


#### [Tip. | Representación usando Arrays]

Usa un arreglo unidimensional del tipo booleano para representar la tabla de asientos del avión. Inicializa todos los elementos del arreglo con -false- para indicar que todos los asientos están vacíos. A medida que se asigne cada asiento, establezca el elemento correspondiente del arreglo en true para indicar que ese asiento ya no está disponible.

Tu aplicación nunca deberá asignar un asiento que ya haya sido asignado. Cuando esté llena la sección económica o primera clase, tu programa deberá preguntar a la persona si acepta ser colocada en la sección de primera clase (y viceversa).

![GitHub Logo](https://image.ibb.co/nH4rzF/avion_6.jpg)

Si la persona acepta, haga la asignación de asiento apropiada.

Si no, debe imprimir el mensaje “El proximo vuelo sale en 3 horas”.

![GitHub Logo](https://image.ibb.co/d2Hpmv/avion_7.jpg)


#### 2. Buscaminas
El juego de buscaminas funciona de la siguiente forma:

Se muestra una tabla donde se encuentran celdas vacías, con número o con minas. En caso de oprimir una mina entonces el juego termina, si se oprimen lugares sin minas (vacia o de número), el juego continúa.

![Buscaminas](https://lh4.googleusercontent.com/c4jnMEV2CirXxh8CRzP1y6_VSqfPOLNQnTGyv2uKyPzEMfa42ztBClyMCigW7K3dJqNWacIJDjaj-kfVDFWtQbHySxNhSSRBPVnf2Q2SbHK3MUkWD0WMpsVyXeUAfrI11ya9heW5lng)

##### Preguntas guia
- ¿Cómo puedes estructurar el tablero en el navegador? (pista: HTML)
- ¿Cómo puedes diferenciar una bomba de un número ó de una celda vacia en el HTML?
- ¿Qué evento necesitas para captar el click del usuario?
- Una vez que el usuario haga click sobre la "celda", ¿Que tiene que pasar?
- ¿Como podemos hacer que elementos aparescan y desaparescan en el HTML?
- ¿Como hacemos para que ya no se puedan ingresar clicks del usuario? (hint: remove EventListener)

##### Requerimientos
- Mostrar una tabla de 4 x 4 (con bombas, celdas vacías y números en posición fija)
- Al dar clic en una celda vacía cambiar de color de la celda.
- Al dar clic en una celda con bomba, terminar el juego (no debo poder clickear mas celdas) y mostrar mensaje: “Esto ha explotado”
- Al dar click en una celda con un número, mostrar el número que tiene.
- Crear un botón Re iniciar que reinicie el juego.

##### Puntos extras
- Al dar clic fuera de la tabla mostrar mensaje: “Sigue jugando”. (inner html o alert).
- Preguntar el tamaño de la tabla al usar.
- Preguntar el nivel de dificultad deseada (fácil, nivel, difícil, y significa el número de bombas que tendrá)
- Llenar de manera automática todo (bombas, celdas vacías y números)

#### 3. Crear un menu de hamburgesa.

Un menu de hamburgesa nos permite tener escondido el menu y únicamente mostrar un boton (3 lineas horizontales) que cuando lo apretamos (o hacemos click), se muestra en la pantalla todas las opciones del menu.

Algo asi:

![Hamburger Menu](http://i.imgur.com/JKJ8V9v.gif)

Replicar esa funcionalidad usando DOM y CSS. (No agregar efectos "bonitos", únicamente enfocarse en funcionalidad)

#### 4. Crear tabs

Las tabs nos sirven para agrupar contenido similar usando solo un espacio.

Algo asi:

![Tabs Menu](https://diypm8fk7dlz0.cloudfront.net/support/wp-content/uploads/2014/06/simulate-tabs.gif)

Replicar esa funcionalidad usando DOM y CSS. (No agregar efectos "bonitos", únicamente enfocarse en funcionalidad)

#### 5. Crear un menu drop down

El menu drop down nos ayuda a ahorrar espacio en un menu, ya que agrupa elementos similares.

Algo asi:

![Drop Down Menu](https://cdn.codemyui.com/wp-content/uploads/2016/06/jQuery-Dropdown-Navigation-Menu.gif)


## Solucionarios

A continuación, Amalia, Karla e Inti te explican cómo resolvieron cada uno de los
ejercicios anteriores.  

#### 1. Aerolinea

[![Solución aerolínea](https://img.youtube.com/vi/ov2pYXulNvc/0.jpg)](https://www.youtube.com/watch?v=ov2pYXulNvc)

#### 2. Buscaminas

[![Solución Buscaminas](https://img.youtube.com/vi/ZtnY3ojz91k/0.jpg)](https://www.youtube.com/watch?v=ZtnY3ojz91k)

#### 3. Menú de Hamburgesa

[![Solución Menu Hamburgesa](https://img.youtube.com/vi/ej2MVZpPaoM/0.jpg)](https://www.youtube.com/watch?v=ej2MVZpPaoM)

#### 4. Tabs

[![Solución Menu Tabs](https://img.youtube.com/vi/nEKbaKIat1g/0.jpg)](https://www.youtube.com/watch?v=nEKbaKIat1g)


#### 5. Menú dropdown

[![Solución Menu Drop Down](https://img.youtube.com/vi/yV7L6r6D464/0.jpg)](https://www.youtube.com/watch?v=yV7L6r6D464)


***

[Continuar]()