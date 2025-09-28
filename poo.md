# POO

### Descripción

Este proyecto de consola muestra ejemplos de uso de POO en java:

Interface Trabajador

* Interface que obliga la implementación del método trabajar()
* paquete interface

Clase Abstracta Persona

* Clase abstracta que implementa la interface Trabajador, además de los atributos nombre, edad, constructor, getter y setter de nombre, getter de edad y el método abstracto mostrarInfo()
* paquete model

Clase EmpleadoException

* En esta clase se agrega una excepción personalizada para la clase empleado
* paquete exceptions

Clase Empleado

* Clase que implementa la clase abstracta persona y la interface Trabajador, miembros estáticos empresa y contadorEmpleados, atributo salario, constructor, getter contadorEmpleados, getter de salario, métodos mostrarInfo() y trabajar()
* paquete model

Clase Gerente

* Clase que implementa la clase Empleado, atributo departamento, constructor, métodos mostrarInfo() y trabajar()
* paquete model

Clase Desarrollador

* Clase que implementa la clase Empleado, atributo lenguaje, constructor, métodos mostrarInfo() y trabajar()
* paquete model

Clase DatabaseConnection

* Clase que implementa la conexión a base de datos oracle, miembros estáticos url, usuario, password, instancia y la propiedad conexion, constructor que hace la conexión a base de datos, getter de instancia y conexion,
* paqete db

Clase EmpleadoDAO

* Clase que implementa el create y findAll de la clase empleado, métodos insertarEmpleado(), obtenerEmpleados()
* paquete dao

Clase EmpleadoRepository

* Clase que implementa los métodos de empleado, atributo Map de empleados y contador de empleados, métodos agregarEmpleado(), obtenerEmpleado(), listarEmpleados(), eliminarEmpleado()
* paquete repository

Archivo ojdbc11.jar

* Librería oracle connector para version 21.3 XE
* paquete lib

Clase Main

* Se crean objetos empleado, gerente y desarrollador
* Se visualiza polimorfismo con for mostrando clase persona con los objetos creados
* Prueba de exception personalizada
* Conexion a oracle
* Insertar empleados
* Se crean empleados
* Recorrido de empleados
* Creacion de map
* listar empleados
* Buscar empleado
* Eliminar empleado

src/\
└── poo/\
├── Main.java\
├── db/DatabaseConnection.java\
├── dao/EmpleadoDAO.java\
├── exceptions/EmpleadoException.java\
├── interfaces/Trabajador.java\
├── model/Persona.java\
├── model/Empleado.java\
├── model/Gerente.java\
├── model/Desarrollador.java

└── lib/ojdbc11.jar\
└── repository/EmpleadoRepository.java

### Requisitos

* Java 17+ (recomendado)
* IDE como IntelliJ, Eclipse o VS Code

