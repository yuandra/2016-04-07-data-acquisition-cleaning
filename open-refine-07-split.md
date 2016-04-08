---
layout: page
title: Splitting and Join Multi-Valued Cells in Open Refine
root: .
---

### Split Multi Valued Cells

Open Refine has the function of splitting multi valued cells

You can access the function by going to the cell that has the multi valued cell and do the edit cell - split multi valued cell operation

### Records vs Rows

You will see that Open Refine has split the multi valued cells into multiple rows, however that does not mean that it creates more rows in reality.

This is because Open Refine think as a row of data that we imported as a "record" while rows inside Open Refine is the representation of the Open Refine to make it easier for us to work with data that has multi value in a cell. It displays them as a multiple rows, while keeping them in a single record.

### Joining multi valued cells

To join a multi valued cells back to one row, you can select the multi valued cells that has been splitted, and then select edit cells - join multi valued cells, and put the separator back

### Splitting into new column

We can also split a multi valued cell into its own column by the way of edit column - split into new column

Next: [Clustering cells in Open Refine](open-refine-08-clustering.html)

Prev: [Open Refine Filtering](open-refine-06-filtering.html)


[Main menu](index.html)
