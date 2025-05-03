# Front-End Deep Practice: 06-Notification-Toast

## Features
- Lightweight, animated **toast notification system** for dynamic user feedback.  
- Three types of toasts: **Success**, **Error**, and **Info**, each with distinct colors.  
- **Input-based message** entry enables custom toast content at runtime.  
- **Single-click buttons** to trigger toasts based on category.  
- Toasts automatically **fade in and out** with smooth animation.  
- Supports **stacked notifications**, displayed in order with spacing.  
- **Auto-dismiss** after 4 seconds, no manual closing required.  
- **Responsive design**: fixed positioning and scaling for consistent display across devices.  
- Clean, minimalist interface with monospace typography and modern color scheme.  
- Uses high **z-index layering** to ensure toasts float above all UI content.

## Methods and Techniques Used
- **CSS Keyframe Animation** (`@keyframes fadeInOut`) for smooth toast transitions.  
- **CSS Variables** (`--fg`, `--bg`, `--neon`) for unified theming and style control.  
- **DOM Manipulation** with JavaScript to create and inject toast elements.  
- **Event Listeners** (`addEventListener`) to trigger different toast types via button clicks.  
- **Dynamic Element Lifecycle**: create toast, display, animate, and auto-remove via `setTimeout`.  
- **Class-Based Styling** (`.success`, `.error`, `.info`) for semantic toast visuals.  
- **Responsive Container** (`#toast-container`) with flexible `flex-direction: column` layout.  
- **Input Handling** and validation to ignore empty messages and reset field post-toast.  
- **Separation of Concerns**: HTML for structure, CSS for style, JavaScript for logic.
