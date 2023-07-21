# Udemy CSS Grid Course - Exercise Sheet 1

Exercise Sheet 1 for Udemy's [Ultimate CSS Grid Course](https://anniecannons.udemy.com/course/css-grid/).

### Setup

Fork and clone this repo. You will be submitting the link to your Pull Request when you turn it in on Canvas. Please see Canvas for more information on submitting by Pull Request.

### Instructions

##### Exercise 1

1. Review the HTML file to get familiar with its code. We don't have to change the HTML, **unless your solution involves adding classes**.
2. Connect the CSS file to the HTML file with a `link` tag in the `head`. Pay careful attention to the path to the CSS file!
3. Open the CSS file.
4. Recreate the grid below, making the four divs into grid items using what you've learned in this section of the course.

![Exercise 1 Goal](goal-1.png)

##### Exercise 2

1. Review the HTML file to get familiar with its code. We don't have to change the HTML, **unless your solution involves adding classes**.
2. If you didn't do this already for Exercise 1, connect the CSS file to the HTML file with a `link` tag in the `head`. Pay careful attention to the path to the CSS file!
3. Open the CSS file.
4. Arrange the grid items as in the grid below. Pay attention to their order within the grid!

![Exercise 2 Goal](goal-2.png)

### Hints

- Don't forget that no item will be arranged in a grid unless its **parent** (commonly called a grid container) has `display: grid`.
- Pay attention to which properties are set on grid items and which on the grid container.
- If you haven’t already, make use of the `span` values for `grid-column-start` and `grid-column-end` (and the matching row properties) 
- Don't forget you can use `grid-row` as a shorthand property for `grid-row-start` and `grid-row-end` (and the same for columns).
- Use `grid-template-rows` and `grid-template-columns` to define the structure of the grid.
- You can use `grid-gap` to add spacing between all rows and columns.
- For Exercise 2, remember that the `order` property can change the order of the items, **no matter what their original order** is in the HTML.

### Resources

CSS Tricks' excellent [Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/) is an enormous help.
