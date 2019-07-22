### Atributos ARIA: role

El atributo __role ARIA__ permite indicar la función de un elemento de la interfaz. 

```xml
<div class="checbox checked" role="checkbox" aria-checked="true">
    Acepto las condiciones
</div>
```
El rol de ARIA se prioriza al rol del elemento HTML.

No es necesario redefinir la semántica de los elementos nativos

```xml
<input type="checkbox" role="checkbox">
```

[Lista de roles ARIA](https://www.w3.org/TR/wai-aria-1.1/#roles_categorization)