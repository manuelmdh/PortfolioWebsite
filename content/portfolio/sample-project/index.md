---
title: Design and Printing Of Aero-Bracket In Laser Powder Bed Fusion (LPBF)
description: This is the description of our sample project
date: "2020-06-02T19:47:09+02:00"
work: [Mechanical design, Additive Manufacturing]
techs: [Fusion 360, Generative Design, LPBF]
thumbnail: sample-project/image28.gif

---

The objective of the project is to go through the entire design process of an aerospace application bracket, while exploring the capabilities of Fusion 360 for 3D engineering.  As a requirement, a shape optimization design and a generative design must be made. All the design choices must consider that it will be printed on a SLM 125 HL Printer with AlSi10Mg for stock material.

![Topology Results](/image18.png)

The Dimensions of the original bracket where given in a blueprint. Shape optimization was achieved by using the original shape on Fusion 360 shape optimization tool, then material was removed manually from non critical path areas.

![Shape Opt FEA](/image24.png)
For generative design, the original dimensions where used to indicate preserve regions, which are critical for the part to comply with the intended function. As well as creating obstacles to indicate the algorithm not to add material on specified area

![Generative Design FEA](/image43.png)
![Printing](https://media.giphy.com/media/dWNhZ4OhjPbyvMvjT2/giphy.gif)
![Printed Parts](/image56.png)

|Design   |  mass | weight reduction %  |  
|---|:---:|---:|
|Original   | 499.43 grams  |   
|Shape Opt   |237.06 grams   |52.5%   |   
|Generative Dsg.   |77.111 grams   |84.6%   |   
