### Orden de tabulación del foco

El __orden de tabulación__ de los elementos nativos se basa en su __posición en el DOM__.

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

El orden de lectura y de ordenación debe ser lógico e intuitivo.

[Web AIM - 1.3.2 Meaningful Sequence](https://webaim.org/standards/wcag/checklist#sc1.3.2)