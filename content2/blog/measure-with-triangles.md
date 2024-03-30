---
title: Measure with triangles
date: 2020-04-08T09:51:00+01:00
description: Making a plan for an irregular shaped garden can be tricky. Triangles, cosines and The Internet to the rescue
tags: 
- ForestGarden
- Plan
images: 
- https://res.cloudinary.com/growdigital/image/upload/v1586269476/rhug-triangulation-fg.jpg
imageAlt:
- Outline of garden on graph paper triangulated with interconnecting triangles
imageCap:
- If each point on the garden perimeter has 3 measurements coming from it, then you can calculate the angles
draft: false
---

First off, a disclaimer. I’m shit at maths. Luckily, there’s clever people and the internet. I have a lovely design job at the moment and it has an irregular shaped rear garden. 

The trick is to mark out (with small stakes if necessary) set points around the perimeter of the garden, and then make sure that there are **3** measurements from each point to other points (see image above). 

If you know the three sides of a triangle, you can work out the angles in a triangle. Luckily, someone has made [triangle-calculator.com](https://www.triangle-calculator.com), and if you can click on [SSS](https://www.triangle-calculator.com/?what=sss) you get to calculate [“Side Side Side”](https://www.mathsisfun.com/algebra/trig-solving-sss-triangles.html) triangles, with the click of a button:

{{< figure src="https://res.cloudinary.com/growdigital/image/upload/v1586269475/triangle-calculator.com.png" alt="Screenshot of triangle-calculator.com" caption="Calculating angles from 3 known lengths of a triangle" >}}

Once you have the angles, you can use [CAD](https://en.wikipedia.org/wiki/Computer-aided_design) software like [QCAD](https://qcad.org/en/), and re-create the triangle. This is fiddly and requires some CAD knowledge but totally doable (and the subject of a whole workshop in itself 😆). 

Then you recreate the triangles, one from the other (hint, use duplicate and the [Lines with given angle](https://qcad.org/doc/qcad/2.2/reference/en/chapter17.html) tool). When you’ve recreated all the triangles, rotate the whole outline to a known fixed point, which is usually the house. You can see, I’ve taken some measurements from the house in the first diagram, so that I can work from them.

{{< figure src="https://res.cloudinary.com/growdigital/image/upload/v1586269475/rhug-triangulated-mesh.png" alt="CAD mesh triangle outline of garden" caption="All recreated triangles rotate to fit to angle of the house" >}}

Finally, delete the lines in the centre of the garden, and you are left with an outline. I know, it’s tricky and not as easy tracing the outline of a satellite photo but it’s one way of getting a plan of a smaller irregular garden.

{{< figure src="https://res.cloudinary.com/growdigital/image/upload/v1586269475/rhug-triangulated-border.png" alt="Finished outline of garden in CAD" caption="At the end of all that hard work, you’re left with a few lines outlining your irregularly shaped garden" >}}

Good luck! And the next blog post will be more plant-based 😎 🌱
