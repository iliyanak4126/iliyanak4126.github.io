---
layout: post
title: "Iliyana's Week 12"
date: 2018-12-13
---
Welcome Back to my blog... Week 12! YAY!

The past week(December 10-13), we did the following:
Monday(December 10), we didn't have regular lessons because Mr. Allatta was out but we had assign work to complete. For example we had to update our blogs, or work on our collage project. I decided to update all my blogs because last week's blog, I didn't have time to finish it, so it was a good time to do so now. 

Tuesday(December 11)


Wednesday(December 12)


Thursday(December 13)



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
 
