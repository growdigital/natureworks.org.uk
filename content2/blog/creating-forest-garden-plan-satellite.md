---
title: Creating a forest garden plan with a satellite background image
date: 2019-11-22T18:11:00Z
discussionId: creating-forest-garden-plan-satellite
description: As part of my online forest garden course, I’ve been looking at how to use a screenshot of a satellite photo as the basis of a forest garden plan. If you’re comfortable with computers, the process is relatively straightforward.
tags: 
- ForestGarden
- Plan
- CAD
- HowTo
- Tutorial
- Satellite
images: 
- https://res.cloudinary.com/growdigital/image/upload/v1574448595/avant-garden-trees.jpg
imageAlt:
- Screenshot of CAD program with large scale satellite photo in background and circles for trees
imageCap:
- Using a satellite photo as the basis for a CAD forest garden plan is only 4 steps away
draft: false
---

Using a CAD plan, it’s easy to move trees around to try out different ideas. The hard bit is setting up the boundaries of the land in the first place.

The easiest way I’ve found to achieve this is to take a screenshot of a satellite photo and scale it down to the right size in the CAD software.

This walkthrough will show you the 4 steps of importing and scaling the image.

## What you need 

* A copy of [QCAD](https://qcad.org/en/download), Computer Aided Design software that is Free and Open Source. There’s a free version which is absolutely fine for our purposes. In the demo, we’re using **metres** as the unit!
* A bitmap editor like [Photoshop](https://en.wikipedia.org/wiki/Adobe_Photoshop). [GIMP](https://www.gimp.org) is a Free Open Source alternative.

## 1. Take a screenshot of your satellite image

{{< figure src="https://res.cloudinary.com/growdigital/image/upload/v1574447386/avant-garden-background.jpg" alt="Satellite photo of farm area" caption="Satellite photo of land in Apple Maps" >}}

1. Use [Google Maps](https://www.google.co.uk/maps), [Apple Maps](https://en.wikipedia.org/wiki/Apple_Maps) or [Bing Maps](https://www.bing.com/maps) and get the highest resolution satellite image of your land that you can. 
2. Make sure to include a **metres** scale (this demo is in metric!)
3. Take a [screenshot](https://www.wikihow.com/Take-a-Screenshot-in-Microsoft-Windows)
4. Open in your image editor and save as a JPEG in the same folder you’ll save your CAD file.

## 2. Measure pixels per metre

{{< figure src="https://res.cloudinary.com/growdigital/image/upload/v1574447778/avant-garden-px-per-metre.png" alt="Screenshot of metres scale on satellite photo in Photoshop" caption="Rectangular marquee tool measuring the width of the scale" >}}

1. Using the rectangular marquee tool and measure the metres scale.
2. In our example, there are 210 pixels per 30 metres.
3. 210 divided by 30 equals **7 pixels per metre**

## 3. Calculate image scale factor

1. QCAD imports images in at **1 pixel per 1 metre**.
2. In our example, we want **7 pixels per metre**.
3. So, we divide 1 by 7, which gives us **0.142857143**

This is the **image scale factor**, ie how much we need to scale the image once it’s in QCAD.

## 4. Scale the image in QCAD

{{< figure src="https://res.cloudinary.com/growdigital/image/upload/v1573817366/scale-image-05-widthfactor.png" alt="Screenshot of bitmap image in CAD software" caption="Enter the image scale factor into the Width and Height Factor field in the Property Editor" >}}

1. Hop into QCAD, save a new file in the same folder as your background image
2. Choose `File → Import` from the drop-down menu, then import your image
2. Select your image with `Select → Select All`
3. Bring up the Property Editor with `View → Property Editor`
4. Enter the image scale factor (our example is 0.142857143) into both the `Width Factor:` and `Height Factor:` fields

You’ll see the image scale down. And now you can use the `Circle` tools to create circles of a set diameter, which will represent trees. You can find the approximate height and diameter of common forest garden trees and shrubs from the brilliant [Plants For A Future](https://pfaf.org/user/Default.aspx).

If you found this tutorial helpful, please [sign up to my newsletter](https://www.forestgarden.wales/newsletter/) for information about free forest garden mini-courses and resources. 

I made a short, unedited video of this process which you can view here:

{{< vimeo 375367632 >}}

And the slideshow is online here:

[www.forestgarden.wales/wildlife-forest-garden/plan](https://www.forestgarden.wales/wildlife-forest-garden/plan/#13)

Happy forest gardening! 🌳 💚
