---
layout: post
title: "Iliyana's Week 12- Flag Project- In Process"
date: 2018-12-13
---
Welcome Back to my blog... Week 12! YAY!

The past week(December 10-13), we did the following:
Monday(December 10), we didn't have regular lessons because Mr. Allatta was out but we had assign work to complete. For example we had to update our blogs, or work on our collage project. I decided to update all my blogs because last week's blog, I didn't have time to finish it, so it was a good time to do so now. 

Tuesday(December 11)


Wednesday(December 12)


Thursday(December 13)


![Flag Image](/images/flag.png)

This is the code from the USA Flag that I used:

```include image
size = 100 
width = size * 1.9
height = size * 1
stripe-height = height * 0.076
blue-rectangle-width = (stripe-height / 7) * 0.76
blue-rectangle-height = (stripe-height / 7) * 0.535

nsh = 0 - stripe-height
half-width = width  * 1/2

base = rectangle(width, height, "solid", "red")
stripe = rectangle(width, stripe-height, "solid", "white")

flag1 = overlay-xy(stripe,0,0,base)
flag2 = overlay-xy(stripe,0,3 * nsh,flag1)
flag3 = overlay-xy(stripe,0,5 * nsh,flag2)
flag4 = overlay-xy(stripe,0,7 * nsh,flag3)
flag5 = overlay-xy(stripe,0,9 * nsh,flag4)
flag6 = overlay-xy(stripe,0,11 * nsh,flag5)
flag7 = overlay-xy(stripe,0,13 * nsh,flag6)

blue-rectangle = rectangle(174 * blue-rectangle-width, 174 * blue-rectangle-height, "solid", "blue")

flag8 = overlay-xy(blue-rectangle, 0,0, flag7)```
 
 Some questions I had were:
 * How would I put the 13 stripes together plus a rectangle with 50 stars?
 *How would the stars be placed so they could be equal spaced from each other? 
 *Also how would the 13 stripes work and be equaled spaced?
 
 The code that I have, some of it I got from Mr.Allatta which is the first three lines. Afther that I had to define everything by myself. I got some help from my classmate named Derek and also Mr. Allata. A specific code that Mr.Allatta and I disscused was "overlay-xy" because I wanted to place things all together either with overlay or place imaged, but I've seen overlay-xy in the Pyret website and also it puts image 1 which is x over image 2 which is y. So like it combines the two images by putting it onto each other. But something special about overlay-xy is that when it puts the two images into each other and lines their upper left sides, the x-axis of image two shifts it to the right and the y-axis shits it down. I used it because I need to shift my stripes up and down and certain positions in order to get the 13 stripes equal distanced and fit them together on my base(image one which in this case is red). 
Some challenges I have are how am I gotta put all these 50 stars together in the blue rectangle and how would they still be the same equal spaced distanced when the size of the flag is bigger or smaller. 

Some things I'm really looking forward is putting those god dam stars together so they could fit in the blue rectangle and when the flag is in larger or smaller sizes would still fit. 

Hopefully I could show you my flag next week! See you next week!:)
