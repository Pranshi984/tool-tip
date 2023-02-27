# tool-tip
A tooltip is a common UI element that provides additional information or context when the user hovers over an element. In React, we can create a tooltip component that conditionally renders a tooltip when a user hovers over a button.

Approach:
To create a tooltip component, we can use React's useState hook to maintain a state variable that keeps track of whether the button is being hovered over. When the button is hovered over, we can render a tooltip component that displays additional information.

Here's a approach to create a simple tooltip component using React:

Create a new React component called Tooltip.
Add a text prop to the Tooltip component which specifies the text to be displayed in the tooltip.
Use useState hook to maintain a state variable showTooltip that is initially set to false.
Render a button element inside a container div element.
Add two event handlers to the button element to update the showTooltip state when the mouse enters or leaves the button.
Conditionally render a div element that displays the tooltip text when showTooltip is true.
By following these steps, we can create a simple tooltip component that shows a tooltip when a button is hovered over.
