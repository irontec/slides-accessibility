### Uso del tabindex

Utilizamos el atributo __tabindex__ para especificar un __orden explícito_- para los elementos de página que puedan tener el foco.

```
<div tabindex="0">Focus</div>
```

* __tabindex=0__ agrega el elemento en el orden natural de tabulación.
* __tabindex=-1__ fuera del orden de tabulación.
* Llamar al método __focus()__.
* __tabindex=5__ trae el elemento al frente. __¡Anti-pattern!__