# Batanes Tourism Website

A beautiful, responsive single-page website showcasing the breathtaking beauty and rich culture of Batanes, the northernmost province of the Philippines.

## Features

- **Responsive Design**: Fully responsive layout that works on all devices (desktop, tablet, mobile)
- **Hero Image Carousel**: Dynamic image slider showcasing multiple scenic views of Batanes
- **Bootstrap 5**: Built with the latest Bootstrap framework for modern UI components
- **Multiple Sections**:
  - Hero section with image carousel
  - About Batanes with statistics
  - Must-Visit Attractions (6 featured locations)
  - Culture & Heritage with detailed paragraphs and images
  - Call-to-Action section
  - Footer with contact information

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Custom styling with CSS variables
- **Bootstrap 5.3.0**: For responsive grid and components
- **Bootstrap Icons**: For iconography

## File Structure

```
zyy/
├── index.html          # Main HTML file
├── README.md          # This file
├── logo.png           # Website logo
├── batanes.jpg        # Hero carousel images
├── batanes2.jpg
├── batanes3.jpg
├── batanes4.jpg
├── batanes5.jpg
├── rollingHills.jpg   # Attraction images
├── bascoLighthouse.jpg
├── stoneHouses.jpg
├── mountIraya.jpg
├── chavayanVillage.jpg
├── dramaticCoastlines.jpg
├── farming.jpg         # Culture & Heritage images
├── fishing.jpg
├── ivatanCuisine.jpg
├── rirualsPractices.jpg
├── traditionalHouse.jpg
├── handicrafts.jpg
└── games.png
```

## How to Use

1. **Open the Website**: Simply open `index.html` in your web browser
2. **No Build Process Required**: This is a static website with no dependencies to install
3. **View Sections**: Use the navigation menu to jump to different sections:
   - Home (Hero section)
   - About
   - Attractions
   - Culture & Heritage

## Sections Overview

### Hero Section
- Features an automatic image carousel with 5 images
- Overlay text with call-to-action button
- Fixed navigation bar

### About Section
- Information about Batanes province
- Statistics boxes showing key facts
- Clean, readable layout

### Attractions Section
- 6 must-visit locations with images and descriptions:
  - Rolling Hills
  - Basco Lighthouse
  - Traditional Stone Houses
  - Mount Iraya
  - Chavayan Village
  - Dramatic Coastlines

### Culture & Heritage Section
- 7 detailed topics with images and paragraphs:
  - Farming
  - Fishing
  - Ivatan Cuisine
  - Rituals and Practices
  - Traditional Ivatan Houses
  - Traditional Handicrafts
  - Traditional Games

## Customization

### Colors
Edit CSS variables in the `<style>` section:
```css
:root {
    --primary-color: #2c5530;      /* Main green */
    --secondary-color: #6b8e6b;    /* Secondary green */
    --accent-color: #87ceeb;      /* Sky blue */
    --text-dark: #2c3e50;         /* Dark text */
}
```

### Images
Replace image files in the root directory and update the `src` attributes in `index.html` accordingly.

### Content
All text content is directly editable in `index.html`. Simply locate the section and modify the text.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Credits

- **Images**: Local images of Batanes
- **Icons**: Bootstrap Icons
- **Framework**: Bootstrap 5

## License

This project is open source and available for educational purposes.

## Contact

For inquiries about Batanes tourism:
- Email: info@batanes.com
- Location: Batanes, Philippines

---

**Note**: This is a static website project. All images should be placed in the same directory as `index.html` for proper loading.

