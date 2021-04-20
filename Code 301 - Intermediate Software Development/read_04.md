# GRID

- When grid-column-start is used alone, the grid item by default will span exactly one column. However, you can extend the item across multiple columns by adding the grid-column-end property.
  grid-column is a shorthand property that can accept both values at once, separated by a slash.
  One of the things that sets CSS grids apart from flexbox is that you can easily position items in two dimensions: columns and rows. grid-row-start works much like grid-column-start except along the vertical axis.

- If typing out both grid-column and grid-row is too much for you, there's yet another shorthand for that. grid-area accepts four values separated by slashes: grid-row-start, grid-column-start, grid-row-end, followed by grid-column-end.

- If grid items aren't explicitly placed with grid-area, grid-column, grid-row, etc., they are automatically placed according to their order in the source code. We can override this using the order property, which is one of the advantages of grid over table-based layout.

- By default, all grid items have an order of 0, but this can be set to any positive or negative value, similar to z-index.

- The repeat() function takes two arguments, the first will define the number of column tracks and the second, what width the tracks should be.

# Grids in CSS:

The CSS Grid Layout Module offers a grid-based layout system, with rows and columns, making it easier to design web pages without having to use floats and positioning. A grid layout consists of a parent element, with one or more child elements. An HTML element becomes a grid container when its display property is set to grid or inline-grid.

- Example:

```
.grid-container {
  display: grid;
}
```

- All direct children of the grid container automatically become grid items. The vertical lines of grid items are called columns. The horizontal lines of grid items are called rows. The spaces between each column/row are called gaps.

## Grid Container

- display : defines element as grid
- grid-template-columns / grid-template-rows : defines the columns/rows of the grid
- grid-template-areas: defines a grid template by referencing the names of the grid areas which are specified with the grid-area property
- grid-template: shorthand for setting grid-template-rows, grid-template-columns, and grid-template-areas
- column-gap / row-gap / grid-column-gap / grid-row-gap: used to set the width of the gutters between the columns/rows
- gap / grid-gap: shorthand for row-gap and column-gap
- justify-items: aligns grid items along the inline (row) axis
- align-items: aligns grid items along the block (column) axis
- place-items: sets both the align-items and justify-items properties in a single declaration
- justify-content: set the alignment of the grid within the grid container
- align-content: set the alignment of the grid within the grid container
- place-content: sets both the align-content and justify-content properties in a single declaration
- grid-auto-columns / grid-auto-rows: specifies the size of any auto-generated grid track
- grid-auto-flow: places grid items that you don’t explicitly place on the grid
- grid: shorthand for grid-template-rows, grid-template-columns, grid-template-areas, grid-auto-rows, grid-auto-columns.

## RegEx:

- A regular expression is an object that describes a pattern of characters. Regular expressions are used to perform pattern-matching and "search-and-replace" functions on text.

## Responsice Web Design (RWD):

- Responsive web design is the practice of building a website suitable to work on every device and every screen size, no matter how large or small, mobile or desktop. Responsive generally means to react quickly and positively to any change, while adaptive means to be easily modified for a new purpose or situation, such as change. Currently the most popular technique lies within responsive web design, favoring design that dynamically adapts to different browser and device viewports, changing layout and content along the way. This solution has the benefits of being all three, responsive, adaptive, and mobile.

<img src='https://i.ytimg.com/vi/68O6eOGAGqA/maxresdefault.jpg' width=800 height= 450>
