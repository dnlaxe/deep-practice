# Front-End Deep Practice: 09-Countdown-Timer-ii

## Features
- Fully interactive **countdown timer** that lets users manually select **year, month, day, hour, and minute**.  
- Provides a **live countdown** to the target date and time, updating every second.  
- **Drop-down input selectors** for all date and time parts with dynamic validation and intelligent defaults.  
- Automatically adjusts the **day selector** based on selected month and year (including leap years).  
- Displays remaining time in a **large-format UI** broken down into **days, hours, minutes, and seconds**.  
- **Immediate feedback** if the selected time is in the past, encouraging valid future input.  
- Modern **monospace design** with minimalist theme and clean layout using flexbox.  
- **Auto-resets timer** whenever a new valid time is selected.  

## Methods and Techniques Used
- **CSS Variables** (`--fg`, `--bg`) to define and manage consistent color theming across all UI components.  
- **Responsive Flex Layout** for vertical centering and scalable form arrangement.  
- **Dynamic DOM Manipulation** for populating select elements and updating countdown in real time.  
- **Date Calculations** using JavaScript's `Date` API to compute time differences precisely.  
- **Event Listeners** on each dropdown to update the countdown immediately as user makes selections.  
- **Leap Year and Month Logic** to dynamically calculate the number of days in the selected month/year.  
- **Reusable Utility Function** `pad()` ensures all time units are zero-padded for uniformity.  
- **Error Handling** gracefully shows user feedback when a past time is selected or inputs are incomplete.  
- **SetInterval and ClearInterval** logic ensures only one timer runs at any time with proper cleanup.
