# Blueprint for The Freedom Program Website

## Overview

This document outlines the plan to replicate a webpage for "The Freedom Program" wellness site. The goal is to create a visually appealing and functional website based on the provided HTML and image.

## Current Implementation Plan

The user has requested to replicate a webpage.

### Phase 1: Initial Setup (Static HTML)

1.  **Create `blueprint.md`**: This file will be the source of truth for the project plan and changes.
2.  **Update `index.html`**: Replace the content of the existing `public/index.html` or `index.html` with the provided HTML code. This will serve as the base for the website.
3.  **Verify assets**: The provided HTML uses TailwindCSS via CDN and external images. For now, we will use these external resources directly.
4.  **Cleanup**: The project seems to be a React project. The new `index.html` will not reference the React application, so the existing React components in `src` will be unused for now. I will leave them as they are, but will remove the react-specific code from `index.html` if any. The user provided a full html page, I'll use it as it is.
5.  **Review**: Check the preview of the application to see if the page renders correctly.

### Phase 2: Add RTT Services Page

1.  **Create `rtt-services.html`**: A new HTML file for the RTT Services page has been created with the provided code.
2.  **Update Navigation**: The navigation links in `index.html` and `rtt-services.html` have been updated to allow navigation between the two pages.

## Future Enhancements (Post-MVP)

*   **Componentization**: Convert the static HTML into reusable React components.
*   **Routing**: Implement client-side routing using `react-router-dom` if more pages are added.
*   **Local Assets**: Download remote images and serve them locally.
*   **Styling**: Move away from CDN-based Tailwind and integrate it into the Vite build process.
*   **State Management**: If the application becomes more interactive, introduce a state management library.
