# Pound Ridge Party 2025 Campaign Website

Official campaign website for the Pound Ridge Party 2025 election slate:
- **McCown** for Town Supervisor
- **Avellino** for Town Board
- **Asaro** for Town Board

## About This Campaign

Our platform focuses on fiscal responsibility and transparent governance, addressing the issues highlighted in the New York State Comptroller's audit of Pound Ridge's financial practices.

### Key Issues
- **Fiscal Oversight**: Implementing proper competitive bidding and claims auditing
- **Transparent Governance**: Ending late financial filings and ensuring accountability
- **Comprehensive Planning**: Completing the town's comprehensive plan
- **Infrastructure Development**: Responsible investment with proper oversight

## Website Features

- **Responsive Design**: Mobile-first approach with modern UI/UX
- **Accessibility**: WCAG compliant with proper contrast and navigation
- **Performance**: Optimized for fast loading and SEO
- **Security**: Proper headers and best practices implemented

## Deployment

This website is designed for easy deployment to Vercel:

### Quick Deploy to Vercel

1. **Install Vercel CLI** (if not already installed):
   ```bash
   npm i -g vercel
   ```

2. **Deploy from this directory**:
   ```bash
   vercel
   ```

3. **Follow the prompts**:
   - Set up and deploy: `Y`
   - Which scope: Select your account
   - Link to existing project: `N` (for first deployment)
   - Project name: `pound-ridge-party-2025`
   - Directory: `./` (current directory)

### Manual Deployment Steps

1. Create a new project on [Vercel Dashboard](https://vercel.com/dashboard)
2. Connect your Git repository or upload files directly
3. Set build settings:
   - Framework Preset: `Other`
   - Build Command: (leave empty)
   - Output Directory: `./`
4. Deploy!

### Custom Domain Setup

After deployment, you can add a custom domain:
1. Go to your project settings in Vercel
2. Navigate to "Domains"
3. Add your domain (e.g., `poundridgeparty.com`)
4. Configure DNS records as instructed

## Local Development

To run locally for testing:

```bash
# Using Python (if available)
python -m http.server 3000

# Using Node.js (if you have http-server installed)
npx http-server -p 3000

# Using PHP (if available)
php -S localhost:3000
```

Then open `http://localhost:3000` in your browser.

## File Structure

```
public_website/
├── index.html          # Main homepage
├── styles.css          # All CSS styles
├── script.js           # JavaScript functionality
├── package.json        # Project metadata
├── vercel.json         # Vercel deployment config
└── README.md           # This file
```

## Content Management

### Updating Candidate Information
Edit the candidates section in `index.html` around line 120-180.

### Modifying Issues/Platform
Update the issues section in `index.html` around line 80-120.

### Changing Audit Facts
Modify the audit facts section in `index.html` around line 200-300.

### Styling Changes
All styles are in `styles.css` - the file is well-organized with clear sections.

## SEO & Analytics

### Current SEO Features
- Semantic HTML structure
- Meta descriptions and titles
- Open Graph tags ready for social sharing
- Structured data markup ready

### Adding Analytics
To add Google Analytics, insert your tracking code before the closing `</head>` tag in `index.html`.

## Compliance & Legal

### Campaign Finance Compliance
- All required disclaimers are included
- "Paid for by" statements in footer
- Contact information available

### Accessibility Compliance
- WCAG 2.1 AA compliant
- Keyboard navigation support
- Screen reader friendly
- Proper color contrast ratios

## Support & Maintenance

### Regular Updates Needed
- Election date reminders
- Event announcements
- News and press releases
- Volunteer opportunities

### Technical Maintenance
- Monitor site performance
- Update security headers as needed
- Backup content regularly
- Test mobile responsiveness

## Contact Information

For technical support or content updates, contact the campaign's digital team.

---

**Paid for by Pound Ridge Party Committee**

*This website contains information based on official government documents including NYS Comptroller Report 2024M-150.*
