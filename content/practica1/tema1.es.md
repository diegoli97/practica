+++
title = "Explicación"
weight = 15
+++

### Proceso de comunicación de cliente/servidor

El navegador/cliente hace una petición o solicita una página web al servidor a través de una URL. 

Si no la tiene almacenada ya la petición viaja al servidor mediante el protocolo HTTP o HTTPS y si no hay intermediarios, como un proxy o un VPN, el servidor dns asocia esa url a una ip en el lado del servidor.

Entonces le manda al cliente la petición parcial o completa (dependiendo de los permisos), de la página html, javascript, css...  de nuevo mediante el protocolo TCP/IP y HTTP.

El navegador renderiza esa página web y la muestra al usuario, guardando esos archivos en el sistema.

**No he conseguido que me funcionen los gráficos perdón**