# JPIEM Website - Customization Checklist

## 🎯 Priority 1: Essential Information (Do First!)

### [ ] Church Information
- **Address:** Update in Contact Section (Line ~290 in index.html)
  - Find: `<p>[Your Church Address]<br>[City, State ZIP]</p>`
  - Replace with: `<p>123 Main Street<br>Your City, ST 12345</p>`

- **Phone:** Update in Contact Section
  - Find: `<p>+1 (XXX) XXX-XXXX</p>`
  - Replace with: `<p>+1 (555) 123-4567</p>`

- **Email:** Update in Contact Section  
  - Find: `<p>info@jpiem.com</p>`
  - Replace with: `<p>your-email@yourchurch.com</p>`

### [ ] Service Times
- Find in Contact Section: `<p>Sunday: 9:00 AM<br>Wednesday: 7:00 PM</p>`
- Update with your actual service times

### [ ] Website Title
- Find in `index.html` header: `<title>Jesus Power International Evangelical Ministry</title>`
- Update if desired (appears in browser tab)

---

## 🎨 Priority 2: Branding

### [ ] Color Scheme (Optional)
Edit `css/styles.css` line 8-14:
```css
:root {
    --primary-color: #c41e3a;      /* Main color (currently red) */
    --secondary-color: #ffc700;    /* Accent color (currently gold) */
}
```

**Use hex color codes from:**
- colorhexa.com
- colorpicker.com  
- Your brand guidelines

### [ ] Logo/Images
1. Create folder: `assets/images/`
2. Add your files:
   - Church logo
   - Pastor photo
   - Building photos
   - Banner image

3. Update HTML image references

---

## 📝 Priority 3: Content Updates

### [ ] About Section
Edit in `index.html` around line 108:
```html
<p>Jesus Power International Evangelical Ministry is dedicated to...</p>
```
- Replace mission statement
- Keep your vision brief (2-3 sentences)

### [ ] Core Values
Edit the values list (around line 117-122):
```html
<li><strong>Faith:</strong> We trust in God's word and guidance</li>
```
- Update 4 core values
- Keep descriptions short (1 line each)

### [ ] Services/Ministries
Edit Service Cards (around line 155-200):
- Sunday Worship
- Bible Study  
- Children's Ministry
- Prayer Ministry
- Community Service
- Worship & Praise

Update titles and descriptions for each

### [ ] Events
Edit Events Section (around line 240-300):
Update 4 example events with:
- Date (day/month)
- Event name
- Time
- Location

---

## 🌐 Priority 4: Social & Contact

### [ ] Social Media Links
Edit Footer section (around line 355-365):
```html
<a href="https://facebook.com/your-page">
```
Update URLs for:
- Facebook
- Twitter
- Instagram
- YouTube

### [ ] Contact Form
Already functional! Currently shows success message on submit.

**To receive actual emails:**
- Sign up at formspree.io
- Follow their integration steps
- Update form action attribute

---

## 📄 Priority 5: Add Sermons Page

**Already created!** The `sermons.html` page is ready to use:
- 6 sample sermon cards
- Filter buttons
- Featured series section
- Full responsive design

**To customize:**
1. Replace sermon titles with your actual sermons
2. Update speaker names
3. Add sermon dates
4. Update descriptions
5. Link to audio/video (advanced)

**Link from main page:**
Add to Navigation menu in `index.html`:
```html
<li class="nav-item">
    <a href="sermons.html" class="nav-links">Sermons</a>
</li>
```

---

## 📱 Testing Checklist

### [ ] Desktop Browser
- [ ] Chrome
- [ ] Firefox
- [ ] Edge
- [ ] Safari (if available)

### [ ] Mobile Testing
- [ ] iPhone (5.5"+)
- [ ] Android Phone
- [ ] Tablet
- [ ] Check in portrait & landscape

### [ ] Link Testing
- [ ] All navigation links work
- [ ] Anchor links (smooth scrolling)
- [ ] External links open correctly
- [ ] No 404 errors

### [ ] Form Testing
- [ ] Contact form validates
- [ ] Required fields show error
- [ ] Success message displays
- [ ] Email field validates

### [ ] Content Verification
- [ ] No broken images
- [ ] Text is readable
- [ ] No typos or errors
- [ ] Information is accurate

---

## 🚀 Deployment Checklist

### Before Publishing:

- [ ] All contact info updated
- [ ] All events current
- [ ] All links tested
- [ ] Mobile view verified
- [ ] Images optimized
- [ ] No placeholder text remains
- [ ] Social media links correct
- [ ] Chosen hosting provider

### After Publishing:

- [ ] URL works correctly
- [ ] All pages load properly
- [ ] Forms work on live site
- [ ] Mobile views work
- [ ] Share on social media
- [ ] Add Google Analytics
- [ ] Submit to Google Search Console

---

## 📊 File Reference

| Section | File | Lines |
|---------|------|-------|
| Navigation | index.html | 13-35 |
| Hero | index.html | 37-45 |
| About | index.html | 48-80 |
| Services | index.html | 83-130 |
| Events | index.html | 133-200 |
| Contact | index.html | 203-270 |
| Footer | index.html | 273-310 |
| Styling | css/styles.css | 1-650 |
| JavaScript | js/script.js | 1-100 |
| Sermons Page | sermons.html | 1-400 |

---

## 🎓 Common Customizations

### Change "JPIEM" Logo
In `index.html` line 13:
```html
<div class="navbar-logo">
    <i class="fas fa-cross"></i> JPIEM
</div>
```
- Replace "JPIEM" with your abbreviation
- Change icon: See font-awesome.com for options
- Example: `<i class="fas fa-heart"></i>`

### Add New Page
1. Create `newpage.html`
2. Copy navbar and footer from `index.html`
3. Add your content
4. Link from main navigation
5. Add to footer links

### Change Font
Find in `css/styles.css`:
```css
font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
```
Replace with your choice (include fallbacks)

### Add Background Image
Find hero section in `css/styles.css`:
```css
.hero {
    background: linear-gradient(135deg, var(--primary-color) 0%, var(--dark-bg) 100%);
}
```
Change to:
```css
.hero {
    background: url('assets/images/church.jpg') center/cover;
}
```

---

## 🛠️ Advanced Customizations

### Add Newsletter Signup
1. Integrate with Mailchimp (mailchimp.com)
2. Follow their website embed instructions
3. Add form to homepage

### Add Online Giving
Options:
- PayPal giving (paypal.com/donate)
- Stripe giving (stripe.com)
- GiveWP (givewp.com)
- Tithe.ly (tithe.ly)

### Add Sermon Audio/Video
Services:
- YouTube (free)
- SoundCloud (for audio)
- Vimeo (professional)
- Mixlr (live streaming)

### Add Prayer Request Form
Options:
- Formspree with custom form
- Google Forms embedded
- Church management software

---

## 📞 Support Resources

### Getting Help:
1. Read README.md (full documentation)
2. Check QUICK_START.md (basic setup)
3. Look at code comments in files
4. Google the specific issue
5. Ask ChatGPT for code help
6. Contact professional developer if stuck

### Free Tools:
- **Figma** - Design mockups
- **TinyPNG** - Compress images
- **ColorPick** - Find brand colors
- **WaveAccess** - Check accessibility

### Paid Services:
- Web developer freelancers
- Wix or Squarespace (pre-built)
- Local IT consultants
- Church tech companies

---

## ✨ Pro Tips

1. **Keep Updated** - Update events every week
2. **Fresh Content** - Add new messages/events regularly
3. **Mobile First** - Always test mobile
4. **Fast Loading** - Optimize images (<100KB each)
5. **Easy Navigation** - 3 clicks max to any info
6. **Clear CTAs** - Tell people what to do
7. **Professional Look** - Use quality photos
8. **Regular Backups** - Save copies monthly

---

## 📅 Maintenance Schedule

### Weekly
- [ ] Update event listings
- [ ] Check form submissions
- [ ] Respond to contact requests

### Monthly
- [ ] Add new sermon
- [ ] Update photo gallery
- [ ] Check for broken links
- [ ] Backup all files

### Quarterly
- [ ] Review analytics
- [ ] Update testimonials
- [ ] Refresh landing page
- [ ] Check SEO

### Annually
- [ ] Plan major updates
- [ ] Redesign if needed
- [ ] Review user feedback
- [ ] Update information

---

**Remember:** This is your church's digital home. Keep it welcoming, updated, and reflective of your ministry!

---

**Created:** May 2024  
**Version:** 1.0  
**Last Updated:** May 2024
