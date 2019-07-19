### Uso del tabindex

Utilizamos el atributo __tabindex__ para especificar un __orden explícito__ para los elementos de página que puedan tener el foco.

```
<div tabindex="0">Focus</div>
```

* __tabindex=0__ agrega el elemento (div, p) en el orden natural de tabulación. 
* __tabindex=-1__ fuera del orden de tabulación. Volve a enfocarlo llamando al método __focus()__.
* __tabindex=5__ trae el elemento al frente. __¡Anti-pattern!__ Mejor subirlo en el DOM.