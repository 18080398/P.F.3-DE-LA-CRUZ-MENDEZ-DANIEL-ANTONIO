# P.F.3-DE-LA-CRUZ-MENDEZ-DANIEL-ANTONIO
PROYECTO FORMATIVO 3
Como se presenta este proyecto formativo, trato sobre la compresión del sistema de redes petri.
El conocimiento adquirido fue que es una representacion grafica de un sistema de eventos discretos en el cual se puede describir la topologia de un sistema distribuido. en pocas palabras son grafos bipartidos que tienes tres objetivos
1. lugares son los puntos donde se aloja la informacion y se retienen.
2. transiciones se puede referir la conexion con otro punto.
3. arcos de orientados son aquellos que definen la orientacion de si va hacia la derecha, atras, izquierda, derecha o se repite. 
De una forma mas clara seria como un proceso de control ya que al hacer una accion produce una respuesta. El ejemplo mas reconocido seria un bagon que se tiene que mover del punto A al punto B, el punto seria representado como el bagon ya que es el que se movera , entonces la transicion sera que quiere moverse del punto A al punto B, para que al final el arco sera en que sentido se movera a la izquierda o derecha. 
Este tipo de red pueden variar dependiendo a lo que nos solicitan como seria hacer el mismo ejemplo pero con dos bagones, esto llevaria una estructura mas compleja por la razón que se tiene que colocar todas las combinaciones que tiene, como estar en la misma posicion, moverse juntos, moverse inversamente, etc. 
Con esto comprendido tenemos el conocimento de como funciona y pudimos comprobarlo en la practica de codificador binario que al ingresarr un dato, este transformaria el numero de salida cambiado y es facil de hacer, claro conociendo una logica concreta.
Con esto dicho, ¿que funcion tiene el archivo .ino? Este es un sistema de red petri que al ingresar la tecla A o B crea un codigo binario que cambiara dependiendo que tecla uses. esto demuestra lo anterior mencionado ya que al combinar letras, crea las combinaciones de variables como si fuera un decodificador de 7 segmento de 4 bits. 
