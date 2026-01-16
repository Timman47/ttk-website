# Toy Time King Website

Official website for the Toy Time King YouTube channel - Competitive Pokemon content since 2017.

## About

This website serves as the online home for Toy Time King, a YouTube channel dedicated to competitive Pokemon battles, strategies, and tournament coverage. The site provides information about the channel and links to the latest content.

## Features

- Clean, modern homepage with green and black color scheme
- Three-section layout: Hero, Featured Videos, and About
- Horizontal scrolling video carousel with navigation buttons
- Responsive design that works on desktop, tablet, and mobile devices
- Direct links to the YouTube channel
- Information about competitive Pokemon content

## Technology Stack

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Vanilla JavaScript (for video carousel functionality)

## Local Development

To view the website locally:

1. Clone or download this repository
2. Open `index.html` in your web browser
3. No build process or server required!

### Using Python's Built-in Server (Optional)

If you want to test with a local server:

```bash
# Create a virtual environment (optional but recommended)
python -m venv venv

# Activate the virtual environment
# On Linux/Mac:
source venv/bin/activate
# On Windows:
# venv\Scripts\activate

# Start a simple HTTP server
python -m http.server 8000

# Visit http://localhost:8000 in your browser
```

## Color Scheme

The website uses a green and black color palette matching the channel banner:

- Primary Green: `#00ff00` (Bright Green)
- Secondary Green: `#00cc00` (Medium Green)
- Accent Green: `#33ff33` (Light Green)
- Dark Background: `#000000` (Pure Black)
- Light Background: `#0a0a0a` (Near Black)
- Card Background: `#1a1a1a` (Dark Gray)

## Customization

### Updating the Latest Video

To update the latest video in the hero section:

1. Open `index.html`
2. Find the line with `src="https://www.youtube.com/embed/ax0IJRbhR6M"`
3. Replace `ax0IJRbhR6M` with your new video ID
4. The video ID is the part after `watch?v=` in your YouTube URL
   - Example: `https://www.youtube.com/watch?v=NEW_VIDEO_ID`
5. Save the file and refresh your browser

### Changing Colors

To customize the colors to match your channel banner:

1. Open `styles.css`
2. Modify the CSS variables in the `:root` section at the top of the file
3. Save and refresh your browser

## Links

- YouTube Channel: [Toy Time King](https://www.youtube.com/c/ToyTimeKing)

## License

© 2026 Toy Time King. All rights reserved.
