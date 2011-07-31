This project adds [CoffeeScript] syntax highlighting to the gedit text editor. (and any other gtksourceview-2.0 compliant text editor)

[CoffeeScript]: http://coffeescript.org

### Installation and Use

1. Download and place coffee_script.lang in `~/.local/share/gtksourceview-2.0/language-specs`
    > Note: if those directories don't exist, make them and gedit will know what to do.

2. Run gedit or make sure to restart to see changes. 

3. Go to View -> Highlight mode -> Scripts -> JavaScript. Open a CoffeeScript file or Cakefile.

Patches and improvements welcome!

![screenshot](http://wavded.github.com/gedit-coffeescript/screenshot.png)

### Extra: Install the Ruycius-Mod theme

1. Download and place rubycius-mod.xml in `~/.local/share/gtksourceview-2.0/styles`
    > Note: if those directories don't exist, make them and gedit will know what to do.

2. Run gedit then Edit > Preferences > Fonts and Colors > Color Scheme > Rubycius-Mod

3. I like using Liberation Mono for a base font as well which is available within the standard repo for many Linux distros.

