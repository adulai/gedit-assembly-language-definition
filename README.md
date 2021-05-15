# Intel Assembly Language Definition for `gedit`

The file `asm-intel.lang` can be used to provide syntax highlighting for Intel assembly in `gedit`.

Note that the file uses version 2 of the language definition file format, which works with GtkSourceView 2, 3 and 4. See [here](https://developer.gnome.org/gtksourceview/stable/lang-tutorial.html) for details. The file is based on [this](https://wiki.gnome.org/Projects/GtkSourceView/LanguageDefinitions?action=AttachFile&do=view&target=asm-intel.lang) version 1 implementation.

To use `asm-intel.lang`, copy it to your GtkSourceView folder. For example, for GtkSourceView 4, you would use this command:
```
sudo cp asm-intel.lang /usr/share/gtksourceview-4/language-specs/
```