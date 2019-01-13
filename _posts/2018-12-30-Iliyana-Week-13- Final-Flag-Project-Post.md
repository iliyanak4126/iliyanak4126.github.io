---
layout: post
title: "Flag Project - Final Submission"
date: 2018-12-21
---

## Flag of United States of America by Iliyana Kirilova 

## Describe your program
 The country I designed was the United States of America! 
What grade do you expect? A grade that I expect is a 3 because I really put hard work into this, but I didn't have the chance to actually have the 50 stars. But I think I could get a 3 with everything I have. 

## Current output

* * *
![Flag](/images/flag2.png)
* * *

## Describe your process.
Some questions, strategies that help me were how I would place the stripes and also the blue rectangle. At first I was making the first 7 stripes of my flag smaller than the usual size because the blue rectangle was suppose to be their. But Mr.Allatta just told me to use the full size stripes for each one and than place the blue recatngle on them when finish, which actually helped me a lot and it worked. 



## Explain your code.

-   Explain each argument in the code section. _then delete this instruction_
The code I choosed to explain is this because it shows how my 13 stripes and my base join together. Also I added the blue flag in it too. 
-   Tell us how it functions independently and within the whole program _then delete this instruction_

* * *

```
nsh = 0 - stripe-height
half-width = width  * 1/2

base = rectangle(width, height, "solid", "red")
stripe = rectangle(width, stripe-height, "solid", "white")

flag1 = overlay-xy(stripe,0,1 * nsh,base)
flag2 = overlay-xy(stripe,0,3 * nsh,flag1)
flag3 = overlay-xy(stripe,0,5 * nsh,flag2)
flag4 = overlay-xy(stripe,0,7 * nsh,flag3)
flag5 = overlay-xy(stripe,0,9 * nsh,flag4)
flag6 = overlay-xy(stripe,0,11 * nsh,flag5)

blue-rectangle = rectangle( 92 * blue-rectangle-width, 92 * blue-rectangle-height, "solid", "blue")

flag8 = overlay-xy(blue-rectangle, 0,0, flag6)


```

* * *

-   Explain the code you posted by telling us about each argument.
-   Then tell us how your code section fits into the whole.
 
<!--- Delete this comment and add your writing -->


## Program code

```
include image

size = 100 
width = size * 1.9
height = size * 1
stripe-height = height * 0.076
blue-rectangle-width = (stripe-height / 7) * 0.76
blue-rectangle-height = (stripe-height / 7) * 0.5385
#W-star = star(200 * 0.0616,"solid","white")

nsh = 0 - stripe-height
#(negative stripe- height = nsh)
half-width = width  * 1/2

base = rectangle(width, height, "solid", "red")
stripe = rectangle(width, stripe-height, "solid", "white")

flag1 = overlay-xy(stripe,0,1 * nsh,base)
flag2 = overlay-xy(stripe,0,3 * nsh,flag1)
flag3 = overlay-xy(stripe,0,5 * nsh,flag2)
flag4 = overlay-xy(stripe,0,7 * nsh,flag3)
flag5 = overlay-xy(stripe,0,9 * nsh,flag4)
flag6 = overlay-xy(stripe,0,11 * nsh,flag5)
#flag7 = overlay-xy(stripe,0,13 * nsh,flag6)

blue-rectangle = rectangle( 92 * blue-rectangle-width, 92 * blue-rectangle-height, "solid", "blue")

flag8 = overlay-xy(blue-rectangle, 0,0, flag6)
``` 
