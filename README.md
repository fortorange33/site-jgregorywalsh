# Project Overview

This project is a basic static site setup designed for deployment on Cloudflare Pages. It includes a simple HTML structure, styling with Tailwind CSS, and optional JavaScript functionality.

[![GitHub](https://img.shields.io/badge/Source-GitHub-black?logo=github&style=flat-square)](https://github.com/fortorange33/site-jgregorywalsh)


[![Cloudflare Pages](https://badgen.net/badge/Cloudflare%20Pages/site--jgregorywalsh/F38020?icon=https://jgwalsh.net/assets/icons/cloudflarepages.svg)](https://dash.cloudflare.com/63bd5ab77c2e4c0d47629ce6bcc38633/pages/view/site-jgregorywalsh)

[![TailwindCSS](https://img.shields.io/badge/TailwindCSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)

## Project Structure

```
site-jgregorywalsh/
├── dist/                # Output directory for production-ready files
├── src/                 # Source files during development
│   ├── index.html       # Homepage HTML
│   ├── style.css        # Site-wide styling
│   └── scripts.js       # Optional JavaScript
├── assets/              # Folder for icons, images, logos, etc.
├── wrangler.toml        # Cloudflare Pages config file
└── README.md            # Project overview
```

## Getting Started

To get started with this project, follow these steps:

1. **Clone the repository**:
   ```
   git clone <repository-url>
   cd site-jgregorywalsh
   ```

2. **Install dependencies** (if any):
   - Use your preferred package manager to install any required dependencies.

3. **Development**:
   - Open the `src/index.html` file in your browser to view the homepage.
   - Modify `src/style.css` to customize the styling.
   - Add any JavaScript functionality in `src/scripts.js`.

4. **Build for Production**:
   - Run the build command to generate production-ready files in the `dist` directory.

5. **Deploy**:
   - Use the `wrangler.toml` configuration to deploy your site to Cloudflare Pages.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
