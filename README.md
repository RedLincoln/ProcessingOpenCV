# Processing OpenCV

## Sobre el Autor

> **Miguel Lincoln Capote Pratts** - Universidad de Las Palmas de Gran Canaria [**ULPGC**](https://www.ulpgc.es).

![](peek.gif)

## Desarrollo

El desarrollo se realizó en Ubutu
 por ello fue necesario añadir una libreria
 de `video` distinta a la que ofrece processing
 por defecto. La librería es [Video Library
](https://github.com/processing/processing-video) y para añadirla a processing
 es necesario hacer una [instalación manual](https://github.com/processing/processing/wiki/How-to-Install-a-Contributed-Library).

Se hace uso de la librería de `Video` mencionada con anterioridad para capturar la `Cam` y con ello una imagen la cual es procesada por `OpenCV` para detectar la cara y los ojos que estén en la imagen. Se intentó detectar la boca pero no fue posible, por ello se hizo una suposición de la posición de la boca teniendo en cuenta la posición de la cara y de los ojos. Esta práctica es solo una toma de contacto con la potente librería de `OpenCV`.

## Referencias y Librerías utilizadas

Se desarrollo
 utilizando como referencia la página oficial de processing. 
 
[CVImage library](http://www.magicandlove.com/blog/2018/11/22/opencv-4-0-0-java-built-and-cvimage-library/)
<br>
[Video Library](https://github.com/processing/processing-video)
