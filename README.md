> # Titulos.
```
# Titulo h1
## Titulo h2
### Titulo h3
#### Titulo h4
##### Titulo h5
###### Titulo h6
```

.
> # Textos en negrita, italica y tachado.
```
Texto en *italica*
Texto en **negirta**
Texto ~~tachado~~
```
* texto en *italica*
* texto en **negrita**
* texto ~~tachado~~

.
> # Listas desordenadas.
```
* Item 1
* Item 2
	* Item 1 de Item 2
	* Item 2 de Item 2
* Elemento 3
```
* Item 1
* Item 2
	* Item 1 de Item 2
	* Item 2 de Item 2
* Elemento 3

.
> # Listas ordenadas.
```
1. Item 1
2. Item 2
	1. Item 1 de Item 2
	2. Item 2 de Item 2
3. Item 3
```
1. Item 1
2. Item 2
	1. Item 1 de Item 2
	2. Item 2 de Item 2
3. Item 3

.
> # Enlaces.
```
[Ir a youtube](https://www.youtube.com)
```
* [Ir a youtube](https://www.youtube.com)
```
Al poner el mouse sobre el enlace muestra el title.

[Ir a youtube](https://www.youtube.com "Enlace con title")
```
* [Ir a youtube](https://www.youtube.com "Title")

.
> # Citas.
```
> Esto es una cita
```
* > Esto es una cita

.
> # Crear lineas.
Se pueden crear lineas con tres guiones medios ( --- ) o con tres guiones bajos ( ___ ).
```
---
___
```
---
___


.
> # Crear recuadro para colocar texto o codigo.

En si es crear un recuadro donde puedes mostrar texto o bloques de codigo.
```
	```
	Texto dentro del recuadro.
	```
```
```
Texto dentro del recuadro.
```



Para mostrar codigo se usan ( `` ).
```
`Console.log("Esto es codigo js")`
```
* `Console.log('Esto es codigo js')`



Para colocar un bloque de codigo sin color.
```
	```
	if ( start < end ) {
		while ( num < start ) {
			num = Math.round( Math.random() * end );
		}
	}
	```
```
```  
if ( start < end ) {
	while ( num < start ) {
		num = Math.round( Math.random() * end );
	}
}
```



Para colocar un bloque de codigo con color, colocas el nombre del lenguaje de programacion.
```
	```javascript 
	if ( start < end ) {
		while ( num < start ) {
			num = Math.round( Math.random() * end );
		}
	}
	```

```
```javascript  
if ( start < end ) {
	while ( num < start ) {
		num = Math.round( Math.random() * end );
	}
}

```

Ejemplo con codigo html.
```
	```html
	<script src="code/main.js"></script>
	```
```
```html
<script src="code/main.js"></script>
```

.
> # Crear tablas.
```
| titulo      | titulo      |
|-------------|-------------|
| Contenido 1 | Contenido 4 |
| Contenido 2 | Contenido 5 |
| Contenido 3 | Contenido 6 |
```


| titulo      | titulo      |
|-------------|-------------|
| Contenido 1 | Contenido 4 |
| Contenido 2 | Contenido 5 |
| Contenido 3 | Contenido 6 |

.
> # Colocar Imagenes.
Es como en los enlaces, solo que en los corchetes es como colocar el atributo alt en las imagenes en html.
```
![Alt en la imagen](vsc-logo.png "Logo vsc")
```
![Alt en la imagen](vsc-logo.png "Logo vsc")

.
> # Listas con visto de realizaso.
Esto se ve en github y no en el editor con la previsualizacion.

```
* [x] elemento 1
* [x] elemento 2
* [ ] elemento 3
* [ ] elemento 4
* [x] elemento 5

```

* [x] elemento 1
* [x] elemento 2
* [ ] elemento 3
* [ ] elemento 4
* [x] elemento 5