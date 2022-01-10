
# canvas-parametroRestJs

_Ejercicio practico, usando canvas y parámetro rest de JS, para dibujar cuadrado._

## Comenzando 🚀

### Uso 🔧

_function contextCanvas()_

_Esta function espera como parametro un elemento HTML. Y retorna un objeto canvas CanvasRenderingContext2D_

```
-llamando a la funcion contextCanvas-
   let pizarra = contextCanvas("canvas");
   
   //la variable pizarra es nuestra area de trabajo, se usara posteriormente para dibujar en ella.
```

_function isColor()_

-Esta function espera como parametro un valor STRING, y retorna true o false, esta se usa para validar el parametro color-

```
-llamando a la funcion isColor-
isColor("nameColor")

//si el parametro es un color valido devuelve true, sino false.
```


_function dibujarContorno()_
-Esta funcion dibuja un contorno o borde, en la posicion especificada por usted-

```
-llamando a la funcion dibujarContorno-
dibujarContorno(x, y, "nameColor", width, height, pizarra);


//x int, y int, "nameColor" String, width int, heigth int, pizarra objeto canvas.
```

_function dibujarCuadrado()_
-Esta funcion dibuja un cuadrado, en la posicion especificada por usted-

```
-llamando a la funcion dibujarCuadrado-
dibujarCuadrado(x, y, "nameColor", width, height, pizarra);


//x int, y int, "nameColor" String, width int, heigth int, pizarra objeto canvas.
```

_Ejemplo pintando un cuadro color fondo red y contornos orange_

```
  let pizarra = contextCanvas("canvas");
  dibujarCuadrado(x, 0, "red", 50, 50, pizarra);
  dibujarContorno(x, 0, "orange", 50, 50, pizarra);

```


## Gracias Por Descargar y Probar 🎁

* Este es un ejemplo practico, para usar parametros rest 📢
* Puede Mejorarlo. 
* Si deseas corregir, No dudes hacerlo saber 🤓.



---
⌨️ con ❤️ por [CRIS19N](https://github.com/CRIS19N) 😊
