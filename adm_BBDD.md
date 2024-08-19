## BBDD
- colección de datos interrelacionados que garantiza la consistencia, integridad y seguridad de los mismos, para servir a diferentes aplicaciones. Los datos se guardan independientemente de las aplicaciones que se usen.

### Modelo relacional
- se usan filas(datos/registros) y columnas(atributos/campos)

### Datos
- representación simbólica que por sí solo no tiene significado que representa un hecho o realidad

### Información
- son los datos ya procesados y ordenados que permiten tomar decisiones y entender su contexto. Es el significado de los datos

- en la BBDD se guarda 2 TIPOS DE INFORMACIÓN
1. DATOS DE USUARIOS: los que usan las app
2. DATOS DE SISTEMA: los que utiliza para su gestión ej permiso de usuarios

### BBDD organizada
1. Ser versátil
2. Rapidez
3. Alta integridad: los menores errores posibles al modificar la BBDD cuando hay muchos usuarios tocando
4. Alta seguridad y privacidad: no solo el robo de información, sino la destrucción física de los medios de almacenamiento
5. Actualización y que sea mantenible
6. Indepencia física y lógica de los datos: ya sea al cambiar de medio físico o por ejemplo agregar nuevos campos

### Sistema de información
- colección de datos debidamente recopilados y estructurados que ayudan a administrar, recolectar, recuperar, procesar, almacenar y distribuir información relevante a la organización.
1. Sistema de información de software
2. Sistema de información de hardware

### ¿Por qué usar BBDD y NO planillas de cálculos?
- Redundancia: la falta de control del tipo de datos o datos repetidos
- Estandarización: ingresar en un formato diferente el mismo tipo de dato ej fechas
- Seguridad

### Sistema gestor de base de datos (SGBD) (DataBase Managment System DBMS)
- Es un sistema que permite crear, administrar y consultar la BBDD como también el manejo de las estructuras necesarias para almacenar la información.

### Clientes gráficos o programas para BBDD
- son las aplicaciones que nos permiten realizar y manipular las BBDD, como sus tablas y datos.

### Transacciones
- son operaciones lógicas que se ejecutan como una única unida atómica de trabajo

### Paradigma ACID (A: atomicidad, C: consistencia, I(Isolation, Aislamiento), D: durabilidad)
- Es la inicial de 4 propiedades para realizar transacciones de forma segura
1. ATOMICIDAD: determina que cada transacción es "todo o nada", si una transacción falla, todas sus operaciones se anulan, inclusive las anteriores a la operación que tuvo el error, por lo que la BBDD no sufre cambios. En esta propiedad se encuentras también las fallas de energía eléctrica o caída del sistema
2. CONSISTENCIA: los datos tienen que ser válidos
3. AISLAMIENTO(Isolation): que cada transacción es independiente de la otra
4. DURABILIDAD: es cuando ya se realizó una transacción al estar confirmada, si al instante sucede algo no esperado, esa transacción no debe sufrir cambios

### Niveles de Abstracción
1. NIVEL INTERNO O FÍSICO: es el más bajo de todos los niveles. Describe como se almacenan los datos y como es el detalle de las estructuras de datos complejos. ej en que parte de memoria se guardan. Los programadores o administradores no pueden ingresar a este nivel
2. NIVEL CONCEPTUAL O LÓGICO: describe que datos se guardan y sus relaciones y tipos
3. NIVEL EXTERNO O DE VISTA: es el más alto y muestra solo una parte de la BBDD(lo que quiere ver el usuario y que por cuestiones de seguridad se debe ocultar) ej un cajero automático, cuando un cliente desea extraer dinero, el cajero solo va a entrar a la cuenta del cliente y no a todos los clientes del banco

### Entidad
- Objeto sobre el cual queremos registrar información. Dentro de la BBDD es una tabla. Cada columna tiene un tipo de dato definido.

### Nivel de abstracción lógico o conceptual
- describe que datos son almacenados y sus relaciones (estructura de diseño). Este nivel lo usan los adm de BBDD que deciden que información guardar.
- Esta decisión consta de diferentes tareas:
1. Definición de los datos: titulo de columna, tipo de datos y/o longitud y otras propiedades
2. Relaciones entre datos.

### Modelos de datos
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



