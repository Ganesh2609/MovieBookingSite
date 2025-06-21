# FilmFanatics - Movie Booking Website

A modern, responsive movie booking website featuring user authentication, movie browsing, and interactive seat selection functionality. Built with HTML5, CSS3, and vanilla JavaScript for optimal performance and cross-browser compatibility.

## Overview

FilmFanatics is a comprehensive movie booking platform that provides users with an intuitive interface to browse popular movies, view detailed information, and book tickets with an interactive seat selection system. The project demonstrates modern web development practices with responsive design and smooth user interactions.

## Features

### 🎬 Movie Browsing
- Dynamic movie carousel with popular releases
- Movie details pages with cast information and trailers
- Responsive grid layout for movie collections
- Search functionality for finding specific movies
- Movie categorization (Action, Thriller, Sci-Fi, etc.)

### 🔐 User Authentication
- Dual login/signup interface with smooth transitions
- Email and phone number authentication options
- Password visibility toggle for enhanced UX
- Social media integration (Google, Microsoft, Facebook, Apple)
- Form validation and error handling

### 🎭 Interactive Seat Selection
- Real-time seat availability visualization
- Multiple seat states (Available, Selected, Occupied)
- Dynamic pricing calculation based on selection
- Local storage for maintaining user selections
- Multiple ticket class options (Premium, First, Second Class)

### 📱 Responsive Design
- Mobile-first approach with adaptive layouts
- Touch-friendly navigation and interactions
- Optimized for various screen sizes and devices
- Smooth animations and transitions
- Progressive enhancement strategy

## Project Structure

```
MovieBookingSite/
├── index.html                 # Main homepage with movie listings
├── play-page.html            # Individual movie details page
├── style.css                 # Main stylesheet with responsive design
├── script.js                 # Core JavaScript functionality
├── Login/
│   ├── login.html            # Authentication interface
│   ├── login.css             # Login-specific styles
│   ├── login.js              # Authentication logic
│   └── Images/               # Authentication page assets
├── Seat Booking/
│   ├── note.html             # Seat selection interface
│   ├── style.css             # Seat booking styles
│   └── script.js             # Seat selection logic
└── External Libraries/
    ├── swiper-bundle.min.css # Carousel component styles
    └── swiper-bundle.min.js  # Carousel functionality
```

## Technical Implementation

### Frontend Technologies
- **HTML5**: Semantic markup with accessibility considerations
- **CSS3**: Modern styling with Flexbox, Grid, and custom properties
- **JavaScript (ES6+)**: Interactive functionality and DOM manipulation
- **Swiper.js**: High-performance touch slider for movie carousels

### Key Features Implementation

#### Authentication System
The login system features a dual-interface design allowing users to switch between login and registration modes with smooth animations. It supports both email and phone number authentication with real-time form validation.

#### Movie Carousel
Implemented using Swiper.js library for smooth, touch-enabled navigation through movie collections. Features autoplay functionality, responsive breakpoints, and navigation controls.

#### Seat Selection Algorithm
The seat booking system uses a grid-based approach with JavaScript to track seat states, calculate pricing dynamically, and persist user selections using localStorage for session continuity.

#### Responsive Design Strategy
Utilizes CSS Grid and Flexbox for layout flexibility, with mobile-first media queries ensuring optimal viewing across all device types.

## Browser Compatibility

- Chrome 70+
- Firefox 65+
- Safari 12+
- Edge 79+
- Mobile browsers (iOS Safari, Chrome Mobile)

## Installation & Setup

1. Clone the repository:
```bash
git clone [repository-url]
cd MovieBookingSite
```

2. Launch the application:
```bash
# Using Python (if available)
python -m http.server 8000

# Using Node.js (if available)
npx serve .

# Or simply open index.html in your browser
```

3. Navigate to `http://localhost:8000` (or directly open index.html)

## Usage

1. **Browse Movies**: Start from the homepage to explore featured and popular movies
2. **User Authentication**: Click the user icon to access login/registration
3. **Movie Details**: Click on any movie to view detailed information and trailers
4. **Book Tickets**: Select "Book Tickets" and choose your preferred seats
5. **Complete Purchase**: Review selection and proceed to payment

## Performance Optimizations

- Lazy loading for movie images and content
- Optimized CSS with minimal specificity conflicts
- Efficient JavaScript with event delegation
- Compressed assets and minified libraries
- Progressive enhancement for core functionality

## Future Enhancements

- Payment gateway integration
- User profile management
- Movie reviews and ratings system
- Advanced search and filtering options
- Progressive Web App (PWA) capabilities
- Backend API integration for dynamic content

## Contributing

Contributions are welcome! Please follow these guidelines:
1. Fork the repository
2. Create a feature branch
3. Implement changes with proper testing
4. Submit a pull request with detailed description

## Browser Testing

The application has been tested across major browsers and devices to ensure consistent functionality and appearance. Special attention has been paid to touch interactions on mobile devices and keyboard navigation for accessibility.