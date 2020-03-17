# FAQ

## How to save a Mosaic patch?

Mosaic Patches are saved as .xml files. To save it, select **Save Patch As** from the File menu, a computer dialog box will open, name it and click save.

When you save it, Mosaic generates a folder with the same name as the Patch, inside it you will see the .xml file and another folder called **data** in which all the scripting, video, audio or image files you use in the Patch will be automatically incorporated. To avoid files duplication, we recommend that you put the files you are going to use in the data folder so that Mosaic doesn't duplicate them.

When Mosaic is first opened, a folder called Mosaic is generated on your computer:

- MacOS: `Documents/Mosaic/`
- Windows: `My Documents/Mosaic/`
- Linux: `~/.Mosaic/`

We recommend to save all the patches in a folder inside that Mosaic folder without touching the other data and examples folders it contains.

Patches are only saved once, and while you are working the file will be saved automatically so when you finish your work you don't have to save it again. If you want to leave a Patch as is, but follow the process to another level, then you do have to save it again with Save Patch As, by typing another name and continue working on this last one. When you have finished, there is no need to save, both files are saved.


## How to open a Mosaic patch?

You can open a previously saved Mosaic patch from the File/Open patch menu, or you can drag the .xml file into the canvas and it will open in Mosaic.

You cannot open it by clicking on the file icon, because .xml (Extensible Markup Language) is a standard for structured information exchange between platforms, and if you click on it directly, it will be opened by the code editor assigned by default on your computer.

## How to add an object?

You can add an object by selecting it from the objects menu, where the objects are organized by categories.

This menu also appears when you right-click on any empty place in the canvas. In this floating menu you have the option Search with a text field, if you know the object's name you can start typing it and with the tab Mosaic completes its name, and if it's the object you were looking for press Enter, and the object will be placed near that position.

In the objects that contain files (image loader, video player, soundfile player, bash script, lua script, processing script or shader object) you can drag the file directly on the canvas, the object will appear with the file already loaded. In the configuration menu of these objects you will see the option Open, if you have incorporated the empty object, from Open you can load the file.

## How to activate sound?

When Mosaic is opened, DSP is not activated. If you are not going to use audio in your patch, no problem, although the logger says in red: : [error] The selected audio devices couldn't be properly installed in your system!

To activate the DSP, from the Sound menu, select in **Input device** the sound input device of your computer that you want to use, and in **Output device**, the output device. Then click on **DSP ON**. Then the Audio device object appears in the canvas with the same number of inlets and outlets as the selected devices.

Audio device is a Mosaic system object, which means that it cannot be added/deleted like the other objects, and it establishes a direct connection with the selected computer audio device.

## How to activate Warping in Output window object?

In the Output window object, warping only works with the projector window in full screen, and the Warping button activated. If you type W, a rectangle appears whose vertices can be moved with the mouse, to adjust the projection limits. The keys for enlarging the grid inside the image are


    - F2 add vertical sections.
    - F1 delete vertical sections
    - F4 add horizontal sections
    - F3 delete horizontal sections
    - M activates/deactivates curved/linear grid

You can adjust the position of all grid intersections with the mouse. By default the deformations are adapted to curved shapes, if you type M you change to linear grid, if you type M again it returns to curves.

The **Load warping** option allows you to load a previously saved warping, and **Save warping** to save it in a json-type file.

## How to do live-coding in Mosaic?

In Mosaic you can visualize the code of Lua script object in the projector window (strict classic live-coding), for this you have to connect the two outlets, red and blue, from Lua script object to Output window object. The commands list  to activate live coding, and other basic functions is

```
- (⌘ or ctrl) + F = Fullscreen on/off
- (⌘ or ctrl) + T = Show/hide live code editor
- (⌘ or ctrl) + K = ZOOM IN/ZOOM OUT (at cursor height)
- (⌘ or ctrl) + L = Toggle Line Wrapping
- (⌘ or ctrl) + N = Show/hide line numbers
- (⌘ or ctrl) + E = Runs the script
- (⌘ or ctrl) + C = Copy
- (⌘ or ctrl) + V = Paste
- (⌘ or ctrl) + X = Cut
- (⌘ or ctrl) + Z = Undo
```

To write code use the arrow keys to move the cursor.
