# William Sebastian - Portfolio

A modern, single-page portfolio website built with Middleman. Features smooth scrolling navigation, interactive animations, and a beautiful space-themed design.

## Features

- **Single-Page Design**: All content is on one page with smooth scrolling between sections
- **Interactive Navigation**: Active section highlighting and smooth scroll navigation
- **Responsive Design**: Works beautifully on desktop, tablet, and mobile devices
- **Animated Elements**: Floating elements, parallax effects, and hover animations
- **Project Showcase**: Beautiful project cards with hover effects and live demos
- **Scroll Progress Indicator**: Visual progress bar at the top of the page
- **Space Theme**: Beautiful gradient backgrounds with animated stars

## Sections

1. **Hero Section**: Introduction with animated floating elements
2. **About Section**: Personal story with skills and timeline
3. **Projects Section**: Showcase of featured projects with live demos
4. **Contact Section**: Contact information and social links

## Technologies Used

- **Middleman**: Static site generator
- **SCSS**: Advanced CSS with variables and mixins
- **JavaScript**: Interactive features and animations
- **Font Awesome**: Icons
- **PP Neue Montreal**: Typography

## Getting Started

1. Install dependencies:
   ```bash
   bundle install
   ```

2. Start the development server:
   ```bash
   bundle exec middleman server
   ```

3. Open your browser and navigate to `http://localhost:4567`

## Customization

### Adding Projects
Edit `data/projects.yml` to add or modify projects:

```yaml
- name: Project Name
  description: "Project description"
  images:
    - images/projects/project_image.png
  tech:
    - Technology 1
    - Technology 2
  url: https://project-url.com
```

### Styling
The main styles are in `source/stylesheets/site.css.scss`. The design uses a space theme with:
- Primary color: `#3a6a8b`
- Background: Dark gradient with animated stars
- Typography: PP Neue Montreal

### JavaScript Features
Interactive features are in `source/javascripts/site.js`:
- Smooth scrolling navigation
- Active section highlighting
- Scroll progress indicator
- Hover animations
- Intersection Observer animations

## Build for Production

```bash
bundle exec middleman build
```

This will generate static files in the `build/` directory.

## License

This project is open source and available under the [MIT License](LICENSE).
