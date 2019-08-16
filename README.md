# LainARG
Repositorio demostrativo Java, WS, JS,angularJS, Spring, Hibernate.

Hola! gracias por spotear mi repositorio público. 

La primer carpeta contiene un REST webService al más clásico estilo CRUD+2 (CRUD+getRepo+clearRepo). Se encuentra tanto el cliente como el servidor. Ninguno fue compilado(.WAR,.JAR) por motivos de legibilidad. 

La segunda carpeta contiene un SOAP webService al más clásico estilo CRUD+2 (CRUD+getRepo+clearRepo). Se encuentra tanto el cliente como el servidor. Ninguno fue compilado(.WAR,.JAR) por motivos de legibilidad. 

La tercer carpeta contiene una WEB application que también realiza CRUD+2, utiliza JPÀ-hibernate para mapear los objetos contra una base de datos mysql básica (Paquete DAL), utiliza maven como gestor de dependencias, luego mediante el paquete controller erigido en Spring, se comunica la DAL con la PL(vista) que se compone de páginas JSP con validación html y javascript del lado front, asi como captura(back) y muestreo de excepciones, no se utiliza inyección de dependencias puesto que el tamaño del proyecto no lo amerita. Este proyecto fue compilado en un .WAR para facilitar su ejecución, aunque también se encuentran disponibles las fuentes, además en su home el programa contiene un button que crea la base de datos y la tabla correspondientes, de tal manera
que solo se precisa contar con un gestor mysql activo para poder hacer uso del programa.     

La cuarta carpeta contendrá un programa front, basado en javascript y angular JS, la idea básicamente es
llamar a un servicio de tipo API, como amazon o mercadolibre y realizar un demostrativo de destrezas front. 
