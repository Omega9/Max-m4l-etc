# MAX-M4L-etc
My patches for Max/m4l/etc

Some thing that I've made for my microtonal (but not only) needs.

---
## MJammer
_Not Max4Live, just Max patch for now._

**MJammer** is made for use with midi-mapper called [NoteMapper][14a0d579].
NoteMapper allows to remap your midi-keyboard to play a diatonic or any other scale instead of plain chromatic scale.
You can use up to 16 mappings according to 16 midi-channels.

**NOTE** is device that you actually playing.
"Input note" indicates the key you've pressed and "Output note" indicates the note coming outside of MJammer

**CHANNEL** is to change a channel inside NoteMapper or, obviously, to change a scale. For example, from Major (Ch.1) to Minor (Ch.2).
"Input note" is the central note and allows you to choose the more suitable.

**TRANSPOSITION** speaks for itself. You press a key and the tonic is changing.

Little buttons beside drop-down menus is a panic buttons.

![MJammer](/MJammer/MJammer_screenshot.png)
  [14a0d579]: http://www.codefn42.com/notemapper.html "NoteMapper"

---
## [NoteMapper](http://codefn42.com/notemapper.html) scales

**Scales.txt** locates in **C:/Users/_Username_/My Documents/CodeFN42/NoteMapper/** and contain scales in such format:
```
Chromatic;0,1,2,3,4,5,6,7,8,9,10,11
Major;0,2,4,5,7,9,11
Minor - Natural;0,2,3,5,7,8,10
Minor - Melodic;0,2,3,5,7,9,11
Minor - Harmonic;0,2,3,5,7,8,11
Pentatonic - Major;0,2,4,7,9
Pentatonic - Minor;0,3,5,7,10
Blues;0,3,5,6,7,10
```
Since version 1.02 you can set a note where pattern begins to repeat. Many thanks to [CodeFN42](http://codefn42.com/) for that feature.
```
Chromatic;0,1,2,3,4,5,6,7,8,9,10,11;12
```
So now you can do things like this:
```
22-edo "Just" Major;0,4,7,9,13,16,20;22
22-edo "Just" Minor;0,4,6,9,13,15,18;22
```

In this repository there's a collection of scales for [22-edo](http://xenharmonic.wikispaces.com/22edo), [19-edo](http://xenharmonic.wikispaces.com/19edo) or [Carlos Beta](http://xenharmonic.wikispaces.com/Carlos+Beta).
