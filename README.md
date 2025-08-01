# Elly B - Portfolio Website

A modern, responsive portfolio website showcasing full-stack development skills and projects. Built with vanilla HTML and CSS, featuring a clean design with dark theme support and smooth animations.

## Features

- [ ]**Responsive Design**: Optimized for all device sizes with mobile-first approach
- [x]**Dark Theme**: Automatic dark mode support based on system preferences
- [ ]**Interactive Navigation**: Tab-based content switching using CSS radio buttons
- [x]**Contact Form**: Integrated contact form with FormSubmit service
- [x]**PWA Ready**: Progressive Web App configuration with manifest and icons
- [x]**Smooth Animations**: CSS animations and transitions for enhanced user experience
- [ ]**SEO Optimized**: Proper meta tags and semantic HTML structure

## Live Website

Visit the live portfolio at: [https://jrdv.link](https://jrdv.link)

## Project Structure

```
portfolio/
├── index.html              # Main portfolio page
├── blog.html              # Blog coming soon page
├── thanks.html            # Contact form thank you page
├── README.md              # Project documentation
└── resources/
    ├── main.css           # Main stylesheet
    ├── site.webmanifest   # PWA manifest
    ├── favicon.ico        # Favicon
    ├── favicon-16x16.png  # 16x16 favicon
    ├── favicon-32x32.png  # 32x32 favicon
    ├── apple-touch-icon.png # Apple touch icon
    ├── android-chrome-192x192.png # Android icon 192x192
    └── android-chrome-512x512.png # Android icon 512x512
```

## Design System

### Color Palette (Dark Theme)
- **Background**: `#060606` (Main), `#101010` (Secondary)
- **Text**: `#f3f3f3` (Primary), `#f1f1f1` (Secondary)
- **Accent**: `#cad5a6` (Green accent for highlights)

### Typography
- **Font Family**: Inter (from CDN Fonts)
- **Headings**: Bold weights with large sizes
- **Body Text**: Regular weight, optimized line heights

### Layout
- **Container**: Responsive clamp sizing `clamp(300px, 800px, 90%)`
- **Grid System**: Flexbox-based layout
- **Spacing**: Consistent rem-based spacing scale

## Technologies Used

- **HTML5**: Semantic markup and accessibility features
- **CSS3**: Modern CSS with custom properties, animations, and responsive design
- **FormSubmit**: Third-party service for contact form handling
- **PWA**: Progressive Web App capabilities

## Sections

### 1. Header
- Name and title display
- Location information
- Quick links (Email, GitHub, Blog)
- CV download button

### 2. Navigation Tabs
- **Projects**: Showcase of development projects
- **Programming Languages**: Technical skills with descriptions
- **About**: Professional background and experience
- **Education**: Academic qualifications
- **Interests**: Professional interests and hobbies
- **Contact**: Contact form for inquiries

### 3. Content Areas

#### Projects
- **trysafely**: TypeScript utility for error handling
- **rp-scissors**: Web-based rock-paper-scissors game
- Each project includes live links and descriptions

#### Programming Languages
- **TypeScript**: Primary development language
- **HTML/CSS**: Web development fundamentals
- **C/C++**: Systems programming experience
- **Python**: Data processing and automation
- **SQL**: Database management

#### About Section
- 2+ years of full-stack development experience
- Expertise in modern frameworks (Vue, Next.js, Astro)
- Backend technologies (Express, Hono, tRPC, Convex)
- Community involvement and mentorship

#### Education
- **Current**: Bachelor of Engineering in Computer Engineering (2023-Present)
- **Completed**: Ordinary Diploma in Electronics and Telecommunications (2020-2023)
- **Institution**: Dar es Salaam Institute of Technology (DIT)

## Contact Form Configuration

The contact form uses FormSubmit service with the following features:
- **Endpoint**: Configured with encrypted email
- **Redirect**: Automatic redirect to thank you page
- **Spam Protection**: Honeypot and captcha protection
- **Blacklist**: Automatic spam keyword filtering

### Form Fields
- **Name**: Required text input
- **Phone**: Optional telephone input
- **Email**: Required email input with validation
- **Message**: Required textarea for detailed messages

## Performance Features

- **Optimized Assets**: Compressed resouces
- **Fast Loading**: No dependencies and efficient code
- **No Images**: The page only need load the html and css

## Customization

**If you clone this repository, do the following:**

### Updating Content
1. **Personal Information**: Edit the header section in `index.html`
2. **Projects**: Update the projects list with your own work
3. **Skills**: Modify the programming languages section
4. **Styling**: Customize colors and fonts in `resources/main.css`

### Adding New Sections
1. Add new radio input in the main element
2. Create corresponding label in the categories section
3. Add content section with appropriate CSS classes
4. Update CSS selectors for show/hide functionality

## Contributing

While this is a personal portfolio, suggestions and feedback are welcome:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

- **GitHub**: [@EllyBax](https://github.com/EllyBax)
- **Portfolio**: [Live Site](https://jrdv.link)

---

**Built with ❤️ by Elly B** | *Full Stack Developer from Dar es Salaam, Tanzania*
