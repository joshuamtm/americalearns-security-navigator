# AmericaLearns Security Navigator

A comprehensive security assessment tool designed specifically for AmeriCorps programs, volunteer organizations, and public service entities to strengthen their cybersecurity posture in an era of high staff turnover and evolving threats.

## Overview

The AmericaLearns Security Navigator helps volunteer-driven organizations and AmeriCorps programs:
- Assess their security readiness across 15 essential controls tailored for volunteer programs
- Address unique challenges of high staff turnover and volunteer management
- Get personalized, actionable remediation steps based on industry best practices
- Generate a prioritized action plan (3-month and 6-month priorities)
- Export their assessment results as a PDF for grant reporting and board presentations

## Assessment Framework

This assessment is built on proven cybersecurity frameworks, adapted for small nonprofits:

### **Technical Foundation:**
- **NIST Cybersecurity Framework 2.0** - The gold standard for organizational cybersecurity
- **CIS Controls 8.1** - Implementation guidance for essential security measures
- **"Reasonableness" Standard** - Appropriate expectations for organizations with limited budgets and IT resources

### **Specialized for Nonprofits:**
- Addresses unique challenges of volunteer-driven organizations
- Considers resource constraints typical of small nonprofits (1-5 staff)
- Includes AmeriCorps-specific compliance requirements
- Focuses on practical, achievable security improvements

## Target Organizations

Designed specifically for:
- **AmeriCorps Programs** - State and local programs managing volunteers
- **Volunteer Organizations** - Nonprofits with high volunteer turnover (30-50% annually)
- **Public Libraries** - Running adult literacy and community programs
- **Governor's Office Programs** - State-level AmeriCorps administration
- **Small Nonprofits** - Limited IT resources but handling sensitive data

## Features

- **No Data Storage**: Runs entirely in the browser - no data is saved or transmitted
- **Non-Technical Friendly**: Designed for users with limited technical experience
- **Actionable Guidance**: Each control includes specific steps and "Where to Get Help" sections
- **AmericaLearns Branding**: Integrated logo and organization-specific support
- **High-Turnover Focus**: Special controls for managing volunteer access and staff transitions
- **PDF Export**: Generate a complete action plan for offline use and grant reporting
- **Mobile Responsive**: Works on desktop, tablet, and mobile devices

## 15 Security Controls Assessed

### Govern (4 controls)
1. **Cybersecurity Roles & Responsibilities** - Clear ownership and accountability
2. **Information Security Policy** - Written guidelines for staff and volunteers
3. **Risk Assessment** - Modern threat identification and prioritization
4. **AmeriCorps Compliance & Data Privacy** - Federal requirements and volunteer data protection

### Identify (3 controls)
5. **Hardware & Software Inventory** - Know what technology you have
6. **Data Inventory & Classification** - Understand what sensitive data you hold
7. **Access Control Management** - Control who can access what systems

### Protect (5 controls)
8. **Device Security & Management** - Secure computers and mobile devices
9. **Password Management & Passkeys** - Modern credential protection
10. **Security Awareness Training** - AI-era threat education for staff
11. **Email Security** - Prevent spoofing and improve deliverability
12. **Data Backup** - Ransomware-resistant backup strategies
13. **Data & Equipment Disposal** - Secure deletion and hardware disposal
14. **Volunteer & Staff Turnover Management** - *Specialized control for high-turnover environments*

### Monitor (3 controls)
15. **Cloud Security Monitoring** - Visibility into security events
16. **Vulnerability Management** - Find and fix security weaknesses
17. **Vendor Risk Management** - Assess third-party security practices
18. **Incident Response** - Prepare for and respond to security incidents
19. **Business Continuity** - Ensure operations can continue after disruptions

## Technology Stack

- **Frontend**: HTML5, Tailwind CSS, Vanilla JavaScript
- **PDF Generation**: jsPDF & html2canvas
- **Deployment**: Static site compatible with any web server
- **Privacy**: No backend, database, or data transmission required

## Quick Start

### Live Application
**🌐 Access the tool:** https://joshuamtm.github.io/americalearns-security-navigator/

### Local Development
1. Clone this repository
2. Open `index.html` in a web browser
3. No build process or dependencies required

### GitHub Pages Deployment
1. Fork this repository
2. Enable GitHub Pages in repository settings
3. Select "Deploy from branch" and choose `main`
4. Your assessment will be available at `https://[username].github.io/americalearns-security-navigator/`

## Customization

To customize the assessment for your state or organization:

1. **Contact Information**: Update `support@americalearns.net` references
2. **State Requirements**: Modify controls to include state-specific AmeriCorps compliance
3. **Branding**: Replace logo and adjust colors in the `controlsData` object
4. **Support Resources**: Add links to your preferred IT providers or security vendors

## Security & Privacy

- **Privacy-First Design**: All assessment data stays in the user's browser
- **No Data Collection**: No tracking, analytics, or data transmission
- **Client-Side Processing**: PDF generation and scoring happen locally
- **Anonymous Usage**: No user identification or organization data stored

## Use Cases

### For AmeriCorps Programs
- **Grant Compliance**: Demonstrate security measures for state commissions
- **Board Reporting**: Generate professional security assessments
- **Staff Transitions**: Manage security during high turnover periods
- **Volunteer Onboarding**: Establish security practices for new volunteers

### For Governor's Offices
- **Grantee Requirements**: Distribute to AmeriCorps sub-grantees
- **Security Standards**: Establish minimum security baselines
- **Capacity Building**: Support programs lacking IT resources
- **Risk Management**: Identify security gaps across programs

### For Small Nonprofits
- **Budget Planning**: Prioritize security investments
- **IT Provider Communication**: Clear requirements for technical support
- **Board Education**: Help leadership understand cybersecurity needs
- **Insurance Requirements**: Document security practices for cyber insurance

## Support & Development

**Support**: Contact AmericaLearns at support@americalearns.net

**Development**: Developed in partnership with [Meet the Moment](https://meetthemoment.ai) - AI-powered consulting for nonprofits

**Contributing**: This is an open-source project. Contributions welcome via GitHub issues and pull requests.

## License

This project is open source and available under standard terms. See repository for specific license details.

---

*The AmericaLearns Security Navigator helps bridge the gap between enterprise-grade security frameworks and the practical realities of resource-constrained nonprofit organizations.*