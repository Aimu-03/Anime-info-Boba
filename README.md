# Anime Info Boba

A beautiful, modern anime information website built with HTML, CSS, and JavaScript. Features a stunning glassmorphism design with smooth animations and comprehensive anime database.


##  Features

###  Modern Design
- **Glassmorphism UI** with translucent elements and backdrop blur effects
- **Gradient animations** with dynamic color transitions
- **Smooth hover effects** and micro-interactions
- **Responsive design** that works on all devices
- **Dark theme** with vibrant accent colors

###  Functionality
- **Real-time search** through anime database
- **Interactive anime cards** with detailed information
- **Modal popups** for comprehensive anime details
- **Animated loading effects** and smooth transitions
- **Mobile-friendly** navigation and layout

###  Anime Database
- Curated collection of popular anime series
- Detailed information including:
  - Ratings and episode counts
  - Release years and studios
  - Genres and status (ongoing/completed)
  - Full descriptions and synopses

##  Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required!

### Installation

1. **Download the HTML file**
   ```bash
   # Clone or download the HTML file
   wget [your-file-url] -O anime-website.html
   ```

2. **Open in browser**
   ```bash
   # Simply double-click the HTML file or
   open anime-website.html
   ```

3. **Or serve locally** (optional)
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Then visit http://localhost:8000
   ```

##  Usage

### Basic Navigation
- **Search**: Use the search bar to find anime by title, genre, or description
- **Browse**: Scroll through the anime cards to discover new series
- **Details**: Click on any anime card to view detailed information in a modal
- **Close Modal**: Click the X button or click outside the modal to close

### Search Tips
- Search by anime title: "Attack on Titan"
- Search by genre: "Action", "Romance", "Psychological"
- Search by keywords: "ninja", "demon", "superhero"

##  Customization

### Adding New Anime
To add new anime to the database, modify the `animeData` array in the JavaScript section:

```javascript
const animeData = [
    // Existing anime...
    {
        title: "Your Anime Title",
        genre: "Genre",
        description: "Short description...",
        rating: 8.5,
        episodes: 24,
        year: 2023,
        status: "Ongoing",
        studio: "Studio Name",
        fullDescription: "Detailed description..."
    }
];
```

### Customizing Colors
The main color scheme uses CSS custom properties. You can modify these in the CSS:

```css
:root {
    --primary-gradient: linear-gradient(45deg, #ff6b6b, #4ecdc4);
    --background-gradient: linear-gradient(135deg, #1a1a2e 0%, #16213e 100%);
    --accent-color: #4ecdc4;
    --text-color: #ffffff;
}
```

### Modifying Animations
Animation speeds and effects can be adjusted in the CSS:

```css
.anime-card {
    transition: all 0.3s ease; /* Change duration here */
}

@keyframes fadeInUp {
    /* Modify animation keyframes */
}
```

##  Responsive Design

The website is fully responsive and includes:
- **Desktop**: Full grid layout with hover effects
- **Tablet**: Adjusted grid spacing and navigation
- **Mobile**: Single column layout with touch-friendly interactions

### Breakpoints
- **Desktop**: > 768px
- **Mobile**: ≤ 768px

##  Design Philosophy

### Visual Design
- **Glassmorphism**: Modern design trend with translucent elements
- **Gradient Accents**: Vibrant coral-to-teal gradients throughout
- **Smooth Animations**: Subtle movements that enhance user experience
- **Dark Theme**: Easy on the eyes with high contrast for readability

### User Experience
- **Intuitive Navigation**: Clear hierarchy and logical flow
- **Fast Loading**: Optimized CSS and minimal JavaScript
- **Accessibility**: Proper contrast ratios and semantic HTML
- **Performance**: Smooth 60fps animations and transitions

##  Technical Details

### Technologies Used
- **HTML5**: Semantic markup and modern features
- **CSS3**: Advanced features including:
  - CSS Grid and Flexbox
  - Backdrop filters
  - CSS animations and transforms
  - Custom properties (CSS variables)
- **Vanilla JavaScript**: No frameworks or libraries required
  - ES6+ features
  - DOM manipulation
  - Event handling


### Performance Features
- **Optimized animations** using `transform` and `opacity`
- **Efficient DOM manipulation** with minimal reflows
- **Lazy loading** animations using Intersection Observer
- **Lightweight** - single HTML file under 15KB

##  Animation Details

### Hover Effects
- **Card lift**: Subtle elevation on hover
- **Glow effects**: Border glow and shadow enhancement
- **Color transitions**: Smooth gradient overlays

### Loading Animations
- **Staggered appearance**: Cards fade in with delayed timing
- **Floating elements**: Background elements with floating animation
- **Gradient shifts**: Dynamic color transitions

## 📄 File Structure

```
anime-website.html          # Main HTML file containing everything
├── HTML structure          # Semantic markup
├── CSS styles             # All styling and animations
└── JavaScript             # Functionality and interactivity
```

##  Contributing

Feel free to contribute to this project by:
1. Adding more anime to the database
2. Improving the design or animations
3. Adding new features like favorites or ratings
4. Optimizing performance
5. Fixing bugs or improving accessibility



##  Support

If you encounter any issues or have questions:
1. Check the browser console for error messages
2. Ensure you're using a modern web browser
3. Try refreshing the page or clearing cache
4. Verify the HTML file is complete and not corrupted

---

**Built with  for anime enthusiasts**

*Discover your next favorite anime with AnimeVerse!*
