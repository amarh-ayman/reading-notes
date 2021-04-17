# HTML & CSS

## Responsive Web Design

The practice of building a website suitable to work on every device and every screen size, no matter how large or small, mobile or desktop. Responsive web design is focused around providing an intuitive and gratifying experience for everyone. Desktop computer and cell phone users alike all benefit from responsive websites.

![food](https://learn.shayhowe.com/assets/images/courses/advanced-html-css/responsive-web-design/food-sense.png)

> ## Responsive web design is broken down into three main components, including flexible layouts, media queries, and flexible media

- Flexible Layouts
  - Flexible Grid
- Media Queries

---

# All About Floats

Float is a CSS positioning property.
![](https://css-tricks.com/wp-content/uploads/2021/03/web-layout.png)

- This same layout could be accomplished using relative positioning on container and absolute positioning on the avatar as well. In doing it this way, the text would be unaffected by the avatar and not be able to reflow on a size change.

![](https://css-tricks.com/wp-content/uploads/2021/03/reflow-example-1.png)

- Clearing the Float
  Float’s sister property is clear. An element that has the clear property set on it will not move up adjacent to the float like the float desires, but will move itself down past the float. Again an illustration probably does more good than words do.
  <br><br>
  ![](https://css-tricks.com/wp-content/uploads/2021/03/unclearedfooter.png)
  <br><br>
  Clear has four valid values as well. **Both** is most commonly used, which clears floats coming from either direction. **Left** and **Right** can be used to only clear the float from one direction respectively. None is the default, which is typically unnecessary unless removing a clear value from a cascade. Inherit would be the fifth, but is strangely not supported in Internet Explorer. Clearing only the left or right float, while less commonly seen in the wild, definitely has its uses.

# Grid

The vast majority of websites out there use a grid. They may not explicitly have a grid system in place, but if they have a “main content area” floated to the left a “sidebar” floated to the right, it’s a simple grid.

If a more complex layout presents itself, people often reach for a grid framework. They assume grids are these super difficult things best left to super CSS nerds. That idea is perpetuated by the fact that a lot of the grid systems they reach for are very complicated.
<br><br>
for more information [visit this site](https://css-tricks.com/snippets/css/complete-guide-grid/)
<br><br>
![](https://codingthesmartway.com/wp-content/uploads/2017/12/01_CSS_Grid_Overview.png)
