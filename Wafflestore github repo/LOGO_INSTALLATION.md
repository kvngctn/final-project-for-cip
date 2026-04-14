<!-- LOGO INSTALLATION GUIDE -->

# Add Your Logo

## Instructions

1. **Prepare Your Logo Image**
   - Save your logo as `logo.png` in the `images/` folder
   - Recommended size: 200x200 pixels or larger (square format preferred)
   - Supported formats: .png, .jpg, .jpeg, .svg, .gif
   - For best quality, use PNG with transparency

2. **File Path**
   - Location: `images/logo.png`
   - Current references in HTML files: `<img src="images/logo.png" ...>`

3. **Where Your Logo Appears**
   - Splash page (animated, larger size)
   - Navigation bar (40px height)
   - Homepage hero section (large display)
   - About page
   - All other pages in navigation

4. **Logo Sizing**
   - Responsive sizing automatically adjusts for all screen sizes
   - Ensure your logo looks good at small sizes (navigation bar)
   - Will scale up to 200x200px on splash page

## Alternative: Using Different Logo Formats

If using a different filename or format, update these files:

1. **index.html** - Line ~17
   ```html
   <img src="images/your-logo.png" alt="Central Food Hub" ...>
   ```

2. **home.html** - Lines ~26 and ~64
   ```html
   <img src="images/your-logo.png" alt="Central Food Hub" ...>
   ```

3. **Other pages** - Replace all `images/logo.png` references

## Quick Logo Replacement

Search for `images/logo.png` in all files and replace with your logo path.

---

**Current users from the attachment:** Copy the Central Food Hub logo image and save as `logo.png` in the `images/` folder.
