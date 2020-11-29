# MQTT YOLO
### Introduccion:
MQTT(Message Queuing Telemetry Transport) es un protocolo de comunicación ligero M2M(Machine2Machine). 

<p align="center">
  <img src="https://cdn.sparkfun.com/assets/learn_tutorials/8/2/7/mqtt-explanation2.png" width="350" title="hover text">
</p>

# PASOS
1. Instalar mosquitto

Tal como dice Abraham Lincoln:

> Con perdón de la expresión

https://repo.anaconda.com/archive/Anaconda3-2020.11-Linux-x86_64.sh  // Instalar esto en linux

2.Crear env con python 3.6 estable
	$ conda create -n yolo python=3.6

3. Elegir framework programación(yo uso jupyter de momento)

4. Instalar los siguientes modulos dentro del env yolo:
	- pip install opencv-python (con contrib se arreglará el problema versiones)
	- pip install git-clone
	- pip install opencv-contrib-python
	- pip install numba (0.44 version)

5. Descargar yolov4_tiny y yolov4_tiny weights y meterlos dentro de proyecto
	- https://github.com/AlexeyAB/darknet


ATENCIÓN:
Para instalar opencv en arquitectura arm hay que hacerlo a mano, para ello, hay que basarse en el siguiente video.
https://pysource.com/2019/08/26/install-opencv-4-1-on-nvidia-jetson-nano/


Fuentes:
Social Distance Detector
https://heartbeat.fritz.ai/social-distance-detector-with-python-yolov4-darknet-and-opencv-62e66c15c2a4
Yolo Theory
https://blog.paperspace.com/how-to-implement-a-yolo-object-detector-in-pytorch/
Yolo from scratch
https://www.youtube.com/watch?v=h56M5iUVgGs



