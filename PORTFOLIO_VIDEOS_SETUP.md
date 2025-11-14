# Portfolio Videos Setup Guide

## Overview
Your portfolio now includes a tabbed interface that allows visitors to toggle between your **Projects** and **Video Tutorials**. When users click on the "Projects" link in the navigation menu, they'll see both sections with easy switching between them.

## What Was Added

### 1. **HTML Changes** (`index.html`)
- Added **Portfolio Tabs Navigation** with two buttons:
  - "Projects" (default active tab)
  - "Video Tutorials" (shows embedded YouTube videos)
- Created **Video Gallery Section** with 6 embedded YouTube videos:
  - Introduction to Web Development
  - Advanced CSS Techniques
  - JavaScript Mastery
  - React for Beginners
  - Node.js Backend Development
  - UI/UX Design Principles

### 2. **CSS Styling** (`assets/css/main.css`)
Added comprehensive styling for:
- **`.portfolio__tabs`** - Tab navigation container with flex layout
- **`.portfolio__tab-btn`** - Individual tab buttons with hover effects
- **`.portfolio__tab-btn--active`** - Active state styling
- **`.portfolio__video-item`** - Video card container
- **`.portfolio__video-wrapper`** - Video frame wrapper
- **`.portfolio__video-content`** - Video title and description area
- **`.portfolio__video-title`** & **`.portfolio__video-description`** - Text styling
- Responsive grid layout for desktop (3 columns)

### 3. **JavaScript Functionality** (`assets/js/main.js`)
Added interactive tab switching:
- Toggles between Projects and Videos sections
- Updates active tab styling
- Shows/hides corresponding content
- Smooth user experience

## How to Use

### To View the Videos Section:
1. Click "Projects" in the navigation menu
2. You'll see two tabs: "Projects" and "Video Tutorials"
3. Click "Video Tutorials" to see the embedded YouTube videos
4. Click "Projects" to return to your project portfolio

### To Replace YouTube Videos:
Each video iframe has a `src` attribute with a YouTube embed URL. To replace a video:

```html
<iframe 
  width="100%" 
  height="300" 
  src="https://www.youtube.com/embed/VIDEO_ID" 
  ...
></iframe>
```

1. Find the YouTube video you want
2. Get its YouTube ID (the part after `v=` in the URL)
3. Replace `VIDEO_ID` in the `src` with your actual video ID
4. Update the title and description as needed

### Example:
If you have a YouTube video: `https://www.youtube.com/watch?v=abc123xyz`
- Video ID: `abc123xyz`
- Embed URL: `https://www.youtube.com/embed/abc123xyz`

## Responsive Design
- **Desktop**: 3-column grid layout
- **Tablet**: 2-column grid layout (adjust in CSS media queries if needed)
- **Mobile**: 1-column layout (automatically stacks)

## Features
✅ Tabbed interface for easy navigation
✅ Embedded YouTube videos with full player controls
✅ Responsive design that works on all devices
✅ Smooth animations and hover effects
✅ Easy to customize and add more videos

## File Changes Summary
- **index.html**: Added tab navigation and 6 video embeds
- **assets/css/main.css**: Added 60+ lines of CSS styling
- **assets/js/main.js**: Added JavaScript tab switching logic

## Notes
- Videos use responsive iframe heights (100% width)
- Each video card includes a title and description
- The "Projects" tab is active by default when loading the page
- Videos are set to allow: accelerometer, autoplay, clipboard-write, encrypted-media, gyroscope, and picture-in-picture
