# FAQ

## ¿Cómo se guarda un patch de Mosaic?

Los patch de Mosaic se guardan en archivos tipo .xml. Para guardarlo, selecciona **Save patch As** desde el menú File, se abrirá una ventana de diálogo del ordenador y ponle un nombre Los patch de Mosaic se guardan en archivos tipo .xml. Para guardarlo, selecciona Save patch As desde el menú File, se abrirá una ventana de diálogo del ordenador y ponle un nombre en código ASCII de 7 bits (que no lleve "ñ", ni acentos, ni espacios vacíos:poner "video_project" no "video project") y ten cuidado en no borrar .xml. 

Al guardarlo se genera una carpeta con el mismo nombre que le hayas puesto al patch, dentro de ella verás el archivo .xml y otra carpeta llamada **data** en la que se irán incorporando automáticamente todos los archivos de scripting, video, audio o imagen que uses en el patch. Para evitar la duplicación de archivos, se recomienda poner en la capeta data del patch los archivos que vayamos a utilizar para que Mosaic no los duplique.

Cuando se abre Mosaic por primera vez, se genera en tu ordenador una carpeta llamada Mosaic:

- MacOS: `Documents/Mosaic/`
- Windows: `My Documents/Mosaic/`
- Linux: `~/.Mosaic/`

 Se aconseja guardar todos los patch de Mosaic en una carpeta (con el nombre que quieras) dentro esa carpeta Mosaic sin tocar las carpetas data y examples que contiene.     

Los patch se guardan solo una vez, y según vayamos trabajando el archivo  se irá guardando automáticamente por lo que al terminar el trabajo no  hay que volver a guardarlo. Si quieres dejar un patch tal como está, pero seguir el proceso hasta otro nivel, entonces sí tienes que guardarlo de nuevo con Save patch As, poniendo otro nombre y seguir trabajando en este último. Al finalizar no hay que guardar, los dos archivos estarán guardados.

## ¿Cómo se abre un patch de Mosaic?

Puedes abrir un pacht previamente guardado de Mosaic desde el menú File/ Open patch, o puedes arrastrar el archivo .xml al canvas. 

No puedes abrirlo clicando sobre el icono del archivo, porque .xml (Extensible Markup Language) es un estándar para el intercambio de información estructurada entre  plataformas, y si lo clicas directamente te lo abrirá el editor de código que tengas asignado por defecto en tu ordenador. 

## ¿Cómo se pone un objeto?

Puedes añadir un objeto seleccionándolo desde el menú objects, en el que los objetos están organizados por categorías. 

Este menú también aparece cuando clicas el botón derecho del ratón en cualquier lugar vacío del canvas. En este menú flotante tienes la opción Search con un campo de texto, si sabes el nombre del objeto puedes empezar a escribirlo y al teclear el tabulador Mosaic completa su nombre y si es el buscado al teclear Enter el objeto se situará cerca de esa posición. 

En los objetos que contienen archivos (Image loader, Video player, Soundfile player, Bash script, Lua script, Processing script o Shader script) puedes arrastrar directamente el archivo al canvas, el objeto aparecerá con el archivo ya cargado. En el menú de configuración de estos objetos verás la opción Open, si has incorporado el objeto vacío, desde Open puedes cargarle el archivo. 

## ¿Cómo activar el sonido?

Cuando se abre Mosaic, el sistema de sonido no está activado. Si no vas a usar audio en tu patch puede seguir así, no hay problema aunque en el logger ponga en rojo: [error] The selected audio devices couldn't be properly installed in your system! 

Para activar el sistema de sonido, desde el menú Sound, selecciona en **Input device** el dispositivo de entrada de sonido de tu ordenador que quieras utilizar, y en **Output device**, el de salida. Después clica **DSP ON**. Entonces el objeto Audio device aparece en el canvas con el mismo número de inlets y outlets que tengan los dispositivos seleccionados. 

Audio device es un objeto de sistema de Mosaic, lo que significa que no se puede agregar/eliminar como los otros objetos, y establece una conexión directa con el dispositivo de audio del ordenador que se ha seleccionado.

## ¿Cómo se activa Warping en el objeto Output window?

En el objeto Output window, el warping solo funciona con la ventana del proyector a pantalla completa y el botón de Warping activado. Si tecleas W aparece un recuadro cuyos vértices pueden moverse con el ratón, para ajustar los límites de la proyección. Las teclas para ampliar la retícula en el interior de la imagen son:


    - F2 añadir secciones verticales.
    - F1 borrar secciones verticales
    - F4 añadir secciones horizontales
    - F3 borrar secciones horizontales
    - M  activa/desactiva retícula curva/lineal

La posición de todas las intersecciones de la retícula puede ajustarse con el ratón. Por defecto las deformaciones se adaptan a formas curvas, si tecleas M cambias a retícula lineal, si tecleas M de nuevo vuelve a curvas.

La opción Load warping permite cargar un warping previamente guardado y Save warping para guardarlo en un archivo tipo json.



## ¿Cómo hacer live-coding en Mosaic?

En Mosaic se puede visualizar el código del objeto Lua script en la ventana proyector, para ello hay que conectar los dos outlets, el rojo y el azul del objeto Lua script al objeto output window. La lista de comandos para activar el live coding y otras funciones básicas es:
```
- (⌘ o ctrl) + F = Activa/desactiva fullscreen
- (⌘ o ctrl) + T = Muestra/oculta live code editor
- (⌘ o ctrl) + K = ZOOM IN/ZOOM OUT (a la altura del cursor)
- (⌘ o ctrl) + L = Toggle Line Wrapping (retornos de líneas)
- (⌘ o ctrl) + N = Muestra/oculta la numeración de líneas
- (⌘ o ctrl) + E = Efectúa el script
- (⌘ o ctrl) + C = Copiar
- (⌘ o ctrl) + V = Pegar
- (⌘ o ctrl) + X = Cortar
- (⌘ o ctrl) + Z = Deshacer
```
Para escribir  código utiliza las teclas de flecha para mover el cursor al punto deseado. 

 