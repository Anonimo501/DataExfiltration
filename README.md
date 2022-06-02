# DataExfiltration

(WIKIPEDIA)

"La exfiltración de datos ocurre cuando el malware y / o un actor malintencionado lleva a cabo una transferencia de datos no autorizada desde una computadora. También se denomina comúnmente extrusión de datos o exportación de datos. La exfiltración de datos también se considera una forma de robo de datos."

=======================================================================================================================================

Para extraer un archivo de la maquina victima, necesitamos ejecutar un servidor HTTP (server.py) en la máquina Atacante que pueda aceptar y guardar el archivo cuando se envía desde la maquina victima a través del protocolo HTTP.

Para lo anterior he subido este script, el cual se puede sacar el codigo de la pagina de INE, os dejo a continuacion el script en python.

## Lo anterior quiere decir que:

(Este script sirve para montar el servidor normal HTTP para compartir archivos y descargar desde la maquina victima como tambien sirve para enviar archivos desde la maquina victima a la maquina atacante)

![Screenshot_1](https://user-images.githubusercontent.com/67207446/171551255-53a00cb3-9e87-41fd-9ae0-14f8f5072fe6.png)

# Instalacion y Uso

git clone https://github.com/Anonimo501/DataExfiltration.git

cd DataExfiltration/

> python server.py 80

> python server.py 8080

> python server.py 8443
