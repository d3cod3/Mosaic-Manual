# Installing & Running

According to the operating system, you can download the application, the installation script or the files to be compiled from  [Mosaic](https://mosaic.d3cod3.org/#download)

### Installing on Mac

Download and unzip the folder Mosaic_vn.n.n_osx_release.zip (vn.n.n is the release number), and move the app to the applications folder. When you open Mosaic for the first time, a folder named Mosaic is generated in Documents, inside it there are two folders, one named **data**, I recommend you to NOT ALTER the content of that folder, and another named **examples** which contains the examples that come with Mosaic.

### Installing on Windows

Mosaic support for windows will continue at a source code level only. The code will be tested to compile correctly on windows machines, but no installers will be available for download.

If you want to use Mosaic on Windows, Compiling with [qtcreator 4.6.1](https://download.qt.io/official_releases/qtcreator/4.6/4.6.1/) with no issues, and download the following files.

##### openFrameworks

Download OF 0.11.0 STABLE (official download from [OF site](https://openframeworks.cc/download/))

After you have openFrameworks running, you need to clone the ofxAddons from git.

##### ofxAddons

Clone all the required addons listed:

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

Next, you should clone from git the [Mosaic repository](https://github.com/d3cod3/Mosaic.git) and follow the setup guide for the [qtcreator IDE](https://www.qt.io/).

### Install on Linux

 Use the automatic install script for your distro:

- Ubuntu: [install_mosaic_ubuntu.sh](https://gist.github.com/d3cod3/81b8971ebf5fc9a6d288ca93fc3c3dad)
- Ubuntu Studio: [install_mosaic_ubuntustudio.sh](https://gist.github.com/d3cod3/869d6d36b2e4c6a5aa01c17cf6395e6b)
- Linux Mint: [install_mosaic_linuxmint.sh](https://gist.github.com/d3cod3/d1a544e0cf21b8733b567a3d87905d23)
- Debian: [install_mosaic_debian.sh](https://gist.github.com/d3cod3/fbb76735554c3b38e811414d96fc28d6)
- Fedora: [install_mosaic_fedora.sh](https://gist.github.com/d3cod3/2a6e9f1f21045d763571cc4172cf2d6c#file-install_mosaic_fedora-sh)

Here you can download (and check) a script for automatically download/clone/compile and build everything for your linux distro, and magically have Mosaic appearing on your desktop  menu.
