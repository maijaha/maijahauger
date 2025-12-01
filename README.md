# Maija Hauger Portfolio Website

A beautiful, minimalist portfolio website showcasing Maija Hauger's design work with smooth page transitions and elegant navigation.

## Features

- **Smooth Page Transitions**: Elegant fade-in/fade-out animations between pages
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Interactive Elements**: Hover effects and smooth animations
- **Project Showcase**: Interactive project cycling with smooth transitions
- **Default Landing Page**: `index.html` serves as the main entry point

## File Structure

```
/
├── index.html          # Main landing page (default)
├── projects.html       # Projects showcase page
├── main.css           # Styles for the main page
├── project.css        # Styles for the projects page
├── images/            # Portfolio images
├── server.js          # Local development server
├── package.json       # Node.js dependencies
├── .htaccess          # Apache server configuration
└── README.md          # This file
```

## Getting Started

### Option 1: Simple Local Server (Recommended)

1. Install Node.js dependencies:
   ```bash
   npm install
   ```

2. Start the local development server:
   ```bash
   npm start
   ```

3. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

### Option 2: Direct File Access

Simply open `index.html` in your web browser. The website will work, but some features may be limited due to browser security restrictions.

### Option 3: Apache Server

If you're using an Apache server, the `.htaccess` file will automatically:
- Set `index.html` as the default landing page
- Enable compression for better performance
- Add security headers

## Navigation

- **Home Page** (`index.html`): Click on the card to navigate to projects
- **Projects Page** (`projects.html`): Click "Home" to return to the main page
- **Project Cycling**: Click anywhere on the projects page to cycle through different projects

## Smooth Transitions

The website features several types of smooth transitions:

1. **Page Load**: Fade-in animation when pages load
2. **Page Navigation**: Fade-out before redirecting to the next page
3. **Project Cycling**: Smooth transitions between different projects
4. **Hover Effects**: Subtle scaling and shadow effects on interactive elements

## Browser Compatibility

The website is designed to work on modern browsers that support:
- CSS3 transitions and transforms
- ES6 JavaScript features
- Modern CSS Grid and Flexbox

## Customization

- **Colors**: Modify the CSS variables in the stylesheets
- **Animations**: Adjust transition timing in the CSS files
- **Content**: Update the HTML files with your own content
- **Images**: Replace images in the `images/` folder

## Performance

The website is optimized for performance with:
- Compressed assets
- Efficient CSS animations
- Optimized image loading
- Minimal JavaScript footprint

## License

This project is licensed under the MIT License.












