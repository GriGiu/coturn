
# Docker image for CoTurn server
A Docker container based debian stretch with the [Coturn TURN server](https://github.com/coturn/coturn)

sudo docker run -d -p 3478:3478 -p 3478:3478/udp --restart=always grigiu/coturn

