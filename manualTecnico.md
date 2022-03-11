## **Proyecto 1 - Progamación Orientada A Objetos**

### Integrantes:

- Juan Ignacio Gándara
- Sebastián Hernández
- Nicolás Izquierdo

### Tabla de contenidos
- Introducción 
- Objetivos
- Funcionalidades
- Funcionalidades del programa:
  - Clases
  - Métodos
  - Entradas
  - Salidad
- UML 

### Introducción
<ul> 
    
El siguiente programa consiste en la implementación de una base de datos para una veterinaria, este cliente ha colocado cierta cantidad de requisitos que se deben de   cumplir durante la condificación, así como en el diseño y comodidad de su uso. En el siguiente manual técnico del programa realizado, daremos una explicación generalizada del código a partir del enunciado dado por la profesora en su github [POO](https://github.com/lufe089/POO/blob/main/Proyecto/ClinicaVeterinaria.pdf).

 </ul>
 
 ### Objetivos

<ul> Los objetivos de este proyecto son:
  <p>     
  <ol>  
    <li> Practicar los conceptos de clase, atributo, método y objeto. </li> 
    <li> Practicar el mecanismo de paso de mensajes entre objetos de una clase. </li>
    <li> Entender la relación entre diagramas de clase UML y código. </li>
    <li> Practicar el uso de constructores. </li>
    <li> Practicar el uso de mapas y vectores. </li>
    <li> Practicar el modelado de relaciones de muchos a muchos con entidades intermedias. </li>  
  </ol>
  </p>
  <p>  
  El objetivo general como estudiantes, es poder darle respuesta al enunciado cumpliendo los objetivos propuestos.
  </p>
  </ul>
  
### Funcionalidades

  <u1> El siguiente programa tiene la funcionalidad de una base de datos, es capaz de almacenar información específica de la clase propietario, de la misma forma que almacena información acerca de la clase Mascota. Además, existe diferentes relaciones a tener en cuenta entre las clases que podemos encontrar en el programa. 
  
  Función Main:
  <p>## **Proyecto 1 - Progamación Orientada A Objetos**

### Integrantes:

- Juan Ignacio Gándara
- Sebastián Hernández
- Nicolás Izquierdo

### Tabla de contenidos
- Introducción 
- Objetivos
- Funcionalidades
- Funcionalidades del programa:
  - Clases
  - Métodos
  - Entradas
  - Salidad
- UML 

### Introducción
<ul> 
    
El siguiente programa consiste en la implementación de una base de datos para una veterinaria, este cliente ha colocado cierta cantidad de requisitos que se deben de   cumplir durante la condificación, así como en el diseño y comodidad de su uso. En el siguiente manual técnico del programa realizado, daremos una explicación generalizada del código a partir del enunciado dado por la profesora en su github [POO](https://github.com/lufe089/POO/blob/main/Proyecto/ClinicaVeterinaria.pdf).

 </ul>
 
 ### Objetivos

<ul> Los objetivos de este proyecto son:
  <p>     
  <ol>  
    <li> Practicar los conceptos de clase, atributo, método y objeto. </li> 
    <li> Practicar el mecanismo de paso de mensajes entre objetos de una clase. </li>
    <li> Entender la relación entre diagramas de clase UML y código. </li>
    <li> Practicar el uso de constructores. </li>
    <li> Practicar el uso de mapas y vectores. </li>
    <li> Practicar el modelado de relaciones de muchos a muchos con entidades intermedias. </li>  
  </ol>
  </p>
  <p>  
  El objetivo general como estudiantes, es poder darle respuesta al enunciado cumpliendo los objetivos propuestos.
  </p>
  </ul>
  
### Funcionalidades

  <u1> El siguiente programa tiene la funcionalidad de una base de datos, es capaz de almacenar información específica de la clase propietario, de la misma forma que almacena información acerca de la clase Mascota. Además, existe diferentes relaciones a tener en cuenta entre las clases que podemos encontrar en el programa. 
  
  Función Main:
  <p>
    <ol>
    La función main en nuestro programa cumple la labor de un menú creado a partir de un ciclo Do While y un switch, esto permitirá al usuario permanecer en el programa siempre y cuando lo desee y pueda elegir que acción tomar dentro del programa. Inicialmente se declara la variable administracion de tipo Administracion cuyos atributos serán los mapas que guardarán la información de las clases Mascota, Propietario y Enlace. Dentro del menú dependiendo de la opción que elija el usuario, se llamará a las funciones que permitirán agregar, editar, eliminar y listar la información tanto de mascotas como de propietarios, además la opción de enlazar, permitirá al usuario atribuirle muchas mascotas a un propietario o viceversa. Finalmente la última opción (opción 0) permitirá al usuario finalizar el programa.
    </ol>
  </p>
  Archivo Makefile:
  <ol>
  La función principal del archivo Makefile es compilar el programa, con sus diferentes objetivos, dependencias e instrucciones. Cuenta con 7 objetivos, entre estos podemos encontrar el objetivo clean cuyo objetivo es eliminar cada archivo de código objeto y limpiar el programa. El objetivo compilar cuya función es compilar las funciones principales y finalmente los objetivos, propietario, mascota, administracion, enlace y main, con las instrucciones de guardar cada una de las funciones del programa.
  </ol>
  Cabecera mascota.h
  <p>
  En la siguiente cabecera se crea una clase llamada mascota, con los siguiente atributos:
  <ol>
     <li> estatus </li> 
     <li> fechaDeDefuncion </li> 
     <li> identificacion </li> 
     <li> nombre </li> 
     <li> tipoDeSangre </li> 
     <li> edad </li> 
     <li> peso </li> 
     <li> tipo </li> 
     <li> raza </li> 
   </ol>
   Y sus respectivos métodos, que son los constructores, setters y getters, donde se nos permitirán establecer los valores a los atributos de nuestra clase Mascota, además, de poder sacar y mostrar la información que contengan los atributos de la clase 
  </p>
  Función Mascota
  <p>
  <ol>
    En el siguiente archivo se llama a la dependencia mascota.h, y a partir de esto hacemos uso del constructor para asignarle las variables que utilizaremos y posteriormente cambiaremos para los atributos de la clase mascota, posteriormente se crea la función imprimirInformacion con el propósito de mostrar al usuario los valores de los atributos de la clase Mascota y finalmente le asignamos los valores obtenidos a los atributos de la clase Mascota.
  </ol>
  </p>
  Cabecera propietario.h
  <p>
  En la siguiente cabecera se crea una clase llamada Propietario, con los siguientes atributos:
  <ol>
    <li> nombre </li> 
    <li> email </li> 
    <li> Documento de identidad </li> 
    <li> telefono </li> 
  </ol>
  Y sus respectivos métodos, que son los constructores, setters y getters, que funcionarán de la misma manera que la cabezera de mascota.
  </p>
  Función Propietario
  <p>
  <ol>
    En la función propietario se hace llamado a la cabecera propietario.h y cumple la misma funcionalidad que la función Mascota.cpp
  </ol>
  </p>
  Cabecera administracion.h
  <p>
  <ol>
    En la siguiente cabecera se crea una clase llamada Administracion, la cual será fundamental en el desarrollo de nuestro programa, ya que la principal función de esta clase es contener como atributo los mapas donde se almacena la información tanto de la clase Mascota como de la clase Propietario, así como el vector que guardará la información acerca de las mascotas enlazadas a dueños. Sus métodos serán las funciones que puede realizar el usuario con la información, como por ejemplo editar, agregar, eliminar, listar y enlazar la información de las mascotas y los dueños. 
  </ol>
  </p>
  Función Administrador
  <p>
  <ol>
  En la siguiente función haremos llamado a la cabecera administracion.h, a partir de esto crearemos las funciones que podrá realizar el usuario en el programa, en este caso se podrá enlazar las mascotas a propietarios o viceversa haciendo llamado a la función enlace que recibirá las clases de propietario y mascota. Podrá imprimir la información de los atributos de las clases, agregar nuevas mascotas y propietarios, editar la información de estos y finalmente eliminarlos.
  </ol>
  </p>
  Cabecera enlace.h
  <p>
  <ol>
    La siguiente cabecera recibe como dependencias las cabeceras de mascota y propietarios, de las cuales sacaremos variables de tipo mascota y de tipo propietario, además, las usaremos como atributos de la nueva clase que crearemos llamada Enlace. Entonces enlace recibirá como atributos a mascota de tipo Mascota y propietario de tipo Propietario, y sus métodos será un constructor y dos gets, uno que pertenece a la clase propietario y otro que pertenece a la varibale mascota, este nos permitirá extraer la información. 
  </ol>
  </p>
  Función Enlace
  <p>
  <ol>
    Esta función va a recibir como dependencia la cabecera enlace.h, a partir de aquí se hará llamado a al constructor para enlazar el propietario a la mascota o la mascota al propetario, información que después será guardada en el vector.
  </ol>
  </p>
  </u1>
  
 ### UML
 
 ![Imágen UML](https://user-images.githubusercontent.com/98536590/157802670-62a40d56-cbba-427b-84fe-d39bc2264521.PNG)
