---
layout: post
title: "Flag Project - Final Submission"
date: 2018-12-21
---

## Flag of United States of America by Iliyana Kirilova 

## Describe your program

-   What country did you design for? _then delete this instruction_
-   What grade do you expect? _then delete this instruction_

## Current output

* * *
![Flag](/images/flag2.png)
* * *

## Describe your process.

-   What questions, strategies, help from peers or teacher, or thinking got you to this point? _then delete this instruction_

<!--- Delete this comment and add your writing -->


## Explain your code.

-   Choose a significant part of your program (15 lines max) and paste it below. Do not insert your entire program here. _then delete this instruction_
-   Explain each argument in the code section. _then delete this instruction_
-   Tell us how it functions independently and within the whole program _then delete this instruction_

* * *

```
Insert 10-15 line code section here _then delete this instruction_
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
