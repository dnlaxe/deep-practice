# Front-End Deep Practice: 14-Simple-Blog

## Features  
- Fully interactive **in-browser blogging platform** with **localStorage persistence**.  
- Users can **create, edit, and delete** simple blog posts directly in the browser.  
- Posts support **multi-line content**, **timestamps**, and **custom tags**.  
- Real-time **character count** displayed while typing for user feedback.  
- Dynamic **tag-based filtering** lets users view posts by individual topics.  
- Responsive design with **clean typography**, **readable spacing**, and minimal layout.  
- All posts and tag states are **saved automatically to localStorage**, surviving page reloads.  
- Posts appear in **reverse chronological order** with the newest on top.  
- Supports **inline editing** with seamless UI switching between display and input modes.  
- Graceful UX with **input validation** and alerts for empty content.  

## Methods and Techniques Used  
- **Vanilla JavaScript** handles dynamic rendering, post management, filtering, and state logic.  
- **DOM Manipulation** for creating posts, filtering content, and updating tags dynamically.  
- **localStorage API** used to **persist posts and tags** without a backend.  
- **CSS Variables & Custom Properties** enable a consistent and maintainable color and spacing system.  
- **Inconsolata** and **Andika** web fonts deliver elegant monospace and readable headers.  
- **Responsive and minimal layout** using modern CSS techniques like **Flexbox** and **Grid-ready structure**.  
- **Form inputs and buttons** are styled for clarity and usability with hover effects.  
- Clean separation of concerns between **content, behavior, and structure**.  

## Key UX Enhancements  
- Real-time **character count** while typing blog content.  
- Dynamic **tag filter buttons** auto-generate based on post tags.  
- **All**, **Edit**, and **Delete** buttons provide a full CRUD experience.  
- Edits can be saved inline, updating both the DOM and localStorage.  
- Input validations ensure **title and content** are not left blank.