# ExpandImages_InSimpleWay

# The Main goal is to Understand The Logic How it is working.
# Open project code one side and this readme another side to better understand what I'm trying to say.
Check out Demo: https://simplifiedweb.github.io/ExpandImages_InSimpleWay/

CSS Play:

The primary technique you're using here is CSS, specifically the :hover selector.

Steps:

Image Expansion on Hover:

You're using the :hover selector to target the image element.
On hover, you're adjusting the width of the image. This gives the visual effect of the image expanding when hovered over.

Text Appearance:

You're hiding the text within the image initially.

To reveal the text, you're using the position: absolute property for the text container.

The text container's positioning is adjusted based on the positioning of the image's container (which should have position: relative).

This allows the text to appear outside the image container when the image expands.

Transition:

To make the expansion smooth, you're using the transition property in CSS. This adds a gradual animation effect when the image's width changes on hover.
In summary, you're using CSS to create an engaging interaction:

Hovering over the image expands it smoothly.

As the image expands, hidden text is revealed outside the image container.

This is achieved through a combination of :hover, adjusting widths, absolute positioning, and transitions.

Hope This explantion helps you.
