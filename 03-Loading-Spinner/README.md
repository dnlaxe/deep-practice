# Front-End Deep Practice: 03-Loading-Spinner  

## Features  
- Display three unique loading animations: a spinning ring, a loading bar with centered text, and bouncing dots.  
- Smooth infinite animations to visually indicate loading state.  
- Center all loaders vertically and horizontally within the viewport.  
- Clean, minimal responsive design with flexible layout.  
- Support theming with CSS variables (`--fg`, `--bg`, `--neon`).  
- Spinner uses layered circular borders to create a rotating effect.  
- Loading bar fills from left to right using animated pseudo-element.  
- Bouncing dots animate in a staggered sequence.  
- All animations run purely with HTML and CSS (no JavaScript needed).  
- Seamless integration into different layouts and screen sizes.  

## Methods and Techniques Used  
- **Flexbox** for layout alignment, spacing, and centering within the container.  
- **CSS Variables** (`--fg`, `--bg`, `--neon`) for easy theming and color management.  
- **Keyframe Animations** in CSS for spinning, bouncing, and loading effects.  
- **CSS Pseudo-elements** for animated bar fill without extra HTML markup.  
- **Absolute Positioning** for layering spinner elements and centering loading text.  
- **Animation Delay** for staggered bouncing dot animation.  
- **Responsive Design Techniques** using `flex-wrap` and scalable `vh` layout. 
