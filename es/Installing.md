# Instalación y funcionamiento

Según el sistema operativo, desde la web de [Mosaic](https://mosaic.d3cod3.org/#download)  se puede descargar la aplicación, el script de instalación o los archivos a compilar.

### Instalar en Mac

Descargar y descomprimir la carpeta Mosaic_vn.n.n_osx_release.zip (vn.n.n corresponde al número de la *release*), y trasladar la app a la carpeta de aplicaciones. Al abrir  el programa por primera vez se genera una carpeta denominada Mosaic en  Documentos, dentro de ella hay dos carpetas, una denominada **data**, se recomienda NO TOCAR el contenido de esa carpeta y otra llamada **examples** que contiene los ejemplos que vienen con la aplicación.

### Instalar en Windows

Mosaic para Windows continuará sólo a nivel de código fuente. El código estará probado para compilar correctamente en Windows, pero no habrá instaladores disponibles para descargar. 

Si quieres usar Mosaic en windows, tienes que compilarlo con [qtcreator 4.6.1](https://download.qt.io/official_releases/qtcreator/4.6/4.6.1/).

##### openFrameworks
Descarga OF 0.11.0 STABLE (descarga oficial desde [OF site](https://openframeworks.cc/download/))

Después de tener openFrameworks funcionando, necesitas clonar desde git los ofxAddons.

##### OFXADDONS

Clona este listado de addons necesarios: 

```
cd <your_openframeworks_release_folder>/addons

git clone https://github.com/d3cod3/ofxAudioAnalyzer
git clone https://github.com/npisanti/ofxAudioFile
git clone https://github.com/d3cod3/ofxBTrack
git clone https://github.com/d3cod3/ofxChromaKeyShader
git clone https://github.com/kylemcdonald/ofxCv
git clone https://github.com/d3cod3/ofxDatGui
git clone https://github.com/arturoc/ofxEasing
git clone https://github.com/kylemcdonald/ofxFaceTracker
git clone https://github.com/d3cod3/ofxFFmpegRecorder
git clone https://github.com/d3cod3/ofxFontStash
git clone https://github.com/d3cod3/ofxGLEditor
git clone https://github.com/armadillu/ofxGLError
git clone https://github.com/d3cod3/ofxHapPlayer
git clone https://github.com/armadillu/ofxHistoryPlot
git clone https://github.com/d3cod3/ofxJava
git clone https://github.com/jeffcrouse/ofxJSON
git clone https://github.com/d3cod3/ofxImGui
git clone https://github.com/d3cod3/ofxInfiniteCanvas
git clone --branch=of-0.10.0 https://github.com/d3cod3/ofxLua
git clone https://github.com/d3cod3/ofxMidi
git clone https://github.com/d3cod3/ofxMtlMapping2D
git clone https://github.com/d3cod3/ofxNDI
git clone --branch=OF0.9.8 https://github.com/d3cod3/ofxPython
git clone https://github.com/d3cod3/ofxParagraph
git clone https://github.com/danomatika/ofxPd
git clone https://github.com/d3cod3/ofxPdExternals
git clone https://github.com/npisanti/ofxPDSP
git clone https://github.com/armadillu/ofxSimpleHttp
git clone https://github.com/d3cod3/ofxThreadedFileDialog
git clone https://github.com/d3cod3/ofxTimeline
git clone https://github.com/armadillu/ofxTimeMeasurements
git clone https://github.com/d3cod3/ofxVisualProgramming
git clone https://github.com/d3cod3/ofxWarp
```

Después, debes clonar desde git el [repositorio de Mosaic](https://github.com/d3cod3/Mosaic.git) y seguir la guía de configuración para el IDE de [qtcreator](https://www.qt.io/).

### Instalar en Linux

En Linux, se puede descargar un script bash para la terminal. Según la distro de Linux las opciones son:

- Ubuntu: [install_mosaic_ubuntu.sh](https://gist.github.com/d3cod3/81b8971ebf5fc9a6d288ca93fc3c3dad)
- Ubuntu Studio: [install_mosaic_ubuntustudio.sh](https://gist.github.com/d3cod3/869d6d36b2e4c6a5aa01c17cf6395e6b)
- Linux Mint: [install_mosaic_linuxmint.sh](https://gist.github.com/d3cod3/d1a544e0cf21b8733b567a3d87905d23)
- Debian: [install_mosaic_debian.sh](https://gist.github.com/d3cod3/fbb76735554c3b38e811414d96fc28d6)
- Fedora: [install_mosaic_fedora.sh](https://gist.github.com/d3cod3/2a6e9f1f21045d763571cc4172cf2d6c#file-install_mosaic_fedora-sh)

Estos scripts automáticamente descargan, clonan, compilan e instalan todo, tras lo cual, Mosaic aparece en el menú de escritorio.