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