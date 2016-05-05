#### CSS Quiz
1. Which of the following are block elements?
  * a
  * p
  * ul
  * ol
  * li
  * th
  * tr
  * td
  * div
  * span
  * input
  * label
  * img
  * button
  * fieldset

2. What is the term for the other elements?

3.  Which of the following can be applied to an inline element?
  ```
  position: relative;
  background-color: red;
  height: 30 px;
  display: block;
  ```
4. Given the following example:

  ```
  <div>
    <p>
    <ul>
      <li><a></a></li>
      <li><li>
    </ul>
    <ol>
    </ol>
  </div>
  ```
  * which element is the *parent* of the ul element?

  * which element(s) are the *siblings* of the ul element?

  * which element(s) are the *children* of the ul element?

5.  What items will be selected by each of the following?  Also, describe the practical difference between each item and the one above it.

  ```
  p
  .navigation
  #navigation
  p.navigation
  p>.navigation
  p .navigation
  ```

6. Order the above in terms of specificity weighting.

7.  Given the following HTML and CSS samples, answer the following questions:

  ```
  <div>
    <p class="sample" id="first"></p>
    <p>class="sample" id="second"</p>
    <p id="last"></p>
  </div>
  ```

  ```
  p#first {
    color: green
  }
  #first {
    color: red
  }
  #second {
    color: purple
  }
  p {
    color: blue
  }
  .sample {
    color: pink
  }
  ```

  * what color is the first p element?

  * what color is the second p element?

  * what color is the third p element?

8. If you have the following, what's the practical result of giving the p and ul elements a position of `float: left` and `width: 200px`?
f
  *  what would happen if you didn't specify the width of the p and ul elements?

  * what would it look like if the total screen width was 300px?

  * if you had a background color on the div element, would the background color show up around the full height of it's child elements?  Why or why not?  If not, how can you address this?

9.  What display type is demonstrated in each of the following:
  ![image}](/images/display_quiz.png)

10. When you specify `position: relative` - the element will be positioned relative to what?  Does it remain in the normal flow?  

11. What else do you need to specify for a relative position to have any effect?

12. What position would you use if you wanted to have a sidebar element showing no matter where the user is currently position on the page?

12. Will an absolute positioned element always be visible to the user, no matter where the user is on the page?  

13.  Given the following, what element will the p position be absolutely positioned relative to?  What does this look like?  

  ```
  <body>
  <div id ="absContainer">
    <p id ="abs"></p>
  </div>
  </body>
  ```

  ```
  #absContainer {
    position: relative;
    top: 100px
  }

  #abs {
    position: absolute;
    top: 100px
  }
  ```
14.  Would anything change  above if the div element was not given a position?  

15. Give an example of a situation where you may want to give something an absolute position.  Why is it necessary?  Do the same for relative and float.

16.  Which of the following takes the element out of normal flow?
  ```
  position: static
  position: relative
  position: absolute
  position: float
  ```

17.  If you float the ul element left in the example below, what element will it float next to (assume available width).  Why?
  ```
  <body>
    <div>
      <p>
      <ul>
        <li></li>
        <li><li>
      </ul>
    </div>
  </body>
  ```
18.  Where would the ul element be positioned if there was not available width?

20.  If you didn't give the p and ul elements a width, what would happen if you gave the ul element a floated position? Why?

21.  Given the following, what is the font size of the li element?

  ```
  <body>
    <ul>
      <li></li>
    </ul>
  </body>

  ```
  ```
  body {
    font-size: 20px;
    color: red;
    padding: 10px;
  }
  ul {
    font-size: 80%
  }
  li {
    font-size: 75%
  }
  ```
22.  If you want the li element above to be in red font, do you need to add a color to the li element above?  Why or why not?  Will the li element have padding?  Why or why not?

23.  Label each part of the block element box below:
  ![Image](/images/box_quiz.png)

24. If you want white space between two block elements, what attribute do you need to set?

25.	If you want to center text within a block vertically, what attribute do you need to set?

26.	How much total width will the div block below take up?

  ```
  body {
    width: 200px;
    border-weight: 2px;
    padding: 10px;
    margin: 10px, 0px;
  }
  ```
