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
    var s = "JavaScript syntax highlighting";
    alert(s);
    ```
```


```
    ```python
    s = "Python syntax highlighting"
    print s
    ```
```
```
    ```
    Si no se indica lenguaje no se resalta nada.
    ```
```

* Resultado

```
    ```javascript
    var s = "JavaScript syntax highlighting";
    alert(s);
    ```
```


```
    ```python
    s = "Python syntax highlighting"
    print s
    ```
```
```
    ```
    Si no se indica lenguaje no se resalta nada.
    ```
```