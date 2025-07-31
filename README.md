# AmericaLearns Security Navigator

A comprehensive security assessment tool designed specifically for AmeriCorps programs, volunteer organizations, and public service entities to strengthen their cybersecurity posture in an era of high staff turnover and evolving threats.

## Overview

The AmericaLearns Security Navigator helps volunteer-driven organizations and AmeriCorps programs:
- Assess their security readiness across 15 essential controls tailored for volunteer programs
- Address unique challenges of high staff turnover and volunteer management
- Get personalized, actionable remediation steps
- Generate a prioritized action plan (3-month and 6-month priorities)
- Export their assessment results as a PDF

## Features

- **No Data Storage**: Runs entirely in the browser - no data is saved or transmitted
- **Non-Technical Friendly**: Designed for users with limited technical experience
- **Actionable Guidance**: Each control includes specific steps and "Where to Get Help" sections
- **PDF Export**: Generate a complete action plan for offline use
- **Mobile Responsive**: Works on desktop, tablet, and mobile devices

## Technology Stack

- HTML5
- Tailwind CSS (via CDN)
- Vanilla JavaScript
- jsPDF & html2canvas for PDF generation

## Deployment

This is a static site that can be hosted on any web server or CDN. Recommended deployment on Netlify for simplicity.

### Netlify Deployment

1. Fork or download this repository
2. Connect your GitHub repository to Netlify
3. Deploy with default settings (no build command needed)

## Security & Privacy

- All assessment data stays in the user's browser
- No backend or database required
- No tracking or analytics
- PDF generation happens client-side

## Customization

To customize the assessment for your organization:
1. Update AmericaLearns contact information with your support details
2. Modify the controls in the `controlsData` object to match your specific compliance requirements
3. Adjust branding to match your governor's office or program identity
4. Add any state-specific AmeriCorps compliance requirements

## Based on

This assessment is based on the Reasonable Cyber and Data Security Framework, aligned with ACLU security recommendations and NIST standards, specifically tailored for AmeriCorps programs, volunteer organizations, and public libraries with limited technical resources.

## License

[Add your license here]

## Support

For questions or support, contact AmericaLearns at support@americalearns.net

Developed in partnership with Meet the Moment (www.meetthemoment.ai)