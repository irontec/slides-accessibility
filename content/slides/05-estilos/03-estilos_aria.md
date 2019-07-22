### Estilo de estados con ARIA

Es una práctica común reflejar estados de componentes mediante clases CSS.

```xml
<div class="toggle pressed" role="button" aria-pressed="true">
</div>
```

En vez de utilizar el selector:

```css
.toggle.pressed{

}
```

Mejor reemplazarla por atributos ARIA, para verificar el estado de ARIA.


```css
.toogle[aria-pressed="true"]
```