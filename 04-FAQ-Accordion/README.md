# Front-End Deep Practice: 04-FAQ-accordion  

## Features  
- Interactive accordion interface to display FAQ content in a collapsible format.  
- Clicking a question expands the corresponding answer panel while updating ARIA attributes.  
- Smooth panel animation using CSS `max-height` transition.  
- Visual indicator arrow rotates to reflect expanded/collapsed state.  
- Fully accessible markup using WAI-ARIA roles and attributes (`aria-expanded`, `aria-controls`, `aria-hidden`).  
- Clean and minimal design with clear contrast between questions and answers.  
- Centralized layout with fixed width and responsive margins.  
- Each FAQ item is independently expandable.  
- Uses semantic HTML for clarity and screen reader support.  
- JavaScript handles state toggling and dynamic style changes.  

## Methods and Techniques Used  
- **Flexbox** for aligning button content and arrow indicator.  
- **CSS Variables** (`--fg`, `--bg`, `--neon`) for easy color customization.  
- **ARIA Attributes** (`aria-expanded`, `aria-controls`, `aria-hidden`, `aria-labelledby`) for accessibility compliance.  
- **JavaScript Event Listeners** for toggle functionality and DOM updates.  
- **CSS Transitions** for animating `max-height` during panel open/close.  
- **Pseudo-elements and Borders** to create a rotating arrow icon.  
- **Progressive Enhancement**: base functionality works with HTML/CSS; interactivity added via JS.  
- **Dynamic Style Adjustments** using `scrollHeight` to smoothly expand panels.  
- **Separation of Concerns**: HTML for structure, CSS for styling/animation, JS for behavior.  
