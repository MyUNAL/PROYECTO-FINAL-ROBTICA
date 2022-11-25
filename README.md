# Proyecto Final
## Robótica - Universidad Nacional De Colombia - Sede Bogotá
### Sebastian Cubides - Julián Velandia - Sergio Gerena
***
### Descripción de la solución planteda:

Comprendiendo el objetivo del proyecto, se diseño en inventor el modelo de un gripper de 5 piezas, de las cuales todas tienen un circulo del mismo diametro de la ventosa con el fin de alinear estos centros y realizar el levantamiento y armado con el manipulador de una forma mucho más sencilla. Véase en las imagenes subsecuentes el diseño planteado para el gripper.

![IMG_PLANO](IMG/PLANO.png)

![IMG_PLANO](IMG/PLANO.png)

Una vez completado este diseño se contrató el servicio de corte laser en MDF y se adecuó una lámina del mismo material y de dimensiones 400x200mm para realizar el procedimiento de recogida y ensamblaje. Véase en la imágen siguiente la disposición física de los elementos.

![IMG_FOTO_CONSTRUCCION](IMG/FOTO_CONSTRUCCION.png)

![IMG_FOTO_CONSTRUCCION](IMG/FOTO_CONSTRUCCION.png)

Ahora procedemos a examinar el desarrollo en simulación. Se hizo el modelado CAD de todo el sistema y la herramienta, decidiendo usar la misma herramienta ya implementada en laboratorios anteriores y se sujetó la ventosa utilizando una serie de amarres plásticos. Se llevaron todas estas geometrías a Robot Studio y se programó el código RAPID correspondiente para todas las trayectorias de recogida y ensamble de cada una de las piezas del gripper y señales de las salidas digitales de control de la válvula. Véase el siguiente vídeo de la simulación en Robot Studio.

![VID_SIM](IMG/VIDEO_SIMULACION.png)

Finalmente, realizamos el montaje del sistema en el laboratorio y cargamos el código RAPID en el manipulador. El siguiente video enseña el correcto funcionamiento de la implementación e ilustra todo lo mencionado anteriormente.

![VID_COMP](IMG/VIDEO_COMPLETO.png)

Por último recordamos que todos los diseños CAD y simulaciones se encuentran presentes en los archivos de este repositorio.

***
