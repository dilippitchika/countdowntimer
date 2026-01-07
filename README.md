# Product Launch Countdown Timer

A beautiful countdown timer for the SpotterViz and SpotterModel product launch, featuring a modern gradient design with animated elements.

## Features

- **Live Countdown**: Real-time countdown to March 01, 2026
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Animated Elements**: Floating decorative icons with smooth animations
- **Modern Aesthetics**: Gradient backgrounds, glassmorphism effects, and cyan accents
- **Auto-updating**: The countdown updates every second

## Design Highlights

- Two product showcases (SpotterModel & SpotterViz) with circular icon displays
- Central countdown timer with separators
- Launch date prominently displayed
- Network/constellation background pattern
- Blue/cyan color scheme matching ThoughtSpot branding

## Usage

Simply open `index.html` in any modern web browser. No build tools or dependencies required!

```bash
# Open directly in your default browser
open index.html

# Or use a local server (optional)
python -m http.server 8000
# Then visit http://localhost:8000
```

## Customization

### Change the Launch Date
Edit line 287 in `index.html`:
```javascript
const launchDate = new Date('March 01, 2026 00:00:00').getTime();
```

### Modify Colors
The main colors are defined in the CSS:
- Primary gradient: `#072B5C` to `#08062F`
- Accent color: `#58d7db` (cyan)
- Countdown background: `#161F4E` to `#29649A`

### Update Product Information
Edit the HTML content in the product cards:
- Product titles (SpotterModel, SpotterViz)
- Subtitles
- Product icons (replace the image URLs)

## Browser Compatibility

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Technologies Used

- Pure HTML5
- CSS3 (Gradients, Animations, Flexbox)
- Vanilla JavaScript (Countdown logic)
- No external dependencies!

## License

Created from Figma design for SpotterViz Spotlight Demo

