# DrillCost Migration Landing Page

This repository hosts a static landing page designed to redirect users from the legacy "Cost Per Meter" application to the new "DrillCost" platform.

## Purpose

The "Cost Per Meter" web application has been rebranded and expanded into "DrillCost" to support all measurement units. This landing page serves as a professional notice to users visiting the old domain, informing them of the change and automatically redirecting them to the new URL.

## Features

- **Professional UI**: Clean, glassmorphism-inspired design using Tailwind CSS.
- **Particle Animation**: Lightweight, vanilla JavaScript canvas animation for a modern aesthetic.
- **Auto-Redirect**: Automatically redirects users to the new domain after 8 seconds.
- **Responsive**: Fully optimized for desktops, tablets, and mobile devices (including landscape orientation).
- **Zero Dependencies**: Runs completely in the browser with Tailwind CSS loaded via CDN. No build step required.

## Installation / Deployment

Simply host the `index.html` file at the root of your web server or GitHub Pages repository for the old domain.

1. Copy `index.html` to your project root.
2. Ensure internet access is available to load the Tailwind CSS and Font resources.

## Configuration

To change the redirect URL or delay, edit the `script` section at the bottom of `index.html`:

```javascript
// --- Constants ---
const NEW_URL = "https://son-n-pham.github.io/drillcost/";
const REDIRECT_DELAY_SEC = 8;
```

## Credits

Created by Son Pham.
