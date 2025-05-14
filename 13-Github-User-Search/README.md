# Front-End Deep Practice: 13-Github-User-Search

## Features
- Fully interactive **GitHub user search tool** using **real-time data from GitHub's public API**.  
- Users can enter any GitHub username and fetch a concise **public profile overview**.  
- Auto-displays **profile image, bio, public repos, follower/following counts**, and a **link to the user’s GitHub page**.  
- Includes a custom **animated loader** inside a stylized circular avatar frame while fetching data.  
- **Error handling** covers invalid input, empty fields, and GitHub API errors (like user not found).  
- Automatically triggers search on pressing the **Enter** key for seamless UX.  
- Uses a **minimal, centered layout** with clean typography, monospace styling, and smooth layout spacing.  
- Fully **responsive and touch-friendly**, built with **CSS Flexbox and Grid** for structured layout.  
- Loader delay ensures consistent **user feedback timing**, even on fast networks.  

## Methods and Techniques Used
- **Fetch API** to retrieve live user data from [GitHub Users API](https://api.github.com/users/).  
- **Dynamic DOM Manipulation** to populate the UI with live profile content and handle loaders/states.  
- **CSS Keyframe Animation** powers the **rotating loader effect** inside a circular frame.  
- **Input validation** and user-friendly **error messaging** ensure smooth usability.  
- **Responsive Layout** using Flexbox and Grid for modern layout adaptability.  
- **CSS Hover Effects** enhance interactivity on the **search button**.  
- Graceful handling for:
  - **Empty input**
  - **Invalid usernames**
  - **404 errors**
  - **API failures**

## API Used
- 🐙 [GitHub Users API](https://api.github.com/users/)
