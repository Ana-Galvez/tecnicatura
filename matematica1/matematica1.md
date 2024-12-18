## Teoría de conjunto
- Es una lista o colección de objetos bien definidos que tienen algo en común y de cualquier tipo. Los objetos son los elementos del conjunto.
### Notación
- Para los conjuntos letra mayúscula A,B,G,H, ...
- Para los elementos letra minúscula a,b,g,h, ...
### Conjunto vacío
- Es el conjunto que no posee elementos
- Se representa como ∅ o {}
### Pertenencia
- si x es un elemento del conjunto A, entonces x pertenece a A, x ∈ A.
- si x no es un elemento del conjunto A, entonces x no pertenece a A, x ∉ A.
### Formas de representación
1. Por extensión: enumerando todos y cada uno de sus elementos ej el conjunto V posee como elementos a las vocales  V= {a,e,i,o,u}
el conjunto P posee como elementos a los números pares   P={2,4,6,8,...}

2. Por comprensión: diciendo cuál es la propiedad que los caracteriza  ej el conjunto V posee como elementos a las vocales V={vocales} o V={x:x es vocal} V es el conjunto de todas las x tal que x es vocal   : = tal que
el conjunto P posee como elementos a los números pares  P={pares}  P={x:x es par}
práctica - A={1,2,3,4,5}   ==>  A={x ∈ N : x <= 5}
B={...,−3,−2,−1,0,1,2,3,4,5}  ==>   B={x ∈ Z : x <= 5}
C={−2,−1,0,1,2,3,4}   ==>  C={x ∈ Z : -2 <= x <= 4}

### Diagrama de Venn
- Representación gráfica de los conjuntos y sus elementos. El o los conjuntos se dibujan como un círculo u óvalo y sus elementos con un punto (.) y escribiendo el elemento. Los círculos u óvalos se superponen para ver si tienen una intersección.

![Ejemplo esquema operaciones entre conjuntos](./operaciones-entre-conjuntos.png)
### Cardinal de un conjunto
- Es la cantidad de elementos que posee un conjunto. Se denota con # ej V={a,e,i,o,u} ==>  #V=5
L={x:x es letra del alfabeto} ==>  #L=27
P={2,4,6,8,...}  ==> #P=∞
### Relaciones entre conjuntos
1. Igualdad
- Se dice que A=B si tienen los mismos elementos, sin importar si los elementos se repiten y/o están ordenados de diferentes formas
ej C={1,2,3,4}, D={4,3,1,2,3,1}, E={1,3,1,2,4,2,1}  ==>  C=D=E
2. Desigualdad
A≠B si no hay elementos iguales
3. Inclusión
- Un conjunto A está incluido en un conjunto B, si todo elemento de A también está en B  A⊆B, también se dice A es subconjunto de B
  - Subconjunto propio
   - B es subconjunto de A, si B es subconjunto y tiene menos elementos que A.  B⊊A  sería B⊆A y B≠A
### Conjunto Universal
- Es el conjunto que agrupa a todos los conjuntos. Se denota con U con un rectángulo en el diagrama de Venn
- Sus elementos dependeran de lo que se esté desarrollando.
ej A={1,4,7}  su conjunto universal puede ser variado, como, los números naturales, los números enteros o el conjunto {1,2,3,4,5,6,7,8,9} o cualquier otro conjunto.

![Ejemplo conjunto universal](./diagrama-de-venn-conjunto-universal.png)
### Operaciones entre conjuntos

![Ejemplo esquema operaciones entre conjuntos](./operaciones-entre-conjuntos.png)
1. Unión: la unión de A∪B(A unión B) son todos los elementos de A, también todos los elementos de B y también los elementos comunes entre A y B
ej A={b,i,r,o,m,e} y B={j,p,e} ==>  A∪B ={b,i,r,o,m,e,j,p}

![Ejemplo operación unión](./operacion-union.png)
ej C={1,3,5}, D={2,4,6} y E={7}  ==> C∪D∪E={1,2,3,4,5,6,7}

![Ejemplo operación unión](./operacion-union-2.png)
ej A={1,2,3} y B={1}  B⊊A ==>  A∪B=A  ==> porque todos los elementos B están dentro del conjunto A

![Ejemplo operación unión](./operacion-union-3.png)

2. Intersección: son los elementos que tienen en común todos los conjuntos
A∩B A intersección B  y en símbolos  A∩B={x:x∈A y x∈B}
ej A={b,i,r,o,m,e} y B={j,p,e} ==> A∩B={e}

![Ejemplo operación intersección](./operacion-interseccion.png)
ej P={1,2,3,4,5,6}, Q{5,6,7,9} y R{4,5,6,9,10}
P∩Q∩R ={5,6}

![Ejemplo operación intersección](./operacion-interseccion-2.png)
ej A={1,2,3} y B={1} B⊊A ==> A∩B=B ==> porque todos los elementos B están dentro del conjunto A

![Ejemplo operación intersección](./operacion-interseccion-3.png)

3. Diferencia: son aquellos elementos que están en un conjunto pero que NO pertenecen a los otros conjuntos
A-B   A-B={x:x∈A y x∉B} y de esto se deduce que A-B⊊A
ej A={b,i,r,o,m,e} y B={j,p,e}  A-B={b,i,r,o,m}

![Ejemplo operación diferencia](./operacion-diferencia.png)
PERO NO ES LO MISMO A-B QUE B-A
B-A={j,p}

![Ejemplo operación diferencia](./operacion-diferencia-2.png)
4. Complemento: son aquellos elementos que solo pertenecen a los demás conjuntos y NO al conjunto mencionado o que NO pertenecen a la operación descripta.
ej U-A ==> es el complemento de A respecto de U ==> A<sup>c</sup>
ej U={a,e,i,o,u} y A={e,i} ==> A<sup>c</sup>=U-A={a,o,u}

![Ejemplo operación complemento](./operacion-complemento.png)

ej conjunto A y conjunto B
Complemento de A  A<sup>c</sup>

![Ejemplo operación complemento](./operacion-complemento-2.png)
ej conjunto A y conjunto B
Complemento de B  B<sup>c</sup>

![Ejemplo operación complemento](./operacion-complemento-3.png)
ej conjunto A y conjunto B
Complemento de A∩B

![Ejemplo operación complemento](./operacion-complemento-4.png)
ej conjunto A y conjunto B
Complemento de A∪B

![Ejemplo operación complemento](./operacion-complemento-51.png)


### Ejercicios 
- A={ x : x ∈ Z, -3 < x >= -1 }
- B={ x + 8 : x ∈ N, x < 5}
- C={ x ∈ N, -6 <= x >= 6}
- D={ (x+5)/2 : x ∈ N, x < 5}
---------------------------------------------------

- A={1,2,3,4,5,6}
- B={2,4,6,8,10}
- C={5,6,7,8,9}
1. (B∩C)∪(A∩B)
2. (A∪B)∩C
3. (A∩C)∩(B∪C)
4. (A∩B)∪C
----------------------------------------------------
- U={a,b,c,d,e,f,g}
- A={a,b,c,d}
- B={a,c,e,g}
- C={b,e,f,g}
1. A<sup>c</sup> - B
2. (A-C)<sup>c</sup>
3. (B<sup>c</sup>∪C)<sup>c</sup>
4. (A∪B)∩(C<sup>c</sup>-A<sup>c</sup>)

## Conjuntos Numéricos
### Números Naturales N
- se la puede representar en una semirrecta
1. Primer conjunto de Números usados
2. Números enteros positivos: donde hacia la izquierda es un número menor y a la derecha un número mayor
3. ordenado, inifinito, discreto
4. Su primer elemento es el 1
5. Conjunto discreto: entre 2 N dados, hay otros N entre ellos
6. Al sumar 2 o más N su resultado es otro N, lo mismo para multiplicar
### Números Enteros Z
- se la puede representar en una recta
1. Conjunto ordenado, infinito, discreto.
2. No tiene primer Número
### Números Racionales Q
- División entre 2 naturales y surge la fracción
1. Puede representarse como fracciòn o decimal o que es la división de la fracción.
2. Tiene decimal finito
3. Entre 2 racionales hay otros Q  conjunto discreto o de orden denso
4. En la recta se los pone con punto
### Números Irracionales I
1. Número que tienen infinitas cifras no periódicas(que no tienen el mismo patrón)
2. No puede representarse como fracciòn
- pi  Euler   muchas raices cuadradras: ej de 2,3,5,7,11,83

- Solo un número puede ser Q o I, nunca ambos pero siempre Real

### Intervalos
1. Intervalo Abierto: no incluye
2. Intervalo cerrado: incluye
3. Intervalo semicerrado: si hay () no incluye y si tiene [] incluye
4. Los infinitos siempre van abierto

## Relaciones
- R es una relación de A en B, si y solo si R está incluida en el producto cartesiano (AxB)
- A es conjunto de partida y B conjunto de llegada
- El par (x,y)  se lo simboliza (x,y) pertenece a R
- y=R(x)  o sea x e y están relacionados

### Pares ordenados
- (x,y) no es igual a (y,x)
- primera coordenada o 1 componente, segunda coordenada o 2 componente

### Producto cartesiano (AxB)
- De 2 conjuntos A y B (AxB) es el conjunto de todos los pares ordenados (x,y), siendo que x pertenece a A e y pertenece a B
- AxB={(x,y):x E A, y E B}
- Piso x Letra  3 pisos 4 letras
- P x L= {(1,a),(1,b),(1,c),(1,d),(2,a),(2,b),(2,c),(2,d),(3,a),(3,b),(3,c)(3,d)}
- cantidad de elementos #P=3 #L=4  #P x L=12

### Representación de los productos cartesianos
1. X extensión
2. X comprensión
3. Diagrama sagital
4. Diagrama cartesiano

### Dominio
- Son los elementos del conjunto de partida que intervienen en una relación
### Imagen o rango
- Son los elementos del conjunto de llegada que intervienen en una relación

### Representación de las relaciones
1. Verbal
2. Simbólica
3. Tabla de valores
4. Gráfica
5. Diagrama sagital

## Funciones
- es una relación entre 2 conjuntos, donde a todos y cada uno de los elementos de partida le corresponde solo un elemento de llegada
- Existencia: es cuando todos los elementos de partida tienen una relación.
- unicidad: es cuando cada elemento de partida tiene solo un elemento de llegada
- dominio: elementos del conjunto de partida 
- codominio: elementos del conjunto de llegada
- imagen, rango o conjunto imagen: elementos del conjunto de llegada que intervienen en una relación
- Puntos notables: son las coordenadas que ayudan a construir de forma gráfica un función

### Representación de funciones
1. Verbal
2. Simbólica
3. Tabla de valores
4. Diagrama sagital
5. Gráfico

### Tipos de funciones
1. Polinómicas
- Hay de diferentes grados: grado 0 es constante, grado 1 lineal, grado 2 cuadrática, etc
- Las potencias deben ser enteras, ejemplo x elevada a la 1/2 no es polinómica   raíz de 3 tampoco
- En principio, porque depende la función el dominio son todos los reales
- En principio, porque depende la función la imágen son todos los reales
- Raíz o raíces del polinomio o ceros de la función, desde 0 hasta el grado del polinomio. Es cuando y vale 0
- Ordenada al origen: cuando x es cero

2. Racionales
- Son aquellas que en su fórmula tiene una fracción   ej   (5x+2)/(x-3)
- El numerador y denominador deben ser funciones polinómicas
- Siempre verificar que valor de x en el denominador da 0 para excluirlo
- El dominio de una función racional en principio son todos los reales excepto el valor que hace que el denominador sea 0
- La imagen en principio son todos los reales excepto si no hay raíces que se exceptua el valor
- Las raíces desde 0 a 1, si al calcular la raíz da 0 es porque no corta al eje x
- La ordenada cuando x es 0, pero hay que ver que el 0 no anule al denominador, si lo anula entonces no hay ordenada al origen
- Tiene asíntota vertical: línea imaginaria vertical que indica que la función racional se acerca a la asíntota pero nunca la toca
  - Su valor no pertenece al dominio de la función. Pero hay que analizar que el o los valores que no pertenecen al dominio no anulen el numerador de la función.
- Tiene asíntota horizontal: línea imaginaria horizontal que indica que la función racional se acerca a la asíntota pero nunca la toca
  - se debe tener en cuenta el grado del polinomio del numerador y denominador:
  1. si el grado del numerador es menor que el denominador: la asíntota H es y=0
  2. si el grado de numerador es = que el denominador: la asíntota H es   y= (coeficiente principal del numerador)/(coeficiente principal del denominador)
  - El coeficiente principal es el número que acompaña a la x que tiene el mayor grado
  3. si el grado del numerador es mayor que el denominador: la función no tiene asíntota H
- Función homográfica: es si el cociente entre 2 polinomios de grado 1 no comparten raíces

3. Irracionales
- Aquella que tiene raíz y dentro debe ser un polinomio o racional  ej √4x-3
- si la raíz es par, lo de adentro no puede dar negativo
- dominio: si raíz par entonces dom mayor o igual que 0,  si raíz impar son todos los reales

4. Exponenciales
- cuando la x es la potencia y su base es mayor a 0 y su base diferente a 1, porque sino sería constante   ej a elevado x+2*3
- Siempre tienen asíntota horizontal

5. Logaritmicas
- siempre tienen asíntota vertical

## Límites
- es el valor al que se acercan las imágenes cuando los valores de x se acercan a un valor concreto o a valores cada vez más grandes

### Propiedades
1. el límite de una constante, es la misma constante
2. el límite de la función cuando f de x=x  es tiende a x  es X
3. potencia entera positiva en la x , también es el tiende a x 
4. raiz entera positiva de x tiembien es el tiende a X
5. el límite de una suma o resta es la suma o resta de los límites de cada término
6. el límite de un producto es el producto de los limites
7. el límite de una constante por una función es la constante por el límite de la función
8. el límite de un cociente es la división de los límites siempre que el cociente no sea cero
9. el límite de una potencia es la potencia del limite
10. el limite de la raiz es la raiz del limite
11. sustitución directa

### Limites al infinito
- cuando x toma valores muy grandes

