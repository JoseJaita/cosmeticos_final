# PoC-SMARK

| Name | Type | Version|
|---|---|---|
| Reconocimiento de Cosméticos | PoC | 1.0 |

### Authors
- Gianmarco Jhair Gallardo Callalli ggallard@everis.com
- Ricardo Díaz Brinceño	

### Description
Este es un sistema de clasificación de imágenes basado en redes neuronales convolucionales profundas 
capaz de reconocer diferentes tipos de productos de belleza

### Quality metrics
- Reconocimiento: 90 % accuracy on validation dataset

### Tecnologies
- **Tecnologias utilizadas y dependencias de software:** Anaconda (Python 3.6 y librerías extras de anaconda), Tensorflow, Kera, Tensorflow Lite, Cuda 9.0, cuDNN 7, Git, Android Studio
- **Requerimientos de hardware (recomendado):** GPU GeForce GTX 1080 Ti, CPU Intel Core i9.

### Links
- **Papers:**
	- proyecto : (https://gitlab.com/everis-innovation/showroom-ia/reconocimiento_cosmeticos)

### Usage

Para entrenar el modelo
```bash
$ jupyter lab
```
Luego ejecutar demo.ipynb

Despues, para convertir el modelo a tensorflow-Lite
```bash
$ python convert_to_tflite.py 
```
