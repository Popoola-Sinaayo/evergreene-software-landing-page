# Evergreene Softwares

A stunning, modern website for Evergreene Softwares - an AI-powered software development company specializing in rapid application development and intelligent infrastructure management.

## Features

- **Modern Design**: Clean, professional aesthetic with green theme
- **AI-Focused Content**: Highlighting AI development and infrastructure management
- **Responsive Layout**: Perfect on all devices from mobile to desktop
- **Smooth Animations**: Engaging scroll animations and hover effects
- **Professional Sections**:
  - Hero section with compelling messaging
  - About section with company DNA
  - Projects showcase with AI examples
  - Services overview
  - Statistics and metrics
  - Tech stack display
  - Contact form and consultation booking
  - Professional footer

## Design Inspiration

Inspired by the modern, clean design of Supaapps but with unique Evergreene Softwares branding and AI-focused content.

## Technology Stack

- **Framework**: Astro 5.14.5
- **Styling**: Tailwind CSS 3.4.0 with custom CSS
- **PostCSS**: Autoprefixer for browser compatibility
- **Fonts**: Inter (Google Fonts)
- **Icons**: Heroicons (SVG)
- **Animations**: CSS animations with Intersection Observer

## Getting Started

### Quick Setup

1. **Install dependencies:**
   ```bash
   npm install
   ```

2. **Start the development server:**
   ```bash
   npm run dev
   ```

3. **Open your browser and visit:** `http://localhost:4321`

### Alternative Setup (if npm install fails)

If you encounter permission issues with npm, try:

```bash
# Clear npm cache
npm cache clean --force

# Or use yarn instead
yarn install
yarn dev
```

### Troubleshooting

If you get errors about missing modules:
1. Delete `node_modules` folder: `rm -rf node_modules`
2. Delete `package-lock.json`: `rm package-lock.json`
3. Run `npm install` again

## Building for Production

```bash
npm run build
```

## Key Features

### Color Scheme
- Primary Green: `#22c55e` (primary-500)
- Dark Theme: Slate colors for professional look
- Gradient accents for visual appeal

### Animations
- Scroll-triggered fade-in animations
- Floating background elements
- Smooth hover effects
- Gradient text animations

### Responsive Design
- Mobile-first approach
- Tablet and desktop optimizations
- Accessibility features (reduced motion support)
- High contrast mode support

### Content Sections
1. **Navigation**: Fixed header with smooth scrolling
2. **Hero**: Compelling AI-focused messaging
3. **About**: Company DNA and values
4. **Projects**: AI development examples
5. **Services**: Core service offerings
6. **Stats**: Impressive metrics
7. **Tech Stack**: Technologies used
8. **Contact**: Consultation booking form
9. **Footer**: Links and company info

## Customization

The website is built with modularity in mind. Key areas for customization:

- **Colors**: Update CSS variables in `src/layouts/Layout.astro`
- **Content**: Modify text in `src/pages/index.astro`
- **Animations**: Adjust timing in CSS animations
- **Sections**: Add/remove sections as needed

## Performance

- Optimized for fast loading
- Minimal dependencies
- Efficient CSS animations
- Responsive images
- SEO-friendly structure

## Browser Support

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile browsers
- Accessibility features for screen readers
- Reduced motion support

---

Built with ❤️ for Evergreene Softwares