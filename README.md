# Portfolio Template 2

A polished, responsive portfolio and personal brand template built for creatives, developers, and freelancers. The project includes a static HTML version and a React-based implementation, making it easy to use as a starter for a modern online portfolio or personal website.

## Overview

This template is designed to showcase:

- Personal branding and hero sections
- About and skills information
- Service offerings
- Portfolio work and case studies
- Testimonials and client feedback
- Blog/news sections
- Contact form and call-to-action areas
- Responsive layouts for desktop, tablet, and mobile devices

## Project Structure

```text
portfolio-tmpl2-master/
├── documentation/          # Static HTML portfolio demo and assets
│   ├── index.html
│   ├── css/
│   ├── js/
│   ├── img/
│   └── assets/
├── tunis/                  # React portfolio application
│   ├── public/
│   ├── src/
│   ├── package.json
│   └── README.md
├── README.md               # Project overview
└── .gitignore
```

## Included Versions

### Static HTML Version

The full template experience is available in the `documentation/` folder and is ready to open as a static website.

### React Version

A modern React implementation is available in the `tunis/` folder, using:

- React
- React Router
- Bootstrap
- Sass
- Slick carousel and animation libraries

## Getting Started

### Prerequisites

Before running the project, ensure you have the following installed:

- Node.js 14 or later
- npm or yarn

### Run the React app

```bash
cd tunis
npm install
npm start
```

This will run the app in development mode. Open the local URL shown in the terminal to view the portfolio.

### Build for production

```bash
cd tunis
npm run build
```

The production build will be generated in the `build/` folder.

## Customization

You can tailor the template to your brand by updating:

- `tunis/src/App.js` for page structure and content
- `tunis/src/colors.json` for theme colors
- `tunis/src/assets/` for images and media
- `documentation/index.html` and the relevant CSS/JS files for the static template

## Recommended Workflow

1. Choose the template version that fits your needs.
2. Replace demo content with your own name, bio, projects, and contact details.
3. Update branding, colors, and typography.
4. Add your own portfolio items and media assets.
5. Run the project locally and test responsiveness across devices.

## Notes

- The project contains third-party libraries and assets under their own licensing terms.
- Some files in `documentation/assets/` are vendor-supplied and should be reviewed before commercial deployment.
- This repository is best suited as a starter template for a portfolio, personal website, or freelance brand site.

## Contributing

Contributions are welcome if you want to improve the template structure, responsiveness, or documentation. If you make changes, keep the project clean and ensure they remain compatible with both the static and React versions.

## Support

If you are using this template as a starting point, you can customize it easily for your own personal or business brand by replacing placeholder content and styling elements.
