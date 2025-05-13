# Front-End Deep Practice: 12-Currency-Converter

## Features
- Fully interactive **currency converter** using live **exchange rates from Frankfurter API**.  
- Users can select both **source** and **target currencies** from dropdowns auto-populated with country codes.  
- Converts user-entered amounts with a single click using a **stylized currency exchange button**.  
- Includes an animated **loader** while waiting for conversion results to fetch.  
- Real-time feedback displays either the **converted amount** or a helpful **error message**.  
- Automatically **pre-selects USD to EUR** for immediate usability.  
- Uses a **visually centered, minimal UI** layout with a **background image** and **3D-styled form elements**.  
- Fully **responsive and touch-friendly**, designed for clarity and ease of use across devices.  
- Conversion logic includes fallback behavior for **same-currency conversions** and **invalid input checks**.  

## Methods and Techniques Used
- **Fetch API** to retrieve currency lists and perform real-time conversion using the [Frankfurter API](https://www.frankfurter.app/).  
- **Dynamic DOM Manipulation** to populate `<select>` dropdowns from API response data.  
- **CSS Keyframe Animation** used to create a custom **loader effect** while data is being fetched.  
- **HTML5 Form Validation** ensures amount input is present and positive before triggering conversion.  
- **Responsive Centered Layout** using Flexbox for vertical and horizontal centering.  
- **CSS Box Shadow Effects** add depth and polish to inputs and dropdowns.  
- **Material Icons** integrated via Google Fonts to enhance the **conversion button** with a rotating animation on hover.  
- **Graceful Fallback Handling** for invalid input, identical currency selections, and API errors.

## API Used
- 🌐 [Frankfurter API](https://www.frankfurter.app/)