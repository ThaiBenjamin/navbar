# Responsive Navbar

A CSS practice project: a navigation bar built with Flexbox and media queries that goes
from a horizontal desktop layout to a stacked mobile one, with no framework involved.

The layout is the one most real sites use — logo on the left, links in the middle, action
button on the right — which is what made it worth building rather than inventing something
arbitrary.

## What I took from it

Before this I was mostly guessing at Flexbox properties and nudging values until things
looked right. Building a navbar forced me to understand why each one does what it does.
`justify-content: space-between` puts the logo on the left and the links on the right
because it pushes children to opposite ends of the main axis — not because it's the
property that happened to work.

Media queries taught me to think in breakpoints rather than in screen sizes. Once the
viewport gets narrow enough that horizontal items stop fitting, collapsing them into a
column is a few lines, and the interesting decision is picking where that point is.

Between them, Flexbox and media queries cover most of what responsive layout actually
requires.
