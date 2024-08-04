---
title: Forest garden CAD photo
date: 2019-05-26T11:47:25+01:00
discussionId: forest-garden-cad-photo
description: Using a satellite photo as the basis for your forest garden plan is a good and quick way of creating an approximate plan without having to measure out in the field.
tags: 
- ForestGarden
- GdnBloggers
- Plan
- Satellite
images: 
- https://res.cloudinary.com/growdigital/image/upload/v1558867390/01-satellite.jpg
imageAlt: 
- Satellite photo
imageCap:
- Satellite photo of the Forest Garden Wales forest garden
draft: false
---

I discovered how to easily scale a satellite photo in [QCAD](https://www.qcad.org/en/) to create a #ForestGarden plan.

1. **Satellite:** Take a screenshot of your satellite map. Apple Maps has the best resolution satellite photos in the UK, although I have been trying to get photos from [USGS EarthExplorer](https://earthexplorer.usgs.gov). Be sure to include the scale.
2. **Scale:** Using the rectangular selection tool in Photoshop on the scale, calculate the number pixels per metre. In the example, it’s 5.8.
3. **Width:** Then find out the width in pixels of the entire satellite photo. Trim the canvas size to make it a nice round number of metres. In the example, the width is 754 pixels, divided by 5.8 is exactly 130 metres (you can use a [modulus calculator](https://www.miniwebtool.com/modulo-calculator/) to help with this).
4. **Import:** Create a new QCAD file, put the satellite photo in the same folder, import the photo image.
5. **Resize:** The image is scaled at 1 metre per pixel, which means the example is 754 metres. Make sure the image is selected and in the `Property Editor`, enter 130 (metres) into the width box. 
6. **Voilà:** All done. Using the [Plants For A Future website](https://www.pfaf.org/), find out the diameters of the trees you want to plant, position the trees on the plan and make sure you have the correct [tree spacing](https://www.forestgarden.wales/blog/tree-spacing-forest-garden/) to allow enough light in.

{{< figure src="https://res.cloudinary.com/growdigital/image/upload/v1558867390/01-satellite.jpg" alt="Satellite photo" caption="1. Satellite" >}}
{{< figure src="https://res.cloudinary.com/growdigital/image/upload/v1558867389/02-scale.jpg" alt="Close up in Photoshop of map scale, showing pixels" caption="2. Scale" >}}
{{< figure src="https://res.cloudinary.com/growdigital/image/upload/v1558867390/03-width.jpg" alt="Photoshop info box showing total width in pixels" caption="3. Width" >}}
{{< figure src="https://res.cloudinary.com/growdigital/image/upload/v1558867390/04-import.jpg" alt="Image imported into QCAD" caption="4. Import" >}}
{{< figure src="https://res.cloudinary.com/growdigital/image/upload/v1558867390/05-resize.jpg" alt="Image resized, using Property Editor in QCAD" caption="5. Resize" >}}
