# My Extension

## Overview

**My Extension** is a simple Chrome extension created as a learning project. It demonstrates the basics of building a Chrome extension using JavaScript and HTML, following the Manifest Version 3 standard. This project is designed to help understand the fundamental concepts of Chrome extensions, including background scripts and popup interfaces.

## Features

- **Service Worker**: Handles background tasks and event listeners. It's defined in `service-worker.js`.
- **Popup Interface**: Provides a basic user interface through `index.html`, allowing interaction with the DOM using `index.js`.

## Project Structure

- `manifest.json`: Configuration file for the extension, specifying metadata, permissions, and scripts.
- `static/js/service-worker.js`: Contains the service worker script for background processing.
- `static/js/index.js`: The script for interacting with the DOM elements within the popup.
- `static/index.html`: The HTML file that defines the popup UI.

## Permissions

The extension requests the following permissions:

- **Scripting**: Allows the extension to inject and execute scripts on webpages.
- **Host Permissions**: Grants access to all websites (`http://*/*`, `https://*/*`).

## Purpose

This project was created to learn how to build a Chrome extension using basic web technologies like JavaScript and HTML. It serves as a foundational step towards developing more advanced extensions with additional features and capabilities.
