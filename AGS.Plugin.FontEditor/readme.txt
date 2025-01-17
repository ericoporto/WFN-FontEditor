﻿Manual
======


1. Explanation
---------------
This is an editor for wfn fonts, as well as for sci fonts.
The functions depends on the usage as a plugin for AGS (AdventureGameStudio)
or as a stand alone version.


2. Terms and Definitions
------------------------
p = Plugin
s = Stand Alone


3. Features
-----------
- Edit wfn fonts                                                           (p/s)
- Edit sci fonts                                                           (  s)
- The fonts can be outlined [Button 'Outline']                             (p/s)
- Convert between sci and wfn fonts [Button 'Convert selected']            (  s)
  the field text height is only for sci fonts interesting.
  It set the space between two text lines and not
  the textheight itself
- Shift the characters to up, down, left, right                            (p/s)
  [Buttons 'U', 'L', 'D', 'R']
- Invert a character [Button 'Invert']                                     (p/s)
- Clear a character (with black) [Button 'Clear']                          (p/s)
- Fill a character (with white) [Button 'Fill']                            (p/s)
- Swap a character horizontally or vertically                              (p/s)
  [Buttons 'Swap H', 'Swap V']
- Outline the complete font [Button 'Outline Font']                        (p/s)
- Show a grid for better font designing                                    (p/s)
- Multiple Redo/Undo [Right click on the character selection field]        (p/s)
- Copy to and Paste from the clipboard                                     (p/s)
  [Right click on the character selection field]
- Zoomable edit field (2–40)                                               (p/s)
- Swap the left color and the right color (click on the connected arrows)  (p/s)

Since 1.2.0.1:
- save the selection field background color                                (p/s)
- save the state of the grid option                                        (p/s)
- save the render text                                                     (p/s)
- render the font in an example text                                       (p/s)
- change the color of the selection field with right click on it           (p/s)
- extend the font to 256 character                                         (p/s)
- show, if a font is 128 or 256 characters                                 (p/s)

4. Start
--------
Start the program, or copy the plugin to your AGS path and start AGS.

4.1 Stand alone
---------------
After you have started the program stand alone, you have to click open and
select a path. In the list on the left side, it shows you all the fonts, you can
edit (wfn and sci [version 1.2.0.0 and higher]).

4.2 Plugin
----------
Start AGS and load a game. On the pane you found an entry named 'FontEditor'. 
Open it and it will show all editable fonts. Under 'Fonts' you found all fonts, 
used by your game. It is possible, that you find more than just the ones under 
'FontEditor', because AGS is able to handle .ttf fonts as well, but not this 
editor. Double click on an entry under 'FontEditor' to edit the selected 
.wfn font, or right click under 'Fonts' and select 
'Edit font (with WFN-FontEditor)'.

5. Workflow (usage)
-------------------
After you have selected a font, you have to click on an character on the left 
side (selection field) to show it zoomed. You can select the check box 
'Show grid' for a better editing feel. Now you can click in the (zoomed) field 
to edit the selected character. It updates the character in the left selection 
field. By dragging your mouse, while holding the mouse button down, you can 
edit more pixels in a row.

6. Tips
-------
If you want to make a font as well as an outline font too, it would be better 
if you have a border around your characters. That means, one pixel on every side 
of the character is black. After you've designed your font (or converted it from 
ttf by using the TtfToWfnSci converter), save it and make a copy (with a 
file manager). Name the copy correct (file convention) with a number higher and 
reopen the Editor. Than select the correct font and click 'Outline Font'.
Check the characters and you will be done.
