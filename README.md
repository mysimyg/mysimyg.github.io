# Amelia's Memorial Website

A beautiful, elegant memorial website for Amelia, inspired by the sophisticated design of Royce Lingerie. This website provides a space to showcase precious photos and memories of your beloved dog.

## Features

- **Elegant Design**: Sophisticated layout with soft colors and beautiful typography
- **Photo Galleries**: Organized sections for different periods of Amelia's life
- **Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **Smooth Animations**: Subtle animations and transitions for a polished experience
- **Easy to Customize**: Simple structure for adding your own content

## File Structure

```
mysimyg.github.io/
├── index.html              # Main homepage
├── styles.css              # Main stylesheet
├── script.js               # JavaScript functionality
├── README.md               # This file
├── photos/                 # Photo collections
│   ├── puppy/              # Puppy photos
│   │   └── index.html      # Puppy gallery page
│   ├── adventures/         # Adventure photos
│   ├── family/             # Family time photos
│   └── senior/             # Senior years photos
└── story/                  # Detailed story section
```

## How to Add Your Photos

### 1. Replace Placeholder Images

The website currently uses placeholder images. To add your actual photos:

1. **Prepare your photos**: Resize them to a reasonable size (recommended: 800x600px or similar aspect ratio)
2. **Add photos to the appropriate folders**:
   - `photos/puppy/` - For puppy photos
   - `photos/adventures/` - For outdoor adventures, walks, trips
   - `photos/family/` - For family moments, cuddles, home life
   - `photos/senior/` - For older years

### 2. Update the HTML

Replace the placeholder divs with actual images. For example, in `photos/puppy/index.html`:

**Before (placeholder):**
```html
<div class="photo-placeholder-large">
    <i class="fas fa-image"></i>
    <p>Add puppy photo 1</p>
</div>
```

**After (with your photo):**
```html
<img src="amelia-puppy-1.jpg" alt="Amelia as a puppy" class="photo-image">
```

### 3. Add CSS for Real Images

Add this CSS to `styles.css` for proper image styling:

```css
.photo-image {
    width: 100%;
    height: 300px;
    object-fit: cover;
    border-radius: 8px;
}

.photo-placeholder-large img {
    width: 100%;
    height: 300px;
    object-fit: cover;
}
```

## Customization Options

### 1. Update Amelia's Information

In `index.html`, you can customize:
- **Name**: Change "Amelia" to your dog's name
- **Years**: Update the dates (currently "2010 - 2023")
- **Story**: Modify the text in the "Her Story" section
- **Memories**: Update the memory cards with your own special moments

### 2. Color Scheme

The current color scheme uses:
- Primary: `#8B7355` (warm brown)
- Background: `#F8F6F3` (soft cream)
- Text: `#333` (dark gray)

You can change these colors in `styles.css` to match your preferences.

### 3. Add More Photo Collections

To add new photo collections:
1. Create a new folder in `photos/` (e.g., `photos/holidays/`)
2. Copy the structure from `photos/puppy/index.html`
3. Update the navigation links in the main `index.html`

## Photo Organization Tips

### Recommended Photo Sizes
- **Hero image**: 1200x800px
- **Gallery photos**: 800x600px
- **Thumbnail photos**: 400x300px

### File Naming
Use descriptive names like:
- `amelia-puppy-first-day.jpg`
- `amelia-adventure-hiking.jpg`
- `amelia-family-couch.jpg`

### Photo Quality
- Use high-quality photos (but compress them for web)
- Ensure good lighting and clear subjects
- Consider the emotional impact of each photo

## Creating Additional Pages

### Story Page
Create `story/index.html` for a detailed biography of Amelia's life.

### Individual Photo Pages
You can create individual pages for special photos with larger views and more detailed captions.

## Technical Notes

- **Hosting**: This site is designed to work with GitHub Pages
- **Browser Support**: Works on all modern browsers
- **Performance**: Optimized for fast loading
- **SEO**: Includes proper meta tags and semantic HTML

## Getting Help

If you need assistance with:
- Adding photos
- Customizing the design
- Creating additional pages
- Technical issues

Feel free to modify the code or ask for help with specific customizations.

## Remembering Amelia

This website is a beautiful way to honor Amelia's memory and share her story with others. Take your time adding photos and memories - each one is precious and helps keep her spirit alive.

---

*Created with love and remembrance for Amelia* 