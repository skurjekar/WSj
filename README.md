# WSJ Reader

A simple browser-based tool hosted on GitHub Pages that lets you read Wall Street Journal articles for free by routing them through [archive.is](https://archive.is).

## How It Works

This tool uses `archive.is/newest/<URL>` to fetch archived versions of WSJ pages. When you load the WSJ homepage or any article URL through this tool, it redirects the request through archive.is, bypassing the paywall.

## Features

- **URL Bar**: Paste any WSJ article URL and click "Read" to load it in-frame, or "New Tab ↗" to open it directly
- **Home Button**: Quickly load the WSJ homepage through archive.is
- **Inline Viewing**: Articles load within an iframe so you stay on the same page
- **New Tab Mode**: Open articles directly in a new tab if the iframe doesn't work
- **Responsive Design**: Works on desktop and mobile

## Usage

1. Visit the hosted page (GitHub Pages URL)
2. Click "⌂ Home" or "Load WSJ Homepage" to browse the WSJ homepage
3. Complete the one-time archive.is CAPTCHA (if prompted)
4. Browse articles as normal — links within the archived page stay within archive.is
5. To read a specific article, paste its URL in the bar and click "Read" or "New Tab ↗"

## Deployment

This is a static single-page HTML file. Simply enable GitHub Pages on the repository (from the `main` branch) and access it at:

```
https://<username>.github.io/WSj/
```

## Note

- archive.is may show a one-time CAPTCHA on first access
- Some pages may take a few seconds to load as archive.is fetches/serves the cached version
- If the iframe doesn't load properly, use the "New Tab ↗" button to open directly
