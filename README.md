# VELLORE DIGITAL Marketing Website

A modern, responsive 5-page marketing website for VELLORE DIGITAL built with HTML5, Tailwind CSS, and JavaScript.

## Features

- **Mobile-first responsive design** - Optimized for all device sizes
- **Semantic HTML5** - For better SEO and accessibility
- **Tailwind CSS** - For styling with utility classes
- **Interactive elements** - Including testimonial carousel, form validation, and portfolio filtering
- **Accessibility features** - ARIA attributes, keyboard navigation, and semantic structure
- **Performance optimized** - Fast loading with minimal dependencies

## Pages

1. **Home (index.html)** - Hero section, features, services, testimonials, newsletter
2. **Services (services.html)** - Detailed service offerings with pricing
3. **Portfolio (portfolio.html)** - Filterable project showcase
4. **Contact (contact.html)** - Contact form with validation and information
5. **About (about.html)** - Company information, team, and timeline

## Project Structure

```
/
├── index.html              # Home page
├── services.html           # Services page
├── portfolio.html          # Portfolio page
├── contact.html            # Contact page
├── about.html              # About page
├── js/                     # JavaScript files
│   ├── main.js             # Shared functionality
│   ├── carousel.js         # Testimonial carousel
│   ├── portfolio.js        # Portfolio filtering
│   └── contact.js          # Form validation
├── assets/                 # Static assets
│   ├── images/             # Image files
│   └── icons/              # Icon files
└── README.md               # Project documentation
```

## Build and Deployment Instructions

### Prerequisites

- A modern web browser
- Basic knowledge of HTML, CSS, and JavaScript
- (Optional) Node.js and npm for development tools

### Local Development

1. **Clone or download the repository**

2. **Open the project in your code editor**

3. **Install Tailwind CSS (optional for customization)**

   If you want to customize the Tailwind configuration:

   ```bash
   # Install Node.js dependencies
   npm install
   
   # Install Tailwind CSS
   npm install -D tailwindcss
   
   # Initialize Tailwind CSS
   npx tailwindcss init
   ```

4. **Run a local development server**

   You can use any of these methods:

   - **Using Node.js:**
     ```bash
     # Install http-server globally
     npm install -g http-server
     
     # Run the server
     http-server
     ```

   - **Using Python:**
     ```bash
     # Python 3
     python -m http.server
     
     # Python 2
     python -m SimpleHTTPServer
     ```

   - **Using VS Code:**
     Install the "Live Server" extension and click "Go Live"

5. **View the website**

   Open your browser and navigate to `http://localhost:8080` (or the port shown in your terminal)

### Deployment

This website can be deployed to any static hosting service:

1. **GitHub Pages**

   - Push your code to a GitHub repository
   - Go to Settings > Pages
   - Select your branch (usually `main`) and save

2. **Netlify**

   - Sign up for a Netlify account
   - Drag and drop your project folder to the Netlify dashboard
   - Or connect your GitHub repository for continuous deployment

3. **Vercel**

   - Sign up for a Vercel account
   - Import your GitHub repository
   - Vercel will automatically deploy your site

4. **Traditional Web Hosting**

   - Upload all files to your web hosting service using FTP
   - Ensure the `index.html` file is in the root directory

## Customization

### Tailwind CSS

The website uses the Tailwind CSS CDN for simplicity. For production, consider:

1. Installing Tailwind locally and purging unused styles
2. Customizing the color scheme in the Tailwind config
3. Adding custom plugins as needed

### Images and Content

Replace the placeholder content with your own:

1. Update images in the `assets/images/` directory
2. Replace placeholder text in the HTML files
3. Update contact information in `contact.html`

### JavaScript

The JavaScript files are modular and can be extended:

- `main.js` - Shared functionality
- `carousel.js` - Testimonial carousel
- `portfolio.js` - Portfolio filtering
- `contact.js` - Form validation

## Browser Support

This website is optimized for modern browsers including:

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is available for use under the [MIT License](https://opensource.org/licenses/MIT).

## Contact

For questions or support, please contact:

- Email: ssaranmga@gmail.com
- Phone: 7010703850