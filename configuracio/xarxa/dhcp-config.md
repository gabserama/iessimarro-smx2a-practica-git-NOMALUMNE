1. Activacion servicio dhcp
Instalar y activar el servicio dhcp en ub server para asignar automaticamente direcciones ip a los equipos de la red.

2. Rango de direcciones ip
Configurar el rango DHCP desde 192.168.1.10 hasta 192.168.1.50, con mascara de subred 255.255.255.192 (/26).

3. Puerta de enlace
Establecer la puerta de enlace 192.168.1.1 para permitir la comunicacion con otras redes.

4. Servidor DNS
Configurar el servidor DNS 192.168.1.254 para que los equipos puedan resolver nombres de dominio.

5. Verificacion con tres equipos de prueba
Comprobar en tres equipos que reciben automaticamente una direccion ip dentro del rango configurado. Verificar las 
direcciones mediante el comando ip address show y comprobar la conectividad con el servidor.

ESTADO: Pendiente de verificar las pruebas con los tres equipos.
