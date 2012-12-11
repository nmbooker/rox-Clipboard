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

## How to use it

1. Copy the text you want to save into the clipboard.
2. Open Clipboard application from ROX filer.
3. Type a name for the new file, and drag it into place.  You can also drag and drop the text into an application that accepts text/plain drops, such as edit or gedit.

## Caveats
### Primary selection gets replaced on load
If you're using the primary selection, be sure to load Clipboard FIRST, enter the target filename and THEN select the text you want to save before dragging the icon to its destination.
