PRIMER PAS
El primer que hem de fer a l'hora d'instal·lar una versió de Java és comprovar quina és la versió actual si és que tenim alguna versió instal·lada. Per fer-ho obrim la consola de Windows i situant-nos al directori C:\
inserim el següent comandament:

java -version

SEGON PAS
Depenent del tipus de sistema operatiu haurem de descarregar el JDK d'Oracle que més s'ajusti a les nostres necessitats.
Ens ho podem descarregar desde el següent enllaç acceptant els acords de llicència.
http://www.oracle.com/technetwork/es/java/javase/downloads/jdk7-downloads-1880260.html

TERCER PAS
Una vegada descarregat, procedim a instalar-ho. És tan senzill com executar l'arxiu i prèmer següent.

QUART PAS
A continuació hem de configurar les variables d'entorn. Per fer-ho hem de seguir les següents passes:
- "Panel de control" > "Sistema y seguridad" > "Sistema"
- "Configuración avanzada del sistema" > "Variables de entorno"
- Cream una nova variable de sistema de nom "JAVA_HOME" amb el valor de la ruta on es troba la versió de java que hem instal·lat, normalment a C:\Program Files\Java\jdk.....
- Buscamos la variable "Path", le damos a "Editar" y se coloca al final “;%JAVA_HOME%\bin”