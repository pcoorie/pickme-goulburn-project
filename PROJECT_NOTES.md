# PickMe Goulburn Project - Implementation Notes

## Project Overview
This is a complete redesign of the PickMe Goulburn ride-sharing website with a dark theme color scheme and embedded booking functionality.

## Files Created/Modified

### Main Files:
1. **`index.html`** - Main landing page with embedded booking widget
2. **`styles.css`** - Dark blue, grey, and black theme styling
3. **`main.js`** - JavaScript functionality and animations


## Key Features Implemented

### Design & Theme:
- Light blue, grey, and black color scheme as requested
- Modern glass-morphism effects with backdrop filters
- Responsive design for all device sizes
- Properly scaled background image from goulburnnsw.com.au

### Booking Integration:
- Embedded iframe widget from https://canupikme.ondelight.app
- Image URL parameter: https://i.imgur.com/2Slf8Yi.png (generic hybrid sedan; the hero background still uses the Big Merino photo)
- Widget height: 450px, width: 100%
- Geolocation permission enabled

### Website Structure:
- Fixed navigation header with smooth scrolling
- Hero section with call-to-action buttons
- Embedded booking widget prominently displayed
- "How It Works" process explanation
- Features highlighting service benefits
- Pricing plans with popular option highlighted
- Contact form with information
- Comprehensive footer

## Technical Implementation Details

### HTML Structure:
- Semantic HTML5 sections for proper SEO and accessibility
- Responsive grid layouts using CSS Grid and Flexbox
- Proper form elements with validation
- Mobile-friendly navigation

### CSS Features:
- Custom CSS variables for consistent theming
- Responsive breakpoints for all device sizes
- Modern styling with shadows, transitions, and hover effects
- Backdrop filters for glass-morphism effects
- Gradient overlays for better text readability

### JavaScript Functionality:
- Smooth scrolling navigation
- Form validation and submission handling
- Interactive elements with hover effects
- Scroll animations for content sections
- Dynamic behavior for booking widget

## Deployment Instructions

1. Place all files in the same directory
2. Open `index.html` in any modern web browser
3. The site will automatically adapt to different screen sizes
4. The embedded booking widget will function immediately

## Customization Options

### Color Scheme:
- Theme colors defined in CSS variables
- Easy to modify by changing variable values in :root

### Content:
- All text content is editable directly in HTML
- Sections can be reordered or removed as needed
- Images can be swapped by modifying the background URL

## Known Requirements

### Browser Compatibility:
- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile responsive design for all devices
- Iframe widget requires internet connectivity

### Dependencies:
- External CSS from Google Fonts
- Font Awesome icons via CDN
- External booking widget from ondelight.app
