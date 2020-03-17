# Mosaic Objects List


### Audio analysis
[audio analyzer](https://mosaic.d3cod3.org/reference.php?r=audio-analyzer). Este objeto es una estación de análisis de audio que transmite un vector con todos los datos analizados. Cada uno de los parámetros de audio analizado está disponible en los diferentes objetos extractores.

[beat extractor](https://mosaic.d3cod3.org/reference.php?r=beat-extractor). Este objeto extrae la detección del beat en el vector de análisis de audio.

[bpm extractor](https://mosaic.d3cod3.org/reference.php?r=bpm-extractor).Este objeto extrae el promedio de bmp en un periodo de tiempo, y ese periodo de tiempo en millisegundos.  

[centroid extractor](https://mosaic.d3cod3.org/reference.php?r=centroid-extractor). Este objeto extrae el centro de gravedad en los datos del espectro sonoro, su energía media.

[dissonance extractor](https://mosaic.d3cod3.org/reference.php?r=dissonance-extractor). Este objeto extrae la disonancia sensorial  (no musical o estética) midiendo la rugosidad perceptual del sonido.

[fft extractor](https://mosaic.d3cod3.org/reference.php?r=fft-extractor). Este objeto extrae la FFT (Fast Fourier Transform) desde el vector de análisis de audio.

[hfc extractor](https://mosaic.d3cod3.org/reference.php?r=hfc-extractor). Este objeto extrae el coeficiente HFC (High Frequency Content) de las altas frequencias del espectro sonoro.

[hpcp extractor](https://mosaic.d3cod3.org/reference.php?r=hpcp-extractor). Este objeto extrae el HPCP (Harmonic Pitch Class Profile) como un vector dinámico de 12 valores float.

[inharmonicity extractor](https://mosaic.d3cod3.org/reference.php?r=inharmonicity-extractor). Este objeto extrae la np-armonicidad de una señal sonora. El rango de disonancia va de 0 (señal muy armónica) a 1 (señal disonante).

[mel bands extractor](https://mosaic.d3cod3.org/reference.php?r=mel-bands-extractor). Este objeto extrae el valor dinámico de 24 bandas de mel  desde el vector de análisis de audio.

[mfcc extractor](https://mosaic.d3cod3.org/reference.php?r=mfcc-extractor). Este objeto extrae un vector dinámico de 13 datos del  MFCC (Mel Frequency Cepstral Coeﬃcients) desde el vector de análisis de audio.

[onset extractor](https://mosaic.d3cod3.org/reference.php?r=onset-extractor). Este objeto extrae la detección de un onset en la señal de audio como valor float (0 o 1).

[pitch extractor](https://mosaic.d3cod3.org/reference.php?r=pitch-extractor). Este objeto extrae el dato del pitch en la señal de audio como valor float (entre 0.0 y 4186.0).

[power extractor](https://mosaic.d3cod3.org/reference.php?r=power-extractor). Este objeto extrae el promedio de energía del vector de análisis de audio, como un valor float (entre 0.0 y 1.0).

[rms extractor](https://mosaic.d3cod3.org/reference.php?r=rms-extractor). Este objeto extrae el rms (Root Mean Square), la media cuadrática de energía del vector de análisis de audio, como un valor float  (entre 0.0 y 1.0).

[rolloff extractor](https://mosaic.d3cod3.org/reference.php?r=rolloff-extractor). Este objeto extrae el valor de la frecuencia roll-off del vector de análisis de audio, como un valor float  (entre 0.0 y 1.0).

[tristimulus extractor](https://mosaic.d3cod3.org/reference.php?r=tristimulus-extractor). Este objeto extrae un vector de tres elementos que miden la mezcla de armónicos en el vector de análisis de audio.

### Communications

[arduino serial](https://mosaic.d3cod3.org/reference.php?r=arduino-serial).  Este objeto se comunica con Arduino tanto para enviar como para recibir datos. El template [MosaicConnector.ino](https://mosaic.d3cod3.org/mosaicdoc/wp-content/uploads/2019/08/MosaicConnector.zip) tiene que utilizarse como archivo de Arduino.

[key pressed](https://mosaic.d3cod3.org/reference.php?r=key-pressed). Este objeto envía un bang cuando se presiona la tecla seleccionada. Para conocer el código ascii de la tecla, púlsala y el número aparece junto a "Last Key:"

[key released](https://mosaic.d3cod3.org/reference.php?r=key-released). Este objeto envía un bang cuando se suelta la tecla seleccionada. Para conocer el código ascii de la tecla, presiónala y su número aparecerá junto a "Last Key:"

[midi key](https://mosaic.d3cod3.org/reference.php?r=midi-key). Este objeto se usa vinculado al objeto midi receiver para mapear una tecla en un dispositivo midi.

[midi knob](https://mosaic.d3cod3.org/reference.php?r=midi-knob). Este objeto se usa vinculado al objeto midi receiver para mapear un knob en un dispositivo midi.

[midi pad](https://mosaic.d3cod3.org/reference.php?r=midi-pad). Este objeto se usa vinculado al objeto midi receiver para mapear un pad on en un dispositivo midi.

[midi receiver](https://mosaic.d3cod3.org/reference.php?r=midi-receiver). Con este objeto puedes recibir datos desde una interfaz midi.

[osc receiver](https://mosaic.d3cod3.org/reference.php?r=osc-receiver). Con este objeto puedes recibir datos por osc del tipo: numérico (float), texto (string), vector, o imagen (max 640x 480 para escala de grises, o 320x240 con RGB).

[osc sender](https://mosaic.d3cod3.org/reference.php?r=osc-sender). Con este objeto puedes enviar datos por osc del tipo: numérico (float), texto (string), vector, o imagen (max 640x 480 para escala de grises, o 320x240 con RGB).

### Computer vision

[background subtraction](https://mosaic.d3cod3.org/reference.php?r=background-subtraction). Este objeto aplica el algoritmo de Background subtraction.

[chroma key](https://mosaic.d3cod3.org/reference.php?r=chroma-key). Este objeto aplica el efecto chromakey entre dos texturas.

[color tracking](https://mosaic.d3cod3.org/reference.php?r=color-tracking).Este objeto aplica un tracking (rastreo) a un color determinado.

[contour tracking](https://mosaic.d3cod3.org/reference.php?r=contour-tracking). Este objeto procesa las áreas detectadas por el objeto background subtraction, y obtiene los blobs, el contorno y la envoltura convexa (convex hulls).

[haar tracking](https://mosaic.d3cod3.org/reference.php?r=haar-tracking).Este objeto detecta formas con características o estructuras específicas dentro de imágenes o frames de video.

[motion detection](https://mosaic.d3cod3.org/reference.php?r=motion-detection). Este objeto calcula la cantidad de movimiento frente a la cámara.

[optical flow](https://mosaic.d3cod3.org/reference.php?r=optical-flow). Este objeto muestra el impulso de movimiento reflejado en los frames de un video en directo o un archivo de video.

### Data

[bang multiplexer](https://mosaic.d3cod3.org/reference.php?r=bang-multiplexer). Este objeto puede recibir hasta 6 bangs y procesarlos como un medio de transmisión compartido (enchufe múltiple).

[bang to float](https://mosaic.d3cod3.org/reference.php?r=bang-to-float). Este objeto sólo envía el valor numérico después de recibir un bang.

[data to file](https://mosaic.d3cod3.org/reference.php?r=data-to-file). Este objeto guarda en un archivo txt los datos de un vector.

[data to texture](https://mosaic.d3cod3.org/reference.php?r=data-to-texture). Este objeto realiza síntesis de video usando el mismo motor de síntesis de audio de Mosaic, con un control separado sobre los canales RGB.

[file to data](https://mosaic.d3cod3.org/reference.php?r=file-to-data). Este objeto carga un archivo txt, previamente guardado por el objeto data to file, con los datos de un vector.

[floats to vector](https://mosaic.d3cod3.org/reference.php?r=floats-to-vector). Este objeto concatena hasta 6 datos float en un vector.

[texture to data](https://mosaic.d3cod3.org/reference.php?r=texture-to-data). Este objeto procesa los datos de una textura y los transmite como un vector con el que puede generar una forma de onda de sonido.

[vector at](https://mosaic.d3cod3.org/reference.php?r=vector-at). Este objeto extrae el valor en una posición particular de un vector.

[vector concat](https://mosaic.d3cod3.org/reference.php?r=vector-concat). Este objeto recibe hasta 6 vectores, y los concatena como un solo vector.

[vector gate](https://mosaic.d3cod3.org/reference.php?r=vector-gate). Este objeto recibe hasta 5 vectores, y transmite sólo el indicado en su inlet: open.

[vector multiply](https://mosaic.d3cod3.org/reference.php?r=vector-multiply). Este objeto escala todos los valores de un vector multiplicándolos por un valor.

### Graphics
[image exporter](https://mosaic.d3cod3.org/reference.php?r=image-exporter). Este objeto exporta imágenes de todos los cables de textura (azules).

[image loader](https://mosaic.d3cod3.org/reference.php?r=image-loader). Objeto para cargar archivos de imagen. Los formatos compatibles son jpg, png, gif y tif.

### GUI
[2d pad](https://mosaic.d3cod3.org/reference.php?r=2d-pad). Este objeto permite ajustar simultáneamente dos valores float (con un rango de 0,0 a 1,0) moviendo el punto del pad.

[bang](https://mosaic.d3cod3.org/reference.php?r=bang). Este objeto dispara un bang. Puedes controlarlo manualmente con el ratón o automatizarlo por su inlet.

[comment](https://mosaic.d3cod3.org/reference.php?r=comment). Objeto para comentarios. Pasa el ratón por encima para escribir el contenido y se autoformatea.

[message](https://mosaic.d3cod3.org/reference.php?r=message). Objeto para enviar mensajes de texto.

[player controls](https://mosaic.d3cod3.org/reference.php?r=player-controls). Este objeto permite controlar el estado de otro u otros objetos, como el video player, soundfile player, o timeline.

[signal viewer](https://mosaic.d3cod3.org/reference.php?r=signal-viewer). Un visualizador de señal de audio básica, también la transmite a través de sus outlets.

[slider](https://mosaic.d3cod3.org/reference.php?r=slider). Este objeto permite ajustar dinámicamente un valor numérico float (con un rango de 0,0 a 1,0) para enviarlo a otro objeto.

[sonogram](https://mosaic.d3cod3.org/reference.php?r=sonogram). Este objeto es una representación visual de las frecuencias del espectro de una señal sonora (FFT), mostrando cómo cambia con el tiempo.

[timeline](https://mosaic.d3cod3.org/reference.php?r=timeline). Módulo con interfaz gráfica, que permite visualizar el tiempo y poner keyframes en pistas de curvas, bang, switch, color y lfo. El objeto añade outlets automáticamnete cuando se crea un nuevo track.

[trigger](https://mosaic.d3cod3.org/reference.php?r=trigger). Este objeto permite mantener una acción activa, o inactiva, continuamente a lo largo del tiempo.

[video viewer](https://mosaic.d3cod3.org/reference.php?r=video-viewer). Un visor de video básico, el objeto lo visualiza, y lo transmite por su outlet.

[vu meter](https://mosaic.d3cod3.org/reference.php?r=vu-meter). Este objeto es un visualizador que muestra una representación del nivel de la señal de audio.


### Logic

[and &&](https://mosaic.d3cod3.org/reference.php?r=and). Objeto para el operador lógico "and" (&&), se utiliza en combinación con los objetos larger than (>) and smaller than (<).

[bigger than >](https://mosaic.d3cod3.org/reference.php?r=bigger-than). Objeto para el operador lógico "Mayor que" (>),útil en estructuras condicionales.

[counter](https://mosaic.d3cod3.org/reference.php?r=counter). Contador básico para estructuras iterativas.

[delay bang](https://mosaic.d3cod3.org/reference.php?r=delay-bang). Este es un objeto que envía un bang poco después de recibir otro bang.

[equality ==](https://mosaic.d3cod3.org/reference.php?r=equality). Objeto para el operador lógico ==, útil para estructuras condicionales.

[gate](https://mosaic.d3cod3.org/reference.php?r=gate). Este objeto recibe hasta 5 valores numéricos y transmite sólo el indicado en su inlet: open.

[inequality !=](https://mosaic.d3cod3.org/reference.php?r=inequality).  Objeto para el operador lógico !=, útil para estructuras condicionales.

[inverter](https://mosaic.d3cod3.org/reference.php?r=inverter). Objeto para invertir el valor transmitido por un objeto trigger o un bang.

[loadbang](https://mosaic.d3cod3.org/reference.php?r=loadbang). Igual que el objeto bang, pero actúa de forma automática al cargar el patch, un solo bang se dispara después de un tiempo de retardo configurable.

[or ||](https://mosaic.d3cod3.org/reference.php?r=or). Objeto para el operador lógico "o" (||) que se utiliza en combinación con los objetos bigger than (>) o smaller than (<).

[select](https://mosaic.d3cod3.org/reference.php?r=select). Este objeto permite activar secuencialmente hasta 16 bangs.

[smaller than <](https://mosaic.d3cod3.org/reference.php?r=smaller-than). Objeto para el operador lógico "Menor que" (>), útil para estructuras condicionales.

[spigot](https://mosaic.d3cod3.org/reference.php?r=spigot). Este objeto actúa como un interruptor, para transmitir, o no, la señal de diferentes tipos.

[timed semaphore](https://mosaic.d3cod3.org/reference.php?r=timed-semaphore). Este objeto interrumpe, durante cierto tiempo, el flujo continuo de datos para generar una acción discreta.


### Math
[add](https://mosaic.d3cod3.org/reference.php?r=add). Objeto para la operación aritmética básica de sumar (adición).

[clamp](https://mosaic.d3cod3.org/reference.php?r=clamp). Con este objeto se puede establecer un rango de valores (máximo y mínimo), y el objeto fuerza los valores de entrada a ese rango.

[constant](https://mosaic.d3cod3.org/reference.php?r=constant). Objeto para introducir o recibir un valor numérico.

[divide](https://mosaic.d3cod3.org/reference.php?r=divide). Objeto para la operación aritmética básica de dividir.

[map](https://mosaic.d3cod3.org/reference.php?r=map). Este objeto re-mapea un número de un rango a otro.

[metronome](https://mosaic.d3cod3.org/reference.php?r=metronome). Este objeto envía un bang con la periodicidad de tiempo que se especifica en milisegundos.

[modulus](https://mosaic.d3cod3.org/reference.php?r=modulus). Este objeto calcula el resto de un número dividido por otro.

[multiply](https://mosaic.d3cod3.org/reference.php?r=multiply). Objeto para la operación aritmética básica de multiplicar.

[simple noise](https://mosaic.d3cod3.org/reference.php?r=simple-noise). Este objeto es un generador de estándar ruido Perlin unidimensional.

[simple random](https://mosaic.d3cod3.org/reference.php?r=simple-random). Este objeto es un generador de números aleatorios estándar (pseudoaleatorio).

[smooth](https://mosaic.d3cod3.org/reference.php?r=smooth). Este objeto aplica un filtro de suavizado por interpolación al flujo de datos recibidos.

[subtract](https://mosaic.d3cod3.org/reference.php?r=subtract). Objeto para la operación aritmética básica de restar.

### Scripting
[bash script](https://mosaic.d3cod3.org/reference.php?r=bash-script). Objeto para cargar un archivo de programación en lenguaje bash (Bourne-Again SHell).

[lua script](https://mosaic.d3cod3.org/reference.php?r=lua-script). Este objeto es un contenedor live-coding de archivos de programación en lenguaje Lua con un binding a la libreria de openFrameworks (OF) e imita la estructura de programación de OF. Puedes escribir el código con el code editor de Mosaic, o con el editor de códigos por defecto de tu ordenador.

[processing script](https://mosaic.d3cod3.org/reference.php?r=processing-script). Este objeto es un contenedor de archivos para programación de Processing incorporada a un template de Mosaic. Puedes escribir el código con el code editor de Mosaic, o con el editor de códigos por defecto de tu ordenador.

[python script](https://mosaic.d3cod3.org/reference.php?r=python-script).Este objeto es un contenedor de archivos para programación en python incorporada a un template de Mosaic. Puedes escribir el código con el code editor de Mosaic, o con el editor de códigos por defecto de tu ordenador.

[shader object](https://mosaic.d3cod3.org/reference.php?r=shader-object). Este objeto es un contenedor de archivos GLSL, capaz de cargar los shaders y editarlos en tiempo real. Puedes escribir el código con el code editor de Mosaic, o con el editor de códigos por defecto de tu ordenador.

### Sound

[ADSR envelope](https://mosaic.d3cod3.org/reference.php?r=adsr-envelope). Con este objeto se puede regular el Attack, Decay, Sustain and Release de un sonido.

[AHR envelope](https://mosaic.d3cod3.org/reference.php?r=ahr-envelop). Con este objeto se puede regular la envolvente estándar del AHR con Attack Hold and Release.

[amp](https://mosaic.d3cod3.org/reference.php?r=amp). Este objeto regula la potencia de la señal de una onda sonora de 0 (sin sonido) a 12.

[audio exporter](https://mosaic.d3cod3.org/reference.php?r=audio-exporter). Este objeto permite grabar el sonido generado por un patch.

[audio gate](https://mosaic.d3cod3.org/reference.php?r=audio-gate). Este objeto puede recibir hasta 5 señales de sonido, y transmite sólo la indicada en su inlet: open.

[bit cruncher](https://mosaic.d3cod3.org/reference.php?r=bit-cruncher). Este objeto genera un efecto de audio lo-fi (baja fidelidad), que produce una distorsión al reducir la resolución en la señal de datos de audio.

[bit noise](https://mosaic.d3cod3.org/reference.php?r=bit-noise). Este objecto es un generador de bit noise digital.

[chorus](https://mosaic.d3cod3.org/reference.php?r=chorus). Este objeto es un efecto de coro en la señal de datos de audio.

[comb filter](https://mosaic.d3cod3.org/reference.php?r=comb-filter). Este objeto es un filtro comb (peine) para la señal de audio.

[compressor](https://mosaic.d3cod3.org/reference.php?r=compressor). Este objeto es un filtro compresor para la señal de audio.

[crossfader](https://mosaic.d3cod3.org/reference.php?r=crossfader). Este objeto le permite producir una transición suave entre dos señales de audio.

[data oscillator](https://mosaic.d3cod3.org/reference.php?r=data-oscillator). Este objeto procesa un vector de datos float y lo transmite como señal de audio.

[decimator](https://mosaic.d3cod3.org/reference.php?r=decimator). Este objeto reduce el sample rate de una señal de audio.

[delay](https://mosaic.d3cod3.org/reference.php?r=delay). Este objeto es un efecto de sonido que produce la multiplicación y retardo modulado de una señal de audio.

[ducker](https://mosaic.d3cod3.org/reference.php?r=ducker). Este objeto es un efecto ducker en la envolvente de un sonido.

[hi pass](https://mosaic.d3cod3.org/reference.php?r=hi-pass). Este objeto es un filtro de paso-alto para permitir que las altas frecuencias pasen mientras se filtra o corta las bajas frecuencias.

[low pass](https://mosaic.d3cod3.org/reference.php?r=low-pass). Este objeto es un filtro de paso-bajo que filtra o corta las frecuencias que están por encima de la frecuencia de corte.

[lfo](https://mosaic.d3cod3.org/reference.php?r=lfo). Este objeto es un oscilador de baja frecuencia.

[mixer](https://mosaic.d3cod3.org/reference.php?r=mixer). Este objeto combina hasta 6 señales de audio.

[note to frequency](https://mosaic.d3cod3.org/reference.php?r=note-to-frequency). Este objeto extrae la frecuencia fundamental de una nota midi.

[pd patch](https://mosaic.d3cod3.org/reference.php?r=491). Este objeto es un contenedor de archivos de Pure Data con entradas y salidas. El archivo de datos puro está programado en una plantilla que ya tiene comunicación entre ambos programas.

[panner](https://mosaic.d3cod3.org/reference.php?r=panner). Este objeto es un control de distribución de paneo para una señal de sonido.

[pulse](https://mosaic.d3cod3.org/reference.php?r=pulse). Este objeto es una forma de onda de pulso en la que el pitch y el ancho de pulso pueden ser ajustados dinámicamente.

[quad panner](https://mosaic.d3cod3.org/reference.php?r=quad-panner). Este objeto es una interfaz de 2d pad para distribuir dinámicamente el paneo cuadrafónico de una señal de audio.

[resonant 2pole filter](https://mosaic.d3cod3.org/reference.php?r=resonant-2pole-filter). Este objeto es un filtro de 12 db que regula el pitch,  cut-off y resonancia para las opciones de paso-bajo, paso de banda, paso-alto y notch (rechazo).

[reverb](https://mosaic.d3cod3.org/reference.php?r=reverb). Este objeto es un efecto de reverberación, en el que se puede regular dinámicamente el tiempo, densidad, atenuación y velocidad

[saw](https://mosaic.d3cod3.org/reference.php?r=saw). Este objeto es una forma de onda de sierra en la que se puede regular dinámicamente el pitch.

[signal trigger](https://mosaic.d3cod3.org/reference.php?r=signal-trigger). Este objeto lanza un bang cuando el nivel de la señal sonora excede el umbral marcado.

[sine](https://mosaic.d3cod3.org/reference.php?r=sine). Este objeto es una forma de onda sinusoidal en la que se puede regular dinámicamente el pitch.

[soundfile player](https://mosaic.d3cod3.org/reference.php?r=soundfile-player). Este es un objeto de archivo de audio, puede cargar archivos .wav, .mp3, .ogg y .flac.

[triangle](https://mosaic.d3cod3.org/reference.php?r=triangle). Este objeto es una forma de onda triangular en la que se puede regular dinámicamente el pitch.

[white noise](https://mosaic.d3cod3.org/reference.php?r=white-noise). Este objeto es un generador de ruido blanco.


### System
[audio device](https://mosaic.d3cod3.org/reference.php?r=audio-device). Es un objeto del sistema Mosaic, lo que significa que no se puede añadir/eliminar, sino que aparece cuando se configura el sistema de sonido desde el menú Sound. El objeto audio device es una conexión virtual directa al hardware de audio.


### Video
[kinect grabber](https://mosaic.d3cod3.org/reference.php?r=kinect-grabber). Este objeto recibe directamente la señal de un sensor Kinect.

[video crop](https://mosaic.d3cod3.org/reference.php?r=video-crop). Este objeto permite recortar un fragmento rectangular de una textura (imagen, vídeo, gráfico...).

[video feedback](https://mosaic.d3cod3.org/reference.php?r=video-feedback). Con este objeto puedes hacer una retroalimentación de la textura. La acción se visualiza escalando y/o moviendo la textura, mostrando el rastro de sus bordes en el camino.

[video exporter](https://mosaic.d3cod3.org/reference.php?r=video-exporter). Este objeto exporta un archivo de video desde cualquier cable de textura (azul). Puedes seleccionar el codec de video: mpg4, mjpeg, jpg2000, libx264, o hevc.

[video gate](https://mosaic.d3cod3.org/reference.php?r=video-gate). Este objeto recibe hasta 5 texturas y transmite sólo la indicada en su entrada: open.

[video grabber](https://mosaic.d3cod3.org/reference.php?r=video-grabber). Este objeto recibe directamente la señal de una webCam.

[video player](https://mosaic.d3cod3.org/reference.php?r=video-player). Objeto para reproducir archivos de vídeo. En mac OSX puedes cargar archivos .mov y .mp4; en linux, archivos .mp4, .mpeg y .mpg.

[video receiver](https://mosaic.d3cod3.org/reference.php?r=video-receiver). Este objeto recibe la transmisión de video desde el objeto  video sender a través del protocolo de comunicación [NDI](https://en.wikipedia.org/wiki/Network_Device_Interface) (Network Device Interface).

[video sender](https://mosaic.d3cod3.org/reference.php?r=video-sender). Este objeto envía una transmisión de video al objeto video receiver a través del protocolo de comunicación [NDI](https://en.wikipedia.org/wiki/Network_Device_Interface) (Network Device Interface).

[video streaming](https://mosaic.d3cod3.org/reference.php?r=video-streaming).Objeto para streaming video vinculado con el player de video VLC

[video timedelay](https://mosaic.d3cod3.org/reference.php?r=video-timedelay). Con este objeto puedes retrasar la reproducción de un archivo de video o de un video en directo.

[video transform](https://mosaic.d3cod3.org/reference.php?r=video-transform). Este objeto permite escalar y rotar una textura (imagen, video, gráfico...)


### Windowing
[live patching](https://mosaic.d3cod3.org/reference.php?r=live-patching). Muestra la textura en tiempo real en el fondo del patch, con alfa para que puedas trabajar con los objetos.

[output window](https://mosaic.d3cod3.org/reference.php?r=output-window). Este objeto crea una ventana de proyección. (⌘ o ctrl) + F = activar/desactivar la ventana a pantalla completa. Con la opción de warping y a pantalla completa se puede ajustar la superficie de proyección. Para todos los comandos de ajuste ver [output window reference](https://mosaic.d3cod3.org/reference.php?r=output-window)

[projection mapping](https://mosaic.d3cod3.org/reference.php?r=projection-mapping). Módulo de video mapping. Proporciona una interfaz con recursos más flexibles que la retícula de la warping.
