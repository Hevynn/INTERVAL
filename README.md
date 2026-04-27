# INTERVAL

A web application project.

## Live Demo

The application is hosted on GitHub Pages and is available at:
👉 **https://hevynn.github.io/INTERVAL/**

## Local Development

To run this project locally:

1. Clone the repository
2. Serve the `docs` folder using any local web server:
   ```bash
   # Using Python 3
   python -m http.server 8000 --directory docs
   
   # Using Node.js (with http-server)
   npx http-server docs
   
   # Using PHP
   cd docs && php -S localhost:8000
   ```
3. Open http://localhost:8000 in your browser

## Features

- Progressive Web App (PWA) support
- Service Worker for offline functionality
- Responsive design
- Installable on mobile devices

## Project Structure

```
docs/
├── index.html              # Main HTML file
├── manifest.webmanifest    # PWA manifest
├── sw.js                   # Service Worker
├── icon-192.png            # App icon (192x192)
├── icon-512.png            # App icon (512x512)
└── icon-maskable-512.png   # Maskable app icon
```

## Deployment

This project is automatically deployed to GitHub Pages from the `docs` folder on the `main` branch.

To make changes go live:
1. Push your changes to the `main` branch
2. GitHub Pages will automatically rebuild within seconds
3. Your app will be available at https://hevynn.github.io/INTERVAL/
