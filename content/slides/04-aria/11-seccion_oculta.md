### Secciones ocultas a la vista

Cualquier elemento que no tenga visibilidad, es __ocultado__ también __por la tecnología asistida__.

```xml
<div style="visibility: hidden;">
<button style="display:none;">
<span hidden>
```

Un elemento que no se representa visualmente, __se incluye__ en el __árbol de accesibilidad__.
 
 ```css
.lectorpantalla {
    position:absolute;
    left: -100000px;
    width: 1px;
    height: 1px;
    overflow: hidden;
}
```