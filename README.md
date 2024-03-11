
Dentro del directorio JAVA5_AXIS/lib ejecutar el siguiente comando para 
generar las clases descritas en el WSDL. 
Solo sirve para los WSDL Gobierno de la Rioja.
Una vez generado, mover el directorio creado a raíz del proyecto.

```java -cp axis.jar;commons-logging-1.0.4.jar;commons-discovery-0.2.jar;jaxrpc.jar;saaj.jar;wsdl4j-1.5.1.jar org.apache.axis.wsdl.WSDL2Java http://someURL?WSDL```

WSDLs utilizados:

```url_ejemplo.wsdl```