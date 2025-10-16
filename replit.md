# BeaBoo

## Overview

BeaBoo is a Spanish-language web application that appears to be a TikTok-inspired social platform. The application features a modern, mobile-first design with a pink pastel color scheme that mimics TikTok's aesthetic. It's built as a single-page application with Firebase integration for backend services including authentication, storage, and real-time database functionality.

## Recent Changes (October 2025)

### New&HoT Video Section
- **TikTok-Style Video Player**: New vertical video section accessible from bottom navigation
- **Video Content**: Features promotional trailers and content from administrators
- **Interactive Controls**: 
  - Save button with animation to bookmark videos
  - Report functionality with bottom-sliding modal for content moderation
  - Direct links to featured content (e.g., "Start Reading" for comics)
- **First Video**: "Crimson Moon Embrace" comic trailer hosted on Dropbox

### Removed Features
- **Messaging System**: Completely removed real-time chat and messaging functionality to streamline the user experience

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Single-Page Application (SPA)**: Built with vanilla HTML, CSS, and JavaScript
- **Responsive Design**: Mobile-first approach using Tailwind CSS framework
- **TikTok-Inspired UI**: Custom CSS variables and styling that mimics TikTok's modern interface
- **Font Integration**: Uses Google Fonts (Nunito) for typography
- **Icon System**: Font Awesome for scalable vector icons

### Styling and Design System
- **CSS Custom Properties**: Centralized color management using CSS variables
- **TikTok Color Palette**: 
  - Primary pink (#FE2C55)
  - Secondary teal (#25F4EE) 
  - Gradient systems for visual depth
  - Pastel pink variations for backgrounds
- **Component-Based Styling**: Modular CSS classes for reusable UI components
- **Animation Ready**: CSS transitions and hover effects built into the design system

### Backend Architecture
- **Firebase Backend-as-a-Service**: Complete serverless backend solution
- **Firebase Authentication**: User management and authentication system
- **Firebase Realtime Database**: NoSQL database for real-time data synchronization
- **Firebase Storage**: File storage for user-generated content (likely images/videos)
- **Firebase Compatibility Mode**: Uses legacy v8 SDK for broader browser support

### Monetization Integration
- **Google AdSense**: Integrated advertising system for revenue generation
- **Ad Configuration**: Pre-configured with specific publisher ID

## External Dependencies

### CDN Dependencies
- **Tailwind CSS 3.3.0**: Utility-first CSS framework via CDN
- **Google Fonts**: Nunito font family for typography
- **Font Awesome 6.4.0**: Icon library for UI elements

### Firebase Services
- **Firebase App**: Core Firebase SDK
- **Firebase Auth**: Authentication and user management
- **Firebase Storage**: File upload and storage capabilities  
- **Firebase Realtime Database**: Real-time data synchronization

### Third-Party Services
- **Google AdSense**: Advertising platform integration
- **Google Fonts API**: Web font delivery service

### Browser Compatibility
- Uses Firebase compat SDK for broader browser support
- Responsive design ensures mobile and desktop compatibility
- Modern CSS features with fallbacks for older browsers