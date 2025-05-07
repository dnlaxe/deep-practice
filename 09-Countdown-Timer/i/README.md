# Front-End Deep Practice: 09-Countdown-Timer-i

## Features
- Interactive **countdown timer** that calculates time remaining until a **user-specified date and time**.  
- **Real-time live countdown** updates every second once a valid future time is submitted.  
- Built-in **loading animation** (bouncing dots) displays briefly before the countdown begins.  
- **Validation logic** ensures that the selected time is in the future, with **user feedback** for past values.  
- **Dynamic time display** shows remaining **days, hours, minutes, and seconds** in large monospace font.  
- Automatically **resets countdown** when a new valid time is submitted.  
- **Responsive layout** supports different screen sizes with centered vertical and horizontal alignment.  

## Methods and Techniques Used
- **CSS Variables** (`--fg`, `--bg`) used to define and maintain color themes throughout the UI.  
- **Responsive Flexbox Layout** for full-screen vertical centering and flexible input arrangement.  
- **HTML5 Input Types** (`date`, `time`, `submit`) for native date/time pickers and accessibility.  
- **Event Listener on Form Submission** to handle input, validate data, and initiate countdown logic.  
- **JavaScript Date API** for precise time difference calculation and formatting.  
- **setInterval and clearInterval** for managing the timer update loop with clean resets.  
- **Graceful Loading Animation** using CSS keyframes for a brief visual delay before countdown display.  
- **Dynamic DOM Updates** using `innerHTML` to switch between message states, loader, and timer.  
- **Form Input Constraints** with minimum date set to today using dynamic `min` attribute.  
- **Reusable Utility Function** `pad()` to format time values with leading zeros.  
