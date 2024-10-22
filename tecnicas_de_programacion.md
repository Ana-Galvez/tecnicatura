## Informática
- del francés informatique (acrónimo de información y automático). Procesamiento automático de la información

## Programación
- es una disciplina que busca lograr soluciones a determinados problemas usando la computadora
- Los programas realizan:
  1. Acciones sobre los datos
  2. Acciones que actuan sobre sí mismas (flujo de control - 1. Condicional o bifurcación  2. Ciclo o iteración)
  - Cada acción debe tener 1 solo punto de entrada y 1 solo punto de salida

## Construcción de un programa
1. Formulación o Enunciación: leer el enunciado y analizar los elementos que aparecen y si se necesitan más datos y/o realizar hipótesis. También ver de tener todos los elementos para lograr esa solución.
2. Desarrollar el algoritmo: ya sea con diagrama de flujo o pseudocódigo.
3. Codificación: con el lenguaje de programación seleccionado.
4. Ejecución del programa.

## Ciclo de vida de un programa
1. Diagramación: esquema o dibujo con la secuencia lógica de los pasos para resolver el problema.
  1. Formulación del problema:  qué es lo que queremos solucionar, qué queremos lograr con el programa
  2. Analizar el problema: analizar los pasos lógicos 
  3. Desarrollar el algoritmo
  4. Diseño
2. Codificación: expresar el diagrama con un lenguaje de programación.

## Metodología Top Down (modularización)
- Es un enfoque en donde prima el divide y vencerás, o sea, que un gran problema se divida en problemas pequeños. Lo que es en programación se usa en la programación modular, precisamente porque divide por módulos, o sea, es partes lo que es la codificación y/o archivos.
- Mayor legibilidad: al estar separado el código, se hace más entendible
- Mayor productividad: al ser problemas más pequeños se le puede asignar a diferentes personas cada problema. También en lo referente a los tiempos de realización del programa, no solo por cantidad de programadores sino también  en encontrar errores.

## Pseudocódigo
- lenguaje de alto nivel, casi al lenguaje humano, que permite que los algoritmos puedan ser entendidos tanto por los humanos y por las máquinas. Es un paso previo a la codificación. Es un esquema básico del programa.

## Algoritmo
- En general es un conjunto de pasos para realizar una tarea. ej  lavarse los dientes, prepararse un cafe, ir a un lugar
- Conjunto preescrito, sea en gráfico o palabras, de instrucciones o reglas BIEN DEFINIDAS(debe ser bien clara, no generar ninguna duda), ORDENADAS(pasos sucesivos) Y FINITAS(tienen un principio y un final), que permite realizar una tarea mediante pasos sucesivos.
### Características
- Precisión: reglas bien definidas
- Finito: finito, principio y fin
- Eficacia: reglas sencillas para ser realizadas y en tiempo de respuesta
- Entrada: puede ser 0 o más entradas. Cantidad de datos de inicio (escrito en el algoritmo o generado por él) (Estado inicial o input)
- Salida: puede ser 1 o más resultados o datos. (Resultado o output)

### Cómo se representan los algoritmos
1. Diagrama de flujo: son gráficos donde se usan símbolos conectados por flechas y están regidos por ISO. Sirven para algoritmos pequeños
2. Pseudocódigo: forma escrita de un algoritmo para que una persona lo entienda y lo pueda usar en cualquier lenguaje de programación
3. Sistemas formales 4. Variables  5. Estructuras secuenciales

### Los algoritmos en informática
- Son los que permiten diseñar los programas
- Sin algoritmos no existirían los programas
- Pueden estar en cualquier lenguaje y computadora

### Cómo se codifica un algoritmo
- Una computadora entiende el sistema binario (0 y 1), por lo que necesitamos de un compilador para qué el algoritmo codificado sea entendido por la computadora y que luego mande la respuesta para que entienda el ser humano.
- Se escribe el código(programa fuente) y luego se lo va a compilar (probar el programa)
  1. Si hay algún error, se detiene la compilación y obvio hay que buscar el error y volver a compilar
  2. Si no hay error, el programa va a arrancar( ejecuta el programa): es el proceso donde la máquina lleva a cabo las instrucciones del código
- El programador es el que buscar y debe resolver los problemas usando la computadora. (es el que realiza el programa)


## Dato
- valor o representación simbólica de algo concreto pero que por sí solo no significa nada. ej 18  18 qué?
1. Datos simples: enteros(number, int), reales(decimales, float, double, decimal), cadena(string), lógico(true o false, bool, boolean). Son aquellos datos que ya no pueden reducirse más.
2. Datos compuestos: son datos que dentro de estos pueden contener más datos, ya sean simples y/o compuestos. Array, objetos.

## Información
- Grupo de datos ya procesados y ordenados que nos permiten tomar decisiones y en programación podemos sumar el resolver problemas.

## Variable
- Es un contenedor de datos o información que se le da un nombre y un tipo de dato, guardandose en la memoria mientras funciona el programa( memoria ram)
- Según el tipo de dato se puede realizar diferentes operaciones
1. Aritmética
2. Lógicas
  - operadores relacionales
  - operadores lógicos
3. Cadena de caracteres

### Cómo se declara una variable (como se la crea)
- definir nombre_variable como tipo_de_dato  ej  Definir edad como Entero
- Una variable debería estar como sustantivo y ser la mejor representación del o de los dato/s
- Una variable no puede comenzar con Número, pero luego puede contener números  ej Definir 1edad como Entero  MALLLLLLLLLLLLLLL  ej Definir edad123 como Entero  Bien pero no tan bien porque no es la mejor representación
- Una variable no puede comenzar con muchos símbolos, excepto _(guión de abajo) ej _edad Bien pero medio raro, es para casos específicos de algún lenguaje de programación. OJO, HAY LENGUAJES DE PROGRAMACIÓN QUE PUEDEN ACEPTAR OTROS SIGNOS AL PRINCIPIO, ej javascript acepta $
ej BIEN  Definir edad_mayor como Entero,   Definir nombre como Cadena,  Definir numero1 como Entero

### Estilos de codificación o escritura
1. camelCase: diaDeLaSemana
2. PascalCase: DiaDeLaSemana  o también llamado UpperCamelCase
3. snake_case: dia_de_la_semana
4. kebab-case: dia-de-la-semana
5. Train-Case: Dia-De-La-Semana

### Constante
- Es un tipo de dato de variable donde su valor nunca va a cambiar (datos simples)

### Metodología Top Down (modularización)
- Divide y vencerás: de un gran problema, dividirlo en problemas
- Mayor legibilidad
- Mayor productividad: porque cada pequeño problema se le puede asignar a diferentes personas

## Programa informático
- Es una estructura formada por una secuencia de acciones (instrucciones) y que manipula un conjunto de objetos(datos o información)

### Bloques de la estructura
1. Bloque de declaraciones: donde se detallan los datos e información (variables, constantes, archivos, etc)
2. Bloque de instrucciones: acciones que se llevan a cabo para conseguir los resultados esperados.
- Esta dividido en 3 partes:
1. Entrada de datos: instrucciones que almacenan en la memoria interna del programa los datos que vienen de afuera
2. Proceso o algoritmo: intrucciones que modifican los datos o info o crea nuevos
3. Salida de resultados: instrucciones que muestran los datos finales de la memoria interna

### Tipos de estructuras
1. Estructura de secuencia: es aquella en la que una instrucción sigue a otra, o sea, termina una y comienza otra.
2. Estructura de decisión: es aquella en la que se debe tomar una decisión para que continue el programa. Se realiza una acciones dependiendo de las alternativas. Si Sino Si Sino. Segun variable Hacer, De otro modo
3. Estructura de repetición, cíclica, iterativa o de bucles: permite ejecutar un conjunto de instrucciones de manera repetida mientras la expresión lógica sea verdadera

### Tipos de estructura de repetición
1. Ciclo exacto: Valor inicial-final, se repite el ciclo Para cada valor intermedio (PARA)
2. Ciclos condicionales:
- Mientras sea verdadero Hacer (MIENTRAS condición HACER)
- Hacer al menor 1 vez y repetir Mientras se cumpla (HACER MIENTRAS)

- PARA variabledentrodepara = inicio HASTA FIN CON PASO cantidad HACER FIN PARA
- MIENTRAS variable condición HACER FIN MIENTRAS
- REPETIR loquesequiera MIENTRAS QUE condición

## Contadores
- variable que cuenta.
- contador=valor inicial
- contador =contador + - Nº

## Acumuladores
- Es como un contador pero el valor de incremento o decremento es un valor variable

## Prueba y depuración
- Permite identificar y eliminar errores (bugs)
1. Mentalidad saboteadora
2. Sospechar de todos los resultados
3. Considerar todas las situaciones

## Tipos de errores
1. Errores de compilación: suelen ser errores de sintaxis, entonces la computadora no puede comprender la instrucción
2. Errores de ejecución: instrucciones que la computadora entiende pero no puede ejecutar. ej división por cero, raíces cuadradas de números negativos.
3. Errores de lógica: son los más difíciles de detectar, el programa funciona y no tira errores pero el resultado no es el esperado

## Documentación
- externa e interna
1. Descripción del problema
2. Nombre del autor
3. Diagrama y/o pseudo
4. Variables y constantes
5. Codificación

## Prueba de escritorio
- simulación del comportamiento de un algoritmo para determinar la validez del mismo
- se detecta errores en tiempo de ejecución, de lógica para mejorar el algoritmo
- se hace una tabla donde se ingresan las variables y mostrar los pasos que se muestran por pantalla.

## Max min
- Dar a la variable un valor
- al max se le da un valor pequeño
- al min un valor grande

## Arreglos
- conjunto de variables del mismo tipo que pueden ser referenciadas a traves de un mismo nombre: Las variables se almacenan en posiciones contiguas de memoria.
1. finita
2. homogénea
3. ordenada
- vectores: arreglos unidimensionales
- matrices : bidimensionales

- Definir nomArreglo como tipo
- Dimension nomArreglo[cant]

### Ordenamiento
- Procesamiento de reorganizar un conjunto dado de objetos en una secuencia determinada
- x máximos sucesivos: no es el más efectivo porque realiza muchos recorridos del arreglo y muchas comparaciones, por lo tanto, es mucho tiempo de procesamiento
- Se intercambian los valores según ascendente o descendente.

## Matrices
- Tabla de doble entrada. Primera dimensión es filas, segunda es columna

## Modularización
- La programación modular cosiste en definir módulos, usando abstracción de procedimientos. Se puede separar el que hace el módulo del cómo lo hace
- La abstracción reduce algunos aspectos irrelevantes, concepto o proceso para enfocarse en los aspectos más importantes y generales
1. Reutilización de código en el mismo programa u otros
2. los programas se vuelven flexibles y transportables
3. divide un gran problema en problemas pequeños y se puede testear y depurar con mayor facilidad y a la vez un código limpio y fácil de entender
4. Permite crear programas extensibles, o sea, programas que se pueden ampliar crando nuevos módulos
5. Permite que varios programadores puedan trabajar en el programa enfocandose en 1 o más modulos

