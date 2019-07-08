### Orden del DOM

El orden de tabulación de los elementos nativos se basa en su posición en el DOM.

```
<button>I Should</button>
<button>Be Focused</button>
<button>Last!</button>
```

Al agregar estilos en línea, cambia el orden visual pero el DOM es el mismo.

```
<button style="float:right;">I Should</button>
<button>Be Focused</button>
<button>Last!</button>
```
