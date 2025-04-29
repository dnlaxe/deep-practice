# Front-End Deep Practice: 02-Responsive-Navbar  

# Features  
- Display a horizontal navigation menu on large screens.  
- Hide the desktop navigation and show a hamburger menu on smaller screens (≤768px).  
- Open a full-screen modal navigation by clicking the hamburger icon.  
- Animate the hamburger icon into a cross (×) when active.  
- Smoothly animate the modal sliding in from the top.  
- Clicking a navigation link inside the modal closes the modal and resets the hamburger icon.  
- Use a clean and simple responsive design that adapts to different screen sizes.  
- Smooth animations for hamburger transformation and modal appearance.  
- Customizable colors using CSS variables (`--fg`, `--bg`).  

# Methods and Techniques Used  
- **Flexbox** for horizontal and vertical alignment (e.g., navbar, modal links).  
- **CSS Variables** (`--fg`, `--bg`) for easy theming and color management.  
- **Media Queries** for responsive behavior (hiding/showing elements based on screen size).  
- **CSS Transitions** for smooth animations on hamburger and modal.  
- **Absolute and Fixed Positioning** for modal layout and fullscreen cover.  
- **Event Listeners** in JavaScript:  
  - `click` (for toggling modal and hamburger active state).  
- **DOM Manipulation** in JavaScript (toggling classes dynamically).  
- **Responsive Design Techniques** (using media queries and viewport dimensions).  
- **Custom Hamburger Animation** (rotating and translating bars smoothly).  
- **User Experience Enhancements** (closing modal when clicking a link).  
