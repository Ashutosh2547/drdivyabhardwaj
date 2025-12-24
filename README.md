# Dr. Divya - Homeopathic Doctor Website

A modern, responsive single-page website for Dr. Divya's homeopathic clinic, featuring elegant design with smooth animations and interactive elements.

## 🌐 Live Preview

Open `index.html` in a web browser to view the website.

## 🛠️ Tools & Frameworks Used

### CSS Framework
- **[Tailwind CSS](https://tailwindcss.com/)** (v3.x via CDN)
  - Utility-first CSS framework for rapid UI development
  - Custom configuration for primary colors (teal theme) and fonts

### JavaScript Libraries

#### Animation
- **[AOS (Animate On Scroll)](https://michalsnik.github.io/aos/)** (v2.3.1)
  - Scroll-triggered animations
  - Smooth fade, slide, and zoom effects

#### Carousel/Slider
- **[Swiper.js](https://swiperjs.com/)** (v11)
  - Modern touch slider for hero section
  - Services carousel (responsive - 1/2/3 slides based on viewport)
  - Testimonials carousel with navigation arrows and pagination

#### Icons
- **[Lucide Icons](https://lucide.dev/)**
  - Modern, customizable SVG icons
  - Used for navigation, features, contact info, and UI elements

### Fonts
- **[Google Fonts](https://fonts.google.com/)**
  - **Playfair Display** - Elegant serif font for headings
  - **Inter** - Clean sans-serif font for body text

## 📁 Project Structure

```
Dr Divya/
├── index.html      # Main HTML file with all content and styles
└── README.md       # Project documentation
```

## 🎨 Design Features

- **Responsive Design** - Mobile-first approach, optimized for all screen sizes
- **Split Hero Section** - Gradient background with image carousel
- **Custom Color Theme** - Teal/primary color palette
- **Glass Morphism** - Subtle glass effects on cards
- **Smooth Animations** - AOS library for scroll animations
- **Interactive Carousels** - Touch-friendly sliders for services and testimonials

## 📱 Sections

1. **Navigation** - Sticky header with mobile hamburger menu
2. **Hero** - Split layout with rotating image carousel and call-to-action
3. **About** - Doctor introduction with credentials
4. **Services** - 6 service cards in responsive carousel
5. **Why Homeopathy** - Benefits section with Samuel Hahnemann quote
6. **Testimonials** - Patient reviews carousel
7. **Contact** - Appointment form with clinic information
8. **Footer** - Links, social media, and copyright

## 🚀 Getting Started

1. Clone or download the project
2. Open `index.html` in any modern web browser
3. No build process required - all dependencies loaded via CDN

## 📋 Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome for Android)

## 🔧 Customization

### Colors
Edit the Tailwind config in `<script>` tag to change the primary color palette:
```javascript
tailwind.config = {
    theme: {
        extend: {
            colors: {
                primary: {
                    // Modify these values
                    500: '#14b8a6',
                    600: '#0d9488',
                    700: '#0f766e',
                    // ...
                }
            }
        }
    }
}
```

### Content
All content is in `index.html`. Update text, images, and contact information directly in the HTML.

### Images
Images are loaded from [Unsplash](https://unsplash.com/) via URL. Replace with your own images by updating the `src` attributes.

## 📄 License

This project is for personal/commercial use for Dr. Divya's clinic.

---

Built with ❤️ using modern web technologies
