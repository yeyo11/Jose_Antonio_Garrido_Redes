

**Crear cinco redes:**

1. *100 host 192.168.1.0/25, 30 host 192.168.1.128/27 y 6 host 192.168.1.161/29. Sólo esta última podrá salir fuera(Se le indica la puerta de enlace 192.168.1.1/24.*

2. *Servidor con ip fija 192.168.2.2/25  y el servicio DHCP configurado para asignar IPs apartir de la 192.168.2.50 con mascara 255.255.255.0, puerta de enlace 192.168.2.1 y servidor dns el 192.168.5.2*

3. *Servidor con ip fija 192.168.3.2/25  y el servicio DHCP configurado para asignar IPs apartir de la 192.168.3.50 con mascara 255.255.255.0, puerta de enlace 192.168.3.1 y servidor dns el 192.168.5.2*

4. *Los cuatro primeros PCs se configuran en la red 192.168.4.0/24 con IPs anteriores a la 192.168.4.50, se crea un servidor con ip fija 192.168.4.2/25 y el servicio DHCP configurado para asignar IPs apartir de la 192.168.4.50 con mascara 255.255.255.0, puerta de enlace 192.168.4.1 y servidor dns el 192.168.5.2, se añade un punto de acceso a la red con 5 equipos inalambricos conectados a el en modo DHCP*

5. *Se crea la red 192.168.5.0/24 con 5 equipos conectados a ella configurados manualmente dentro de esta con puerta de enlace 192.168.5.1/24 y servidor DNS 192.168.5.2*

**5 routers 1 por cada red**

**Tendremos tres servidores web:**

    +Se crea un servidor  con ip 192.168.5.3./24 configurado con el servicio web habilitado con su respectiba pagina asociada.
    +Se crea un servidor con ip 192.168.5.4/24 configurado con el servicio web habilitado con su respectiba pagina.
    +Se crea un servidor con ip 192.168.5.5./24 configurado con el servicio web habilitado con su respectiba pagina.

    >Se crea un servidor con ip 192.168.5.2/24 configurado con el servicio DNS habilitado para que asocie las IPs de los servidores antes mencionados al nombre de cada uno.
