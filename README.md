# jiveras.github.io

# DockerPI

[https://docs.docker.com/engine/reference/commandline/images/](https://docs.docker.com/engine/reference/commandline/images/)

Starta allt med

* docker run -d --name influxdb --volume=/var/influxdb:/data -p 8086:8086 hypriot/rpi-influxdb:1.1.1
* docker run -d -it --name rabbitmq -h rabbitmqhost -p 1884:1883 -p 15672:15672 -v /var/rabbitmq:/var/lib/rabbitmq myrabbitmq
* docker run -d --name portainer -p 9000:9000 -v /var/run/docker.sock:/var/run/docker.sock -v /var/portainer:/data portainer/portainer:arm

eller med:

* docker start influxdb
* docker start rabbitmq
* docker start portainer

[http://192.168.0.18:9000](http://192.168.0.18:9000)
