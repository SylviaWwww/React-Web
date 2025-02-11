# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

# Project Overview

This project uses several components that have been implemented with the help of GenAI (ChatGPT 4o) to understand how certain libraries, such as `react-leaflet`, `react-qr-code`, and `react-quill`, work and are integrated into a React application.

## Components

### 1. MapPicker

This component integrates the `react-leaflet` library to allow users to select geographical coordinates on a map. When a user clicks on a location on the map, the marker position updates, and the latitude/longitude values are saved for later use.

**Files:**
- `MapPicker.jsx`

GPT was used to assist with understanding how the react-leaflet library works and how to handle map click events, updating marker positions, and setting location data.

### 2. QRCodeGenerator

This component generates QR codes for specific locations using the react-qr-code library. Users can either generate a single QR code for a specific location or multiple QR codes for all locations.

**Files:**
- `QRCodeGenerator.jsx`

GPT helped with understanding the react-qr-code library and how to implement QR code generation dynamically based on user selections.

### 3. RichTextEditor

The RichTextEditor component uses the react-quill library to allow users to input rich text, including formatting options like bold, italic, underline, and more. The editor also supports inserting links, images, and videos.

**Files:**
- `RichTextEditor.jsx`

## How to run

Unzip the code.

run:

`cd story-path`

`npm install`

`npm run dev`
