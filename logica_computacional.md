## Definición de Lógica Computacional

- La lógica computacional es una rama de la lógica matemática que se enfoca en el uso de conceptos lógicos para resolver problemas en informática y computación. Se basa en la lógica proposicional y en la lógica de predicados, proporcionando un marco para la representación, análisis y manipulación de información de manera formal.

## Objetivo de la Lógica Computacional
- El objetivo principal de la lógica computacional es proporcionar una base teórica y práctica para la resolución de problemas relacionados con el procesamiento de información y la toma de decisiones en sistemas computacionales

- **Desarrollar algoritmos efectivos**: La lógica ayuda a formular y analizar algoritmos para garantizar su corrección y eficiencia.
- **Diseñar circuitos digitales**: La lógica computacional es fundamental para el diseño de circuitos digitales y sistemas electrónicos.
- **Garantizar la corrección del software**: La lógica permite verificar y validar que el software se comporte de acuerdo con las especificaciones.
- **Resolver problemas complejos**: Aplicar técnicas lógicas para resolver problemas complejos en áreas como inteligencia artificial, teoría de la computación y criptografía.

## Conceptos Básicos de Lógica y su Importancia en la Computación
- **Proposición**: Es una declaración que puede ser verdadera o falsa, pero no ambas cosas al mismo tiempo.
- **Operadores Lógicos**: Son símbolos utilizados para conectar proposiciones y formar expresiones lógicas, como AND (∧), OR (∨), NOT (¬), entre otros.
- **Tablas de Verdad**: Herramientas para determinar el valor de verdad de expresiones lógicas basadas en todas las combinaciones posibles de valores de entrada.
- **Álgebra Booleana**: Rama del álgebra que utiliza variables binarias y operaciones lógicas para simplificar y analizar expresiones lógicas.

## Historia y Evolución
### Orígenes de la Lógica:
- **Lógica Aristotélica**: La lógica formal tiene sus raíces en la antigua Grecia con Aristóteles, quien desarrolló el
sistema de lógica proposicional que estudia el razonamiento deductivo y los silogismos.
- **Desarrollo en la Edad Media**: Durante la Edad Media, la lógica aristotélica se expandió y se integró con la filosofía escolástica, dando lugar a nuevas formas de análisis y argumentación.
### Lógica en la Computación:
- **Lógica Booleana**: A mediados del siglo XIX, George Boole formalizó el álgebra booleana, que se convirtió en una base fundamental para el diseño de circuitos digitales y la teoría de la computación.
- **Computación Digital**: A principios del siglo XX, con el advenimiento de los primeros ordenadores electrónicos, la lógica booleana se aplicó para construir circuitos lógicos y sistemas de procesamiento digital.
- **Teoría de la Computación**: En la década de 1930, Alan Turing y otros pioneros desarrollaron la teoría de la computación, introduciendo conceptos como las máquinas de Turing, que formalizaron la idea de algoritmos y computabilidad.
- **Lenguajes de Programación y Lógica Formal**: A medida que los lenguajes de programación evolucionaron, la lógica formal se integró en el diseño de lenguajes y en la verificación de software. La lógica de predicados, la teoría de tipos y otros
conceptos lógicos se aplicaron en la creación de lenguajes de
programación y sistemas de verificación.

## Proposiciones
- **Definición de Proposición**: Una proposición es una declaración que tiene un valor de verdad definido: es verdadera (V) o falsa (F). Las proposiciones son los bloques básicos de la lógica proposicional y se utilizan para construir expresiones más complejas.

### Proposiciones Atómicas:
- **Definición**: Son las proposiciones más simples que no se pueden descomponer en otras proposiciones más básicas. Cada proposición atómica representa una afirmación que puede ser verdadera o falsa.
- Ejemplos:
1. p: "El sol es una estrella."
2. q: "El agua hierve a 100°C."
3. r: "La Tierra es plana."

### Proposiciones Compuestas:
- **Definición**: Son proposiciones formadas combinando proposiciones atómicas mediante conectivas lógicas. La verdad de una proposición compuesta depende de la verdad de sus componentes.
- Ejemplos:
1. p∧q: "El sol es una estrella y el agua hierve a 100°C."
2. p∨r: "El sol es una estrella o la Tierra es plana."
3. ¬q: "No es cierto que el agua hierve a 100°C."

## Conectivas Lógicas
### Conjunción (AND, ∧):

- **Definición**: La proposición compuesta p∧q es verdadera si y solo si ambas proposiciones p y q son verdaderas.
- Tabla de Verdad:

p------------------q--------------p∧q<br>
V------------------V--------------V<br>
V------------------F--------------F<br>
F------------------V--------------F<br>
F------------------F--------------F<br>

### Disyunción (OR, ∨):
- **Definición**: La proposición compuesta p∨q es verdadera si al menos una de las proposiciones p o q es verdadera.
- Tabla de Verdad:

p-----------------q-------------------p∨q<br>
V-----------------V-------------------V<br>
V-----------------F-------------------V<br>
F-----------------V-------------------V<br>
F-----------------F-------------------F<br>

### Negación (NOT, ¬):
- **Definición**: La proposición compuesta ¬p es
verdadera si p es falsa y viceversa.
- Tabla de Verdad:

p--------------¬p<br>
V--------------F<br>
F--------------V<br>

### Implicación (→):
- **Definición**: La proposición p→q es falsa solo cuando p es verdadera y q es falsa. En todos los demás casos, es verdadera.
- Tabla de Verdad:

p-----------------q----------------p→q<br>
V-----------------V-----------------V<br>
V-----------------F-----------------F<br>
F-----------------V-----------------V<br>
F-----------------F-----------------V<br>

### Bicondicional (↔):
- **Definición**: La proposición p↔q es verdadera si p y q tienen el mismo valor de verdad, ya sea ambos verdaderos o ambos falsos.
- Tabla de Verdad:

p---------------q-----------p↔q<br>
V---------------V-----------V<br>
V---------------F-----------F<br>
F---------------V-----------F<br>
F---------------F-----------V<br>

## Compuertas Lógicas Avanzadas
### NAND (Negación de AND):
- **Definición**: La proposición compuesta ¬(p∧q) es verdadera si al menos una de las proposiciones p o q es falsa.

p∧q-----------¬(p∧q)<br>
V--------------F<br>
F--------------V<br>

### NOR (Negación de OR):
- **Definición**: La proposición compuesta ¬(p∨q) es verdadera solo cuando ambas proposiciones p y q son falsas

p∨q------------¬(p∨q)<br>
V---------------F<br>
F---------------V<br>


