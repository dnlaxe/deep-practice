# Front-End Deep Practice: 07-Star-Rating-Widget

## Features
- Interactive **star rating system** for quick visual feedback collection.  
- **Five-star layout**, dynamically highlighting based on user interaction.  
- Real-time **hover effect** previews user selection before committing.  
- **Click-to-rate** functionality stores and reflects the user’s selected rating.  
- Dynamic **textual output** below stars indicating selected rating numerically.  
- **Semantic styling** for hover and selected states using CSS classes.  
- Built-in **rating validation** ensures clarity between temporary and final selection.  

## Methods and Techniques Used
- **CSS Variables** (`--fg`, `--bg`, `--neon`) to define consistent color theming.  
- **CSS Transitions** (`transition: color 0.2s`) for smooth star highlight effects.  
- **DOM Selection** and **Event Handling** via `querySelectorAll` and `addEventListener`.  
- **Custom Hover and Selection Logic** through `mouseover`, `mouseout`, and `click` events.  
- **Dynamic Class Toggling** (`.hover`, `.selected`) for responsive visual feedback.  
- **Live Text Feedback** shown in `#rating-value` to confirm user rating choice.  
- **Conditional Pluralization** for proper grammar in star rating message.  
- Clear **separation of responsibilities**:  
  - HTML for structure (star elements and rating container)  
  - CSS for style and animation  
  - JavaScript for interaction logic and state management
