EditPad-Pro-Markdown
====================

Custom [Markdown][md-homepage] syntax coloring scheme for [EditPad Pro][editpad-homepage].

Screenshots:
------------

<table>
  <tr>
    <td>
      <a href="https://lh3.googleusercontent.com/-DPNPuxj_E_k/UBlyPZ20HcI/AAAAAAAACDI/0nf9FfPf288/s1024/ss-fresh-air.png">
        <img src="https://lh3.googleusercontent.com/-DPNPuxj_E_k/UBlyPZ20HcI/AAAAAAAACDI/0nf9FfPf288/s288/ss-fresh-air.png" alt="Fresh Air" />
      </a>
    </td>
    <td>
      <a href="https://lh5.googleusercontent.com/-eZYMpLgpqFY/UBlyPd7emPI/AAAAAAAACDM/ECr6D3fbyoE/s1024/ss-night.png">
        <img src="https://lh5.googleusercontent.com/-eZYMpLgpqFY/UBlyPd7emPI/AAAAAAAACDM/ECr6D3fbyoE/s288/ss-night.png" alt="Night" />
      </a>
    </td>
  </tr>
  <tr>
    <td>
      <a href="https://lh5.googleusercontent.com/-8iay3b2c0mQ/UBlyP9akdhI/AAAAAAAACDU/bipUTcB4ouA/s1024/ss-paper-light.png">
        <img src="https://lh5.googleusercontent.com/-8iay3b2c0mQ/UBlyP9akdhI/AAAAAAAACDU/bipUTcB4ouA/s288/ss-paper-light.png" alt="Paper Light" />
      </a>
    </td>
    <td>
      <a href="https://lh4.googleusercontent.com/-HWklrPd4qfA/UBlyPQF9i6I/AAAAAAAACDQ/aGmw-xtvmVs/s1024/ss-paper-dark.png">
        <img src="https://lh4.googleusercontent.com/-HWklrPd4qfA/UBlyPQF9i6I/AAAAAAAACDQ/aGmw-xtvmVs/s288/ss-paper-dark.png" alt=Paper Dark"" />
      </a>
    </td>
  </tr>
</table>

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

 4. Also inside this `ini` file add color palette sections (copied from provided `ColorPalettes\*.ini` files). Remember to number them appropriately, eg.:

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
 
 5. Restart EditPad Pro if you had it opened.
 
 6. In EditPad Pro go to _Options &rarr; Configure File Types_ and add a new file type titled _Markdown Document_ for these extensions: `*.markdown`, `*.mdown`, `*.mkdn`, `*.md`, `*.mkd`, `*.mdwn`, `*.mdtxt`, `*.mdtext`, `*.text`.
 
 7. Switch to the _Colors and syntax_ tab and select the _Markdown_ scheme along with a color palette of your choice.
 
 8. You might also want to disable the following options:

   * _highlight matching brackets touched by the cursor_,
   * _highlight innermost pair of brackets containing the cursor_.
 
 9. And that's it.

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
