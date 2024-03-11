
<!-- CONTENIDO -->

<ol>
  <li><a href="#intro">INTRO</a></li>
  <li><a href="#hiperenlace">HIPERENLACE</a></li>
  <li><a href="#listas">LISTAS</a></li>
  <li><a href="#imagenes">IMÁGENES</a></li>
  <li><a href="#input">INPUTS</a></li>
</ol>

<br>

<h2 class="h2" id="intro">INTRO</h2>

<br>

<p>Esto es un parrafo.</p>

```javascript
<p>Esto es un parrafo.</p>
```

<br>

<q>Poner un texto entre comillas.</q>

```javascript
<q>Poner un texto entre comillas.</q>
```

<br>

<p>Para poner un trozo de texto <strong>resaltado usaremos la etiqueta strong.</strong></p>

```javascript
<p>Para poner un trozo de texto <strong>resaltado usaremos la etiqueta strong.</strong></p>
```

<br>

<em>Poner un texto en cursiva</em>

```javascript
<em>Poner un texto en cursiva</em>
```

<br>

<b>Poner texto en negrita, otra forma</b>

```javascript
<b>Poner texto en negrita, otra forma</b>
```

<br>

SubÍndice <sub>i</sub>

```javascript
SubÍndice <sub>i</sub>
```

<br>

SuperÍndice <sup>i</sup>

```javascript
SuperÍndice <sup>i</sup>
```

---

<br>

<h2 class="h2" id="hiperenlace">HIPERENLACES</h2>

<br>

<a href="www.google.com">HiperEnlace a google</a>

```javascript
<a href="www.google.com">HiperEnlace a google</a>
```

<br>

HiperEnlace con una foto:

<a href="www.google.com"><img width="50" src="https://png2.cleanpng.com/sh/033064830b5b449e70bb7a4fb0120ace/L0KzQYi4UsE3N5VoT5GAYUO4RYW3Usc4bGpqTpCDNES4RYK7VME2OWQ5TKY8NUS3SYGCTwBvbz==/5a35540277d9e6.8445514415134443544909.png"/></a>

```javascript
<a href="www.google.com"><img width="50" src="enlace de imagen"/></a>
```

<br>

<p>Dependiendo del <strong>target</strong> se abrirá el enlace desde la misma ventana o desde una nueva.</p>

```javascript
// _blank abre en nueva pestaña
<a href="www.google.com" target="_blank"></a>
// _self se abre en la misma ventana
<a href="www.google.com" target="_blank"></a>

```


---

<br>

<h2 class="h2" id="listas">LISTAS</h2>

<br>

<h4>Desordenadas</h4>

<ul>
  <li>Elemento 1</li>
  <li>Elemento 2</li>
  <ul>
    <li>Elemento 2.1</li>
    <li>Elemento 2.2</li>
  </ul>
  <li>Elemento 3</li>
</ul>

```javascript
<ul>
  <li>Elemento 1</li>
  <li>Elemento 2</li>
  <ul>
    <li>Elemento 2.1</li>
    <li>Elemento 2.2</li>
  </ul>
  <li>Elemento 3</li>
</ul>
```

<br>

<h4>Ordenadas</h4>

<ol>
  <li>Elemento 1</li>
  <li>Elemento 2</li>
  <ol>
    <li>Elemento 2.1</li>
    <li>Elemento 2.2</li>
  </ol>
  <li>Elemento 3</li>
</ol>

```javascript	
<ol>
  <li>Elemento 1</li>
  <li>Elemento 2</li>
  <ol>
    <li>Elemento 2.1</li>
    <li>Elemento 2.2</li>
  </ol>
  <li>Elemento 3</li>
</ol>
```

<br>

Podemos decidir desde que numero empieza:

<ol start="10">
  <li>Elemento 1</li>
  <li>Elemento 2</li>
  <li>Elemento 3</li>
</ol>

```javascript	
<ol start="10">
  <li>Elemento 1</li>
  <li>Elemento 2</li>
  <li>Elemento 3</li>
</ol>
```

<br>

También podemos decidir que lo haga de manera asc a desc:

<ol reversed>
  <li>Elemento 1</li>
  <li>Elemento 2</li>
  <li>Elemento 3</li>
</ol>

```javascript	
<ol reversed>
  <li>Elemento 1</li>
  <li>Elemento 2</li>
  <li>Elemento 3</li>
</ol>
```

<br>

Lista de definiciones:

<dl>
  <dt>Automóvil</dt>
<dd>Vehículo de cuatro ruedas con motor</dd>
  <dt>Motocicleta</dt>
<dd>Vehículo de dos ruedas con motor</dd>
  <dt>Bicicleta</dt>
<dd>Vehículo de dos ruedas sin motor</dd>
</dl>

```javascript	
<dl>
  <dt>Automóvil</dt>
<dd>Vehículo de cuatro ruedas con motor</dd>
  <dt>Motocicleta</dt>
<dd>Vehículo de dos ruedas con motor</dd>
  <dt>Bicicleta</dt>
<dd>Vehículo de dos ruedas sin motor</dd>
</dl>
```

---
<br>

<h2 class="h2" id="imagenes">IMÁGENES</h2>

<br>

La forma más antigua:

```javascript	
<img src="" alt="not found"/>
```

Forma más nueva:

```javascript	
<picture>
    <source media="(min-width: 768px)" srcset="descarga1.png">
    <source media="(min-width: 768px)" srcset="descarga2.png">
    // si no cumple ninguna condición
    <img src="descarga.png" alt="Imagen sin etiqueta">
</picture>
```

<br>

  <img width="100" src="https://png2.cleanpng.com/sh/033064830b5b449e70bb7a4fb0120ace/L0KzQYi4UsE3N5VoT5GAYUO4RYW3Usc4bGpqTpCDNES4RYK7VME2OWQ5TKY8NUS3SYGCTwBvbz==/5a35540277d9e6.8445514415134443544909.png" alt="not found">
  <figcaption>Fig.1 – Pie de foto.</figcaption>


```javascript	
<figure>
  <img width="100" src="" alt="not found">
  <figcaption>Fig.1 – Pie de foto.</figcaption>
<figure>
```

---

<br>

<h2 class="h2" id="tablas">TABLAS</h2>

<br>

<table>
    <tr>
        <td>Elemento1</td>
        <td>Elemento2</td>
        <td>Elemento3</td>
    </tr>
    <tr>
        <td>Elemento4</td>
        <td>Elemento5</td>
        <td>Elemento6</td>
    </tr>
</table>

```javascript	
<table>
    <tr> // fila 1
        <td>Elemento1</td> // columna 1
        <td>Elemento2</td> // columna 2
        <td>Elemento3</td> // columna 3
    </tr>
    <tr> // fila 2
        <td>Elemento4</td> // columna 1
        <td>Elemento5</td> // columna 2
        <td>Elemento6</td> // columna 3
    </tr>
</table>
```

<br>

<table>
    <tr>
        <td colspan="2">Elemento1</td>
        <td>Elemento2</td>
    </tr>
    <tr>
        <td>Elemento4</td>
        <td >Elemento5</td>
        <td >Elemento6</td>
    </tr>
</table>

```javascript	
<table>
    <tr>
        <td colspan="2">Elemento1</td>
        <td>Elemento2</td>
    </tr>
    <tr>
        <td>Elemento4</td>
        <td >Elemento5</td>
        <td >Elemento6</td>
    </tr>
</table>
```

<br>

<table>
    <tr>
        <td rowspan="2">Elemento1</td>
        <td>Elemento2</td>
        <td>Elemento3</td>
    </tr>
    <tr>
        <td >Elemento5</td>
        <td >Elemento6</td>
    </tr>
</table>

```javascript	
<table>
    <tr>
        <td rowspan="2">Elemento1</td>
        <td>Elemento2</td>
        <td>Elemento3</td>
    </tr>
    <tr>
        <td >Elemento5</td>
        <td >Elemento6</td>
    </tr>
</table>
```

---

<br>

<h2 style="color:#00A8FF" id="input">INPUTS</h2>

<br>


```javascript	
  // intevalo de numero que podemos introducir
  <input type="number" step="0,1">

  // podemos utilizar tambien max / min
  // meter de 5 en 5
  <input type="number" step="5">
```


<br>


Tipos:

* range
<input type="range">
* password
<input type="password">
* url
<input type="url" />
* email
<input type="email">
* submit
<input type="submit">
* reset
<input type="reset">
* date
<input type="date">
* time
<input type="time">
* file
<input type="file">
* search
<input type="search">
* color
<input type="color">
* checkbox
<input type="checkbox" name="formato" /> JPG
<input type="checkbox" name="formato" /> PNG

```javascript	
<input type="checkbox" name="formato" /> JPG
<input type="checkbox" name="formato" /> PNG
```

* radio
<input type="radio" name="radio"/> Opción 1 
<input type="radio" name="radio"/> Opción 2
<input type="radio" name="radio"/> Opción 3

```javascript	
<input type="radio" name="radio"/> Opción 1 
<input type="radio" name="radio"/> Opción 2
<input type="radio" name="radio"/> Opción 3
```

* textarea
<textarea rows="4" cols="60">Inserte aquí el texto</textarea>

```javascript	
<textarea rows="4" cols="60">Inserte aquí el texto</textarea>
```

* select
<select name="opciones">
  <option value="1">Opción 1</option>
  <option value="2">Opción 2</option>
  <option value="3">Opción 3</option>
</select>

```javascript	
<select name="opciones">
  <option value="1">Opción 1</option>
  <option value="2">Opción 2</option>
  <option value="3">Opción 3</option>
</select>
```



---

<h2 style="color:#00A8FF" id="fieldset">FIELDSET</h2>

```javascript	
  <fieldset>

    <legend>Escribir encabezado</legend> 

    <p>Completar con los datos deseados...</p>

  </fieldset>
```

<fieldset>
  <legend>Escribir encabezado</legend> 
  <p>Completar con los datos deseados...</p>
</fieldset>

---

