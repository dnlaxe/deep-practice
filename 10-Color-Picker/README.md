# Front-End Deep Practice: 10-Color-Picker

## Features
- Fully interactive **HSL color picker** with **live visual feedback** on a morphing animated blob.  
- Users can adjust **hue**, **saturation**, and **lightness** independently via custom **range sliders**.  
- Includes a **hidden native color picker** that synchronizes with HSL sliders when a color is chosen.  
- Dynamic updates to a large central **animated blob** that changes color, shape, and rotation continuously.  
- Displays current color value in **HSL format** in real time beneath the blob.  
- **Responsive layout** with a focus on simplicity, accessibility, and touch-friendly controls.  
- Designed with a **monospace UI**, consistent spacing, and adaptable layout for all screen sizes.  
- **Blob animation** created using CSS keyframes with **fluid morphing and spinning transitions**.

## Methods and Techniques Used
- **CSS Variables** (`--fg`, `--bg`) manage global theming for color consistency and easy customization.  
- **Range Input Styling** for custom thumb and track appearance without relying on third-party libraries.  
- **Responsive Flexbox Layout** vertically centers and distributes header, main, and footer elements cleanly.  
- **CSS Keyframe Animation** enables continuous morphing and rotating of the blob with smooth scaling.  
- **Event Listeners** on each slider provide real-time updates to the blob and HSL value display.  
- **HSL to RGB Conversion Logic** parses color input from native picker and syncs it with slider values.  
- **Hex to RGB Utility** extracts RGB components from a hex color for further HSL calculation.  
- **Click-to-Open Color Picker** makes the blob interactive and enhances user experience with native controls.  
- **Clean JavaScript Architecture** with modular functions for readability, clarity, and reusability.
