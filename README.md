| Carrera: | INGENIERIA DE SISTEMAS | 
| --- | :--- |
| Materia: | TECNOLOGIAS EMERGENTES II  
| Apellidos y nombres: | BERTHY ALDAIR QUISPE APAZA | 
| C.I: | 9130999 L.P. | 
| Lugar y fecha: | EL ALTO 6 DE AGOSTO

**1) Explique que son los sistemas empresariales**

Sistemas empresariales son un conjunto integrado de sistemas de información que son herramientas que unifican los procesos que se llevan a cabo dentro de una empresa por medio de un software y hardware.

**2) Describa cuales son las características más importantes de una aplicación empresarial**

Características de una aplicación empresarial

1. **Disponibilidad** La capacidad de un sistema de ser accesible, teniendo un tiempo de inactiviadad limitado
2. **Capacidad** La capacidad de un sistema de ejecutar varias tareas dentro de un periodo de tiempo
3. **Extensibilidad** Lacapacidad de extender la funcionabilidad de sistema
4. **Flexibilidad** La capacidad de realizar cambios de configuracion, Manteniendo la integridad del sistema
5. **Manejabilidad** Lacapacidad de gestionar los recursos del sistema
6. **Rendimiento** La capacidad de realizar funciones dentro de objetivos especificos
7. **confiabilidad** La capacidad de garantizar la ntegridad y consisitencia del sistema y sus transacciones
8. **Reusabilidad** La capacidad de reutilizar un componente
9. **Escalabilidad** La capacidad de soportar la funcionabilidad cuando la carga aumenta
10. **Seguridad** La capacidad de garantizar la seguridad de la informacion 
11. **Validez** La capacidad de validar los resultados del sisitema o una entrada de usuario

**3) Investigue y proponga cinco (5) instituciones que requerirían aplicaciones de misión crítica** 

**4) Explique cuáles son las diferencias entre la escalabilidad horizontal y escalabilidad vertical**

**Escalamiento Vertical**
El escalamiento Vertical consiste en agregar recursos a un sólo nodo, aumentando su capacidad, esto puede ser aumentar la memoria RAM del servidor, agregar discos duros de mayor capacidad, cambiar de CPU o incluso cambiar todo el servidor por uno de más capacidad.

**Ventajas de escalamiento vertical**
- Es más sencillo de administrar un sólo nodo que múltiples nodos.
- En muchas ocasiones es más práctico.

**Desventajas de escalamiento vertical**
- Representa un punto único de falla.
- El poder de cómputo de la redundancia no se aprovecha.

**Escalamiento Horizontal**
El escalamiento Horizontal, a diferencia del anterior consiste en agregar nodos adicionales para adaptarse a la carga de trabajo. Si la aplicación o el sistema están llegando a su punto crítico, entonces se agregan nodos adicionales y se divide la carga entre los distintos nodos.


**Ventajas de escalamiento horizontal**
- En caso de una falla, no afecta toda la operación. *
- Permite escalar gradualmente, agregando servidores conforme se necesitan.
- Se pueden utilizar el poder computo de las redundancias activas.

**Desventajas de escalamiento horizontal**
- Requiere más espacio en el cuarto de servidores o centro de colocación.
- El nivel de complejidad lo hace más difícil de administrar.
- Encontrar errores puede ser más desafiante.

**5) Que es un servidor Web y que es un servidor de aplicaciones**


**Servidor web**
Un servidor web es el encargado de manejar páginas web y enviarlas a través de la red a quienes lo requieran y tengan los permisos para dichas páginas. Son los principales encargados de generar el tráfico en Internet puesto es a través de ellos se realizan las conexiones a todos los sitios web del mundo, toda página web está almacenada en uno de estos servidores, los cuales en su mayoría pertenecen a empresas de hosting que arriendan sus servicios para que los clientes almacenen sus páginas web en ellos teniendo acceso a ellos durante las veinticuatro horas del día.


**Servidor de aplicaciones**
Un servidor de aplicaciones es un programa de servidor en un equipo en una red distribuida que proporciona la lógica de negocio para un programa de aplicación. El servidor de aplicaciones se ve frecuentemente como parte de una aplicación de tres niveles, que consta de un servidor gráfico de interfaz de usuario (GUI), un servidor de aplicaciones (lógica empresarial) y un servidor de bases de datos y transacciones. De manera más descriptiva, se puede visualizar como la división de una aplicación en:

1. Una interfaz gráfica de usuario de primer nivel, de front-end, basada en el navegador web, normalmente en un equipo de cómputo personal o una estación de trabajo.

2. Una aplicación de lógica de negocio de nivel medio o conjunto de aplicaciones, posiblemente en una red de área local o un servidor de intranet.

3. Un servidor de back-end, base de datos y transacciones de tercer nivel, a veces en un mainframe o servidor grande.

**6) Con un gráfico explique cómo funciona el protocolo HTTP**
![HTTP_Response](https://huguidugui.files.wordpress.com/2013/10/peticion.png)

El funcionamiento del http se basa en un esquema de petición-respuesta entre el servidor web y el “agente usuario” o cliente que realiza la solicitud de transmisión de datos. Un cliente puede ser un explorador determinado, cuando intentamos abrir una página web, o los rastreadores web que las inspeccionan.

A ellos el servidor brinda una respuesta estructurada de modo puntual y dotada de una serie de metadatos, que establecen las pautas para el inicio, desarrollo y cierre de la transmisión de la información. Estos son los “métodos de petición”, es decir, los comandos que disparan la ejecución de recursos determinados, cuyos archivos residen en el servidor

**7) Explique los elementos importantes de REQUEST en HTTP**
![HTTP_Response](https://mdn.mozillademos.org/files/13687/HTTP_Request.png)
- Un método HTTP,  normalmente pueden ser un verbo, como: GET, POST o un nombre como: OPTIONS o HEAD, que defina la operación que el cliente quiera realizar. El objetivo de un cliente, suele ser una petición de recursos, usando GET, o presentar un valor de un formulario HTML, usando POST, aunque en otras ocasiones puede hacer otros tipos de peticiones. 
- La dirección del recurso pedido; la URL del recurso, sin los elementos obvios por el contexto, como pueden ser: sin el  protocolo (http://),  el dominio (aquí developer.mozilla.org), o el puerto TCP (aquí el 80). 
- La versión del protocolo HTTP.
- Cabeceras HTTP opcionales, que pueden aportar información adicional a los servidores.
- O un cuerpo de mensaje, en algún método, como puede ser POST, en el cual envía la información para el servidor.

**8) Explique los elementos importantes de RESPONSE en HTTP**

![HTTP_Response](http://www.hermosaprogramacion.com/wp-content/uploads/2015/01/http-protocolo-peticion.png)
- La versión del protocolo HTTP que están usando.
- Un código de estado, indicando si la petición ha sido exitosa, o no, y debido a que.
- Un mensaje de estado, una breve descripción del código de estado. 
- Cabeceras HTTP, como las de las peticiones.
- Opcionalmente, el recurso que se ha pedido.

**9) Describa con un gráfico la arquitectura Java EE**

![](https://www.ecured.cu/images/thumb/c/ce/J2EE.png/300px-J2EE.png)
* En la Capa Cliente: se ubican los clientes de nuestra aplicación y tienen diversas naturalezas.
* La Capa de Presentación: contiene toda la lógica de interacción entre el programa y el cliente y viceversa. Además, es la encargada de controlar las acciones entre el usuario y la lógica del negocio.
* La Capa de Lógica de Negocio: tiene a su cargo el núcleo de la aplicación. Debe ser mantenible, reutilizable, extensible y flexible.
* La Capa de Integración: se llevan a cabo tareas de integración con otros sistemas.
* En la Capa de Recursos: se localizan los sistemas de almacenamien to disponibles, como bancos de ficheros y bases de dato

**10) Explique cuáles son los contenedores, componentes y servicios de Java EE**

**CONTENEDORES JAVA EE**
Escribir aplicaciones empresariales seria muy complejo y difícil de codificar, ya que implicaría muchas lineas de código complejo para el manejo de transacciones y la gestión de estados, multihilos y otros detalles de bajo nivel,  la arquitectura Java EE hace que las aplicaciones sean fáciles de escribir porque la lógica de negocio se divide en componentes reutilizables y adicionalmente se cuenta con un servidor de aplicaciones que proporciona servicios en la forma de contenedor para los diferentes tipos de componentes, debido a esto no se tiene que desarrollar estos servicios, sino enfocarse en el desarrollo.


**Servicios del contenedor** Los contenedores son la interface entre un componente y el bajo nivel, es especifico para la plataforma, antes de que se pueda ejecutar el componente web, el bean o la aplicación cliente deben ser cargados en un modulo java EE y desplegarlo en el contenedor. al momento de desplegarlo cada componente puede tener su propia configuración en cuanto a seguridad, gestión de transacciones JNDI etc.
**Tipos de contenedores**
![](http://2.bp.blogspot.com/-xtOAc9rZSpc/U9_4CLOvnRI/AAAAAAAAAPQ/vX2vnfJhcWk/s1600/Captura.PNG)
El servidor y los contenedores son:

**Java EE Server**: La porción de tiempo de ejecución de un producto Java EE. provee los contenedores web y de ejb.

**Contenedor EJB**: Maneja la ejecución de los enterprise beans.

**Contenedor Web**: Maneja la ejecución de las paginas web, servlets y algunos componentes ejb para las aplicaciones Java EE.

**Contenedor de aplicación cliente**: Maneja la ejecución de la aplicación cliente no necesita un servidor de aplicaciones.

**Contenedor Applet**: Maneja la ejecución de applets, no necesita servidor de aplicaciones, consiste en un browser y el plugin web de java.

**Componentes de Java EE**

Aplicaciones cliente (lado cliente) 

* Web 
* Applets 
* Aplicaciones de escritorio 

Componentes Web (lado servidor) 

* Servlet 
* JavaServer Pages (JSP)/Facelets 
* JavaServer Faces (JSF), framework para aplicaciones Web. 

Componentes de negocio (lado servidor) 

* Enterprise JavaBeans (EJB) 
    - Session Beans 
    - Message Driven Beans 
* Java Persistence API (JPA) 



