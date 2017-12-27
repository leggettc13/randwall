# Randwall

A simple python script that generates a 1920x1080 image of a 
random solid color and sets it as the desktop background with
```feh --bg-scale```. It saves the background to your home
directory by default.

## Requirements
- feh
- python 3.5

## How do I use it?

1. Save it anywhere on your computer
2. Make it executable with 
```
chmod +x randwall
```
If you changed the filename, replace randwall with whatever you named it.
3. Execute it.

Personally, I have it set to a keybinding in my i3 config, but you could also
set it to run every few minutes, or on every startup.

## The Future

Eventually, I want to expand this into a more fully fledged program that also
themes terminal windows.
