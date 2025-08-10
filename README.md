# Personal Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. Perfect for showcasing your skills, projects, and professional information.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Smooth scrolling, hover effects, and dynamic navigation
- **Contact Form**: Functional contact form with validation
- **Project Showcase**: Dedicated section for displaying your projects
- **Skills Section**: Visual representation of your technical skills
- **Mobile-First**: Optimized for mobile devices with a hamburger menu

## Getting Started

### Prerequisites
- A modern web browser
- A text editor (VS Code, Sublime Text, etc.)

### Installation
1. Clone or download the project files
2. Open `index.html` in your web browser
3. Start customizing with your own information

## Customization Guide

### 1. Personal Information
Update the following sections in `index.html`:

#### Hero Section
```html
<h1>Hi, I'm <span class="highlight">Your Name</span></h1>
<h2 class="hero-subtitle">Your Title</h2>
<p class="hero-description">Your personal description</p>
```

#### About Section
- Update the about text paragraphs
- Modify the statistics (projects completed, years experience, etc.)

### 2. Skills Section
Add or modify skills in the three categories:
- **Frontend**: HTML, CSS, JavaScript, React, etc.
- **Backend**: Node.js, Python, databases, etc.
- **Tools & Others**: Git, Docker, AWS, etc.

### 3. Projects Section
For each project, update:
- Project title and description
- Technologies used
- GitHub repository links
- Live demo links
- Project images (replace placeholder icons)

### 4. Contact Information
Update your contact details:
```html
<span>your-email@example.com</span>
<span>+1 (555) 123-4567</span>
<span>Your City, Country</span>
```

### 5. Social Media Links
Update the social media links in the contact section:
```html
<a href="https://github.com/yourusername" class="social-link">
<a href="https://linkedin.com/in/yourusername" class="social-link">
```

## Color Customization

The website uses CSS custom properties for easy color customization. Update these in `styles.css`:

```css
:root {
    --primary-color: #3b82f6;      /* Main brand color */
    --secondary-color: #1e40af;    /* Darker shade */
    --accent-color: #f59e0b;       /* Accent color */
    --text-color: #1f2937;         /* Main text */
    --text-light: #6b7280;         /* Secondary text */
}
```

## Adding Your Profile Picture

Replace the profile placeholder:
1. Add your photo to the portfolio folder
2. In `index.html`, replace the placeholder div with:
```html
<div class="hero-image">
    <img src="your-photo.jpg" alt="Your Name" class="profile-photo">
</div>
```
3. Add appropriate CSS styling in `styles.css`

## Adding Project Images

For each project:
1. Add project screenshots to an `images` folder
2. Replace the placeholder divs:
```html
<div class="project-image">
    <img src="images/project1.jpg" alt="Project Name">
</div>
```

## Font Customization

The website uses system fonts by default. To use custom fonts:
1. Add Google Fonts link in the `<head>` section
2. Update the font-family in CSS:
```css
body {
    font-family: 'Your Font', sans-serif;
}
```

## Deployment

### GitHub Pages
1. Push your code to a GitHub repository
2. Go to Settings > Pages
3. Select source branch (main/master)
4. Your site will be available at `https://yourusername.github.io/repository-name`

### Netlify
1. Drag and drop the portfolio folder to [Netlify](https://netlify.com)
2. Your site will be automatically deployed

### Vercel
1. Connect your GitHub repository to [Vercel](https://vercel.com)
2. Deploy with one click

## File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # Stylesheet
├── script.js           # JavaScript functionality
├── README.md           # This file
└── images/            # (Create this folder for images)
    ├── profile.jpg
    ├── project1.jpg
    └── project2.jpg
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

Feel free to fork this project and customize it for your own use. If you make improvements, consider sharing them back with the community!

## License

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).

## Support

If you need help customizing your portfolio, feel free to:
- Open an issue on GitHub
- Check the code comments for guidance
- Refer to online tutorials for HTML, CSS, and JavaScript

---

**Happy coding! 🚀**

Make this portfolio your own and showcase your amazing work to the world!
