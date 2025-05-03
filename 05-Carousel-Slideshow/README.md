# Front-End Deep Practice: 05-Carousel-Slideshow

## Features
- Horizontal **carousel slideshow** with scroll-based navigation and responsive layout.  
- Supports both **manual** and **autoplay** modes, toggled by a custom switch.  
- **Next** and **Previous** buttons allow direct navigation between slides.  
- **Dot indicators** dynamically reflect the current visible slide.  
- **Touch swipe support** for intuitive navigation on mobile devices.  
- Smooth scrolling animation when changing slides.  
- Circular behavior in autoplay: jumps back to the first slide after the last.  
- Responsive, modern design with flexible sizing and center alignment.  
- Uses `scroll-snap-type` and `scroll-behavior` for native-like slide alignment.  
- Minimal, clean aesthetic with subtle transitions and consistent typography.

## Methods and Techniques Used
- **CSS Scroll Snap** (`scroll-snap-type`, `scroll-snap-align`) for slide alignment on scroll.  
- **CSS Variables** (`--fg`, `--bg`, `--neon`) for flexible theming and consistent styling.  
- **JavaScript Scroll Manipulation** (`scrollBy`, `scrollTo`) for controlled slide navigation.  
- **Dot Indicators** synced with slide index using scroll position and `scrollLeft`.  
- **Autoplay Logic** using `setInterval` and conditional edge detection for looping behavior.  
- **Custom Toggle Switch** built with `<input type="checkbox">` and styled using pseudo-elements.  
- **Touch Event Handling** (`touchstart`, `touchend`) to detect swipe direction and trigger scroll.  
- **Separation of Concerns**: HTML for structure, CSS for layout/styling, JS for interactivity.  
- **Responsive Design**: Flexible widths and heights that adapt across devices.
