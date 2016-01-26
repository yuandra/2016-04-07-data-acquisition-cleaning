---
layout: page
title: Using facet for selection in Open Refine
root: .
---

### About Faceting

Data cleaning operations in Open Refine basically revolves along two main operations :

- selecting the messy data
- deciding what you will do with it

To help with the first operation, selecting the messy data, Open Refine has a very powerful feature called facet
Faceting in Open Refine means giving a "view" of your data. Open Refine gives several facet of your data such as :

- facet by text, for text data
- facet by numbers, for number data
- facet by star, for those data we mark with a star
- facet by flag, for those data we mark with a flag

and otherfacet such as text length facet and many more

We will try some of the facet, namely text, numbers, star, and flag

For facet by text, it will give you a unique list of every instance of the data inside a column.

- click on the arrow beside the column object title
- click on facet by text
- you will that there are 94 choices.

We have 99 rows of data. Where are the other 5 ?

- click on the count in the facet window to sort it by count
- you will see that there are several items that have the same title
- click on the title
- you will that they indeed have the same title, but different description

You can also use facet to check for blanks

- click on the arrow beside the column height
- click on facet by text
- sort it by count
- you will see that there are 72 data that is blank

You can also mark those rows by clicking on the star / flag in the left side of the rows. You can mark all your selection by clicking on the arrow beside the all column, and also select edit rows, star/flag rows. You can also use the flag/star facet to select them.

### Exercise

Select those that has height and width (not blank)
Hint : use star and flag to help you mark your selection


Next: [Basic data cleaning operation in Open Refine](open-refine-05-basic.html)

Prev: [Open Refine Interface](open-refine-03-interface.html)


[Main menu](index.html)
