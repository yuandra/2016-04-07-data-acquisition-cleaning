---
layout: page
title: Basic data cleaning operation
root: .
---

### Open Refine basic data cleaning operation

Open Refine provides some very useful data cleaning operation that you can try.

Those operation such as :

- trim leading and trailing whitespace
- trim consecutive whitespace
- make uppercase
- make lowercase
- make titlecase

We want to make sure that the height, width, depth, diameter, and height does not have any whitespace in the front or in the back

- click on the arrow bar beside the column name (height/width/depth/diameter/height)
- choose edit cells
- choose common transform
- choose trim leading and trailing whitespace
- repeat on the other columns

### Exercise

- change the categories column to be all uppercase

### Google Refine Expression Language

You can also do more powerful transform by using GREL. GREL has almost the same function with excel function, however it might have a different syntax. A lot of the commands that we are using now can actually be done by GREL also.

You can check the documentation of GREL in here : [https://github.com/OpenRefine/OpenRefine/wiki/General-Refine-Expression-Language](https://github.com/OpenRefine/OpenRefine/wiki/General-Refine-Expression-Language)

Let's try GREL to switch the separator in the categories from | (pipe sign) into - (minus sign)

- click on the arrow bar beside the categories column
- choose edit cells
- choose transform
- you will be shown the GREL interface, the value in the column you were working on, and the value once you've typed a GREL function
- type replace(value,"|","-")
- set the on error set as blank
- apply the function

### Exercise

- Put a text facet in column height
- change it to milimeters
- don't forget to add the "mm" at the end to make it the same format with other
- use functions such as substring, round, value, toNumber
- you can add string by using the operator "+"

Next: [Filtering in Open Refine](open-refine-06-filtering.html)

Prev: [Open Refine Faceting](open-refine-04-faceting.html)


[Main menu](index.html)
