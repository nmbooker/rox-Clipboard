# Clipboard ROX Application

A very simple application to save your X clipboard contents directly into
a file.

It can also save your 'Primary' X selection (what you would get if you middle click), but please see 'Caveats' listed below.

## How to install
Check out this repository and open it by (double-) clicking it in ROX Filer.

```
cd ~/Apps
git clone git://github.com/nmbooker/rox-Clipboard.git Clipboard
```

### Dependencies

* The `xclip` program somewhere in your `PATH`
* Python 2.4 or higher (tested only on Python 2.7)
* ROX-Lib2 (and its dependencies such as pygtk).
* The ROX file manager to launch it from.

## How to use it

1. Copy the text you want to save into the clipboard.
2. Open Clipboard application from ROX filer.
3. Type a name for the new file, and drag it into your file manager.

### If you don't have rox-filer
Instead of launching the application directory from rox filer, you can launch
the program by running the AppRun script within from the command line,
or you can add that program to your desktop's menu system.

## Caveats
### Primary selection gets replaced on load
If you're using the primary selection, be sure to load Clipboard FIRST, enter the target filename and THEN select the text you want to save before dragging the icon to its destination.
