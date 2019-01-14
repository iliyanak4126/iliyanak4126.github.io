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
The code I choosed to explain is this because it shows how my 13 stripes and my base join together. Also I added the blue flag in it too. So I used overlay-xy in order to put the red base on the bottom and than on the top I would add the red stripes. I used flag#(flag1, flag2,flag8) in order to put the next stripe on the base after the first one. Than I would use the stripe and the position of it, in order to place them equal-distanced from each other. NSH is negative stripe height and I used it because overlay-xy uses only negative numbers. So nsh would help me by putting positive numbers and place them where  I want even if I were to use negative numbers.
Overlay-xy helps the whole project because it places my stipes on my base wherever I want to. If I wasn't using overlay-xy, than I wouldn't been able to place my flag together and everything wouldve been a  mess. 
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
The code I posted puts all the United States of America flag together. First I used the size of the base(red rectangle where everything would be on) which has a width of size of the flag * 1.9  and an height of the size of the flag * 1. The stripe-height is the height of the base by 0.076(this is the original stripe height size). The blue rectangle(where the 50 stars are) has an height and a width which are blue-rectangle-width (stripe-height divide by 7) and than multiplied by 0.076 and blue-rectangle-height is (stripe height divide by 7) and than multiplied by 0.5385. For blue-rectangle-width I used the stripe-height divide by 7 because the blue rectangle only covers 7/13 of the stripes on the flag. and I multiply it by 0.76 because thats the width of the blue rectangle. Is the same thing for blue-stripe-height you use te stripe height and divide it by 7 because it only covers the first 7/13 stripes of the flag. Than I multiplies bt 0.5386 because that's the height of the blue rectangle.
After that I used overlay-xy in order to place the 7 white stripes on the red base. The red base was representing the red stripes. Each white stripe had a specific place to be. The flag# represent each of the 7 white stripe being put on the red base. So for example if you were to type flag6 in the interaction side of Pyret, only the white/red stripes would show on(no blue-rectangle yet).

 My code section fits into the whole because by identifying the flag# it show step by step how I added the 7 white stripes. Than when added the blue-rectangle I again showed it by flag8 which would represent the whole flag I have without the stars. So if I would to add the 50 stars I wouldv'e have been adding more of the flag# in order to identify step by step how my stars fitten in the blue rectangle. 



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
