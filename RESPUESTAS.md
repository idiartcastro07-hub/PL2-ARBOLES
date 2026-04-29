Pregunta 1: Las diferencias que podemos encontrar entre los dos programas de prueba al ejecutarlo son: en el primer programa la suma del subárbol izquierdo es 0 
y el del derecho es la suma total porque al estar distribuidos en orden creciente todos los elementos de árbol quedan a la derecha(arbol desequilibrado). Sin embargo, 
en el segundo programa observamos que el arbol ya está más equilibrado puesto que al añadirlo aleatoriamente, los elementos se dividen entre izquierda y derecha. La diferencia
en la altura entre los dos programas se reduce a que en el primero, como esta desequilibrado para la derecha, los 128 elementos añadidos al arbol forman un nivel distinto mientras
que en el segundo como es mas equilibrado y se reparten a ambos lados la altura siempre va a ser menor. En el camino observamos que en el primero se recorre desde la raiz(0) hasta 
el dato seleccionado(110) y en el segundo te dan una lista de los nodos del arbol desde nodo raiz hasta dato final(que sera de menor longitud); por tanto, el camino del primero es mas largo(lo sera 
siempre al estar en desiquilibrio). Finalmente,la longitud del primer programa es más grande a comparación del segundo justamente por lo que hablabamos del camino, el primero recorrerá los 111 elementos(0-110) y 
el segundo la lista dada. 

Pregunta 2: Si ejecutamos el programa varias veces, el primer programa seguirá dando siempre igual puesto que lo insertamos en orden. En el segundo programa, sin embargo, al añadirlos aleatoriamente
se generarán listas con elementos nuevos lo que modificarán la altura, camino y longitud dependiendo del tamaño de dicha lista y conservarán la suma al ser siempre los mismos elementos.
