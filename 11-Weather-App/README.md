# Front-End Deep Practice: 11-Weather-App

## Features
- **Live weather lookup** based on either **user-entered city** or **automatic geolocation detection**.  
- **Autocomplete suggestions** powered by OpenWeather's **Geo API**, with intuitive keyboard and mouse navigation.  
- Displays **dynamic weather cards** with temperature, condition, and icon for each selected location.  
- Clean and accessible **input UI**, with a **touch-friendly**, responsive layout that works across devices.  
- **Multiple weather cards** can be added and removed independently using **in-card close buttons**.  
- Real-time **loading and error feedback** through a status message element.  
- Weather data includes **city name**, **temperature in Celsius**, **weather description**, and a **representative icon**.  
- Fully responsive design with **grid layout on wider screens** for optimal presentation of multiple weather cards.  
- **Keyboard navigation support** using Arrow Keys and Enter for fast and efficient city selection.  
- Styled using **pure CSS**, with **monospace UI** and consistent spacing for visual clarity.

## Methods and Techniques Used
- **Geolocation API** for automatic location detection on page load.  
- **OpenWeatherMap API** integration for both **weather data** and **geographic location suggestions**.  
- **Fetch API with async/await** for clean, modern asynchronous operations and error handling.  
- **Custom Autocomplete List** that responds to user input and highlights active selection via keyboard.  
- **Keyboard Accessibility** with full support for arrow navigation and enter key submission.  
- **Dynamic DOM Manipulation** to generate and remove weather cards on demand.  
- **Responsive Flex/Grid Layout** that adapts to screen size using media queries.  
- **Reusable Weather Card UI** with consistent styling and in-card dismissal button.  
- **CSS Variables** for consistent theming using `--fg` and `--bg`.  
- **Input Debounce Optimization (manual)** via query length check and fetch limit to reduce API calls.

> ⚠️ To use this app, you need your own OpenWeatherMap API key.  
> Get a free key at https://openweathermap.org/api and paste it into the `apiKey` variable in the HTML file.
