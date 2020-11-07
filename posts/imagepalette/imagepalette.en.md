---
title: A slightly different way to the color palette
published: true
description: Extract color palette from images
tags: "image, color, palette"
canonical_url: null
id: 2020110501
---

I wonder how many hours I have spent on Unsplash or similar sites, looking for images for projects, wallpapers or just to get an overview. But sometimes just for pleasure, the need to see beautiful, harmonious images. The focus here is rarely on the motif. I am especially enthusiastic about unusual perspectives or messages. The other main factor are contrasts, as they (almost) only occur in nature and can only be captured very well by photographers.

![Unsplash Screenshot](assets/unsplash.jpeg)

Unfortunately I am not such a good photographer, in fact I am not a photographer at all. But that does not mean that I do not recognize and want to use this beauty.
During my work as a frontend developer I try to create color palettes regularly. If you have ever tried to find two or three of the 16,777,216 colors that fit well together, convey the desired message and have the appropriate contrast, you know that this is not an easy task.
So why not use the harmonic compositions of these images and generate from these color palettes? Since I myself understand very little about the harmony of colors and do not know how they interact in the pictures, I first researched whether there are already projects that can do this. Here, I am referring to this great library [Vibrant.js](https://jariz.github.io/vibrant.js/).

> Vibrant.js is a javascript port of the [awesome Palette class](https://developer.android.com/reference/android/support/v7/graphics/Palette.html) in the Android support library.

In order to use this knowledge as efficiently as possible in everyday life I have written a website where you can copy/pull/upload any image you want. Afterwards the image is analyzed by Vibrant.js and a corresponding color palette is displayed.
Maybe this site can help you find inspiration or even an (almost) finished color concept. Just give it a try [https://image-palette.tomeckardt.com](https://image-palette.tomeckardt.com)

![Unsplash Screenshot](assets/imagepalette.jpeg)
