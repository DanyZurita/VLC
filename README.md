# Comandos de Code 
## Tarea 1.1

**Headers**

* Ejemplo
```
# Título 1
## Título 2
### Título 3
#### Títilo 4
```
* Resultado
# Título 1
## Título 2
### Título 3
#### Títilo 4

**Emfasis**

* Ejemplo
```
*Para crear texto itálico*
_Para crear texto itálico_

```
* Resultado

*Para crear texto itálico*

_Para crear texto itálico_

**NEGRITA**

* Ejemplo
```
__Para crear texto en negrita__
**Para crear texto en negrita**
```
* Resultado

__Para crear texto en negrita__

**Para crear texto en negrita**

**TACHADO**

* Ejemplo
```
~~Para crear texto en tachado~~
```
* Resultado

~~Para crear texto en tachado~~

**LISTAS**

* Ejemplo
```
1. Lista numerada
2. Lista numerada
3. Lista numerada
    * Sublista no numerada
        * Sub-sublista no numerada
* Las listas no ordenadas se pueden crear con asteriscos
- Con el simbolo de -
+ o con el símbolo de +
```
* Resultado

1. Lista numerada
2. Lista numerada
3. Lista numerada
    * Sublista no numerada
        * Sub-sublista no numerada
* Las listas no ordenadas se pueden crear con asteriscos
- Con el simbolo de -
+ o con el símbolo de +

**LINKS**

* Ejemplo
```

[Link de una página web](https://www.google.com)

[Link de una página web con mensaje](https://www.google.com "Google's Homepage")

[Utilizar textos de referencias para hypervincular][Texto de referencia]

[Referencia Relativa a un repositorio](../blob/master/LICENSE)

[También se pueden referenciar números][1]

O dejarlo el texto y añadir el  [link tal cual].

URLs and URLs con braquets se auto linkean solas. 
http://www.ejemplo.com or <http://www.ejemplo.com> and sometimes 
ejemplo.com (pero no en Github).

El texto referenciado se añade al final del documento para que se revisen al final.

[texto de referencia]: https://www.mozilla.org
[1]: http://slashdot.org
[link tal cual]: http://www.reddit.com
```
* Resultado

[Link de una página web](https://www.google.com)

[Link de una página web con mensaje](https://www.google.com "Google's Homepage")

[Utilizar textos de referencias para hypervincular][Texto de referencia]

[Referencia Relativa a un repositorio](../blob/master/LICENSE)

[También se pueden referenciar números][1]

O dejarlo el texto y añadir el  [link tal cual].

URLs and URLs con braquets se auto linkean solas. 
http://www.ejemplo.com or <http://www.ejemplo.com> and sometimes 
ejemplo.com (pero no en Github).

El texto referenciado se añade al final del documento para que se revisen al final.

[texto de referencia]: https://www.mozilla.org
[1]: http://slashdot.org
[link tal cual]: http://www.reddit.com

**IMAGENES**

* Ejemplo
```
Para añadir imágenes también se puede hacer de dos maneras:

En una sola línea: ![alt text](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/1200px-Markdown-mark.svg.png "Texto al hacer hover sobre la imágen")

O utilizando referencias: ![alt text] [Markdown]

Y añadimos la referencia al final.
[Markdown]: https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/1200px-Markdown-mark.svg.png "Texto al hacer hover sobre la imágen referenciada"
```
* Resultado
Para añadir imágenes también se puede hacer de dos maneras:

En una sola línea: ![alt text](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/1200px-Markdown-mark.svg.png "Texto al hacer hover sobre la imágen")

O utilizando referencias: ![alt text][Markdown]

Y añadimos la referencia al final.

[Markdown]: https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/1200px-Markdown-mark.svg.png "Texto al hacer hover sobre la imágen referenciada"

**CÓDIGO**

* Ejemplo

```
    ```javascript
    var s = "Resalto de lenguaje JavaScript";
    alert(s);
    ```
```


```
    ```python
    s = "Resalto de lenguaje Python"
    print s
    ```
```
```
    ```
    Si no se indica lenguaje no se resalta nada.
    ```
```

* Resultado


```javascript
var s = "Resalto de lenguaje JavaScript";
alert(s);
```




```python
s = "Resalto de lenguaje Python"
print s
```


```
Si no se indica lenguaje no se resalta nada.
```

**TABLAS**
* Ejemplo

```
El símbolo | se utiliza para crear las tablas.

| TABLAS 1       | TABLAS 2      | TABLAS 3  |    TABLAS 4    |
| :------------- |:-------------:| -----:| -------------- |
| 1A Contenido Derecha    | 1B Contenido Centrado | 1C Contenido Izquierda  |    1D Contenido por defecto
| 2A      | 2B      |   2C |2D
| 3A | 3B     |   3C | 3D

Tiene que haber almenos 3 dashes separando cada encabezado.
Las | de fuera pueden ser omitidas.
Dentro de las celdas se pueden seguir utilizando los estilos de Markdown

*Ejemplo* | **Ejemplo** | `Ejemplo`
--- | --- | ---
*Ejemplo* | `Ejemplo` | **Ejemplo**
`Ejemplo` | **Ejemplo** | *Ejemplo*
~~1~~ | ~~2~~ | ~~3~~
```

* Resultado

El símbolo | se utiliza para crear las tablas.

| TABLAS 1       | TABLAS 2      | TABLAS 3  |    TABLAS 4    |
| :------------- |:-------------:| -----:| -------------- |
| 1A Contenido Derecha    | 1B Contenido Centrado | 1C Contenido Izquierda  |    1D Contenido por defecto
| 2A      | 2B      |   2C |2D
| 3A | 3B     |   3C | 3D

Tiene que haber almenos 3 dashes separando cada encabezado.
Las | de fuera pueden ser omitidas.
Dentro de las celdas se pueden seguir utilizando los estilos de Markdown

*Ejemplo* | **Ejemplo** | `Ejemplo`
--- | --- | ---
*Ejemplo* | `Ejemplo` | **Ejemplo**
`Ejemplo` | **Ejemplo** | *Ejemplo*
~~1~~ | ~~2~~ | ~~3~~

**ANOTACIONES**

* Ejemplo

```
>Primera frase de la anotación.
>Segunda frase de la misma anotación.

Ruptuta de la anotación.

>Nueva anotación.
```

* Resultado

>Primera frase de la anotación.
>Segunda frase de la misma anotación.

Ruptuta de la anotación.

>Nueva anotación.


Para crear este documento con Markdown he utilizado Visual Studio Code y Github para tener un control de versiones del mismo.

* **Comandos Utilizados**:

    * **git init**: *Para iniciar git en Visual Studio y loggear la cuenta y su correspondiente repositorio.*
    * **git add .**: *Para añadir todos los cambios.*
    * **git commit**: *Para enviar el repositorio con el mensaje de los cambios realizados.*
    * **git push**: *Para enviar definitivamente el documento como versión final.*