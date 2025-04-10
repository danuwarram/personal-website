# Modern Portfolio Website

A clean, responsive portfolio website template built with HTML, CSS, and vanilla JavaScript. Perfect for showcasing your work, skills, and experience.

## Features

- ✨ Modern and clean design
- 📱 Fully responsive layout (works on mobile, tablet, and desktop)
- 🎨 Easy to customize
- 🔍 SEO friendly
- 🌟 Smooth animations
- 📝 Contact form
- 📊 Skills section
- 📁 Projects showcase
- 📄 About me section

## Preview

![Portfolio Preview](https://via.placeholder.com/800x400)

## Live Demo

[View Live Demo](#) - Coming soon

## How to Use

1. Clone or download this repository
2. Customize the content in the HTML file to match your information
3. Replace placeholder images with your own
4. Update the skills and projects sections
5. Modify colors in the CSS file if desired
6. Deploy to your preferred hosting service

## Customization Guide

### Changing Basic Information

1. Open `index.html` and update the following:
   - Title tag: `<title>Your Name - Portfolio</title>`
   - Name in the hero section: `<h1>Hi, I'm <span class="highlight">Your Name</span></h1>`
   - About me text
   - Contact information
   - Copyright text in footer

### Updating Profile Picture

1. Replace the placeholder image URL in the About section:
   ```html
   <img src="your-image-url.jpg" alt="Profile Picture">
   ```

### Updating Projects

1. In the Projects section, modify each project card:
   ```html
   <div class="project-card">
     <div class="project-image">
       <img src="your-project-image.jpg" alt="Project Name">
     </div>
     <div class="project-info">
       <h3>Project Name</h3>
       <p>Project description...</p>
       <div class="project-tags">
         <span>Technology 1</span>
         <span>Technology 2</span>
       </div>
       <div class="project-links">
         <a href="project-url" target="_blank" class="btn small-btn">Live Demo</a>
         <a href="github-url" target="_blank" class="btn small-btn">Source Code</a>
       </div>
     </div>
   </div>
   ```

### Updating Skills

1. Modify the skill cards in the Skills section:
   ```html
   <div class="skill-card">
     <i class="fas fa-code"></i> <!-- Choose icon from Font Awesome -->
     <h3>Skill Category</h3>
     <div class="skill-tags">
       <span>Skill 1</span>
       <span>Skill 2</span>
     </div>
   </div>
   ```

### Changing Colors

1. Open `styles.css` and update the color variables at the top:
   ```css
   :root {
     --primary-color: #4a6cf7; /* Main color */
     --secondary-color: #6c757d;
     --background-color: #f8f9fa;
     --text-color: #212529;
     /* other colors... */
   }
   ```

### Updating Social Links

1. Find the social icons in the hero and contact sections:
   ```html
   <div class="social-icons">
     <a href="your-github-url" target="_blank"><i class="fab fa-github"></i></a>
     <a href="your-linkedin-url" target="_blank"><i class="fab fa-linkedin"></i></a>
     <a href="your-twitter-url" target="_blank"><i class="fab fa-twitter"></i></a>
   </div>
   ```

### Changing the Background Image

1. In `styles.css`, find the hero section and update the background image URL:
   ```css
   .hero {
     background: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)), 
                url('your-background-image.jpg') center/cover no-repeat;
   }
   ```

### Updating Typing Animation Text

1. In `script.js`, find the `textArray` variable and update with your desired texts:
   ```javascript
   const textArray = ['Web Developer', 'Designer', 'Your Text Here'];
   ```

## Deployment

The site can be deployed to various hosting platforms:

- **GitHub Pages**: Free and easy option for static sites
- **Netlify**: Offers free hosting with custom domains
- **Vercel**: Great for frontend deployments
- **Shared Hosting**: Upload files via FTP to your hosting account

## Contact Form Setup

The contact form in this template is set up for demonstration purposes and does not send emails by default. To make it functional, you'll need to:

1. Set up a backend service to handle form submissions (e.g., PHP, Node.js)
2. Use a form submission service like Formspree or Netlify Forms
3. Update the form action attribute and method accordingly

## License

This template is free to use for personal and commercial projects. Attribution is appreciated but not required.

## Credits

- Font Awesome for icons
- Google Fonts for typography
- Unsplash for placeholder images 