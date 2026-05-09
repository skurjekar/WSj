# WSJ Reader

A simple browser-based tool hosted on GitHub Pages that lets you read Wall Street Journal articles for free by routing them through [archive.is](https://archive.is).

## Live URL

**https://skurjekar.github.io/WSj/**

## How It Works

When you open the tool, it automatically loads `archive.is/newest/https://www.wsj.com` in an embedded frame. This shows you the **exact WSJ homepage layout** with all current headlines and article links. Since archive.is serves fully rendered cached snapshots, you see the complete page design.

When you click any article link on the homepage, it navigates through archive.is, letting you read the full article content without hitting the paywall.

## Usage

1. Open the tool in your browser
2. Complete the one-time archive.is CAPTCHA (first visit only)
3. You'll see the full WSJ homepage with all articles and links
4. Click any article to read it — links stay within archive.is
5. To read a specific article: paste its URL in the bar and click **Read** or **↗ New Tab**

## Features

- **Auto-loads WSJ homepage** on open via archive.is
- **URL Bar**: Paste any WSJ article URL and hit Read
- **New Tab mode**: Open articles in a separate tab if you prefer
- **Home button**: Quickly return to the WSJ homepage
- **Responsive**: Works on desktop and mobile
- **No server needed**: Pure static HTML, hosted on GitHub Pages

## Notes

- archive.is shows a one-time CAPTCHA on first visit — once completed, browsing is seamless
- Links within the archived page naturally stay within archive.is, so you can browse freely
- If archive.is blocks iframe embedding on some browsers, use the "↗ New Tab" button
