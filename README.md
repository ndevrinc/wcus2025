# Presentation App

A simple, clean presentation viewer for your Keynote slides exported as images.

## Features

- **Clean Design**: No wrapper styling - your slides are displayed exactly as exported from Keynote
- **Keyboard Navigation**: Use arrow keys (← →) or spacebar to navigate
- **Mobile Support**: Swipe left/right on mobile devices
- **Fullscreen Mode**: Press 'F' or click the fullscreen button
- **Slide Counter**: Shows current slide position (e.g., "5 / 33")
- **Responsive**: Works on all screen sizes while maintaining 16:9 aspect ratio

## Navigation

- **Next Slide**: Right arrow (→) or Spacebar
- **Previous Slide**: Left arrow (←)
- **Fullscreen**: Press 'F' or click the fullscreen button
- **Mobile**: Swipe left/right

## Deployment Options

### Option 1: GitHub Pages (Free)
1. Create a new GitHub repository
2. Upload all files (including the `images` folder)
3. Go to Settings → Pages
4. Select "Deploy from a branch" and choose "main"
5. Your presentation will be available at `https://yourusername.github.io/repository-name`

### Option 2: Netlify (Free)
1. Go to [netlify.com](https://netlify.com)
2. Drag and drop your entire folder
3. Your presentation will be live instantly with a random URL
4. You can customize the URL in the site settings

### Option 3: Vercel (Free)
1. Go to [vercel.com](https://vercel.com)
2. Import your GitHub repository or upload files
3. Deploy with one click
4. Get a custom URL instantly

### Option 4: Any Web Server
Simply upload the files to any web hosting service that supports static files.

## File Structure

```
presentation/
├── index.html          # Main presentation file
├── images/             # Your slide images
│   ├── The_3E_Framework_Building_Resilient_Publishing_Platformsreduced.001.jpeg
│   ├── The_3E_Framework_Building_Resilient_Publishing_Platformsreduced.002.jpeg
│   └── ... (all 33 slides)
└── README.md           # This file
```

## Customization

The app is designed to be minimal and clean. If you need to customize:

- **Change title**: Edit the `<title>` tag in `index.html`
- **Modify navigation**: Edit the JavaScript in the `<script>` section
- **Adjust styling**: Modify the CSS in the `<style>` section

## Browser Compatibility

Works on all modern browsers:
- Chrome, Firefox, Safari, Edge
- Mobile browsers (iOS Safari, Chrome Mobile)
- Fullscreen mode supported on desktop browsers
