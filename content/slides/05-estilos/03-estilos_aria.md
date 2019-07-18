### Estilo de estados con ARIA

Es una práctica común reflejar estados de componentes mediante clases CSS.

```
<div class="toggle pressed" role="button" aria-pressed="true">
</div>
```
En vez de utilizar el selector:
```
.toggle.pressed{

}
```
Mejor reemplazarla por atributos ARIA, para verificar el estado de ARIA.

```css
.toogle[aria-pressed="true"]
```