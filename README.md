# Luminaria escolar con detección de movimiento
Detecta movimiento en una escena y confirma un evento solo si el movimiento se mantiene durante el tiempo configurado.

Este cuaderno reúne la lógica de detección de movimiento de mi proyecto de titulación. El código usa Python y OpenCV para comparar cada fotograma con un fondo de referencia e identificar las zonas donde hubo cambios.

## Temporizador

El temporizador confirma un evento cuando el movimiento se mantiene durante el tiempo configurado. Si el movimiento se interrumpe antes de llegar a ese tiempo, el conteo vuelve a empezar. Se confirma un solo evento por episodio continuo.

## Cuaderno de Google Colab

[Ver el cuaderno de la luminaria](./Luminaria_Colab.ipynb)

El cuaderno contiene el detector y el temporizador. El control de la luminaria física forma parte del montaje original.
