# HW3

PARTE a) 
Desarrollé una malla 3D con los espesores que se piden y la malla está configurada según lo solicitado. Después se desarrolló una malla 2D de esta misma forma (la misma malla pero plana). 
- Se muestra para el caso 3D: "Placa_3D.geo". 
- Se muestra para el caso 2D a desarrollar: "placa_plana_a.geo" y "placa_plana_a.msh" para la malla solicitada.
![imagen](https://user-images.githubusercontent.com/81662690/117753770-0d156600-b1e7-11eb-9bf3-36e20668d7f3.png)


PARTE b)
El problema que tuve es que la malla que se pide en la parte a) no me corrió en mi computador en los archivos Python desarrollados en clases y dado el corto plazo no me dio el tiempo para arreglarlo, por lo que se desarrolló con una malla mas pequeña. El error que aparecía cuando corría la otra malla era: "numpy.core._exceptions.MemoryError: Unable to allocate 9.90 GiB for an array with shape (36446, 36446) and data type float64". A continuación se muestra lo desarrollado con la malla vista en clases:

Estructura no deformada:
![imagen](https://user-images.githubusercontent.com/81662690/117752692-3df49b80-b1e5-11eb-9127-b0b7ccce99ba.png) 

Estructura deformada amplificada en 1e8:
![imagen](https://user-images.githubusercontent.com/81662690/117752735-506ed500-b1e5-11eb-8358-b2304d2bd5f8.png)

Gmsh con sigma x:
![imagen](https://user-images.githubusercontent.com/81662690/117752833-798f6580-b1e5-11eb-9b04-51864dcdd1e1.png) 

Desplazamiento en Gmsh aplificado 1e8:
![imagen](https://user-images.githubusercontent.com/81662690/117753038-d25efe00-b1e5-11eb-9d23-0fdac255ed95.png)

Forma en que se distribuyó la carga:
![imagen](https://user-images.githubusercontent.com/81662690/117753561-abed9280-b1e6-11eb-861c-79cca2ab0439.png) #forma en que se distribuyó la carga

Se adjuntan los archivos "placa_plana_b.geo" y "placa_plana_b.msh" con la estructura y la malla que se usó en esta parte del problema. Además, se adjunta el archivo con los desplazamientos y con sigma x.

Logre identificar los elementos que pertenecen a los Extremos agregandolo al programa, identificar 2 espesores distintos en el quad4 pero no alcancé a implementar los espesores distintos en el desarrollo final.
