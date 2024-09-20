---
title: "Vessel skeletons ...huh?"
date: 2022-01-31
image: images/blog/2022_01_jan_thumb.png
feature_image: images/blog/2022_01_jan.png
---
### Measuring the length of blood vessels in a dish

You're probably wondering what I'm talking about right now.

Maybe you remember that I'm trying to grow mini blood vessels in a dish and that I'm trying to use this method to figure out how cancer cells change the blood vessels? If you didn't remember, well now, you are hopefully all caught up.

I now need a way to measure the little branches coming out of each blood vessel blob. But how exactly is that done? I've been writing a computer algorithm that can identify these branches automatically, tell me how long all the branches are, and how many there are. This algorithm uses a technique called "skeletonization", which is a process where we take all the pixels of the image and reduce them down to a single line of pixels that represent the general structure of the image. It's basically the equivalent of drawing a picture of the human body as a stick figure.

On the left side, you can see the original vessel blob with branches, and on the right side, the vessel skeleton!
