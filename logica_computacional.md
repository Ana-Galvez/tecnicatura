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

### Disyunción o Disyunción inclusiva(OR, ∨):
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

### Implicación (→) se reemplaza como entonces:
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

### XOR (Disyunción Exclusiva):
- **Definición**: La proposición compuesta p⊕q es verdadera si exactamente una de las proposiciones p o q es verdadera.

p-------------q-----------p⊕q
V-------------V-----------F<br>
V-------------F-----------V<br>
F-------------V-----------V<br>
F-------------F-----------F<br>

### NXOR (Negación de XOR, Equivalencia Lógica):
- **Definición**: La proposición compuesta ¬(p⊕q) es verdadera si p y q tienen el mismo valor de verdad.
p⊕q-----------¬(p⊕q)
V-----------------F
F-----------------V

### Equivalencia lógica ≡
- Es cuando se dicen 2 enunciados al revés y siguen siendo los mismos valores
- ej 1. los perros ladran y los gatos maullan, es lo mismo que 2. los gatos maullan y los perros ladran
p-------q-----p∧q------q∧p<br>
V-------V------V-------V<br>
V-------F------F-------F<br>
F-------V------F-------F<br>
F-------F------F-------F<br>

### Propiedad doblemente Negativa  ¬(¬p)≡p
- Significa que la negación de la negación de en enunciado es lógicamente equivalente al enunciado
p------¬p-----¬(¬p)≡p
V------F---------V
F------V---------F

## Tablas de Verdad
### Construcción de una Tabla de Verdad:
1. Identificar las Proposiciones Atómicas: Enumera todas las proposiciones atómicas involucradas.
2. Enumerar las Combinaciones de Valores de Verdad: Lista todas las posibles combinaciones de valores de verdad para las proposiciones atómicas.
3. Aplicar las Conectivas Lógicas: Calcula el valor de verdad de las proposiciones compuestas utilizando las
conectivas lógicas.

### Ejemplo de Tabla de Verdad:
- Para la expresión (p∧q)→r:
- Pasos:
1. Identificar las proposiciones atómicas: p, q, r.
2. Enumerar las combinaciones de valores de
verdad.
3. Aplicar la conectiva de conjunción a p y q, luego aplicar la implicación con r.

1-  p, q, r <br>
2- p------q----------r<br>
   V------V----------V<br>
   V------V----------F<br>
   V------F----------V<br>
   V------F----------F<br>
   F------V----------V<br>
   F------V----------F<br>
   F------F----------V<br>
   F------F----------F<br>

3-1 p------q----------r------p∧q<br>
   V------V----------V------V<br>
   V------V----------F------V<br>
   V------F----------V------F<br>
   V------F----------F------F<br>
   F------V----------V------F<br>
   F------V----------F------F<br>
   F------F----------V------F<br>
   F------F----------F------F<br>
3-2  p∧q----------r---------(p∧q)→r
      V-----------V---------V
      V-----------F---------F
      F-----------V---------V
      F-----------F---------V

## Valuaciones y Tautologías
### Valuaciones:
- **Definición**: Una valuación es una asignación específica de valores de verdad a todas las proposiciones atómicas en una expresión lógica.
- **Ejemplo**: Para la proposición p∨¬q, las valuaciones  posibles podrían ser (V,F)(V, F), etc., dependiendo de los valores asignados a p y q.

### Tautologías, Contradicciones Y contingencias:
- **Tautología**: Una proposición lógica es una tautología si es verdadera para todas las posibles valuaciones de sus variables.
- Ejemplo: p∨¬p es una tautología porque
siempre es verdadera, independientemente del
valor de p.
- **Contradicción**: Una proposición lógica es una contradicción si es falsa para todas las posibles valuaciones de sus variables.
- Ejemplo: p∧¬p es una contradicción porque
nunca puede ser verdadera.
- **Contingencia**: una proposición lógica es una contingencia cuando algunas de sus valuaciones dan verdadero y otras valuaciones dan falso.

### Cómo Determinar Tautologías y Contradicciones:
1. **Construir la Tabla de Verdad**: Para una expresión lógica, construye una tabla de verdad completa.
2. **Analizar los Resultados**:
- Si todas las salidas son verdaderas, la proposición es una tautología.
- Si todas las salidas son falsas, la proposición es una contradicción.
- Si hay una mezcla de verdaderas y falsas, la proposición no es ni una tautología ni una contradicción.

### Información lógica
- Aparte de preguntas, hay informaciónes que devuelven V o F, pero dependerá del momento, ej La Tierra gira alrededor del sol, V, pero hace 700 años hubiera sido F. La lógica analiza la realidad en un momento específico.

### Lógica proposicional o lógica de orden cero
- es la rama de la lógica matemática que estudia las propisiciones, los métodos de vincularlas por medio de los conectores lógicos, y las relaciones y propiedades que se derivan de dichos procedimientos.
#### Proposición
- es una entidad atómica de la lógica proposicional, que posee un valor de verdad (oración que da información sobre lo que podemos decir que es cierto o no). Se usa la función informativa del lenguaje (descriptiva o aseverativa). Debe tener sujeto, verbo y predicado y ser informativo
#### Funciones del lenguaje
1. Imperativa  vení ya   orden
2. exclamativa viva la libertad  emoción o deseo
3. interrogativa
4. informativa  el trabajo es complicado   info que puede ser V o F
- Solo la función  informativa corresponde a las proposiciones

### Proposiciones atómicas o simples
- son las proposiciones que ya no se pueden dividir, o sea, que no llevan conectivas lógicas

### Proposiciones compuestas
- Están formadas por proposiciones atómicas y/o proposiciones compuestas unidas por conectivas lógicas. ej El avión se estrelló o realizó un aterrizaje

### Indicadores
- son palabras o frases que indican una conectiva
- En conjunción: ",", y, tambièn, además, adicionalmente, en adición, incluso, inclusive, así mismo, de igual forma, del mismo modo, ahora, igualmente, sin embargo, no obstante, pero, pese, empero, aunque, aun así, a pesar de, tanto como, al igual que, por otra parte, más, no....ni...., aparte, por otro lado.
- en disyunción inclusiva: o, tal vez.... tal vez...., o de pronto, aunque de pronto, puede.... o puede....., aunque puede.
- en disyunción exclusiva: o bien
- en negación: no, no es cierto que, no es verdad q, ni

### Variables proposicionales
- Son letras que se les asigna a cada proposición atómica ej  p, q, r

### Pasar de lenguaje natural al lenguaje lógico
- ej  El avión se estrelló o realizó un aterrizaje y se encuentra incomunicado
1. ver conectores lógicos:  o    y
2. separar las proposiciones y darle una letra
  -  p= el avión se estrelló
  - q= el avión realizó un aterrizaje
  - r= el avión se encuentra incomunicado
3. Realizar el diccionario(pasar a símbolos)
  - p∨(q∧r)

  ### Leyes de Morgan p∧¬p∨≡
  1. La negación  de un enunciado Y es lógicamente equivalente al enunciado O donde cada proposición atómica es negada
  ¬ (p∧q) ≡ ¬p ∨ ¬q
  2. La negación de un enunciado O es lógicamente equivalente al enunciado Y donde cada proposición atómica es negada
  ¬ (p∨q) ≡ ¬p ∧ ¬q

  