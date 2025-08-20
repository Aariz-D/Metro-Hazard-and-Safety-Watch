# Metro Hazard & Safety Watch (MHSW) Website

## Project Overview
A comprehensive community safety organization website built with SvelteKit. MHSW is a professional, volunteer-based organization dedicated to enhancing community safety through systematic observation, reporting, and community engagement.

## Key Technologies
- **SvelteKit**: Web framework for building the app
- **TypeScript**: Programming language for type safety
- **Tailwind CSS**: Styling framework for beautiful designs
- **Bits UI**: Component library for interactive elements
- **Vite**: Build tool for fast development

## Development Commands
- `npm install` - Install dependencies
- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run check` - Type checking

## Project Structure
- `src/routes/` - App pages and routes
- `src/lib/` - Reusable components and utilities
- `src/app.html` - Main HTML template
- `src/app.css` - Global styles with Tailwind CSS

## Website Features
### Homepage Navigation (8 buttons total)
**Left Side - Safety Resources:**
1. **Emergency Contacts** - 911, crisis lines, suicide prevention, child abuse hotline, etc.
2. **Online Safety** - Internet safety tips, cyberbullying prevention, digital citizenship
3. **Physical Safety** - Personal safety, home safety, transportation safety, emergency preparedness
4. **Kids Safety** - Age-appropriate safety for children (online and offline)

**Right Side - Organization Info:**
5. **About MHSW** - Complete organizational structure, mission, operations, and detailed information
6. **Our Team** - Staff biographies, expertise, volunteer opportunities
7. **Shop & Donate** - Products, merchandise, donation system (PayPal/Venmo ready)
8. **Resources & Downloads** - Free educational materials, guides, videos, infographics

### Additional Features
- Responsive design with mobile-first approach
- Professional gradient backgrounds and modern UI
- Comprehensive safety information with external resource links
- Ready for payment integration (PayPal/Venmo)
- Editable team sections with photo placeholders
- Download system for educational resources
- Newsletter signup functionality

## Current Status
- ✅ Complete homepage with 8 navigation buttons
- ✅ All safety resource pages with comprehensive content
- ✅ Emergency contacts with crisis hotlines
- ✅ Shop page with donation and product purchase system
- ✅ Team page with editable member profiles
- ✅ Resources page with downloadable materials
- ✅ Professional styling with Tailwind CSS
- ✅ Bits UI components for interactivity
- ✅ New Report page (/report) with hazard form (location, detailed description, time last seen, optional photo upload with preview)
- ✅ Reports persist to localStorage and are listed below the form
- ✅ Prominent "Report a Hazard" button added to homepage linking to /report
- ✅ sitemap.json updated to include all routes including /report
- ✅ **UPDATED About page with comprehensive MHSW organizational details including:**
  - Complete organizational structure (Director, Assistant Directors, divisions)
  - Detailed operational procedures and protocols
  - Professional communication systems and equipment
  - AIC Division (Accountability, Integrity, Conduct) details
  - Field Operations Division structure
  - Reporting processes and community liaison functions
  - Professional standards and safety protocols
- ✅ **INTEGRATED OFFICIAL MHSW LOGO:**
  - Created SVG version of the official shield logo
  - Added logo to homepage header with proper sizing
  - Updated favicon to use the MHSW logo
  - Logo features blue shield design with "METRO HAZARD & SAFETY", "MHSW", and "WATCH" text

## MHSW Organization Details
**Mission**: Professional community safety through observation, reporting, and community engagement
**Core Principle**: "We observe, document, and report - we do not enforce or intervene"

### Organizational Structure
- **Director**: Overall leadership and strategic planning
- **Administrative Assistant Director**: Administrative operations, AIC Division leadership
- **Field Assistant Director**: All field operations and patrol coordination
- **Community Safety Liaison**: Interface with authorities and report coordination
- **AIC Division Leader**: Accountability, Integrity, and Conduct oversight

### Key Operations
- Systematic patrols in designated areas
- Real-time documentation and reporting
- Professional 2-way radio communication
- Community event participation
- Equipment funding through merchandise sales
- Collaborative approach with local authorities

## Next Steps for Customization
1. **Team Photos**: Add real team member photos to `static/` folder
2. **Payment Integration**: Set up actual PayPal/Venmo business accounts
3. **Resources**: Upload actual educational materials to `static/resources/`
4. **Contact Information**: Update specific contact details if needed
5. **Branding**: Customize colors, fonts, and styling to match organization brand
6. **Social Media**: Add actual social media links and handles

## Recent Updates
- Removed copyright symbol from footer site-wide.
- Updated footer tagline to "Empowering youth to protect the community through education and action."
- Revised Shop page messaging to center youth-led community protection (donation blurb and product descriptions).
- Verified no remaining instances of "©", "copyright", "All rights reserved", or phrases implying adults protect kids (e.g., "keeping kids safe", "youth and families").
- Fixed Vite "broadcast: Unknown error" during dev by resolving TypeScript errors and minor a11y issues.
- Resources page: typed helper functions and maps to satisfy TypeScript.
- Report page: associated labels with controls (ids) to improve a11y.
- Shop page: refactored modal overlay to accessible dialog structure with overlay button and proper roles/attributes.
- Updated favicon link in src/app.html to use mhsw-logo.svg (SVG).
- Verified with `npm run build` and `npm run check` (0 errors).

## Contact Information
- **Operations Email**: mhswoperations@gmail.com
- **Response Time**: 24-48 hours for general inquiries
- **Emergency Reports**: Contact local authorities directly