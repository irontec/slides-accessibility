### Offscreen content

A veces existen elementos en el DOM que no se muestran en pantalla y hacen que perdamos el foco.

Para encontrar el foco perdido utilizamos __document.activeElement__ en la consola.

![menu offscreen](media/offscreen.png) <!-- .element: style="height: 250px;" --> 

Solución: __display:none__ o __visibility:hidden__