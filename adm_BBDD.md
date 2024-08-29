# BBDD
- colección de datos interrelacionados que garantiza la consistencia, integridad y seguridad de los mismos, para servir a diferentes aplicaciones. Los datos se guardan independientemente de las aplicaciones que se usen.

## Modelo relacional
- se usan filas(datos/registros) y columnas(atributos/campos)

## Datos
- representación simbólica que por sí solo no tiene significado que representa un hecho o realidad

## Información
- son los datos ya procesados y ordenados que permiten tomar decisiones y entender su contexto. Es el significado de los datos

- en la BBDD se guarda 2 TIPOS DE INFORMACIÓN
1. DATOS DE USUARIOS: los que usan las app
2. DATOS DE SISTEMA: los que utiliza para su gestión ej permiso de usuarios

## BBDD organizada
1. Ser versátil
2. Rapidez
3. Alta integridad: los menores errores posibles al modificar la BBDD cuando hay muchos usuarios tocando
4. Alta seguridad y privacidad: no solo el robo de información, sino la destrucción física de los medios de almacenamiento
5. Actualización y que sea mantenible
6. Indepencia física y lógica de los datos: ya sea al cambiar de medio físico o por ejemplo agregar nuevos campos

## Sistema de información
- colección de datos debidamente recopilados y estructurados que ayudan a administrar, recolectar, recuperar, procesar, almacenar y distribuir información relevante a la organización.
1. Sistema de información de software
2. Sistema de información de hardware

## ¿Por qué usar BBDD y NO planillas de cálculos?
- Redundancia: la falta de control del tipo de datos o datos repetidos
- Estandarización: ingresar en un formato diferente el mismo tipo de dato ej fechas
- Seguridad

## Sistema gestor de base de datos (SGBD) (DataBase Managment System DBMS)
- Es un sistema que permite crear, administrar y consultar la BBDD como también el manejo de las estructuras necesarias para almacenar la información.

## Clientes gráficos o programas para BBDD
- son las aplicaciones que nos permiten realizar y manipular las BBDD, como sus tablas y datos.

## Transacciones
- son operaciones lógicas que se ejecutan como una única unida atómica de trabajo

## Paradigma ACID (A: atomicidad, C: consistencia, I(Isolation, Aislamiento), D: durabilidad)
- Es la inicial de 4 propiedades para realizar transacciones de forma segura
1. ATOMICIDAD: determina que cada transacción es "todo o nada", si una transacción falla, todas sus operaciones se anulan, inclusive las anteriores a la operación que tuvo el error, por lo que la BBDD no sufre cambios. En esta propiedad se encuentras también las fallas de energía eléctrica o caída del sistema
2. CONSISTENCIA: los datos tienen que ser válidos
3. AISLAMIENTO(Isolation): que cada transacción es independiente de la otra
4. DURABILIDAD: es cuando ya se realizó una transacción al estar confirmada, si al instante sucede algo no esperado, esa transacción no debe sufrir cambios

## Niveles de Abstracción
1. NIVEL INTERNO O FÍSICO: es el más bajo de todos los niveles. Describe como se almacenan los datos y como es el detalle de las estructuras de datos complejos. ej en que parte de memoria se guardan. Los programadores o administradores no pueden ingresar a este nivel
2. NIVEL CONCEPTUAL O LÓGICO: describe que datos se guardan y sus relaciones y tipos
3. NIVEL EXTERNO O DE VISTA: es el más alto y muestra solo una parte de la BBDD(lo que quiere ver el usuario y que por cuestiones de seguridad se debe ocultar) ej un cajero automático, cuando un cliente desea extraer dinero, el cajero solo va a entrar a la cuenta del cliente y no a todos los clientes del banco

## Nivel de abstracción lógico o conceptual
- describe que datos son almacenados y sus relaciones (estructura de diseño). Este nivel lo usan los adm de BBDD que deciden que información guardar.
- Esta decisión consta de diferentes tareas:
1. Definición de los datos: titulo de columna, tipo de datos y/o longitud y otras propiedades
2. Relaciones entre datos.

## Modelos de datos
- El modelado de datos es el proceso de creación de una representación visual o esquema que define los sistemas de recopilación y administración de la información de cualquier organización. No solo los datos, sino tambièn sus relaciones y los métodos que se usarán para almacenarlos y analizarlos.
- Ventajas
1. Reduce errores en el desarrollo de software
2. Facilita la rapidez y eficacia en el diseño y creación de la BBDD
3. Facilita la comunicación entre los ingenieros de datos y los diferentes departamentos.

### Modelos de datos conceptuales
1. Incluye las entidades importantes y sus relaciones
2. No se especifica ningún atributo
3. No se especifica ninguna clave principal
- Se trata de organizar y clasificar la información en componentes simples que representen la información del negocio

### Modelos de datos físicos
1. Especifica todas las tablas y columnas (tipo, restricciones, PK, FK, relaciones)
2. La desnormalización puede ocurrir según los requisitos de usuario
- Pasos
1. Convertir entidades en tablas
2. Convertir relaciones en claves externas
3. Convertir atributos en columnas
4. Modificar el modelo en función de las restricciones/requisitos físicos

### Modelo de datos lógicos
- describe los datos con el mayor detalle posible
1. Se representan las entidades y sus relaciones
2. Se especifican los atributos para cada entidad
3. Clave principal y claves externas
4. La normalización ocurre en este nivel
- pasos
1. claves primarias
2. encontrar relaciones
3. describir todos los atributos
4. resolver las relaciones de muchos a muchos
5. normalización

### Ventajas de modelar
- Asegura que lo objetos se representen con precisiòn
- Es muy detallado para construir una BBDD fisica
- La info se puede usar para relación, claves primarias y externas y procediemtos almacenados.
- Ayuda a las empresas con la comunicación
- Permite documentar

### Desventajas
- Conocer características físicas de los datos almacenados
- los cambios más pequeños realizados en la estructura requieren modificaciones en toda la aplicación
- no hay lenguaje de manipulación de modelos establecido en DBMS

## Modelo Entidad-Relación
- Es una herramienta para el modelo de datos que facilita la representación de entidades de una BBDD.
- Gráficamente se lo expresa con un diagrama Entidad-Relación.
- Tienen limitaciones semánticas, por eso se suele utilizar los Diagramas Entidad-Relación extendidas
1. Integridad de Entidad: si una entidad tiene un atributo con clave primaria, nunca puede estar vacío
2. Integridad Referencial (de relación): si una entidad tiene una clave foránea, su valor debe ser igual a alguna tupla(filas) de la otra entidad asociada

### Entidad
- es un objeto del que se recoge información de interés para la BBDD
1. Entidad fuerte: son las que no dependen de otra entidad para existir, siempre tienen clave primaria
2. Entidad débil: siempre dependen de otra entidad, siempre tienen clave foránea.

### Relación
- vínculo entre entidades
#### Propiedades de una relación
1. Grados
  1. grado 1 o unario: relación sobre la misma entidad
  2. grado 2 o binario: relación entre 2 entidades
  3. grado 3 o ternario: relación entre 3 entidades
  4. grado n: relación entre 4 o más entidades
2. Conectividad
- Se refiere a la cardinalidad, que son las limitaciones en una relación
  1. Uno a uno: 1 a 1: ej presidente gobierna país, un solo presidente puede gobernar un solo país, un país solo puede ser gobernado por un presidente
  2. uno a muchos: 1 a M o 1 a N: una persona tiene muchos autos, pero los autos solo tienen una persona
  3. muchos a muchos: n a M o m a n: muchos profesores pueden enseñar muchas materias
3. Condicionalidad o modalidad
  1. Relación obligatoria: es cuando una entidad está sujeta a otra entidad, o sea es débil, ej estudiantes y cursos. Si es estudiante es porque está en un curso
  2. Relación optativa: cuando hay entidades qeu no tienen porqué estar sujetas a otra entidad, ej tutor y estudiante, no es necesario que todos los estudiantes tenga un tutor.

### Atributos
- son las propiedades de las entidades y el dominio es el conjunto de valores que puede tener ese atributo
#### Tipos de atributos
1. Identificador único-clave: aquellos atributos que tienen clave primaria
2. Atributos derivables: aquellos que resultan de operaciones con otros atributos. ej edad puede ser una operación de un atributo fecha de nacimiento - fecha actual
3. Atributos Multivaluados: aquellos que se necesitan más de 1 dato. ej teléfono, capaz se quiere no solo 1. Conviene hacer 1 tabla aparte
4. Atributos compuestos: aquellos que se podrían dividir en atributos más chicos porque casi todo su dominio es repetible. ej dirección se podría dividir en calle número ciudad provincia. Conviene hacer otra tabla
5. Atributos discriminantes: aquellos que tienen clave estando en una entidad débil

## Normalización
-Es una metodología que permite que las tablas eviten:
1. Redundancia de datos: datos repetidos y/o abundantes
2. Pérdidas en la integridad de datos
3. Anomalías de actualización:
  1. Anomalías de inserción: es cuando se agrega una tupla(fila) donde hay un campo que se está escribiendo diferente comparado a otro campo que ya se escribió lo mismo, pero el campo de la nueva tupla se escribió diferente
  2. Anomalías de borrado: borrar una tupla pensando que no sirve ningún campo o creyendo que los datos de los campos también están en otra tupla
  3. Anomalías de modificación: cuando se cambia el valor de un atributo en Gral. Habría que cambiar en todas las tuplas que anteriormente usaban el valor antiguo.

  ### Normas de la normalización
  - Son pasos que poseen la normalización que son secuencial a cada una se la llama forma normal, siendo de 1 a 5, aunque con las primeras 3 gralmente es suficiente. 1ºFN hasta 5ºFN.

  
  


