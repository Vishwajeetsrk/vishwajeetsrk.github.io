# Quick Start Guide

## 🚀 Getting Started in 3 Steps

### Step 1: View Your Portfolio
Simply open `index.html` in any modern web browser to view your portfolio website.

### Step 2: Customize Content
Edit the following sections in `index.html`:

1. **Personal Information** (Lines 45-55):
   - Name, tagline, and description
   - Update social media links

2. **About Section** (Lines 95-150):
   - Update your bio and statistics
   - Change contact information

3. **Skills Section** (Lines 155-350):
   - Add/remove skills
   - Adjust proficiency percentages (data-skill attribute)

4. **Experience Section** (Lines 355-480):
   - Update job positions and dates
   - Modify achievements and tags

5. **Projects Section** (Lines 485-650):
   - Replace with your actual projects
   - Update links to GitHub/live demos
   - Change technology tags

6. **Education Section** (Lines 655-780):
   - Update degrees and certifications
   - Modify institutions and dates

7. **Contact Section** (Lines 785-850):
   - Update contact form action
   - Modify contact details

### Step 3: Customize Design
Edit `css/style.css` to change colors and styling:

```css
:root {
    --primary-color: #1e40af;      /* Main brand color */
    --secondary-color: #10b981;    /* Accent color */
    --accent-color: #f59e0b;       /* Highlight color */
}
```

## 🎨 Quick Customizations

### Change Theme Colors
Find and replace color codes in `css/style.css`:
- `#1e40af` - Primary blue
- `#10b981` - Secondary green
- `#f59e0b` - Accent gold

### Update Profile Image
Replace the `.image-placeholder` section with an actual image:
```html
<div class="about-image">
    <img src="your-image.jpg" alt="Vishwajeet S. R. K.">
</div>
```

### Add Project Screenshots
Replace project icon placeholders with images:
```html
<div class="project-image">
    <img src="project-screenshot.jpg" alt="Project Name">
</div>
```

### Update Social Links
Find and update all social media links:
- LinkedIn: `https://www.linkedin.com/in/vishwajeetsrk`
- GitHub: `https://github.com/your-username`
- Email: `vishwajeetsrk@gmail.com`

## 📱 Test Responsiveness

1. **Desktop**: Open in full browser window
2. **Tablet**: Resize browser to 768-1024px width
3. **Mobile**: Resize browser to < 768px or use device emulator

## 🌐 Deploy Your Portfolio

### Option 1: GitHub Pages (Free)
1. Create a GitHub repository
2. Push your code to the repository
3. Go to Settings > Pages
4. Select main branch and save
5. Your site will be live at `https://yourusername.github.io/repository-name`

### Option 2: Netlify (Free)
1. Sign up at netlify.com
2. Drag and drop your project folder
3. Your site will be live instantly with a custom URL

### Option 3: Vercel (Free)
1. Sign up at vercel.com
2. Import your GitHub repository
3. Deploy with one click

## 🔧 Troubleshooting

### Dark Mode Not Working
- Clear browser cache
- Check browser console for errors
- Ensure JavaScript is enabled

### Animations Not Showing
- Check if you're scrolling through sections
- Verify browser supports Intersection Observer API
- Ensure JavaScript file is loaded correctly

### Particles Not Displaying
- Check internet connection (CDN requirement)
- Verify particles.js script is loaded
- Check browser console for errors

### Contact Form Not Submitting
- Currently shows success message locally only
- Integrate with backend service (e.g., Formspree, EmailJS) for actual email functionality

## 📞 Need Help?

If you encounter any issues:
1. Check the README.md for detailed documentation
2. Review the code comments in each file
3. Ensure all CDN links are accessible
4. Contact: vishwajeetsrk@gmail.com

## ✅ Pre-Launch Checklist

Before deploying your portfolio:

- [ ] Updated all personal information
- [ ] Changed all placeholder links to actual URLs
- [ ] Added project screenshots/images
- [ ] Tested on multiple devices and browsers
- [ ] Checked all navigation links work
- [ ] Verified contact form functionality
- [ ] Updated meta tags for SEO
- [ ] Added Google Analytics (optional)
- [ ] Tested dark/light mode toggle
- [ ] Checked mobile menu functionality
- [ ] Verified social media links
- [ ] Spell-checked all content
- [ ] Optimized images for web (if added)
- [ ] Tested website loading speed

## 🎯 Next Steps After Launch

1. **Share Your Portfolio**:
   - Add link to LinkedIn profile
   - Share on social media
   - Include in email signature
   - Add to GitHub profile README

2. **Maintain Your Portfolio**:
   - Update projects regularly
   - Add new skills as you learn
   - Keep experience section current
   - Refresh design annually

3. **Track Analytics** (Optional):
   - Add Google Analytics
   - Monitor visitor traffic
   - Track popular sections
   - Optimize based on data

## 💡 Pro Tips

1. **Keep It Updated**: Refresh your portfolio every 3-6 months
2. **Quality Over Quantity**: Showcase your best 5-8 projects
3. **Tell Stories**: Each project should tell a problem-solution story
4. **Make It Personal**: Add personality while staying professional
5. **Mobile First**: Most visitors view on mobile - ensure it works perfectly
6. **Fast Loading**: Keep images optimized and minimize heavy scripts
7. **Call to Action**: Make it easy for visitors to contact you
8. **Proofread**: Check for typos and grammatical errors

---

**Happy Coding! 🚀**

If you found this portfolio template helpful, consider giving it a star on GitHub!