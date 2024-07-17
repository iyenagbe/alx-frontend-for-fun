# Flexbox

`HTML`, `CSS`

- What is Flexbox?
- How to convert float positioning to a flex display
- How to horizontally and vertically align elements using Flexbox
- The difference between the main and cross axes
- Properties that work on flex elements vs flex container
- Shorthands for flex
- How to create a new page with flex in mind

Flexbox, or the Flexible Box Layout Module, is a CSS3 web layout model designed to provide a more efficient way to lay out, align, and distribute space among items in a container, even when their size is unknown or dynamic. It is particularly useful for creating complex layouts with minimal code and for making responsive design easier to implement.

Key Concepts of Flexbox:
Flex Container:

The parent element that contains flex items. It is defined by setting the display property to flex or inline-flex.
Flex Items:

The child elements within a flex container. These items can be laid out and aligned using various flex properties.
Main Axis and Cross Axis:
Main Axis:
The primary axis along which flex items are laid out. It can be horizontal (default) or vertical, depending on the flex-direction property.
Cross Axis:
The axis perpendicular to the main axis. If the main axis is horizontal, the cross axis is vertical, and vice versa.
Key Properties of Flexbox:
On the Flex Container:
display

Defines a flex container; inline or block-level. Values: flex, inline-flex.
flex-direction

Defines the direction of the main axis. Values: row, row-reverse, column, column-reverse.
flex-wrap

Controls whether flex items are forced into a single line or can wrap onto multiple lines. Values: nowrap, wrap, wrap-reverse.
justify-content

Aligns flex items along the main axis. Values: flex-start, flex-end, center, space-between, space-around, space-evenly.
align-items

Aligns flex items along the cross axis. Values: flex-start, flex-end, center, baseline, stretch.
align-content

Aligns flex lines within the flex container when there is extra space on the cross axis. Values: flex-start, flex-end, center, space-between, space-around, stretch.
On the Flex Items:
order

Controls the order in which flex items appear in the flex container.
flex-grow

Defines how much a flex item will grow relative to the other items in the flex container.
flex-shrink

Defines how much a flex item will shrink relative to the other items in the flex container.
flex-basis

Defines the default size of an element before the remaining space is distributed.
flex

A shorthand property for flex-grow, flex-shrink, and flex-basis.
align-self

Allows the default alignment (or the one specified by align-items) to be overridden for individual flex items.
