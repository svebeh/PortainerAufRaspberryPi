# PortainerAufRaspberryPi

Auf dem Raspi läuft eine Dockerumgebung und darin soll nun auch Portainer laufen.
Dazu muss lediglich im Verzeichnis PortainerAufRaspberryPi der folgende Befehl ausgeführt werden:
```
docker-compose up -d
```
Oder außerhalb des Verzeichnisses
```
docker-compose -f /Pfad/Zur/docker-compose.yml up -d
```
Danach ist Portainer im Browser wie folgt zu erreichen:
```
http://<IpDesRaspberryPi>:9000
