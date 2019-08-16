# LainARG
Repositorio demostrativo Java, WS, JS,angularJS, Spring, Hibernate.

Hola! gracias por spotear mi repositorio p�blico. 

La primer carpeta contiene un REST webService al m�s cl�sico estilo CRUD+2 (CRUD+getRepo+clearRepo). Se encuentra tanto el cliente como el servidor. Ninguno fue compilado(.WAR,.JAR) por motivos de legibilidad. 

La segunda carpeta contiene un SOAP webService al m�s cl�sico estilo CRUD+2 (CRUD+getRepo+clearRepo). Se encuentra tanto el cliente como el servidor. Ninguno fue compilado(.WAR,.JAR) por motivos de legibilidad. 

La tercer carpeta contiene una WEB application que tambi�n realiza CRUD+2, utiliza JP�-hibernate para mapear los objetos en una base de datos mysql b�sica (Paquete DAL), utiliza maven como gestor de dependencias, luego mediate el paquete controller erigido en Spring, se comunica la DAL con la PL(vista) que se compone de p�ginas JSP con validaci�n html y javascript del lado front, asi como captura(back) y muestreo de excepciones, no se utiliza inyecci�n de dependencias puesto que el tama�o del proyecto no lo amerita. Este proyecto fue compilado en un .WAR para facilitar su ejecuci�n, aunque tambi�n se encuentran disponibles las fuentes, adem�s en su home el programa contiene un button que crea la base de datos y la tabla correspondientes, de tal manera
que solo se precisa contar con un gestor mysql activo para poder hacer uso del programa.     

