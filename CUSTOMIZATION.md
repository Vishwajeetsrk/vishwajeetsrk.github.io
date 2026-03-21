# Portfolio Customization Guide

## 🎨 Theme Customization

### Changing Colors

#### Light Mode Colors
Edit these CSS variables in `css/style.css` (around line 9):

```css
:root {
    --primary-color: #1e40af;      /* Main blue color - used in buttons, headings */
    --secondary-color: #10b981;    /* Green accent - used for success states */
    --accent-color: #f59e0b;       /* Gold highlight - used for special elements */
    --text-primary: #1f2937;       /* Main text color */
    --text-secondary: #6b7280;     /* Secondary text color */
    --bg-primary: #ffffff;         /* Main background */
    --bg-secondary: #f9fafb;       /* Section backgrounds */
    --bg-tertiary: #f3f4f6;        /* Card backgrounds */
}
```

#### Dark Mode Colors
Edit these CSS variables in `css/style.css` (around line 28):

```css
body.dark-mode {
    --primary-color: #3b82f6;      /* Lighter blue for dark mode */
    --secondary-color: #10b981;    /* Keep green consistent */
    --accent-color: #fbbf24;       /* Lighter gold for visibility */
    --text-primary: #f9fafb;       /* Light text on dark background */
    --text-secondary: #d1d5db;     /* Secondary light text */
    --bg-primary: #111827;         /* Dark background */
    --bg-secondary: #1f2937;       /* Slightly lighter sections */
    --bg-tertiary: #374151;        /* Card backgrounds */
}
```

### Popular Color Schemes

#### Professional Blue & Gold
```css
--primary-color: #1e40af;
--secondary-color: #f59e0b;
--accent-color: #10b981;
```

#### Tech Purple & Cyan
```css
--primary-color: #7c3aed;
--secondary-color: #06b6d4;
--accent-color: #ec4899;
```

#### Modern Green & Teal
```css
--primary-color: #059669;
--secondary-color: #0d9488;
--accent-color: #f59e0b;
```

#### Elegant Gray & Red
```css
--primary-color: #374151;
--secondary-color: #ef4444;
--accent-color: #f59e0b;
```

## ✍️ Content Customization

### Hero Section

**Location**: `index.html` lines 45-88

```html
<!-- Update your name -->
<h1 class="hero-title">
    Hi, I'm <span class="highlight">Your Name</span>
</h1>

<!-- Update your tagline -->
<p class="hero-subtitle">Your Professional Tagline Here</p>

<!-- Update description -->
<p class="hero-description">
    Your compelling description here
</p>
```

### About Section

**Location**: `index.html` lines 92-145

```html
<!-- Update bio paragraphs -->
<p>Your first paragraph about yourself...</p>
<p>Your second paragraph highlighting expertise...</p>

<!-- Update statistics -->
<div class="stat-number">1000+</div>
<div class="stat-label">Your Metric</div>
```

### Skills Section

**Location**: `index.html` lines 150-350

```html
<!-- Add a new skill -->
<div class="skill-item" data-skill="85">
    <div class="skill-icon"><i class="fab fa-python"></i></div>
    <div class="skill-info">
        <h4>Skill Name</h4>
        <div class="skill-bar">
            <div class="skill-progress" data-progress="85"></div>
        </div>
    </div>
</div>
```

**Proficiency Levels**:
- 90-100%: Expert
- 75-89%: Advanced
- 60-74%: Intermediate
- 40-59%: Basic

### Experience Timeline

**Location**: `index.html` lines 355-480

```html
<!-- Add new experience -->
<div class="timeline-item" data-aos="fade-up">
    <div class="timeline-dot"></div>
    <div class="timeline-content">
        <div class="timeline-date">Month Year – Present/End Date</div>
        <h3>Job Title</h3>
        <h4>Company Name | Location</h4>
        <ul class="timeline-achievements">
            <li><i class="fas fa-check-circle"></i> Achievement 1</li>
            <li><i class="fas fa-check-circle"></i> Achievement 2</li>
        </ul>
        <div class="timeline-tags">
            <span class="tag">Skill</span>
            <span class="tag">Tool</span>
        </div>
    </div>
</div>
```

### Projects Section

**Location**: `index.html` lines 485-650

```html
<!-- Add new project -->
<div class="project-card" data-aos="fade-up">
    <div class="project-image">
        <div class="project-overlay">
            <div class="project-links">
                <a href="demo-link" class="project-link">
                    <i class="fas fa-external-link-alt"></i>
                </a>
                <a href="github-link" class="project-link">
                    <i class="fab fa-github"></i>
                </a>
            </div>
        </div>
        <div class="project-icon-placeholder">
            <i class="fas fa-icon-name"></i>
        </div>
    </div>
    <div class="project-info">
        <h3>Project Name</h3>
        <p>Project description here...</p>
        <div class="project-tech">
            <span class="tech-tag">Tech 1</span>
            <span class="tech-tag">Tech 2</span>
        </div>
        <div class="project-impact">
            <span><i class="fas fa-bolt"></i> Impact metric</span>
        </div>
    </div>
</div>
```

## 🖼️ Adding Images

### Profile Picture

Replace the image placeholder in About section:

```html
<!-- Replace this -->
<div class="image-placeholder">
    <i class="fas fa-user-circle"></i>
</div>

<!-- With this -->
<img src="images/profile.jpg" alt="Your Name" style="width: 300px; height: 300px; border-radius: 50%; object-fit: cover;">
```

### Project Images

Replace project icon placeholders:

```html
<!-- Replace this -->
<div class="project-icon-placeholder">
    <i class="fas fa-chart-line"></i>
</div>

<!-- With this -->
<img src="images/project-name.jpg" alt="Project Name" style="width: 100%; height: 100%; object-fit: cover;">
```

## 🔤 Changing Fonts

### Current Fonts
- **Headings**: Poppins (Display/Headers)
- **Body**: Inter (Body text/Paragraphs)

### To Change Fonts

1. **Find new fonts** at [Google Fonts](https://fonts.google.com/)

2. **Update the import** in `index.html` (line 15):
```html
<link href="https://fonts.googleapis.com/css2?family=YourFont:wght@300;400;500;600;700&display=swap" rel="stylesheet">
```

3. **Update CSS variables** in `css/style.css` (line 20):
```css
--font-primary: 'YourDisplayFont', sans-serif;
--font-secondary: 'YourBodyFont', sans-serif;
```

### Popular Font Combinations

**Modern & Clean**:
- Display: Montserrat
- Body: Open Sans

**Professional**:
- Display: Raleway
- Body: Lato

**Creative**:
- Display: Playfair Display
- Body: Source Sans Pro

**Tech-Focused**:
- Display: Space Grotesk
- Body: IBM Plex Sans

## 🎭 Icon Customization

### Using Font Awesome Icons

Icons are from [Font Awesome](https://fontawesome.com/icons).

**Icon Categories**:
- Brands: `fab fa-icon-name` (LinkedIn, GitHub, etc.)
- Solid: `fas fa-icon-name` (Most icons)
- Regular: `far fa-icon-name` (Outlined versions)

**Example Icons**:
```html
<i class="fab fa-linkedin"></i>      <!-- LinkedIn -->
<i class="fab fa-github"></i>        <!-- GitHub -->
<i class="fas fa-envelope"></i>      <!-- Email -->
<i class="fas fa-code"></i>          <!-- Code -->
<i class="fas fa-database"></i>      <!-- Database -->
<i class="fas fa-chart-line"></i>    <!-- Analytics -->
<i class="fas fa-robot"></i>         <!-- AI/Robot -->
<i class="fab fa-python"></i>        <!-- Python -->
<i class="fab fa-js"></i>            <!-- JavaScript -->
```

## 📏 Layout Adjustments

### Container Width
Change maximum width in `css/style.css` (line 92):
```css
.container {
    max-width: 1200px;  /* Change to 1400px for wider layout */
}
```

### Section Spacing
Adjust spacing in `css/style.css` (line 12):
```css
--spacing-2xl: 4rem;  /* Change to 5rem for more space */
```

### Grid Columns
Adjust project grid in `css/style.css` (line 730):
```css
.projects-grid {
    grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
    /* Change minmax(350px, 1fr) to minmax(400px, 1fr) for wider cards */
}
```

## 🎬 Animation Speed

### Transition Duration
Change in `css/style.css` (line 24):
```css
--transition-fast: 0.2s ease;    /* Faster animations */
--transition-normal: 0.3s ease;  /* Normal speed */
--transition-slow: 0.5s ease;    /* Slower animations */
```

### Scroll Animation
Adjust in `js/main.js` (line 150):
```javascript
threshold: 0.1,  // Change to 0.3 for later trigger
```

## 📱 Responsive Breakpoints

Customize breakpoints in `css/style.css` (lines 950+):

```css
@media (max-width: 1024px) { /* Tablets */ }
@media (max-width: 768px)  { /* Mobile landscape */ }
@media (max-width: 480px)  { /* Mobile portrait */ }
```

## 🔗 Social Media Links

Update all social links in these locations:

1. **Hero Section** (line 82-90)
2. **Contact Section** (line 815-825)
3. **Footer** (line 865-875)

```html
<a href="https://www.linkedin.com/in/your-profile">
<a href="https://github.com/your-username">
<a href="mailto:your-email@example.com">
```

## 🌐 SEO Optimization

### Meta Tags
Add to `<head>` section in `index.html`:

```html
<meta name="description" content="Your portfolio description">
<meta name="keywords" content="your, keywords, here">
<meta name="author" content="Your Name">

<!-- Open Graph / Facebook -->
<meta property="og:type" content="website">
<meta property="og:title" content="Your Name - Portfolio">
<meta property="og:description" content="Your description">
<meta property="og:image" content="link-to-preview-image.jpg">

<!-- Twitter -->
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:title" content="Your Name - Portfolio">
<meta name="twitter:description" content="Your description">
```

### Page Title
Update in `index.html` (line 7):
```html
<title>Your Name | Professional Title</title>
```

## 💬 Contact Form Integration

### Using Formspree (Free & Easy)

1. Sign up at [formspree.io](https://formspree.io/)
2. Update form action:
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

### Using EmailJS

1. Sign up at [emailjs.com](https://www.emailjs.com/)
2. Add their SDK
3. Update the form submission in `js/main.js`

## 🎯 Tips for Best Results

1. **Consistency**: Use the same colors throughout
2. **Hierarchy**: Maintain clear visual hierarchy
3. **White Space**: Don't overcrowd sections
4. **Contrast**: Ensure text is readable on backgrounds
5. **Testing**: Test on multiple devices and browsers
6. **Performance**: Optimize images before adding them
7. **Accessibility**: Maintain good color contrast ratios

---

**Need more help?** Check the README.md for detailed documentation!