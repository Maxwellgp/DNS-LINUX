# DNS-LINUX

Para la configuración creamos un archivo llamado db.example.com.

Rellenamos el archivo con los datos  como el nameserver, SOA y su IP.

Una vez rellenado accedemos al archivo named.conf.local y añadimos el nombre de nuestra zona así como el tipo y el lugar del archivo de configuración de la zona.
  
Para comprobar el funcionamiento de la zona primero reiniciamos el servicio de bind9.

Despues nos conectamos a nuestro cliente y realizamos ping a nuestra dirección de la zona.
  
Si funciona debería devolver la IP asignada.
