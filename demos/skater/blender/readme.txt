To edit the level data of the Allegro demo game, we use the free and open source
tool Blender. You can obtain it here:

http://blender.org

Instructions:

1) Place the file ademo_export.py into your Blender scripts folder. It is the
export script which will convert from .blend format to the .txt format used by
the demo game. Under unix, the path will be:

~/.blender/scripts/ademo_export.py

2) Load the .blend file in blender. Under unix, type this from the directory with
the level.blend file:

blender level.blend

3) Edit the level. In the menu, under

Help -> Scripts Help Browser -> Export -> Allegro Demo Game Level

you will find some useful tips.

4) Save the file (use compression before committing). Export it as .txt from the
export menu, choosing Allegro Demo Game Level.

5) The new level.txt should appear in the game.
