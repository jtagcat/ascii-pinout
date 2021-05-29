# ascii-pinout
ASCII pinouts

## Standards 
 - If an item is not visible from the side, it's pinout should not be shown, unless not practical otherwise.
 - If available, details of components shall be included. Simple components 
 - Large blank spaces (unused space, screens) may be used to document the device's features.
 - Where practical, the device's size/ratio should be true on a monospace font. Same goes for location of components.
 - `ASCII by foobar` should be included on the ASCII. Preferrably on the device, if not, on the top or bottom left corner.
 
 The drawings (must) include (all):
 - Connectors, ports. Things other things are plugged in to.
 - HID devices such as buttons, (single) lights (LED), light matrixes (screen).
 - GPIO and similar.
 
 Filename — `device_name_sidename_full.ascii.txt`
  - Device name should be stylized. Product series/brand should be included.
  - Side name. Rotation is relative to the front side, where the upper top is the top side on all sides (bottom/right/left is reachable with one turn, back with a turn from right to left or LtR, top with turn followed by a 180° turn).
  - Full versions include all capacitors, resistors, etc.

*** 
 
A great tool to make simple ASCII drawings is [asciiflow](https://asciiflow.com)
