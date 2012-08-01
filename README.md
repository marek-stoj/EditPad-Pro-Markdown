EditPad-Pro-Markdown
====================

Custom [Markdown][md-homepage] syntax coloring scheme for [EditPad Pro][editpad-homepage].

Installation:
-------------

  1. Copy `Markdown.jgcscs` to EditPad Pro installation folder, eg.: `C:\Program Files (x86)\Just Great Software\EditPadPro7`.
  
  2. Open `EditPadPro7.ini` located in you 'Roaming' folder, eg.: `C:\Users\YourUsername\AppData\Roaming\JGsoft\EditPad Pro 7`.
  
  3. Inside this `ini` file create (or edit if it exists) a custom color palettes section, eg.:
```ini
[SyntaxColors]
Count=2
Name0=Paper Light
Name1=Paper Dark
Name2=Fresh Air
Name3=Night
```

  4. Also inside this `ini` file add color palette sections (copied from provided `Colors_*.ini` files). Remember to number them appropriately, eg.:
```ini
[SyntaxColors0]
FG1=-16777202
BG1=8421504
; ...
[SyntaxColorsRegex0]
FG1=-16777202
BG1=8421504
; ...
[SyntaxColors1]
FG0=16777215
BG0=0
; ...
[SyntaxColorsRegex1]
FG0=16777215
BG0=0
; ...
```
  4. Restart EditPad Pro if you had it opened.

Kudos:
------

  - [EditPad Pro][editpad-homepage] -- for being the most awesomest text editor on the planet.
  - [Markdown project][md-homepage] -- for not having to type those angle brackets anymore.
  - [Mou][mou-homepage] -- for creating great color palettes.
  - [Large Markdown example][md-example] -- for being useful during testing.
  
  [editpad-homepage]: http://www.editpadpro.com/
  [md-homepage]: http://daringfireball.net/projects/markdown/
  [mou-homepage]: http://mouapp.com/
  [md-example]: http://www.unexpected-vortices.com/sw/gouda/quick-markdown-example.html
