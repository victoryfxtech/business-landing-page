# Nexa Business - Mobile-Optimized

A responsive business landing page with enhanced mobile experience, now fully optimized for phones, tablets, and desktop.

## What's New

### Mobile Navigation
- **Hamburger menu** that appears on tablets and phones
- Smooth animations and overlay when menu opens
- Automatically closes when navigating to a section
- Fully accessible with ARIA labels

### Touch-Friendly Design
- Minimum 48px touch targets for all buttons and links
- Better spacing between interactive elements
- Improved padding throughout for easier tapping
- More comfortable to use on smartphones

### Responsive Typography
- Fluid text scaling using `clamp()` for smooth sizing across all devices
- Optimized line-heights for readability on small screens
- Adjusted hierarchy on mobile for better visual flow

### Mobile Breakpoints
The design responds elegantly at three key breakpoints:

- **768px and below** - Tablet optimization
- **480px and below** - Phone optimization  
- **360px and below** - Extra small devices

### Smart Layout Adjustments
- Hero section adapts from 2-column to single column on mobile
- Service grid collapses from 3 columns to 1 column
- Hero card stats stack vertically instead of overlapping
- Split section becomes single column with proper spacing

### Accessibility
- Respects `prefers-reduced-motion` for users who prefer less animation
- Keyboard-navigable menu with proper focus states
- Semantic HTML with ARIA labels
- Color contrast meets WCAG standards

## Files Included

- `index.html` - Updated HTML with mobile menu functionality
- `style.css` - Fully responsive CSS with mobile-first approach
- `README.md` - This documentation

## How to Use

1. Replace your original `index.html` and `style.css` with these files
2. Keep all files in the same folder
3. Open `index.html` in a browser to preview

## Deployment

Deploy to any static hosting:
- **GitHub Pages** - Upload to a repository and enable Pages
- **Netlify** - Drag and drop the files to deploy
- **Vercel** - Connect your repository or upload files
- **Traditional hosting** - Upload via FTP

## Browser Support

Works on all modern browsers:
- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Mobile browsers (iOS Safari, Chrome Mobile)

## Testing

Test the mobile experience:
1. **Desktop**: Resize your browser window
2. **Mobile**: Use Chrome DevTools device emulation (F12 → Toggle device toolbar)
3. **Real devices**: Test on actual phones and tablets

## Notes

- The hamburger menu uses vanilla JavaScript (no dependencies)
- CSS is optimized for performance
- Mobile navigation automatically closes when navigating to a section
- All interactive elements have hover/active states
- The design maintains the original aesthetic while improving usability

Enjoy your mobile-optimized portfolio!
