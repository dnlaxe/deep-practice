# Front-End Deep Practice: 01-Modal

# Features

- Open a modal window by clicking a button.
- Center the modal dynamically in the viewport when opened.
- Drag the modal around the screen by its header.
- Close the modal with a close (×) button.
- Fill out a form inside the modal (Name and Email fields).
- Submit the form without reloading the page.
- Create a new info card displaying the entered Name and Email.
- Dynamically add multiple info cards to the page.
- Remove individual info cards by clicking their close (×) button.
- Reset the form and hide the modal after submission.
- Smooth button press animation using CSS.
- Custom styling using CSS variables (`--fg`, `--bg`).

# Methods and Techniques Used

- **Flexbox** for layout alignment (e.g., form content, card layout).
- **CSS Grid** for overall page layout (left panel + right panel).
- **CSS Variables** (`--fg`, `--bg`) for easy theme and color management.
- **Absolute Positioning** for placing and dragging the modal window.
- **Event Listeners** in JavaScript:
  - `click` (for opening/closing modal, submitting form, closing cards)
  - `mousedown`, `mousemove`, `mouseup` (for dragging functionality)
- **DOM Manipulation** in JavaScript (creating and removing elements dynamically).
- **Form Handling** with JavaScript (`submit` event with `preventDefault()`).
- **Dynamic Centering** of the modal based on viewport size.
- **Button Interaction Effects** using `box-shadow` and `transform` on `:active`.
- **Responsive Design Techniques** (e.g., dynamic calculations using `window.innerWidth` and `window.innerHeight`).
- **User Input Validation** (simple check to prevent empty submissions).
- **Custom Cursor and User-Select Control** (for better drag experience).
