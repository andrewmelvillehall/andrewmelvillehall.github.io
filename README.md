# AMH Website

An open-source starter template for building high-performance, content-driven church websites with Astro. Pure SSG, SEO-ready, built with Tailwind CSS, Markdown content, ready to integrate with any CMS

## Features

- **Pure Static Site Generation (SSG)**: Fast, SEO-friendly pages generated at build time
- **Content-Driven Architecture**: Content managed via Markdown files using Astro Content Collections
- **Mobile-First Responsive Design**: Tailwind CSS for beautiful, responsive layouts
- **SEO Optimized**: Complete meta tags, JSON-LD Schema, and sitemap.xml
- **CMS-Ready Structure**: Easily integrate with headless CMS solutions
- **Comprehensive Church Website Sections**: All essential pages for a complete church website
- **Accessibility Focus**: WCAG compliant design and markup
- **Modern UI Components**: Reusable components with hover states and micro-interactions
- **Image Optimization**: Proper image organization and fallback handling


## Getting Started

### Prerequisites

- Node.js 18 or later
- npm or yarn

### Installation

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the development server:
   ```bash
   npm run dev
   ```

3. Open your browser and navigate to `http://localhost:4321`

## Content Management

### Adding/Editing Content

All content is stored in Markdown (`.md`) files in the `src/content/` directory.


### Content Schema

See `src/content/config.ts` for the complete schema definitions for all content types.


### Styling

This template uses Tailwind CSS for styling:

1. Customize colors and other theme settings in `tailwind.config.cjs`
2. Global styles are in `src/assets/styles/global.css`
3. The template includes a comprehensive color system with primary, secondary, and accent colors

## Headless CMS Integration

This starter is designed to work well with these headless CMS solutions:

### TinaCMS

1. Install TinaCMS:
   ```bash
   npm install tinacms @tinacms/cli
   ```

2. Add the Tina config file (see TinaCMS documentation)

3. The existing Content Collections schemas can be adapted for TinaCMS

### Decap CMS (formerly Netlify CMS)

1. Add Decap CMS config to `public/admin/config.yml`
2. The existing Content Collections structure works well with Decap CMS

## Deployment

This site can be deployed to any static hosting platform:

### Netlify

1. Push your repository to GitHub
2. Connect to Netlify
3. Set build command to `npm run build` and publish directory to `dist/`

### Vercel

1. Push your repository to GitHub
2. Import in Vercel
3. It will automatically detect Astro and set up the correct build settings

### GitHub Pages

1. Install gh-pages:
   ```bash
   npm install -D gh-pages
   ```

2. Add deploy script to package.json:
   ```json
   "scripts": {
     "deploy": "npm run build && gh-pages -d dist"
   }
   ```

3. Run `npm run deploy`

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- [Astro](https://astro.build) for the awesome static site generator
- [Tailwind CSS](https://tailwindcss.com) for the utility-first CSS framework
- [Heroicons](https://heroicons.com) for the icon system
- [Pexels](https://pexels.com) & [Unsplash](https://unsplash.com) for stock photography

## Support

For questions, issues, or contributions, please visit our GitHub repository or contact the development team.

Created with ❤️ for church communities worldwide
