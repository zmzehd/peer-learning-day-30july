# peer-learning-day-30july
Task 1: Understanding Flexbox Basics
- What is flexbox?

    Flexbox, formally known as the CSS Flexible Box Layout module, is a one-dimensional layout model in CSS designed for arranging items within a container (the flex container) along a single axis, either as a row or as a column. 

- Why flexbox is better than others?

    Flexbox is better than traditional layout methods like floats or inline-block because it makes alignment, spacing, and responsiveness much easier and cleaner. It allows you to center elements both vertically and horizontally, control direction, reorder items without changing HTML, and automatically adjust layout based on screen size — all with less code and no hacks.

- challange: change float layout to flexbox layout
    solution on task 1 folder


Task 2: Aligning elements
- How to align elements horizontally and vertically  using Flexbox?

    To align elements using Flexbox:
        Main axis (horizontal by default): use justify-content
        Cross axis (vertical by default): use align-items

- challenge: Use Flexbox to align items
    solution on task 2 folder


Task 3: Flex Axes and Properties
- What is the difference between the main axis and the cross axis in Flexbox?

    In Flexbox, layout is controlled using two axes:
        Main Axis: The primary direction in which flex items are laid out.
            It depends on the flex-direction property.
            row (default) → main axis is horizontal
            column → main axis is vertical

        Cross Axis: The direction perpendicular to the main axis.
            If flex-direction: row, then cross axis is vertical
            If flex-direction: column, then cross axis is horizontal

- challange: Create a Card Layout with Flexbox
    solution on task 3 folder


Task 4: Flex Container vs. Flex Items
- What are the key properties that work on Flex Containers and Flex Items?

    🔸 Flex Container Properties:
These are applied to the parent element with display: flex:

    - flex-direction -> Defines the direction of the main axis (row, column, row-reverse, column-reverse).
    - justify-content -> Aligns items along the main axis (e.g., center, space-between, space-around).
    - align-items -> Aligns items along the cross axis (e.g., center, stretch, flex-start, flex-end).

🔸 Flex Item Properties
These are applied to child elements inside a flex container:

    - order -> Controls the order of the item in the layout (lower numbers come first).
    - flex -> Shorthand for flex-grow, flex-shrink, and flex-basis. Controls how the item grows or shrinks.
    - align-self -> Overrides align-items for a specific item on the cross axis.

- Challenge: Create a Flexbox Navigation Bar
     solution on task 4 folder


Task 5: Flexbox Shorthands
    The flex property is a shorthand for three separate properties:

flex: <flex-grow> <flex-shrink> <flex-basis>;
- Definitions:
flex-grow: How much the item grows relative to the rest

flex-shrink: How much the item shrinks relative to the rest

flex-basis: The initial size before growing/shrinking

Task 6: