# Introduction to CAD for Gardeners

### Beginners’ guide to computer-aided design

## Reference

* Slides [natureworks.org.uk/slides/cad](https://www.natureworks.org.uk/slides/cad/)
* These notes [natureworks.org.uk/slides/cad/notes.pdf](https://www.natureworks.org.uk/slides/cad/notes.pdf)
* Contact Jake Rayson <hello@natureworks.org.uk>

---

## Outline

1. Why CAD?
2. Setup QCAD
3. Shapes, entities & mods
4. Examples
5. Exercises
6. Tips

## 1. Why CAD?

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

## 2. Setup QCAD
   
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

## 3. Shapes, entities & mods

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

### Finding your way

* Zoom in/out
  * Mouse scroll
  * `+` & `-` keys
  * `View > Zoom > Auto Zoom`
* Panning 
  * Mouse scroll **click**
  * `View > Zoom > Pan Zoom`
* Hit `Escape` to return to arrow tool
* `View > Zoom > Auto Zoom` 

### Snap

1. Snap Auto `SA` - automatically snaps to grid or another point
2. Snap Free `SF` - no snapping
3. Snap on Entity `ST` - snaps on to a line or shape
4. Snap to End `SE` - snaps to the end of a line

### Layers

* Organise different elements
* Shape takes layer colour
* My [template](https://github.com/growdigital/template)

### Pre-made blocks

* [Forest garden plants](https://github.com/growdigital/blocks-forestgarden)
* [Native wild plants](https://github.com/growdigital/blocks-gardenwild)
* [Garden furniture](https://github.com/growdigital/blocks-furniture)

---

class: middle, center

# 4. Examples

<h6 class="breadcrumb">CAD — Setup — Shapes — <span class="u-underline">Examples</span> — Exercises — Tips</h6>

---

# Example walkthroughs🚶

![CAD paths](https://res.cloudinary.com/growdigital/image/upload/w_480,h_270/v1673022407/hedgerows/hedgerows-paths.png)

1. Average garden 
2. Satellite 🛰
3. Garden acre
4. Garden town

<h6 class="breadcrumb">CAD — Setup — Shapes — <span class="u-underline">Examples</span> — Exercises — Tips</h6>

---

# 1. Average garden

[![CAD drawing of 1 acre next to average sized garden](https://res.cloudinary.com/growdigital/image/upload/w_480,h_270/v1672751964/class/average-acre-cad.jpg)](https://res.cloudinary.com/growdigital/image/upload/v1672751964/class/average-acre-cad.jpg)

* UK 188m²
* London 140m²
* cf. 1 acre 4000m²

<h6 class="breadcrumb">CAD — Setup — Shapes — <span class="u-underline">Examples</span> — Exercises — Tips</h6>

???

* ONS article [One in eight British households has no garden](https://www.ons.gov.uk/economy/environmentalaccounts/articles/oneineightbritishhouseholdshasnogarden/2020-05-14)

---

# 2. Satellite 🛰

![Screenshot 3D satellite window](https://res.cloudinary.com/growdigital/image/upload/w_480,h_270/v1591459919/greenroom-satellite-3d-google-south-west-169.jpg)

1. Screenshot
2. Metres per pixel
3. Scale in QCAD

<h6 class="breadcrumb">CAD — Setup — Shapes — <span class="u-underline">Examples</span> — Exercises — Tips</h6>

???

Screengrab **for personal use only**

1. Screenshot: maximum resolution **with scale**, save as JPEG
2. Calculate metres per pixel
3. Same as your image scale factor
4. Import: create new CAD file, save image in same folder, import image
5. Resize: image automatically scaled at 1 pixel per metre. Select image, open `Property Editor`, enter image scale factor

Instructions online: [Forest garden CAD photo](https://www.forestgarden.wales/blog/forest-garden-cad-photo/)

OS maps onscreen from [groundstability.com](https://groundstability.com/public/web/log-order)

<h6 class="breadcrumb">CAD — Setup — Shapes — <span class="u-underline">Examples</span> — Exercises — Tips</h6>

---

# Satellite: <span class="u-smaller">1. Screenshot</span>

![Screenshot 2D satellite window, including browser chrome](https://res.cloudinary.com/growdigital/image/upload/w_480,h_270/v1573757850/course-screenshot-satellite-photo.jpg)

* Highest resolution possible
* Be sure to include scale, in metres
* Save as good quality JPEG

<h6 class="breadcrumb">CAD — Setup — Shapes — <span class="u-underline">Examples</span> — Exercises — Tips</h6>

???

* Resolution varies between vendors
* Vendors
  * [Google Maps](https://www.google.com/maps)
  * [Bing Maps](https://www.bing.com/maps)
  * If you have a mac, [Apple Maps](https://en.wikipedia.org/wiki/Apple_Maps)

---

# Satellite: <span class="u-smaller">2. Metres per pixel</span>

1. Measure pixel length of metres scale
2. **_Metres per pixel_**&nbsp;&nbsp;`5m ÷ 106px = 0.047169811`
3. Image scale factor = metres per pixel

![Closeup of scale in metres on satellite screenshot](https://res.cloudinary.com/growdigital/image/upload/w_560/v1573759452/course-satellite-scale.jpg)

<h6 class="breadcrumb">CAD — Setup — Shapes — <span class="u-underline">Examples</span> — Exercises — Tips</h6>

???

* Use Photoshop, Open Source [GIMP](https://www.gimp.org) or [alternative](https://alternativeto.net/software/gimp/)
* [QCAD](https://qcad.org/en/) imports at 1 metre per pixel

---

# Satellite: <span class="u-smaller">3. Scale in QCAD</span>

1. `File → Import` , `Select → Select All` 👈
2. `View → Property Editor`
3. `Width & Height Factor:` _image scale factor_

<span class="our-scale-factor">Our <em>image<br>scale factor</em> is<br>metres per pixel<br><strong>0.047169811</strong></span>

![Screenshot of CAD program, showing Import image](https://res.cloudinary.com/growdigital/image/upload/w_580/v1573817365/scale-image-01-import.png)

<h6 class="breadcrumb">CAD — Setup — Shapes — <span class="u-underline">Examples</span> — Exercises — Tips</h6>

???

* QCAD document same folder as image
* File → Import

---

# Satellite: <span class="u-smaller">3. Scale in QCAD</span>

1. `File → Import` , `Select → Select All` 👈
2. `View → Property Editor`
3. `Width & Height Factor:` _image scale factor_

<span class="our-scale-factor">Our <em>image<br>scale factor</em> is<br>metres per pixel<br><strong>0.047169811</strong></span>

![Screenshot of CAD program, showing Select All](https://res.cloudinary.com/growdigital/image/upload/w_580/v1573817366/scale-image-02-selectall.png)

<h6 class="breadcrumb">CAD — Setup — Shapes — <span class="u-underline">Examples</span> — Exercises — Tips</h6>

???

* Select → Select All

---

# Satellite: <span class="u-smaller">3. Scale in QCAD</span>

1. `File → Import` , `Select → Select All`
2. `View → Property Editor` 👈
3. `Width & Height Factor:` _image scale factor_

<span class="our-scale-factor">Our <em>image<br>scale factor</em> is<br>metres per pixel<br><strong>0.047169811</strong></span>

![Screenshot of CAD program, showing Property Editor](https://res.cloudinary.com/growdigital/image/upload/w_580/v1573817366/scale-image-03-propertyeditor.png)

<h6 class="breadcrumb">CAD — Setup — Shapes — <span class="u-underline">Examples</span> — Exercises — Tips</h6>

???

* View → Property Editor

---

# Satellite: <span class="u-smaller">3. Scale in QCAD</span>

1. `File → Import` , `Select → Select All`
2. `View → Property Editor` 👈
3. `Width & Height Factor:` _image scale factor_

<span class="our-scale-factor">Our <em>image<br>scale factor</em> is<br>metres per pixel<br><strong>0.047169811</strong></span>

![Screenshot of CAD program, showing Property Editor](https://res.cloudinary.com/growdigital/image/upload/w_580/v1573817366/scale-image-04-propertyeditor.png)

<h6 class="breadcrumb">CAD — Setup — Shapes — <span class="u-underline">Examples</span> — Exercises — Tips</h6>

???

* View → Property Editor

---

# Satellite: <span class="u-smaller">3. Scale in QCAD</span>

1. `File → Import` , `Select → Select All`
2. `View → Property Editor`
3. `Width & Height Factor:` _image scale factor_ 👈

<span class="our-scale-factor">Our <em>image<br>scale factor</em> is<br>metres per pixel<br><strong>0.047169811</strong></span>

![Screenshot of CAD program, showing Property Editor Width Factor](https://res.cloudinary.com/growdigital/image/upload/w_580/v1573817366/scale-image-05-widthfactor.png)

<h6 class="breadcrumb">CAD — Setup — Shapes — <span class="u-underline">Examples</span> — Exercises — Tips</h6>

???

* Width & Height Factor

---

# Satellite: <span class="u-smaller">3. Scale in QCAD</span>

1. `File → Import` , `Select → Select All`
2. `View → Property Editor`
3. `Width & Height Factor:` _image scale factor_ 👈

<span class="our-scale-factor">Our <em>image<br>scale factor</em> is<br>metres per pixel<br><strong>0.047169811</strong></span>

![Screenshot of CAD program, showing Property Editor Height Factor](https://res.cloudinary.com/growdigital/image/upload/w_580/v1573817366/scale-image-06-heightfactor.png)

<h6 class="breadcrumb">CAD — Setup — Shapes — <span class="u-underline">Examples</span> — Exercises — Tips</h6>

???

* Width & Height Factor

---

# Satellite: <span class="u-smaller">3. Scale in QCAD</span>

1. `File → Import` , `Select → Select All`
2. `View → Property Editor`
3. `Width & Height Factor:` _image scale factor_ 👈

<span class="our-scale-factor">Our <em>image<br>scale factor</em> is<br>metres per pixel<br><strong>0.047169811</strong></span>

![Screenshot of CAD program, showing scaled image](https://res.cloudinary.com/growdigital/image/upload/w_580/v1573817366/scale-image-07-complete.png)

<h6 class="breadcrumb">CAD — Setup — Shapes — <span class="u-underline">Examples</span> — Exercises — Tips</h6>

???

* Width & Height Factor

---

# 3. Garden acre

![Satellite photograph of houses & fields](https://res.cloudinary.com/growdigital/image/upload/w_430/v1672751964/class/acre-google-satellite.jpg)

1. Satellite better for acres
2. Update with measurements
3. [Old maps](https://maps.nls.uk/) & [OS maps](https://www.bing.com/maps?osid=99c90955-4484-4d18-bc8f-114f37a9a37f&cp=52.057029%7E-4.469182&lvl=16.0&style=s&v=2&sV=2&form=S00027)

<h6 class="breadcrumb">CAD — Setup — Shapes — <span class="u-underline">Examples</span> — Exercises — Tips</h6>

???

### Add a template directory

1. Download my delicious template [github.com/growdigital/template](https://github.com/growdigital/template)
2. Unzip the file and put the folder somewhere safe eg `Documents`
3. In QCAD, `Edit > Application Preferences > File > Templates`
4. Add folder
5. Restart QCAD
6. `File > New from Template`
7. Choose `template` folder, create new file

Instructions: [bit.ly/add-qcad-template](https://bit.ly/add-qcad-template)

---

* Elements to create
  1. Template
  2. Satellite  
  3. Boundary
  4. Paths
  5. Trees (forest garden block)
  6. Hedges
* Reference
  * [bing.com/maps](https://bing.com/maps) Ordnance Survey & nice photos
  * [google.co.uk/maps](https://google.co.uk/maps) higher resolution?

<h6 class="breadcrumb">CAD — Setup — Shapes — <span class="u-underline">Examples</span> — Exercises — Tips</h6>

---

# 4. Garden town

![Satellite photograph of east-west facing street](https://res.cloudinary.com/growdigital/image/upload/w_430/v1672751964/class/garden-google-satellite.jpg)

1. Satellite rough guide
2. Plan from _measurements_
3. General info from maps

<h6 class="breadcrumb">CAD — Setup — Shapes — <span class="u-underline">Examples</span> — Exercises — Tips</h6>

???

* Elements to create
  1. Template
  2. Satellite  
  3. Boundary
  4. Paths
  5. Plants (forest garden block)
  6. Hedges
* See Survey class

---

class: middle, center

# 5. Exercises

<h6 class="breadcrumb">CAD — Setup — Shapes — Examples — <span class="u-underline">Exercises</span> — Tips</h6>

---

class: middle

# CAD excercises

1. Install & setup QCAD!
2. Draw shapes
3. Draw circles
4. Modifications

<h6 class="breadcrumb">CAD — Setup — Shapes — Examples — <span class="u-underline">Exercises</span> — Tips</h6>

---

class: middle, center

# 6. CAD tips

<h6 class="breadcrumb">CAD — Setup — Shapes — Examples — Exercises — <span class="u-underline">Tips</span></h6>

---

# Class resources

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

<h6 class="breadcrumb">CAD — Setup — Shapes — Examples — Exercises — Tips</h6>

---

class: middle, center

# The End

![Photo from above of newly planted curvey path garden, overlaid with CAD lines on path and edge](https://res.cloudinary.com/growdigital/image/upload/w_420/v1580908407/class/overlay-illustration.jpg)

<hello@natureworks.org.uk>

[natureworks.org.uk/newsletter](https://www.natureworks.org.uk/newsletter)

</textarea>
<script src="/assets/js/remark.js"></script>
<script>
  var slideshow = remark.create({ratio: '16:9'});
</script>
</body>

</html>
