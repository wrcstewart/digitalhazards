# Master List of Digital Hazards - Website

A multi-page, interactive website presenting 77 digital hazards across AI, VR, Social Media, and Video Games, organized into 7 thematic categories.

## Features

- **Multi-page navigation** - Landing page plus 7 category pages
- **PDF Research Reports** - Download links to 4 comprehensive academic reports
- **Clean data presentation** - All 77 hazards organized in clear tables
- **Responsive design** - Mobile-friendly layout that works on phones, tablets, and desktops
- **Modern styling** - Clean, professional design with neutral color scheme
- **Static HTML/CSS** - No frameworks or dependencies required

## Adding PDF Reports

The website includes download buttons for 4 PDF research reports. To make these work:

1. **Upload your PDF files to your GitHub repository root**
   
   Upload these files to the **same directory** as `index.html`:
   - `AI_Hazards_Report.pdf`
   - `Social_Media_Impacts.pdf`
   - `VR_Report.pdf`
   - `Video_Game_Impacts.pdf`

2. **That's it!**
   
   The links are already configured as relative paths. Once you upload the PDFs to the root directory, the download and view buttons will work automatically.

**Note:** Both "Download" and "View Online" buttons will open the PDF. The browser will handle whether to download or display based on user settings.

## File Structure

```
master-list-website/
├── index.html              # Landing page with category overview
├── category1.html          # Harassment and Toxic Behavior (10 hazards)
├── category2.html          # Privacy and Security (5 hazards)
├── category3.html          # Cognitive and Skill Impairment (4 hazards)
├── category4.html          # Mental Health (22 hazards)
├── category5.html          # Physical Health (5 hazards)
├── category6.html          # Social, Political and Economic (29 hazards)
├── category7.html          # Environmental Impact (2 hazards)
├── css/
│   └── style.css          # All styling and responsive design
└── README.md              # This file
```

## Usage

### Local Testing

1. Open `index.html` in any modern web browser
2. Navigate between categories using the navigation menu
3. All functionality works without a web server (can be opened directly from file system)

### Deploying to GitHub Pages

1. Create a new repository on GitHub
2. Upload all files maintaining the folder structure
3. Go to repository Settings → Pages
4. Select branch (usually `main`) and root directory
5. Save and wait for deployment
6. Your site will be available at: `https://[username].github.io/[repository-name]/`

### Deploying to Other Hosting

The website is completely static and can be hosted on:
- GitHub Pages (free)
- Netlify (free)
- Vercel (free)
- Any web server (Apache, Nginx, etc.)

Simply upload all files maintaining the folder structure.

## Platform Abbreviations

- **AI** = Artificial Intelligence
- **SM** = Social Media
- **VG** = Video Games
- **VR** = Virtual Reality

## Categories

1. **Harassment and Toxic Behavior** (10 hazards)
2. **Privacy and Security** (5 hazards)
3. **Cognitive and Skill Impairment** (4 hazards)
4. **Mental Health and Psychological Harms** (22 hazards)
5. **Physical Health Impacts** (5 hazards)
6. **Social, Political and Economic Harms** (29 hazards)
7. **Environmental Impact** (2 hazards)

**Total: 77 distinct hazards**

## Browser Compatibility

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Customization

To modify colors, edit CSS variables in `css/style.css`:

```css
:root {
  --primary-color: #2c3e50;
  --accent-color: #3498db;
  /* ... other variables */
}
```

## License

This website presents academic research on digital technology hazards. Please cite appropriately if using this content.

## Contact

For questions about the research or this website, please contact the project maintainer.
