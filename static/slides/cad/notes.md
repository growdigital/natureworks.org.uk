# Introduction to CAD for Gardeners

### Beginners’ guide to computer-aided design

## Reference

* Slides [natureworks.org.uk/slides/cad](https://www.natureworks.org.uk/slides/cad/)
* These notes [natureworks.org.uk/slides/cad/notes.pdf](https://www.natureworks.org.uk/slides/cad/notes.pdf)
* Contact Jake Rayson <hello@natureworks.org.uk>

---

## Outline

1. [Why CAD?](#why)
2. [Setup QCAD](#setup)
3. [Shapes, entities & mods](#shapes)
4. [Satellite photo](#satellite)
5. [Resources](#resources)

---

# [1. Why CAD?](#why)

* This world needs more wildlife forest gardens & more garden designers to design them!
* CAD stands for [Computer Aided Design](https://en.wikipedia.org/wiki/Computer-aided_design)
* CAD is fast, 2D (plan view), line design software
* Do you even need CAD? Paper plan if only 1 design &/or don’t want to learn more software.
* CAD pros:
   * 1:1
   * Fast & accurate (old PCs)
   * Easy to edit
   * Portable
* CAD cons:
   * Technical
   * Ugly
   * Steep learning curve
* Reasons to plan
   1. [Plant spacing](https://www.natureworks.org.uk/spacing/)
   2. Position of plants
   3. Calculate quantity of plants
   4. Communicate with others
   5. Document what is where

---

# [2. Setup QCAD](#setup)

* QCAD is **free** or **cheap**
   * [Free version](https://www.qcad.org/en/qcad-downloads-trial) £0
   * [Paid version](https://www.qcad.org/en/online-shop?cur=GBP) £41
   * [QCAD Book](https://qcad.org/en/qcad-book) £36
   * QCAD is [Open Source](https://en.wikipedia.org/wiki/Open-source_software)
* [Download QCAD Trial](https://qcad.org/en/download)
* [Install QCAD](https://qcad.org/en/documentation/installation), depends on Operating System
* Set units on first start, I use metres 
* Remove all trial plugins **except** these:
   * `libqcaddarkstyle.so`
   * `libqcaddxf.so`
   * `libqcadscripts.so`<br>![Screenshot of file list of 3 lonely plugins](https://res.cloudinary.com/growdigital/image/upload/v1672257002/class/plugins-remaining.png)
* Location of plugins folder:
   * MacOS: `Applications/QCAD.app/Contents/PlugIns` (Right-click on `QCAD.app` and click `Show Package Contents`)
   * Windows: `[QCAD installation folder]\plugins`
   * Linux: `[QCAD installation directory]/plugins` - I have mine in `~/opt/qcad-3…/plugins`

---

# [3. Shapes, entities & mods](#shapes)

* **4** shapes
  
   1. Rectangle
   2. Line tool
   3. Circles for trees
   4. <a href="https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline" title="Non-uniform rational B-spline">NURBS</a> for curves! I use `Spline (Control Points)`

* **3** entities
  
   1. **Block** - a symbol that can be re-used & edited just once
       * Useful for creating shape, **then** applying angle
       * Also, where there are many instances of an element
   2. **Polyline** - a *connected* line, can calculate area. Use command `Draw > Polyline > Polyline from Selection`, shortcut `OC`
       * Useful for grouping lines together
       * Also gives you **area** (can also use measurement tools)
   3. **Text**

* **4** modifications
  
   1. Offset
   2. Mirror
   3. Divide
   4. Rotate

* Download files from [https://github.com/growdigital/cad-gardeners](github.com/growdigital/cad-gardeners)

* See [Survey Class](https://natureworks.org.uk/classes/) on how to measure up & survey your site.

## 3.1 Finding your way

* Zoom in/out
   * Mouse scroll
   * `+` & `-` keys
   * `View > Zoom > Auto Zoom`
* Panning 
   * Mouse scroll **click**
   * `View > Zoom > Pan Zoom`
* Hit `Escape` to return to arrow tool
* `View > Zoom > Auto Zoom` 

## 3.2 Snap

1. Snap Auto `SA` - automatically snaps to grid or another point
2. Snap Free `SF` - no snapping
3. Snap on Entity `ST` - snaps on to a line or shape
4. Snap to End `SE` - snaps to the end of a line

## 3.3 Layers

* Organise different elements
* Shape takes layer colour
* My [template](https://github.com/growdigital/template)

## 3.4 Pre-made blocks

* [Forest garden plants](https://github.com/growdigital/blocks-forestgarden)
* [Native wild plants](https://github.com/growdigital/blocks-gardenwild)
* [Garden furniture](https://github.com/growdigital/blocks-furniture)

---

# [4. Satellite photo](#satellite)

Including a scaled satellite photo in your CAD drawing

1. Take screenshot, including scale
2. Save image to same folder as CAD file
3. Calculate metres per pixel (image scale factor) in [image editing software](https://alternativeto.net/software/adobe-photoshop/)
4. Import image into CAD file
5. Resize image using the image scale factor

## 4.1 Calculate image scale factor

![Closeup of scale in metres on satellite screenshot](https://res.cloudinary.com/growdigital/image/upload/w_560/v1573759452/course-satellite-scale.jpg)

1. Measure pixel length of metres scale
2. **_Metres per pixel_**&nbsp;&nbsp;`5m ÷ 106px = 0.047169811`
3. Image scale factor = metres per pixel

## 4.2 Resize image in CAD

![Screenshot of CAD program, showing scaled image](https://res.cloudinary.com/growdigital/image/upload/w_580/v1573817366/scale-image-07-complete.png)

1. `File → Import` , `Select → Select All`
2. `View → Property Editor`
3. `Width & Height Factor:` _image scale factor_

---

# [5. Class resources](#resources)

1. [Download free version](https://www.qcad.org/en/qcad-downloads-trial) of QCAD
2. [CAD files](https://github.com/growdigital/cad-gardeners) for class
3. [Garden Wild Edible](https://t.me/WildEdible) public [Telegram](https://telegram.org) group
4. [QCAD forums](https://www.qcad.org/rsforum/index.php?sid=50158f66608a5367aaf3cfb039fd6fc7)
5. [CAD Template file](https://github.com/growdigital/template)
6. [Plant spreadsheet template](https://bit.ly/template-plants)
7. [Native plant spreadsheet](https://bit.ly/garden-wild-spreadsheet)
8. [Forest garden spreadsheet](https://bit.ly/forest-garden-spreadsheet)
9. CAD blocks
    * [Forest garden plants](https://github.com/growdigital/blocks-forestgarden)
    * [Native wild plants](https://github.com/growdigital/blocks-gardenwild)
    * [Garden furniture](https://github.com/growdigital/blocks-furniture)
