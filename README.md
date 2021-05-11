# HW3

a) Desarrollé una malla 3D con los espesores que se piden y la malla está configurada según lo solicitado. Después se desarrolló una malla 2D de esta misma forma (la misma malla pero plana). 
- Se muestra para el caso 3D: "Placa_3D.geo". 
- Se muestra para el caso 2D a desarrollar: "placa_plana_a.geo" y "placa_plana_a.msh" para la malla solicitada.

b) El problema que tuve es que la malla que se pide en la parte a) no me corrió en mi computador en los archivos Python desarrollados en clases y dado el corto plazo no me dio el tiempo para arreglarlo, por lo que se desarrolló con una malla mas pequeña.

![imagen](https://user-images.githubusercontent.com/81662690/117752692-3df49b80-b1e5-11eb-9127-b0b7ccce99ba.png) #estructura no deformada
![imagen](https://user-images.githubusercontent.com/81662690/117752735-506ed500-b1e5-11eb-8358-b2304d2bd5f8.png) #estructura deformada amplificada en 1e8
![imagen](https://user-images.githubusercontent.com/81662690/117752833-798f6580-b1e5-11eb-9b04-51864dcdd1e1.png) #Gmsh con sigma x
![imagen](https://user-images.githubusercontent.com/81662690/117753038-d25efe00-b1e5-11eb-9d23-0fdac255ed95.png) #Desplazamiento en Gmsh aplificado 1e8
![imagen](https://user-images.githubusercontent.com/81662690/117753561-abed9280-b1e6-11eb-861c-79cca2ab0439.png) #forma en que se distribuyó la carga

El error que aparecía cuando corría la otra malla era: numpy.core._exceptions.MemoryError: Unable to allocate 9.90 GiB for an array with shape (36446, 36446) and data type float64
