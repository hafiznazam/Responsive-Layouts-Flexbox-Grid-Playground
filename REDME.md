# Responsive Layouts — Flexbox & Grid Playground

## Project Description

This project demonstrates the same three-column pricing layout using two different CSS layout systems: Flexbox and CSS Grid.

Both versions include:

* Header
* Three pricing cards
* Footer
* Responsive design
* Single-column layout below 600px

## Flexbox vs Grid

### Flexbox

Flexbox was easier for arranging the pricing cards in a single row. Using `display: flex` and `flex: 1` made it simple to give each card equal space. Changing the direction to `column` inside the media query also made the mobile layout straightforward.

### CSS Grid

Grid was easier for creating the three-column structure because `grid-template-columns: repeat(3, 1fr)` directly defines three equal columns. The responsive layout was also simple by changing the columns to `1fr` below 600px.

### What I Learned

Flexbox is useful for one-dimensional layouts, such as arranging items in a row or column. CSS Grid is more suitable for two-dimensional layouts where rows and columns need to be controlled.

For this pricing layout, both methods work well. Flexbox felt slightly more natural for arranging the cards, while Grid made the column structure more explicit and easier to control.
