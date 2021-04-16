# Transforms

transform property comes in two different settings, two-dimensional and three-dimensional. Each of these come with their own individual properties and values.
<br><br>
## 2D Transforms
- 2D Rotate

The rotate value provides the ability to rotate an element from 0 to 360 degrees. Using a positive value will rotate an element clockwise, and using a negative value will rotate the element counterclockwise. The default point of rotation is the center of the element, 50% 50%, both horizontally and vertically. Later we will discuss how you can change this default point of rotation.<br><br>
<br><br>
### HTML
\<figure class="box-1">Box 1\</figure> <br>
\<figure class="box-2">Box 2\</figure> <br>
<br><br>
### CSS
.box-1 {<br>
  transform: rotate(20deg);<br>
}<br>
.box-2 {<br>
  transform: rotate(-55deg);<br>
}

<figure style=" transform: rotate(20deg);background: #2db34a;
  height: 95px;
  line-height: 95px;
  text-align: center;
  width: 95px;" >Box 1</figure>
<br><br>
<figure style="transform: rotate(-55deg);background: #2db34a;
  height: 95px;
  line-height: 95px;
  text-align: center;
  width: 95px;">Box 2</figure>



<br><br>
- 2D Scale

<br><br>
### HTML
\<figure class="box-1">Box 1\</figure> <br>
\<figure class="box-2">Box 2\</figure> <br>
<br><br>
### CSS
.box-1 {<br>
  transform: scale(.75);<br>
}<br>
.box-2 {<br>
  transform: scale(1.25);<br>
}
<br><br>

<figure style=" transform: scale(.75);background: #2db34a;
  height: 95px;
  line-height: 95px;
  text-align: center;
  width: 95px;" >Box 1</figure>
<br><br>
<figure style="transform: scale(1.25);background: #2db34a;
  height: 95px;
  line-height: 95px;
  text-align: center;
  width: 95px;">Box 2</figure>



<br><br>
- 2D Translate
- 2D Skew
> for more info [visit](https://learn.shayhowe.com/advanced-html-css/css-transforms/)

<br><br>
# Transitions & Animations

## Transitions
As mentioned, for a transition to take place, an element must have a change in state, and different styles must be identified for each state. The easiest way for determining styles for different states is by using the :hover, :focus, :active, and :target pseudo-classes.

There are four transition related properties in total, including transition-property, transition-duration, transition-timing-function, and transition-delay. Not all of these are required to build a transition, with the first three are the most popular.

## Animations
Transitions do a great job of building out visual interactions from one state to another, and are perfect for these kinds of single state changes. However, when more control is required, transitions need to have multiple states. In return, this is where animations pick up where transitions leave off.


## 8 SIMPLE CSS3 TRANSITIONS THAT WILL WOW YOUR USERS
CSS3 has introduced countless possibilities for UX designers, and the best thing about them is that the coolest parts are really simple to implement.

Just a couple of lines of code will give you an awesome transition effect that will excite your users, increase engagement and ultimately, when used well, increase your conversions. What’s more, these effects are hardware accelerated, and a progressive enhancement that you can use right now. [visit](https://www.webdesignerdepot.com/2014/05/8-simple-css3-transitions-that-will-wow-your-users)



