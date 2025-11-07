# Movies to Watch - Web Page

## Project Description
A simple, elegant web page displaying 3 movies with interactive hover effects and watch status indicators.

## Features
- **3-Column Layout**: Responsive grid layout displaying 3 movies side by side
- **Hover Effects**: 
  - Image zoom effect on hover
  - Reveals additional movie details (watch date and place)
- **Watch Status Indicator**: 
  - Circular indicator at the bottom of each movie image
  - Green checkmark for watched movies
  - Gray circle for unwatched movies

## File Structure
```
before_nati/
├── index.html          # Main HTML structure
├── styles.css          # All styling and animations
└── project-name.md     # Project documentation
```

## Technical Details

### HTML Structure
- Semantic HTML5 structure
- Three movie cards with image containers and info sections
- SVG icons for watch status indicators

### CSS Features
- CSS Grid for responsive 3-column layout
- CSS transitions for smooth hover effects
- Gradient background
- Responsive design (adapts to tablet and mobile)

### Styling Highlights
- Modern card design with rounded corners and shadows
- Smooth image zoom on hover (scale 1.15)
- Fade-in animation for movie details on hover
- Watch indicator positioned absolutely at bottom-right of image

## Customization
To add your own movies:
1. Replace placeholder images with actual movie poster URLs
2. Update movie titles, dates, and details in `index.html`
3. Change watch status by toggling `watched`/`not-watched` classes on `.watch-indicator`

## Browser Support
- Modern browsers (Chrome, Firefox, Safari, Edge)
- CSS Grid and transitions support required

