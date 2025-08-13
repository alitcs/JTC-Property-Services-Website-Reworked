# JTC Property Services Website

## Overview

JTC Property Services is a static website for a property maintenance company serving the greater Toronto area. The site provides information about their services, showcases their work through a gallery, displays service locations with real map images, and includes contact information and quote request functionality. Built with vanilla HTML and CSS only, it features a responsive design with CSS-only mobile navigation and form handling.

## User Preferences

Preferred communication style: Simple, everyday language.
Technology preference: HTML and CSS only, no JavaScript dependencies.

## System Architecture

### Frontend Architecture
- **Static Website Structure**: Pure HTML/CSS/JavaScript implementation without any frameworks
- **Multi-page Navigation**: Six main pages (Home, Locations, Gallery, Socials, Contact, Quote) with consistent navigation structure
- **Responsive Design**: Mobile-first approach with hamburger menu for mobile devices
- **Component-based CSS**: Modular styling with reusable classes and consistent design system

### Navigation System
- **Sticky Navigation Bar**: Fixed header with company branding and main navigation links
- **CSS-only Mobile Menu**: Hamburger menu using CSS checkbox technique for mobile responsiveness
- **Active State Management**: Visual indication of current page in navigation

### Form Handling
- **HTML-only Forms**: Simple form submission using HTML form action to redirect to confirmation page
- **Quote Request Flow**: Multi-step user journey from quote form to confirmation page
- **Accessible Forms**: Built-in HTML5 validation with required fields and input types

### Content Organization
- **Service-focused Structure**: Dedicated pages for different aspects of the business (locations with real maps, gallery, social media)
- **Visual Communication**: Real map images for service areas and placeholder content for gallery
- **Contact Integration**: Multiple touchpoints for customer engagement
- **Dual Map System**: Limited service area (red zone with fees) and total service area (blue zone acceptance)

### Styling Architecture
- **CSS Reset**: Consistent cross-browser styling foundation
- **Responsive Grid System**: Flexible layouts that adapt to different screen sizes
- **Design System**: Consistent color scheme, typography, and spacing throughout

## External Dependencies

### Core Technologies
- **HTML5**: Semantic markup structure with form validation
- **CSS3**: Modern styling with flexbox, responsive design, and CSS-only interactions
- **PNG Images**: Real service area maps for accurate location representation

### No External Dependencies
- Self-contained codebase with no frameworks, libraries, or JavaScript
- All styling and functionality implemented using native HTML and CSS
- CSS-only mobile navigation using checkbox technique
- Real map images for service area visualization

### Future Integration Points
- Form submission endpoints could be added for quote processing
- Social media integration placeholders exist for future API connections
- Gallery system ready for dynamic image loading and management