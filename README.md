# Portfolio About.me Page

A clean, minimalist portfolio page inspired by read.cv designs, built for GitHub Pages hosting.

## Features

- Responsive design (mobile and desktop)
- Clean, minimalist aesthetic
- Sections: Profile, Work Experience, Projects, Education, Speaking, Writing, Contact
- Optimized for GitHub Pages static hosting

## Setup

1. Clone the repository:
```bash
git clone https://github.com/joaopvilla2/portfolio.git
cd portfolio
```

2. Add your profile photo:
   - Place your profile photo in `assets/images/profile.jpg`
   - Recommended size: 92x92px or larger (will be cropped to circle)
   - Supported formats: JPG, PNG, WebP

3. Open `index.html` in your browser or use a local server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve
```

## GitHub Pages Deployment

1. Push your code to GitHub:
```bash
git remote add origin https://github.com/joaopvilla2/portfolio.git
git add .
git commit -m "Initial commit"
git push -u origin main
```

2. Enable GitHub Pages:
   - Go to repository Settings
   - Navigate to Pages section
   - Select source branch (main/master)
   - Select root directory (/)
   - Click Save

3. Your site will be available at: `https://joaopvilla2.github.io/portfolio/`

## Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # All styles
├── script.js           # Minimal JavaScript (if needed)
├── assets/
│   └── images/         # Profile photo and other images
└── README.md           # This file
```

## Technologies

- HTML5
- CSS3 (with CSS variables)
- Vanilla JavaScript
- GitHub Pages

## License

MIT

