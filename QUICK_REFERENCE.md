# 🚀 Quick Reference Guide

## All Customizable Sections at a Glance

This is a quick reference showing EXACTLY what to change in each file. Look for `🎨 CUSTOMIZE:` comments in the actual files.

---

## 📄 INDEX.HTML - Home Page

### What to Change:

1. **Page Title** (Line ~6)
   ```html
   <title>YOUR TOPIC HERE</title>
   ```

2. **Main Heading** (Line ~25)
   ```html
   <h1>YOUR TOPIC HERE</h1>
   ```

3. **Introduction Paragraph** (Line ~28)
   - Replace entire paragraph with your introduction

4. **Section Headings** (Multiple locations)
   ```html
   <h2>Your Section Title</h2>
   ```

5. **Lists** (Multiple locations)
   - Replace list items with your content
   - Keep the `<strong>` tags for emphasis

6. **Tables** (Around line ~70)
   - Update table headers
   - Replace all table data
   - Add/remove rows as needed

7. **Information Boxes** (Multiple locations)
   ```html
   <div class="info-box">
       <h3>Your Title</h3>
       <p>Your content...</p>
   </div>
   ```

8. **Images** (Multiple locations)
   ```html
   <img src="YOUR_IMAGE_URL" alt="YOUR DESCRIPTION">
   <p class="image-caption">Your caption</p>
   ```

9. **Footer** (Bottom of page)
   ```html
   <p>Your name/info here</p>
   ```

---

## 📄 TOPIC1.HTML - First Topic

### What to Change:

1. **Page Title**
   ```html
   <title>Topic 1: YOUR TOPIC NAME</title>
   ```

2. **Main Heading**
   ```html
   <h1>Topic 1: YOUR TOPIC NAME</h1>
   ```

3. **All Content Sections**
   - Introduction paragraph
   - All `<h2>` section headings
   - All paragraphs
   - All lists (ordered and unordered)
   - All tables
   - All information/warning/success boxes

4. **Images and Captions**
   - Replace image URLs
   - Update alt text
   - Update captions

5. **Summary Section**
   - Write your own conclusion

6. **Navigation Buttons**
   ```html
   <a href="topic2.html" class="btn">Continue to Topic 2</a>
   ```

---

## 📄 TOPIC2.HTML - Second Topic

### What to Change:

Same as Topic1.html:
1. Page title
2. Main heading
3. All content sections
4. Images and captions
5. Summary
6. Navigation buttons

---

## 📄 REFERENCES.HTML - References Page

### What to Change:

1. **Reference Categories**
   ```html
   <h2>Your Category Name</h2>
   ```

2. **Reference Items**
   ```html
   <div class="reference-item">
       <h3>Resource Title</h3>
       <p><strong>URL:</strong> <a href="URL">URL</a></p>
       <p><strong>Description:</strong> Description here...</p>
       <p><strong>Why it's useful:</strong> Explanation...</p>
   </div>
   ```

3. **Add Your Own References**
   - Official documentation
   - Books
   - Websites
   - Videos
   - Tools

4. **Image Sources**
   - List where you got your images

5. **Acknowledgments**
   - Thank people/organizations who helped

---

## 🎨 STYLES.CSS - Stylesheet

### What to Change:

1. **Header Colors** (Line ~30)
   ```css
   header {
       background: linear-gradient(135deg, #YOUR_COLOR1 0%, #YOUR_COLOR2 100%);
   }
   ```

2. **Heading Colors** (Lines ~70-85)
   ```css
   h1 {
       color: #YOUR_COLOR;
   }
   h2 {
       color: #YOUR_COLOR;
   }
   ```

3. **Button Colors** (Line ~180)
   ```css
   .btn {
       background-color: #YOUR_COLOR;
   }
   .btn:hover {
       background-color: #YOUR_HOVER_COLOR;
   }
   ```

4. **Link Colors** (Line ~195)
   ```css
   main a {
       color: #YOUR_COLOR;
   }
   ```

5. **Font Family** (Line ~15)
   ```css
   body {
       font-family: 'YOUR FONT', sans-serif;
   }
   ```

6. **Footer Colors** (Line ~210)
   ```css
   footer {
       background-color: #YOUR_COLOR;
       color: #YOUR_TEXT_COLOR;
   }
   ```

---

## 🎨 Popular Color Schemes

Copy and paste these into your CSS:

### Blue/Purple (Current)
```css
header { background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); }
h1 { color: #667eea; }
h2 { color: #764ba2; }
.btn { background-color: #667eea; }
.btn:hover { background-color: #764ba2; }
```

### Green/Teal
```css
header { background: linear-gradient(135deg, #11998e 0%, #38ef7d 100%); }
h1 { color: #11998e; }
h2 { color: #38ef7d; }
.btn { background-color: #11998e; }
.btn:hover { background-color: #38ef7d; }
```

### Orange/Red
```css
header { background: linear-gradient(135deg, #f46b45 0%, #eea849 100%); }
h1 { color: #f46b45; }
h2 { color: #eea849; }
.btn { background-color: #f46b45; }
.btn:hover { background-color: #eea849; }
```

### Pink/Purple
```css
header { background: linear-gradient(135deg, #ee9ca7 0%, #ffdde1 100%); }
h1 { color: #ee9ca7; }
h2 { color: #c471ed; }
.btn { background-color: #ee9ca7; }
.btn:hover { background-color: #c471ed; }
```

### Dark Professional
```css
header { background: linear-gradient(135deg, #2c3e50 0%, #3498db 100%); }
h1 { color: #2c3e50; }
h2 { color: #3498db; }
.btn { background-color: #2c3e50; }
.btn:hover { background-color: #3498db; }
```

---

## 🖼️ Free Image Sources

### Where to Get Images:
1. **Unsplash** - https://unsplash.com/
2. **Pexels** - https://pexels.com/
3. **Pixabay** - https://pixabay.com/

### How to Use:
1. Search for your topic
2. Click on an image
3. Copy the image URL
4. Paste into your HTML:
   ```html
   <img src="PASTE_URL_HERE" alt="Description">
   ```

### Unsplash URL Format:
```
https://images.unsplash.com/photo-XXXXXXXXX?w=800
```
Always add `?w=800` at the end to optimize size!

---

## 📋 HTML Elements Quick Reference

### Headings
```html
<h1>Largest Heading</h1>
<h2>Section Heading</h2>
<h3>Subsection Heading</h3>
```

### Paragraphs
```html
<p>Your paragraph text here...</p>
```

### Bold Text
```html
<strong>Bold text</strong>
```

### Italic Text
```html
<em>Italic text</em>
```

### Links
```html
<a href="page.html">Link Text</a>
<a href="https://example.com" target="_blank">External Link</a>
```

### Unordered List (Bullets)
```html
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ul>
```

### Ordered List (Numbers)
```html
<ol>
    <li>First item</li>
    <li>Second item</li>
    <li>Third item</li>
</ol>
```

### Images
```html
<img src="image.jpg" alt="Description">
<p class="image-caption">Caption text</p>
```

### Tables
```html
<table>
    <tr>
        <th>Header 1</th>
        <th>Header 2</th>
    </tr>
    <tr>
        <td>Data 1</td>
        <td>Data 2</td>
    </tr>
</table>
```

### Information Boxes
```html
<!-- Blue info box -->
<div class="info-box">
    <h3>Title</h3>
    <p>Content...</p>
</div>

<!-- Yellow warning box -->
<div class="warning-box">
    <h3>Title</h3>
    <p>Content...</p>
</div>

<!-- Green success box -->
<div class="success-box">
    <h3>Title</h3>
    <p>Content...</p>
</div>
```

### Buttons
```html
<a href="page.html" class="btn">Button Text</a>
```

---

## ✅ Pre-Submission Checklist

Before you submit, check:

- [ ] Changed all page titles
- [ ] Updated all headings
- [ ] Replaced all content with your topic
- [ ] Updated all images and alt text
- [ ] Updated all image captions
- [ ] Changed colors (if desired)
- [ ] Updated footer information
- [ ] All links work
- [ ] All pages load correctly
- [ ] Tested on mobile (resize browser)
- [ ] Spell-checked all content
- [ ] Added proper references
- [ ] All files in same folder
- [ ] Validated HTML (https://validator.w3.org/)
- [ ] Validated CSS (https://jigsaw.w3.org/css-validator/)

---

## 🆘 Emergency Fixes

### Images Not Showing?
1. Check image URL is correct
2. Make sure image file is in same folder
3. Check filename spelling (case-sensitive!)

### Styles Not Working?
1. Verify styles.css is in same folder
2. Check `<link rel="stylesheet" href="styles.css">` in HTML
3. Clear browser cache (Ctrl+F5)

### Links Broken?
1. Check filename spelling
2. Make sure all files are in same folder
3. Verify file extensions are .html

### Colors Look Wrong?
1. Use # before hex codes (#667eea)
2. Check for typos in color values
3. Use color picker: https://htmlcolorcodes.com/

---

## 💡 Quick Tips

1. **Save often** - Save after every change
2. **Test frequently** - Preview in browser after changes
3. **One page at a time** - Don't try to do everything at once
4. **Use Find & Replace** - Change repeated text quickly
5. **Keep it simple** - Don't overcomplicate
6. **Be consistent** - Use same style on all pages
7. **Proofread** - Check spelling and grammar

---

## 🎯 Most Important Changes

If you only have time for the essentials, change these:

1. **All page titles** (`<title>` tags)
2. **All main headings** (`<h1>` tags)
3. **Introduction paragraphs** on each page
4. **Section headings** (`<h2>` tags)
5. **Footer information**
6. **At least 3 references** on references page

---

## 📞 Need Help?

1. Read the full CUSTOMIZATION_GUIDE.md
2. Check comments in the HTML/CSS files (marked with 🎨)
3. Use browser developer tools (F12)
4. Search on Google or Stack Overflow
5. Ask your instructor

---

**Remember: All sections marked with 🎨 CUSTOMIZE: in the files should be changed to match your topic!**

Good luck! 🚀