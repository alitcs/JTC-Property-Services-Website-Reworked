# JTC Property Services Website

## Overview

JTC Property Services is a static website for a property maintenance company serving the greater Toronto area. The site provides information about their services, showcases their work through a gallery, displays service locations, and includes contact information and quote request functionality. Built with vanilla HTML, CSS, and JavaScript, it features a responsive design with mobile navigation and form handling.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Static Website Structure**: Pure HTML/CSS/JavaScript implementation without any frameworks
- **Multi-page Navigation**: Six main pages (Home, Locations, Gallery, Socials, Contact, Quote) with consistent navigation structure
- **Responsive Design**: Mobile-first approach with hamburger menu for mobile devices
- **Component-based CSS**: Modular styling with reusable classes and consistent design system

### Navigation System
- **Sticky Navigation Bar**: Fixed header with company branding and main navigation links
- **Mobile-responsive Menu**: Hamburger menu implementation for smaller screens
- **Active State Management**: Visual indication of current page in navigation

### Form Handling
- **Client-side Validation**: JavaScript form validation for quote requests with email and phone number validation
- **Quote Request Flow**: Multi-step user journey from quote form to confirmation page
- **Progressive Enhancement**: Forms work without JavaScript but enhanced with client-side validation

### Content Organization
- **Service-focused Structure**: Dedicated pages for different aspects of the business (locations, gallery, social media)
- **Visual Communication**: SVG graphics and placeholder content for professional presentation
- **Contact Integration**: Multiple touchpoints for customer engagement

### Styling Architecture
- **CSS Reset**: Consistent cross-browser styling foundation
- **Responsive Grid System**: Flexible layouts that adapt to different screen sizes
- **Design System**: Consistent color scheme, typography, and spacing throughout

## External Dependencies

### Core Technologies
- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with flexbox and responsive design features
- **Vanilla JavaScript**: DOM manipulation and form handling without external libraries

### No External Dependencies
- Self-contained codebase with no third-party frameworks, libraries, or external API integrations
- All styling and functionality implemented using native web technologies
- SVG graphics embedded directly in HTML for scalability and performance

### Future Integration Points
- Form submission endpoints could be added for quote processing
- Social media integration placeholders exist for future API connections
- Gallery system ready for dynamic image loading and management