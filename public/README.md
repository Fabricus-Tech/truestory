# TrueStory Landing Page

A professional landing page for TrueStory - the TRACE methodology platform.

## Quick Deploy to Firebase

1. Install Firebase CLI (if not already installed):
   ```bash
   npm install -g firebase-tools
   ```

2. Login to Firebase:
   ```bash
   firebase login
   ```

3. Initialize your project:
   ```bash
   firebase init hosting
   ```
   - Select your Firebase project
   - Set public directory to `.` (current directory)
   - Configure as single-page app: No
   - Don't overwrite index.html

4. Deploy:
   ```bash
   firebase deploy
   ```

## File Structure

- `index.html` - Complete single-page website with inline CSS and JavaScript
- All assets are self-contained (no external dependencies except Google Fonts)

## Features

- Fully responsive design
- Smooth animations and transitions
- Dark theme with modern aesthetics
- Coverage indicator system (red/yellow/green)
- Clean, professional layout optimized for pitches

## Customization

To customize:
- Colors: Edit CSS variables in the `:root` section
- Content: Update text directly in the HTML
- Fonts: Replace Google Fonts links in the `<head>`

## Tech Stack

- Pure HTML/CSS/JavaScript
- Google Fonts (JetBrains Mono, Space Mono, DM Sans)
- No build process required
- No external dependencies

---

Good luck with your pitch! 🚀
