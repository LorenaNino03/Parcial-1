# Parcial-1

# primer punto - conceptual
# a) Explicar la diferencia fundamental entre la latencia y el jitter. ¿Cuál de estas dos métricas tendría un impacto más negativo en una llamada VoIP y por qué?
Respuesta: 
Latencia: tiempo que tarde un paquete en llegar desde su origen hasta su destino - PC A - PC B
Jitter: Es la variación en tiempo (milisegundos) que tarda en llegar un paquete a su destino, dependiendo ciertos parametros y a su vez distancias de un punto A a un punto B. 
Ejemplo: si un paquete tarde menos de diez milisegundos es una conectividad buena. 
El que tendría un impacto mas negativo en una llamada VoIP seria el jitter, ya que esto causa que al momento de entregar el mensaje y tenga un alta tasa de milisegundos la voz del remitente se escucha robotica.

# b) Una aplicación envía datos usando protocolo TCP, mientras que otra usa UDP para la misma tarea de transmisión de video. ¿Cuál es más eficiente en términos de throughput y cuál ofrece mayor control de la pérdida de paquetes? Justifique su respuesta basándote en la "anatomía" de sus cabeceras.
Respuesta: En este caso el mas eficiente seria el protocolo TCP debido a que este al obtener una capa mas de seguridad a la hora de entregar los paquetes a su destino genera una menor perdida de paquetes, caso contrario del protocolo UDP que entrega los paquetes mas rápido pero con mayor perdida de paquetes. 

# C) Al ejecutar el comando “arp -a” en la CMD de Windows, se obtienen una lista de direcciones IP y direcciones físicas. ¿Qué protocolo de la suite TCP/IP llena esta tabla y cuál es su función principal dentro de una red local? Relacionar la respuesta con la estructura de una trama Ethernet.
Respuesta: El protocolo de la suite que llena esta tabla es el del ARP su funcion principal es traducir una dirección IP a una dirección MAC para evitar la repeticion de solicitudes de conectividad. 

<img width="1312" height="807" alt="image" src="https://github.com/user-attachments/assets/17e50fa2-c1c1-48f5-bd56-6fbd424783ef" />
