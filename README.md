# York Modular 4-channel Eurorack mixer

**This module is now discontinued - there will be no more made unless there is sufficient demand to justify a new run of boards and panels.**

[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg

What you'll find here:

- `gerbers` - the Gerber files are in here; if you want to fabricate your own run of boards, these are what the fab will need.
- `4ch-euromixer-BOM.xlsx` - bill of materials
- `4ch-euromixer.png` - circuit schematic for reference
- `4ch-euromixer.{dxf,fpd}` - panel files in AutoCAD format (`.dxf`) and Front Panel Designer format (`.fpd`). These are _blank_ panels.
- `4ch-euromixer-lettered.{dxf,fpd}` - as above, but appropriately lettered.
- `4ch-euromixer.stl` - OpenSCAD `.stl` file for 3D printing. Depending on the accuracy of your 3D printer, you may need to take a deburring tool to the jack and pot holes in order to get things to fit.

If you're planning to have panels laser-cut then the DXF files are probably what you want - if your fabricator requires Adobe Illustrator or a similar format 
then importing the DXF files into a package such as Inkscape and then re-exporting them as SVG should do the trick.

If you're planning to 3D-print a panel, just pull the STL file into your package of choice (I use Cura, others are available) and tweak the settings to suit.
My own experience is that printing with PLA at 200C with a heated bed (60-70C) gives good results - whether you use a raft is a matter of personal choice; for
large panels I tend to use a 10mm raft, even on a heated bed. You don't need insanely high resolution either - 0.2mm/layer is plenty good enough and print time
is around 3hrs on my AnyCubic i3.
