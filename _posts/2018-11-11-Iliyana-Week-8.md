---
layout: post
title: "Iliyana's Week 7"
date: 2018-11-11

---

During the past week(November 5 to November 8) in AP Computer Science, we learned the following topics: Intro to Stucts, Data Definitions and Designing Functions with Examples. 

On Monday(Nov. 5), we learned about Intro to Structs. Intro to Structs is Data definitions and what each thing in a code actually means. For example in we had a code that was:
data Delivery State:  < this thing means the name of the data>
  delivery(    <this thing means the constructor fuction>
  x:: Number    <Container and also ancestors>
  y:: Number    <Container and also ancestors> 
  end
The things that a contract takes in are called containers because when we want to put together stuff that are needed for something we put them together in something that could be a container that has all the stuff. This fuctions shows a table data that is putting a lot of info together to created a table that would represent it. Also we were suppose to find a pattern that would actually deliver the box into the right place, so we had to define what x and y were and by how much they were increasing. 

On Wednesday(Nov. 6) we learned Data Definitions. We had to build are own bakery that would make cakes. We had to answer the question "How could you represent your famous cakes as a data?". We design a function that would take in three thing which are:
1. Flavor -> Categorial and String 
2. Layers -> Number 
3. is-icecream -> Boolean
This was a representation of how it should look like but the data definition was:
data CakeType      <This represents the name of new type of data>
  cake             <name of constructor> 
  flavor:: String   <fields or samw as columms in a table>
  layers:: Number   <fields or samw as columms in a table>
  is-icecream:: Boolean  <fields or samw as columms in a table>


Finally on Thursday(Nov 8) we learned about Designoning functions with examples. So we had to take an function and make examples representing that function. One of the functions we did was:
data CakeType: cake( flavor:: String; layers:: Number; is-icecream:: Boolean. An example with this is chocalate-cake= cake("Chocolate", 8, false)
Than we had to compare the number of layers between two cakes. For example we did chocolate. layers > red-velvet.layers which represented 8 > 4. 
We also got the contract for taller-than which is:
taller-than:: CakeType, CakeType -> Boolean and we check if it's correct by using the boolean functions. An example is 
taller- than(red-valvet-cake, birthday-cake is true 
  red-velvet-cake.layers > birthday-cake.layers 
Examples help us design fuction because when a function is given to us it shows what is needed. By the example we show what are the stuff that were show in the fuction but now you substitute the string and the number with words and actual numbers. 

Well this was what we lear this week, see you soon! :)
