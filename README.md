## What is Flexbox
A CSS3 layout mode that provides an easy and clean way to arrange items within a container

- No Flots!
- Responsive and mobile friendly
- Positioning child elements is MUCH easier
- Flex container's margins do not collapse with the margins of its contents.
- Order of elements can easily be changed without editing the source HTML

### Flexible Box Model Concept
- The ability to alter item width and height to best fit its containers available free space
- Flexbox is direction-agnostic
- Built for small-scale layouts while the upcoming "Grid" specification is for more large scale

#### Flex Properties
- display: flex | inline-flex
- align-content: flex-start | flex-end | center
- align-items: flex-start | flex-end | center
- align-self: flex-start | flex-end | center
- flex: <integer>
- flex-basis: <length>
- flex-direction:  row | column
- flex-flow: The flex-flow CSS property is a shorthand property for flex-direction and flex-wrap individual properties.
/* flex-flow: <'flex-direction'> */
flex-flow: row;
flex-flow: row-reverse;
flex-flow: column;
flex-flow: column-reverse;

/* flex-flow: <'flex-wrap'> */
flex-flow: nowrap;
flex-flow: wrap;
flex-flow: wrap-reverse;

/* flex-flow: <'flex-direction'> and <'flex-wrap'> */
flex-flow: row nowrap;
flex-flow: column wrap;
flex-flow: column-reverse wrap-reverse;

/* Global values */
flex-flow: inherit;
flex-flow: initial;
flex-flow: unset;
- flex-grow: <number>
- flex-shrink: <number>
- flex-wrap: wrap | nowarp | wrapreverse
- justify-content: flex-start | flex-end | center
- order: <integer>
