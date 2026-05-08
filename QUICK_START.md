# Quick Start Guide - JPIEM Website

## 🚀 Getting Started (5 Minutes)

### Step 1: View Your Website
1. Open the `index.html` file in your web browser
   - Simply double-click the file from Windows Explorer, OR
   - Right-click → Open With → Your preferred browser

2. Test all sections and navigation
3. Try the mobile view - resize your browser window to see responsive design

### Step 2: Essential Customizations (Do This First!)

#### Update Contact Information
Edit `index.html` and find these sections:

**Location:**
```html
<p>[Your Church Address]<br>[City, State ZIP]</p>
```
Replace with your actual address.

**Phone Number:**
```html
<p>+1 (XXX) XXX-XXXX</p>
```
Replace with your church phone number.

**Email:**
```html
<p>info@jpiem.com</p>
```
Replace with your church email address.

**Service Times:**
```html
<p>Sunday: 9:00 AM<br>Wednesday: 7:00 PM</p>
```
Update with your actual service times.

#### Update Events
Modify the events in the Events section with your actual upcoming events:
- Update dates (day and month)
- Update event titles
- Update locations
- Update times

### Step 3: Customize Colors (Optional)

If you want to change the color scheme:

1. Open `css/styles.css`
2. Find this section at the top:
```css
:root {
    --primary-color: #c41e3a;      /* Red - Main color */
    --secondary-color: #ffc700;    /* Gold - Accent color */
    --dark-bg: #1a1a1a;            /* Dark background */
    --light-bg: #f5f5f5;           /* Light background */
}
```

3. Replace the color codes with your preferred colors
   - Use online tools like: colorhexa.com or colorpicker.com

### Step 4: Add Your Logo/Images

1. Create an `assets` folder (already exists)
2. Add your church logo/images to this folder
3. In `index.html`, replace the image placeholder with:
```html
<img src="assets/your-church-logo.png" alt="Church Logo" style="height: 80px;">
```

### Step 5: Update Social Media Links

In the footer section of `index.html`, update:
```html
<a href="https://facebook.com/your-page">
    <i class="fab fa-facebook"></i>
</a>
<a href="https://twitter.com/your-page">
    <i class="fab fa-twitter"></i>
</a>
<a href="https://instagram.com/your-page">
    <i class="fab fa-instagram"></i>
</a>
<a href="https://youtube.com/your-channel">
    <i class="fab fa-youtube"></i>
</a>
```

Replace URLs with your actual social media profiles.

---

## 📁 File Guide

| File | Purpose |
|------|---------|
| `index.html` | Main homepage - Edit for content |
| `sermons.html` | Sermons/messages page - Add your sermons here |
| `css/styles.css` | All styling - Modify colors and design here |
| `js/script.js` | Interactivity - Advanced users only |
| `README.md` | Full documentation |
| `assets/` | Store images, logos, and media files |

---

## 🌐 How to Publish Your Website

### Option 1: Free Hosting - GitHub Pages (Easiest)
1. Create a free GitHub account at github.com
2. Create a new repository named: `yourusername.github.io`
3. Upload all your files to this repository
4. Your site will be live at: `https://yourusername.github.io`

**Video Tutorial:** Search "GitHub Pages free hosting" on YouTube

### Option 2: Free Hosting - Netlify
1. Go to netlify.com
2. Click "New site from Git" or drag and drop your files
3. Your site is live immediately!

### Option 3: Paid Hosting (More Control)
Popular options:
- **Bluehost** - $2.95/month (includes domain)
- **GoDaddy** - Various plans
- **SiteGround** - $2.99/month
- **Namecheap** - Budget-friendly

Steps:
1. Buy domain and hosting
2. Upload files via FTP or File Manager
3. Set `index.html` as home page
4. You're live!

---

## ✅ Before Going Live - Checklist

- [ ] All contact information updated
- [ ] Service times correct
- [ ] Events are current
- [ ] Social media links updated
- [ ] Logo/images added
- [ ] All links work (test by clicking)
- [ ] Mobile view looks good (test in browser)
- [ ] Forms work (try submitting contact form)
- [ ] No broken links or typos

---

## 📱 Testing Your Website

### Desktop Testing
1. Resize browser window to different sizes
2. Test all navigation links
3. Click all buttons
4. Try the contact form

### Mobile Testing
1. Test on actual smartphone (best option)
2. Use Chrome DevTools (F12 → Click phone icon)
3. Test both portrait and landscape modes

### Browser Testing
Test in:
- Chrome
- Firefox
- Safari (if on Mac)
- Edge

---

## 🎨 Next Steps to Enhance Your Website

### Add Photos
- Professional church photos
- Team/pastor photos
- Community service photos
- Update placeholder images

### Add More Pages
- Beliefs/Doctrine page
- Ministry pages
- Prayer request page
- Online giving page

### Advanced Features
- Sermon audio/video
- Photo gallery
- Event registration
- Donations/Giving
- Email newsletter signup

### SEO & Marketing
- Add Google Analytics to track visitors
- Submit to Google Search Console
- Create social media content
- Link from other websites

---

## 🆘 Troubleshooting

### Pages not loading correctly
- Clear browser cache (Ctrl+Shift+Delete)
- Check file names and paths match exactly
- Ensure all files are in correct folders

### Styles not applied
- Refresh the page (Ctrl+F5)
- Check CSS file path is correct
- Verify CSS file is in `css/` folder

### Mobile menu not working
- Update browser (F12 → Check console for errors)
- Clear cache and reload
- Test in different browser

### Links don't work
- Check URLs are correct
- Test with full paths: `index.html#about`
- Verify anchor links exist in HTML

---

## 📧 Contact Form Setup

Currently, the contact form displays a success message but doesn't send emails automatically.

To actually receive emails:

### Option 1: Use Formspree (Easiest)
1. Go to formspree.io
2. Create account
3. Follow their instructions to integrate with your form
4. Receive emails when people submit forms

### Option 2: Use Your Email Provider
Contact your hosting provider - they usually offer:
- Built-in form handlers
- Email forwarding
- Contact form builders

### Option 3: Use Third-Party Service
- Netlify Forms (if using Netlify)
- Basin.io
- FormBucket
- MailerLite

---

## 📚 Resources & Learning

### Website Resources
- W3Schools.com - Learn HTML, CSS, JavaScript
- MDN Web Docs - Mozilla's web documentation
- StackOverflow.com - Get help with coding issues
- Canva.com - Design graphics for your site

### Church-Specific Tools
- ChurchCommunityBuilder.com - Church management
- Planning Center - Worship planning & scheduling
- ChurchSpace.com - Church management software

### Design Inspiration
- Dribbble.com - Web design inspiration
- Behance.net - Design portfolio site
- Pinterest.com - Church website ideas

---

## 💡 Pro Tips

1. **Keep Content Fresh** - Update events and messages regularly
2. **Use Photos** - Add professional photos to engage visitors
3. **Mobile First** - Always test on mobile
4. **Fast Loading** - Compress images before uploading
5. **Easy Navigation** - Make it easy to find information
6. **Clear Call-to-Action** - Tell people what to do (visit, give, pray, etc.)
7. **Add Your Touch** - Customize colors and content to match your brand
8. **Regular Backups** - Save copies of your files

---

## 🎓 Learning Path

If you want to learn more:

1. **Start Here:** w3schools.com HTML & CSS tutorials (2-3 hours)
2. **Next:** Learn basic JavaScript (2-3 hours)
3. **Then:** Practice by modifying your website
4. **Finally:** Build your own projects

---

## 📞 Getting Professional Help

If you need help:

1. **Local Web Developer** - Hire someone local
2. **Fiverr/Upwork** - Freelance developers
3. **WordPress Developer** - If you want CMS
4. **Church Tech Support** - Some church software companies offer this

**Budget Range:** $500-$2,000 for professional setup

---

## 🎯 Success Metrics

After launching, track:
- How many people visit
- Which pages are most popular
- How long people stay
- Where visitors come from
- Contact form submissions

Use **Google Analytics** (free) to track these metrics.

---

## Happy to Help!

This website is ready to use. Make it your own by:
1. Adding your content
2. Using your colors
3. Sharing with your community
4. Getting feedback and improving

**Remember:** Your website represents your ministry. Keep it updated and engaging!

---

**Version:** 1.0  
**Last Updated:** May 2024  
**Support:** For technical issues, consult the README.md file or contact a web developer.
