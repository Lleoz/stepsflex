# Ejemplo de Steps en Flex

_Este ejemplo muestra una linea de steps que se adaptan según el espacio en el contendor._

## Comenzando 🚀

_Realiza un push al proyecto para obtenerlo con los últimos cambios._

### Pre-requisitos 📋

_Un editor de texto_
```
Visual Code
Sublime Text
Notepad ++
```
### Instalación 🔧

_Para obtener el proyecto puedes realizar un clone con el comando_
```
git clone https://github.com/Lleoz/stepsflex.git
```
_O descargar el zip y descomprimirlo en una carpeta_

_Se debe abrir el archivo *index.html* en el navegador web_

_Finaliza con un ejemplo de cómo obtener datos del sistema o como usarlos para una pequeña demo_

## Despliegue 📦

_Exiten 3 estilos para los pasos._
```
boxActive
boxInActive
boxSucessful
```
**boxActive**: Se utiliza en el paso activo.

**boxInActive**: Se utiliza en los pasos futuros que no han sido activados.

**boxSucessful**: Se utiliza en los pasos pasados que se cumplieron correctamente.

## Agregar más pasos

_Para agregar más pasos solo debe añadirse el siguiente código entre la clase **flex**
```
 <div class="contenedorPasos" style="z-index: 2;">
    <div class="boxSucessful">
        <div class="numeroPaso">
                1
        </div>
        <div class="numeroPaso"><i class="icon-process-line fa fa-check"></i></div>
        <div class="nombrePaso">Paso 1</div>
    </div>
</div>
```

El ejemplo se puede ver en [EJEMPLO STEPS](https://codepen.io/lleoz/pen/xxwWxjd)

