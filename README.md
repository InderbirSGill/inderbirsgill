# Inderbir Gill - Personal Website

A beautiful, modern personal website built with React, Vite, and TailwindCSS.

## Features

- 🎨 **Modern UI Design** - Clean, gradient-based design with glass morphism effects
- 📱 **Fully Responsive** - Optimized for all screen sizes
- ⚡ **Fast Performance** - Built with Vite for lightning-fast development and builds
- 🎭 **Smooth Animations** - Framer Motion powered animations and transitions
- 🌙 **Dark Theme** - Elegant dark theme with gradient backgrounds
- 📧 **Contact Form** - Functional contact form with validation
- 🎯 **Project Portfolio** - Filterable project showcase
- 📱 **Mobile Navigation** - Responsive hamburger menu for mobile devices

## Tech Stack

- **Frontend**: React 18
- **Build Tool**: Vite
- **Styling**: TailwindCSS
- **Animations**: Framer Motion
- **Icons**: Lucide React
- **Typography**: Inter (Google Fonts)

## Getting Started

### Prerequisites

Make sure you have Node.js (v16 or higher) and npm installed on your system.

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd personal-website
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open your browser and navigate to `http://localhost:5173`

### Building for Production

```bash
npm run build
```

The built files will be in the `dist` directory.

### Preview Production Build

```bash
npm run preview
```

## Project Structure

```
personal-website/
├── public/
├── src/
│   ├── components/
│   │   ├── About.jsx
│   │   ├── Contact.jsx
│   │   ├── Footer.jsx
│   │   ├── Hero.jsx
│   │   ├── Navbar.jsx
│   │   └── Projects.jsx
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── index.html
├── package.json
├── tailwind.config.js
├── postcss.config.js
└── vite.config.js
```

## Customization

### Personal Information

Update the following files with your personal information:

- **Hero.jsx**: Update your name and role descriptions
- **About.jsx**: Update your personal bio and skills
- **Contact.jsx**: Update your contact information and social links
- **Projects.jsx**: Update your project portfolio

### Styling

The website uses TailwindCSS for styling. You can customize the theme by editing:

- `tailwind.config.js` - Theme configuration
- `src/index.css` - Custom CSS and utility classes

### Colors

The color scheme uses gradients of blue and purple. You can modify these by updating the gradient classes throughout the components.

## Deployment

This website can be deployed to any static hosting service:

- **Vercel**: Connect your GitHub repository and deploy automatically
- **Netlify**: Drag and drop the `dist` folder or connect Git
- **GitHub Pages**: Use `gh-pages` package for deployment
- **Firebase Hosting**: Deploy the `dist` folder to Firebase

## Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## Contributing

Feel free to submit issues and enhancement requests!

## License

This project is open source and available under the [MIT License](LICENSE).

---


