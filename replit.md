# replit.md

## Overview

GPC Performance is a static landing page website for an elite strength and conditioning coaching business. The site is designed to maximize lead conversions by showcasing the company's online coaching platform and directing visitors to a chat interface for initial consultation. The website serves as a marketing funnel to attract potential clients and guide them toward engaging with the coaching services.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Pure HTML/CSS/JavaScript**: Static website built with vanilla web technologies for maximum performance and simplicity
- **Mobile-First Design**: Responsive layout using CSS clamp() functions and media queries for optimal viewing across all devices
- **Single Page Application (SPA) Pattern**: All content contained in one HTML file with smooth scrolling navigation between sections
- **Component-Based CSS**: Modular stylesheet organization with reusable classes and consistent naming conventions

### Design System
- **Typography**: Inter font family loaded from Google Fonts for modern, professional appearance
- **Icon System**: Font Awesome integration for consistent iconography
- **Color Scheme**: Professional palette optimized for conversion with strategic use of highlight colors
- **Layout Grid**: Container-based layout with max-width constraints for readability

### Performance Optimizations
- **Minimal Dependencies**: Only essential external resources (Google Fonts, Font Awesome) to maintain fast load times
- **CSS Optimization**: Efficient selector usage and responsive design patterns
- **Smooth Interactions**: CSS transitions and JavaScript scroll behaviors for enhanced user experience

### Navigation System
- **Sticky Navigation**: Fixed navbar with background opacity changes on scroll
- **Mobile Menu**: Hamburger menu implementation for mobile devices
- **Smooth Scrolling**: JavaScript-powered smooth scrolling between page sections

## External Dependencies

### CDN Resources
- **Google Fonts**: Inter font family for typography consistency
- **Font Awesome**: Icon library (version 6.4.0) for visual elements

### Third-Party Integrations
- **GPC Chat Platform**: External chat interface hosted at `gpc-performance.com/gpcchat` for lead qualification and initial consultation
- **Call-to-Action Integration**: Strategic placement of chat platform links to maximize conversion opportunities

### Asset Management
- **Image Assets**: Local image storage in `attached_assets` directory for performance optimization
- **Static File Serving**: All assets served directly from the repository without additional processing