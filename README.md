# euijae.github.io

Personal portfolio website hosted on GitHub Pages.

## Technology Stack

- **Static Site Generator:** Jekyll
- **CSS Framework:** Pico CSS
- **Animations:** Particles.js
- **Smooth Scrolling:** Sweet-scroll
- **Icons:** Feather Icons, FontAwesome, Devicon

## Local Development

### Prerequisites

- Ruby 3.x
- Bundler

### Setup

```bash
# Install dependencies
bundle install

# Run local server
bundle exec jekyll serve
```

Open http://localhost:4000

## Project Structure

```
├── _config.yml          # Jekyll configuration
├── _layouts/            # Page templates
├── _includes/           # Reusable components
│   ├── head.html        # Meta tags, CSS imports
│   ├── header.html      # Animated header with Particles.js
│   ├── intro.html       # Main content
│   └── footer.html      # Footer and scripts
├── assets/
│   ├── css/             # Stylesheets
│   ├── js/              # JavaScript files
│   ├── fonts/           # Icon fonts
│   └── pdf/             # Project documents
├── index.html           # Entry point
├── Gemfile              # Ruby dependencies
└── Gemfile.lock
```

## Deployment

Push to `main` branch. GitHub Pages automatically builds and deploys.
