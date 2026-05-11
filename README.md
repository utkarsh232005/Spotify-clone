# Spotify Clone

A responsive front-end clone of Spotify’s web player built with **HTML** and **CSS**.

## Demo

This project is configured for deployment on Vercel and supports routing under `/spotify-clone`.

## Features

- Spotify-inspired dark UI
- Left sidebar with Home, Search, and Library sections
- Playlist/podcast suggestion cards
- Sticky top navigation bar
- Music content sections (Recently Played, Trending, Featured Charts)
- Bottom fixed player with:
  - Album info
  - Playback controls
  - Progress bar
  - Volume and device controls
- Responsive behavior for smaller screens

## Tech Stack

- HTML5
- CSS3
- [Google Fonts (Montserrat)](https://fonts.google.com/specimen/Montserrat)
- [Font Awesome](https://fontawesome.com/)

## Project Structure

```text
Spotify-clone/
├── assets/                # Icons and images used in UI
├── index.html             # Main page markup
├── styles.css             # Styling and responsive layout
├── vercel.json            # Vercel route configuration
└── .nojekyll              # Static hosting compatibility
```

## Getting Started

### 1) Clone the repository

```bash
git clone https://github.com/utkarsh232005/Spotify-clone.git
cd Spotify-clone
```

### 2) Run locally

Since this is a static project, you can open `index.html` directly in a browser.

For better development experience, use a local static server (example with VS Code Live Server).

## Deployment

The repository includes `vercel.json` with routes:

- `/spotify-clone` → `/`
- `/spotify-clone/(.*)` → `/$1`

This helps when serving the app from a subpath on Vercel.

## Notes

- This project is a UI clone for learning/practice purposes.
- It does not include backend APIs, authentication, or real music playback.

## Author

Created by [utkarsh232005](https://github.com/utkarsh232005).
