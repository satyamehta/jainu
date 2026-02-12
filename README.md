# 💝 Interactive Valentine's Day Gift

A beautiful, interactive web page for your wife featuring:
- ✨ Animated timeline of your love story
- 💌 "Open when..." style love letters
- 🎨 Floating hearts and smooth animations
- 📱 Fully responsive design

## 🎨 How to Customize

### 1. **Update Timeline Events**
Open `index.html` and find the timeline items (starting around line 380). Change:
- **Date labels**: `<div class="timeline-date">The Beginning</div>`
- **Titles**: `<div class="timeline-title">The Day We Met</div>`
- **Descriptions**: The text in `<div class="timeline-description">`

### 2. **Add Your Photos**
Replace the placeholder divs with actual images:

```html
<!-- Replace this: -->
<div class="timeline-image-placeholder">📸 Add your photo here</div>

<!-- With this: -->
<img src="your-photo.jpg" style="width: 100%; border-radius: 10px; margin-top: 15px;" alt="Our memory">
```

You can either:
- Upload photos to the same folder and reference them: `src="photo1.jpg"`
- Use image URLs: `src="https://yourimage.com/photo.jpg"`

### 3. **Customize Love Letters**
Find the `letters` object in the JavaScript (around line 560) and edit:
- Letter titles
- Letter content
- Add more letters by duplicating the pattern

### 4. **Change Colors**
Update the gradient colors in the CSS:
- Main gradient: `background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);`
- Try these alternatives:
  - Romantic pink: `#f093fb 0%, #f5576c 100%`
  - Warm sunset: `#fa709a 0%, #fee140 100%`
  - Ocean blue: `#4facfe 0%, #00f2fe 100%`

### 5. **Add More Timeline Events**
Copy one of the timeline items and paste it. The alternating left/right layout happens automatically!

## 🚀 Deploying to GitHub Pages

### Step 1: Create a Repository
1. Go to GitHub and create a new repository
2. Name it something like `valentine-gift` (can be private)
3. Don't initialize with README (we already have files)

### Step 2: Push Your Code
```bash
cd valentine-gift
git init
git add .
git commit -m "Initial commit - Valentine's gift"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/valentine-gift.git
git push -u origin main
```

### Step 3: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click **Settings**
3. Scroll down to **Pages** (left sidebar)
4. Under **Source**, select `main` branch
5. Click **Save**
6. Your site will be live at: `https://YOUR-USERNAME.github.io/valentine-gift/`

**Note:** The site will be public even if the repo is private! The URL will be hard to guess though.

## 📱 Testing Locally

Just open `index.html` in your browser - no server needed!

## 💡 Tips

- **Keep it secret**: Don't commit any real private information to GitHub
- **Test on mobile**: The design is responsive, but test it on your phone
- **Add music**: You can add background music by including an `<audio>` tag
- **Make it personal**: The more specific details you add, the more special it will be

## 🎁 When to Share

Send her the link on Valentine's Day! You can:
- Text her the URL
- Create a QR code that links to it
- Set it as the homepage on her computer/phone

## ❤️ Making It Extra Special

Consider adding:
1. **Voice messages**: Record audio messages and embed them
2. **Video messages**: Link to unlisted YouTube videos
3. **Future dates**: Add a section with date ideas for the year
4. **Inside jokes**: Personalize with your unique memories
5. **Photo gallery**: Create a grid of your favorite photos together

---

Made with ❤️ for your special someone
