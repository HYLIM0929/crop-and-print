# Image Layout to PDF

A lightweight, purely client-side web application to upload, crop, magnetically align, and arrange images on standard paper layouts (A4 / A3, Portrait / Landscape) and export them directly to PDF.

## Features

- **Multi-Size Canvas:** Supports standard A4 and A3 formats in both Portrait and Landscape orientations.
- **In-Browser Cropping:** Integrated Cropper.js allows free-form and targeted cropping before placing images.
- **Smart Magnetic Snapping:** Objects automatically snap to the edges and centers of adjacent images for precise alignment.
- **Quick Alignment Tools:** One-click options to center horizontally, align left, or match widths with previous elements.
- **Vector-Scale PDF Export:** Powered by jsPDF, converting the layout to a sharp, print-ready PDF document.
- **Zero Backend Required:** Completely static; runs natively in any modern web browser and deploys instantly via GitHub Pages.

## Tech Stack

- [Fabric.js](https://fabricjs.com/) (Canvas manipulation & object handling)
- [Cropper.js](https://fengyuanchen.github.io/cropperjs/) (Image cropping)
- [jsPDF](https://github.com/parallax/jsPDF) (Client-side PDF compilation)

## Getting Started

Simply clone the repository and open `index.html` in your web browser:

