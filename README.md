# openslide-python
how to use openslide python on win10???

(1) install openslide-python according to https://github.com/openslide/openslide-python

(2) For win10 system, you need to download Windows Binaries from: https://openslide.org/download/

(3) You must add the 'bin' file (with dlls) to your system environmental path. the steps are as below:

PC-> Properties->Advanced system settings->Environment variables->Path->Edit->New (put your bin file path here)

Note that: In order to make your changes be working, you need to close and restart your app, or your can restart your computer


######------PIL image operation in python----------######

tile.show() # to display the tile, where tile is a PIL image object

scipy.misc.toimage(tile).show() # to display the tile using scipy package, where tile is a numpy array object
