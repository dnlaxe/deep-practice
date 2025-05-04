# Front-End Deep Practice: 08-Tip-Calculator

## Features
- Functional **tip calculator** for computing gratuity based on bill amount and tip percentage.  
- Supports both **preset tip buttons** (10%, 15%, 20%) and **custom input** for flexibility.  
- Real-time **automatic calculation** as users type or select tip values.  
- **Dynamic result display** shows both **calculated tip** and **total bill** with precision.  
- **Input validation** prevents invalid or negative entries with clear error feedback.  
- Clean, **monospace UI** with modern spacing and layout.  
- Smooth UX with **live error handling** and reset logic when inputs are incomplete.  

## Methods and Techniques Used
- **CSS Variables** (`--fg`, `--bg`, `--neon`) to maintain consistent theme colors.  
- **Responsive Layout** using `.input-group` and `gap` for structured form inputs.  
- **Event Listeners** on `input` and `click` to trigger real-time calculation.  
- **Modular Functions** (`setTip`, `clearActiveButtons`, `calculateTip`) to keep logic organized.  
- **Input Validation** checks for non-numeric and negative values with clear user messaging.  
- **Dynamic DOM Manipulation** to update result and error elements based on user input.  
- **Graceful Error Handling** for incomplete or invalid input scenarios.  
- **Class Management** to toggle `.active` state on tip percentage buttons.  
- **Separation of Concerns**:  
  - HTML for structure (form fields, buttons, result areas)  
  - CSS for spacing, styling, and color themes  
  - JavaScript for behavior, interaction, and state control
