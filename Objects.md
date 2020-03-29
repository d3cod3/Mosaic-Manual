# Mosaic Objects List

### Audio analysis
[audio analyzer](https://mosaic.d3cod3.org/reference.php?r=audio-analyzer). This object is an audio analysis station which transmits a vector with all the analyzed data. Each type of audio data is available in the different extractor objects below.

[beat extractor](https://mosaic.d3cod3.org/reference.php?r=beat-extractor). This object extracts the beat detection from the audio analysis vector.

[bpm extractor](https://mosaic.d3cod3.org/reference.php?r=bpm-extractor).This object extracts the average bmp over a period of time, and that time period in milliseconds.  

[centroid extractor](https://mosaic.d3cod3.org/reference.php?r=centroid-extractor). This object extracts the center of gravity of the spectral energy, its power.

[dissonance extractor](https://mosaic.d3cod3.org/reference.php?r=dissonance-extractor). This object extracts sensory dissonance (not musical or aesthetic) by measuring the sound's perceptual roughness.

[fft extractor](https://mosaic.d3cod3.org/reference.php?r=fft-extractor). This object extracts the FFT (Fast Fourier Transform) from the audio analysis data vector.

[hfc extractor](https://mosaic.d3cod3.org/reference.php?r=hfc-extractor). This object extracts the HFC (High Frequency Content) coefficient from high frequencies of sound spectrum.

[hpcp extractor](https://mosaic.d3cod3.org/reference.php?r=hpcp-extractor). This object extracts the HPCP (Harmonic Pitch Class Profile) data as a dynamic vector of 12 float values.

[inharmonicity extractor](https://mosaic.d3cod3.org/reference.php?r=inharmonicity-extractor). This object extracts the inharmonicity of a sound signal. The discordance range is from 0 (pure harmonic signal) to 1 (discordant signal).

[mel bands extractor](https://mosaic.d3cod3.org/reference.php?r=mel-bands-extractor). This object extracts 24 mel bands from the audio analysis data vector.

[mfcc extractor](https://mosaic.d3cod3.org/reference.php?r=mfcc-extractor).This object extracts 13 data in a dynamic vector of MFCC (Mel Frequency Cepstral Coeﬃcients) from the audio analysis data vector.

[onset extractor](https://mosaic.d3cod3.org/reference.php?r=onset-extractor). This object extracts the detection of an onset in an audio signal as a float value (0 or 1).

[pitch extractor](https://mosaic.d3cod3.org/reference.php?r=pitch-extractor). This object extracts the pitch data of the audio signal as a float value (between 0.0 and 4186.0).

[power extractor](https://mosaic.d3cod3.org/reference.php?r=power-extractor). This object extracts the average power from the audio analysis data vector as a float value (between 0.0 and 1.0).

[rms extractor](https://mosaic.d3cod3.org/reference.php?r=rms-extractor). This object extracts the rms (Root Mean Square) power from the audio analysis data vector as a float value (between 0.0 and 1.0).

[rolloff extractor](https://mosaic.d3cod3.org/reference.php?r=rolloff-extractor). This objects extracts the frequency roll-off value from the audio analysis data vector as a float value (between 0.0 and 1.0).

[tristimulus extractor](https://mosaic.d3cod3.org/reference.php?r=tristimulus-extractor). This object extracts a three-element vector that measures the mixture of harmonics from the audio analysis data vector.


### Communications

[arduino serial](https://mosaic.d3cod3.org/reference.php?r=arduino-serial). This object communicates with Arduino for both sending and receiving data. This template [MosaicConnector.ino](https://mosaic.d3cod3.org/mosaicdoc/wp-content/uploads/2019/08/MosaicConnector.zip) must be used as Arduino template file.

[key pressed](https://mosaic.d3cod3.org/reference.php?r=key-pressed). This object sends a bang when the selected key has been pressed. To know the key ascii code, press it and the number appears next to "Last Key:"

[key released](https://mosaic.d3cod3.org/reference.php?r=key-released). This object sends a bang when the selected key has been released. To know the key ascii code, press it and its number appears next to "Last Key:"

[midi key](https://mosaic.d3cod3.org/reference.php?r=midi-key). This object is used linked to the midi receiver object to map a key on a midi device.

[midi knob](https://mosaic.d3cod3.org/reference.php?r=midi-knob). This object is used linked to the midi receiver object to map a knob on a midi device.

[midi pad](https://mosaic.d3cod3.org/reference.php?r=midi-pad). This object is used linked to the midi receiver object to map a pad on a midi device.

[midi receiver](https://mosaic.d3cod3.org/reference.php?r=midi-receiver). With this object you can receive data from a midi interface.

[osc receiver](https://mosaic.d3cod3.org/reference.php?r=osc-receiver). With this object you can receive data by osc of type numeric (float), text (string), vector or image (max 640x 480 for grayscale, or 320x240 for RGB)

[osc sender](https://mosaic.d3cod3.org/reference.php?r=osc-sender). With this object you can send data by osc of type numeric (float), text (string), vector <float> or image (maximum size 640x 480 for grayscale images, or 320x240 for RGB).


### Computer vision

[background subtraction](https://mosaic.d3cod3.org/reference.php?r=background-subtraction). This object applies the Background subtraction algorithm.

[chroma key](https://mosaic.d3cod3.org/reference.php?r=chroma-key). This object applies a chromakey effect between two textures.

[color tracking](https://mosaic.d3cod3.org/reference.php?r=color-tracking). This object applies a tracking to a certain color.  

[contour tracking](https://mosaic.d3cod3.org/reference.php?r=contour-tracking). This object processes the areas detected by the background subtraction object, and obtains the blobs, contour, and convex hulls.

[haar tracking](https://mosaic.d3cod3.org/reference.php?r=haar-tracking). This object detects shapes with specific characteristics or structures within images or video frames.

[motion detection](https://mosaic.d3cod3.org/reference.php?r=motion-detection). This object calculates the amount of motion in front of the camera.

[optical flow](https://mosaic.d3cod3.org/reference.php?r=optical-flow). This object shows the motion impulse reflected in the frames of a live video or video file.

### Data

[bang multiplexer](https://mosaic.d3cod3.org/reference.php?r=bang-multiplexer). This object can receive up to 6 bangs, and process them as a shared transmission medium (multiple socket).

[bang to float](https://mosaic.d3cod3.org/reference.php?r=bang-to-float). This object only sends the numerical value after receiving a bang.

[data to file](https://mosaic.d3cod3.org/reference.php?r=data-to-file). This object saves the vector data in a txt file, line by line for each computing frame.

[data to texture](https://mosaic.d3cod3.org/reference.php?r=data-to-texture). This object performs "analog style" video synthesis, with a separate control over RGB channels.

[file to data](https://mosaic.d3cod3.org/reference.php?r=file-to-data). This object loads a txt file, previously saved by the **data to file** object, and return the vector data, line by line, with reading synced by his bang inlet.

[float multiplexer](https://mosaic.d3cod3.org/reference.php?r=float-multiplexer). This object can receive up to 6 float values and transmits the last received one.

[floats to vector](https://mosaic.d3cod3.org/reference.php?r=floats-to-vector). This object concatenates up to 6 float data in an vector. It can be used in cascade to concatenate multiples of 6 floats.

[texture to data](https://mosaic.d3cod3.org/reference.php?r=texture-to-data). This object processes the image or video texture data, and transmits them as a data vector that can generate a custom sound waveform via the **data oscillator** object.

[vector at](https://mosaic.d3cod3.org/reference.php?r=vector-at). This object extracts the value at a particular index from a vector.

[vector concat](https://mosaic.d3cod3.org/reference.php?r=vector-concat). This object receives up to 6 vectors, and concatenates them as a single vector.

[vector gate](https://mosaic.d3cod3.org/reference.php?r=vector-gate). This object receives up to 5 vectors, and transmits only the one indicated in its first inlet: open.

[vector multiply](https://mosaic.d3cod3.org/reference.php?r=vector-multiply). This object scales all the values of a float vector by multiplying them by a value.

### Graphics

[image exporter](https://mosaic.d3cod3.org/reference.php?r=image-exporter). This object export images from every texture cable (blue ones).

[image loader](https://mosaic.d3cod3.org/reference.php?r=image-loader). Simple object for loading image files. Compatible formats are jpg, png, gif and tif.

### GUI

[2d pad](https://mosaic.d3cod3.org/reference.php?r=2d-pad). This object allows you to simultaneously adjust two float values (with a range from 0.0 to 1.0) by moving the pad point.

[bang](https://mosaic.d3cod3.org/reference.php?r=bang). This object triggers a bang. You can control it manually with the mouse or automate it by its inlet.

[comment](https://mosaic.d3cod3.org/reference.php?r=comment). A simple comment object. Mouse over to write auto-formatting content.

[message](https://mosaic.d3cod3.org/reference.php?r=message). A simple text message sending object.

[player controls](https://mosaic.d3cod3.org/reference.php?r=player-controls). This object allows you to control the status of another object (or objects), such as video player, soundfile player, or timeline.

[signal viewer](https://mosaic.d3cod3.org/reference.php?r=signal-viewer). A basic audio signal display, also transmits it through its outlets.

[slider](https://mosaic.d3cod3.org/reference.php?r=slider). This object allows you to dynamically adjust a numeric float value (with a range from 0.0 to 1.0) to send it to another object.

[sonogram](https://mosaic.d3cod3.org/reference.php?r=sonogram). This object is a visual representation display of spectrum frequencies of a sound signal (FFT), showing how it change over time.

[timeline](https://mosaic.d3cod3.org/reference.php?r=timeline). Module with graphic interface, it allows you to visualize the time and to put keyframes in curves, bang, switch, color, and lfo tracks. The object automatically adds outlets when you create a new track

[trigger](https://mosaic.d3cod3.org/reference.php?r=trigger). This object allows you to keep an action active, or inactive, continuously over time.

[video viewer](https://mosaic.d3cod3.org/reference.php?r=video-viewer). A basic video viewer, the object visualizes it, and bypasses it by its outlet.

[vu meter](https://mosaic.d3cod3.org/reference.php?r=vu-meter). This object is a display that shows the representation of the audio signal level.


### Logic

[and &&](https://mosaic.d3cod3.org/reference.php?r=and). Object for logical operator "and" (&&), it is used in combination with objects larger than (>) and smaller than (<).

[bigger than >](https://mosaic.d3cod3.org/reference.php?r=bigger-than). Object for logical operator "Bigger than" (>), useful in conditional structures.

[counter](https://mosaic.d3cod3.org/reference.php?r=counter). Basic counter for iterative structures.

[delay bang](https://mosaic.d3cod3.org/reference.php?r=delay-bang). This is an object to send a bang shortly after itself receives another bang.

[equality ==](https://mosaic.d3cod3.org/reference.php?r=equality). Object for the logical operator ==, useful for conditional structures.

[gate](https://mosaic.d3cod3.org/reference.php?r=gate). This object receives up to 5 numeric values and transmits only the one indicated in its inlet: open.

[inequality !=](https://mosaic.d3cod3.org/reference.php?r=inequality). Object for the logical operator !=, useful for conditional structures.

[inverter](https://mosaic.d3cod3.org/reference.php?r=inverter). Object to invert the value transmitted by a trigger or bang object.

[loadbang](https://mosaic.d3cod3.org/reference.php?r=loadbang). The same as bang object, but automatic on patch load, a single bang triggered after a configurable delay time.

[or ||](https://mosaic.d3cod3.org/reference.php?r=or). Object for logical operator "or" (||) which is used in combination with the objects bigger than (>) or smaller than (<).

[select](https://mosaic.d3cod3.org/reference.php?r=select). This object allows you to activate sequentially up to 16 bangs.

[smaller than <](https://mosaic.d3cod3.org/reference.php?r=smaller-than). Object for logical operator Smaller than (>), useful in conditional structures.

[spigot](https://mosaic.d3cod3.org/reference.php?r=spigot). This object acts as a switch, to transmit, or not, the signal of different types.

[timed semaphore](https://mosaic.d3cod3.org/reference.php?r=timed-semaphore). The semaphore object interrupts, for a certain time, the continuous data flow to generate a discrete action.


### Math

[add](https://mosaic.d3cod3.org/reference.php?r=add). Object for basic arithmetic operation to add (addition).

[clamp](https://mosaic.d3cod3.org/reference.php?r=clamp). With this object you can set a value range (max and min), and the object forces the input values to that range.

[constant](https://mosaic.d3cod3.org/reference.php?r=constant). Object to enter or receive a numeric value.

[divide](https://mosaic.d3cod3.org/reference.php?r=divide). Object to the basic arithmetic operation of division.

[map](https://mosaic.d3cod3.org/reference.php?r=map). This object re-maps a number from one range to another.

[metronome](https://mosaic.d3cod3.org/reference.php?r=metronome). This object sends a bang with the time periodicity you specify in milliseconds.

[modulus](https://mosaic.d3cod3.org/reference.php?r=modulus). This object calculates the remainder of a number divided by another.

[multiply](https://mosaic.d3cod3.org/reference.php?r=multiply). Object for the basic arithmetic operation of multiplication.

[simple noise](https://mosaic.d3cod3.org/reference.php?r=simple-noise). This object is a standard one dimensional Perlin noise generator.

[simple random](https://mosaic.d3cod3.org/reference.php?r=simple-random). This object is a standard random number generator (pseudorandom).

[smooth](https://mosaic.d3cod3.org/reference.php?r=smooth). This object applies an interpolation smoothing filter to the received data flow.

[subtract](https://mosaic.d3cod3.org/reference.php?r=subtract). Object for basic subtraction arithmetic operation.

### Scripting

This objects load different scripting languages for live-coding, you can edit the scripts code with the internal Mosaic code editor, or you can use the code editor you prefer. If you don't know which one to use, [Atom](https://www.atom.io) is a good one.

[bash script](https://mosaic.d3cod3.org/reference.php?r=bash-script). Object to load a programming file in bash language (Bourne-Again SHell). You can type code with the Mosaic code editor, or with the default code editor on your computer.

[lua script](https://mosaic.d3cod3.org/reference.php?r=lua-script). This object is a live-coding lua script container, with OF bindings mimicking the OF programming structure. You can type code with the Mosaic code editor, or with the default code editor on your computer.

[processing script](https://mosaic.d3cod3.org/reference.php?r=processing-script). This object is a container for files with Processing programming incorporated into a Mosaic template. You can type code with the Mosaic code editor, or with the default code editor on your computer.

[python script](https://mosaic.d3cod3.org/reference.php?r=python-script).This object is a container for files with python programming incorporated into a Mosaic template. You can type code with the Mosaic code editor, or with the default code editor on your computer.

[shader object](https://mosaic.d3cod3.org/reference.php?r=shader-object). This object is a GLSL container, capable of loading shaders and editing them in real-time. You can type code with the Mosaic code editor, or with the default code editor on your computer.


### Sound

[ADSR envelope](https://mosaic.d3cod3.org/reference.php?r=adsr-envelope). With this object you can regulate the Attack, Decay, Sustain and Release of a sound.

[AHR envelope](https://mosaic.d3cod3.org/reference.php?r=ahr-envelop). With this object you can regulate the standard AHR envelope with Attack Hold and Release.

[amp](https://mosaic.d3cod3.org/reference.php?r=amp). This object regulates the power of a sound wave signal from 0 (no sound) to 12.

[audio exporter](https://mosaic.d3cod3.org/reference.php?r=audio-exporter). This object allows you to record the sound generated from a patch.

[audio gate](https://mosaic.d3cod3.org/reference.php?r=audio-gate). This object can receive, as input, up to 5 sound signals, and transmits only the one indicated in its inlet: open.

[bit cruncher](https://mosaic.d3cod3.org/reference.php?r=bit-cruncher). This object generates a lo-fi (low fidelity) audio effect, which produces a distortion by reducing the resolution in the audio data signal.

[bit noise](https://mosaic.d3cod3.org/reference.php?r=bit-noise). This object is a bit noise digital generator.

[chorus](https://mosaic.d3cod3.org/reference.php?r=chorus). This object is a chorus effect for audio data signal.

[comb filter](https://mosaic.d3cod3.org/reference.php?r=comb-filter). This object is a comb filter for audio data signal.

[compressor](https://mosaic.d3cod3.org/reference.php?r=compressor). This object is a compressor filter for audio  signal.

[crossfader](https://mosaic.d3cod3.org/reference.php?r=crossfader). This object allow you to produce a smooth transition between two audio signals.

[data oscillator](https://mosaic.d3cod3.org/reference.php?r=data-oscillator). This object is a wavetable oscillator, that transform his float vector data into a waveform.

[decimator](https://mosaic.d3cod3.org/reference.php?r=decimator). This object reduces the sample rate of an audio signal.

[delay](https://mosaic.d3cod3.org/reference.php?r=delay). This object is a sound effect that produces a modulated multiplication and delay of a sound signal

[ducker](https://mosaic.d3cod3.org/reference.php?r=ducker). This object is a ducker effect in the envelope of a sound.

[hi pass](https://mosaic.d3cod3.org/reference.php?r=hi-pass). This object is a high-pass filter to allow high frequencies to get through while filtering or cutting low frequencies.  

[low pass](https://mosaic.d3cod3.org/reference.php?r=low-pass). This object is a low-pass filter to reduce or cut the frequencies above the cutoff frequency.

[lfo](https://mosaic.d3cod3.org/reference.php?r=lfo). This object is a low frequency oscillator.

[mixer](https://mosaic.d3cod3.org/reference.php?r=mixer). This object combines up to 6 audio signals.

[note to frequency](https://mosaic.d3cod3.org/reference.php?r=note-to-frequency). This object extracts the fundamental frequency from a midi-note.

[pd patch](https://mosaic.d3cod3.org/reference.php?r=491). This object is a pure data file container with inlets and outlets. The pure data file is programmed in a template that already has communication between both software.

[panner](https://mosaic.d3cod3.org/reference.php?r=panner). This object is a distribution panning control for a sound signal.

[pulse](https://mosaic.d3cod3.org/reference.php?r=pulse). This object is a pulse waveform in which the pitch and pulse width can be dynamically adjusted.

[quad panner](https://mosaic.d3cod3.org/reference.php?r=quad-panner). This object is a 2d pad interface to dynamically distribute the quadraphonic panning of an audio signal.

[resonant 2pole filter](https://mosaic.d3cod3.org/reference.php?r=resonant-2pole-filter). This object is a 12 db filter that regulates pitch, cut-off and resonance for the low-pass, band-pass, high-pass and notch options

[reverb](https://mosaic.d3cod3.org/reference.php?r=reverb). This object generates a reverb effect, in which you can dynamically regulate time, density, damping, and speed

[saw](https://mosaic.d3cod3.org/reference.php?r=saw). This object generates a saw waveform in which you can dynamically regulate the pitch.

[signal trigger](https://mosaic.d3cod3.org/reference.php?r=signal-trigger). This object triggers a bang when the level sound signal exceeds the threshold marked.

[sine](https://mosaic.d3cod3.org/reference.php?r=sine). This object generates a sine waveform in which you can dynamically regulate the pitch.

[soundfile player](https://mosaic.d3cod3.org/reference.php?r=soundfile-player). This is a simple audiofile object, it can load .wav, .mp3, .ogg, and .flac files.

[triangle](https://mosaic.d3cod3.org/reference.php?r=triangle). This object generates a triangle waveform in which you can dynamically regulate the pitch.

[white noise](https://mosaic.d3cod3.org/reference.php?r=white-noise). This object is a white noise generator.


### System

[audio device](https://mosaic.d3cod3.org/reference.php?r=audio-device). It is a Mosaic system object, which means that it cannot be added/deleted, but appears when you configure the sound system from the Sound menu. The audio device object is a virtual direct connection to the audio hardware.


### Video

[kinect grabber](https://mosaic.d3cod3.org/reference.php?r=kinect-grabber). This object receives the signal directly from a Kinect sensor.

[pixels to texture](https://mosaic.d3cod3.org/reference.php?r=pixel-to-texture). This object transforms the signal from a pixels cable (emerald green) into a texture signal (blue cable). In Mosaic, texture data is processed on GPU and pixel data on CPU.

[texture to pixels](https://mosaic.d3cod3.org/reference.php?r=texture-to-pixel). This object transforms the signal from a texture cable (blue) into a pixel signal (emerald green). In Mosaic, texture data is processed on GPU and pixel data on CPU.

[video crop](https://mosaic.d3cod3.org/reference.php?r=video-crop). This object allows you to crop a rectangular fragment of a texture (image, video, graphic...).

[video feedback](https://mosaic.d3cod3.org/reference.php?r=video-feedback). With this object you can make a texture feedback. The action is visualized by scaling and/or moving the texture, showing the trace of its edges in the path.

[video exporter](https://mosaic.d3cod3.org/reference.php?r=video-exporter). This object export video from every texture cable (blue ones). You can select de video code: mpg4, mjpeg, jpg2000, libx264, or hevc.

[video gate](https://mosaic.d3cod3.org/reference.php?r=video-gate). This object receives up to 5 textures and transmits only the one indicated in its inlet: open.

[video grabber](https://mosaic.d3cod3.org/reference.php?r=video-grabber). This object receives the signal directly from a webCam.

[video player](https://mosaic.d3cod3.org/reference.php?r=video-player). Simple object for playing video files. In mac OSX you can upload .mov and .mp4 files; in linux .mp4, .mpeg and .mpg.

[video receiver](https://mosaic.d3cod3.org/reference.php?r=video-receiver). This object receive broadcast video from the video sender object through the [NDI](https://en.wikipedia.org/wiki/Network_Device_Interface) (Network Device Interface)communication protocol.

[video sender](https://mosaic.d3cod3.org/reference.php?r=video-sender). This object sends a video broadcast to the video receiver object through the [NDI](https://en.wikipedia.org/wiki/Network_Device_Interface) (Network Device Interface) communication protocol.

[video streaming](https://mosaic.d3cod3.org/reference.php?r=video-streaming). Object for video streaming linked to the VLC video player

[video timedelay](https://mosaic.d3cod3.org/reference.php?r=video-timedelay). With this object you can delay the playback of a video file or live video.

[video transform](https://mosaic.d3cod3.org/reference.php?r=video-transform). This object allows you to scale and rotate a texture (image, video, graphic...)


### Windowing

[live patching](https://mosaic.d3cod3.org/reference.php?r=live-patching). Displays real-time texture in the background patch, with alpha so you can work with the objects.

[output window](https://mosaic.d3cod3.org/reference.php?r=output-window). This object creates a output window projector. (⌘ o ctrl) + F = activate/deactivate full screen. With warping option active and full-screen  you can adjust the projection surface. For all setting commands see [output window reference](https://mosaic.d3cod3.org/reference.php?r=output-window)

[projection mapping](https://mosaic.d3cod3.org/reference.php?r=projection-mapping). Module for video mapping. It provides an interface with more flexible resources than the warping grid.
