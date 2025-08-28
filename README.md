# HN Overlooked Posts

A simple web app that discovers hidden gems on Hacker News – posts where authors put in significant effort writing detailed content but received minimal community engagement.

## What It Does

This tool searches through recent Hacker News posts to find those high-effort, low-engagement submissions that might have been posted at the wrong time or simply missed by the community. It calculates a "Passion Score" for each post to identify truly overlooked content.

## How It Works

The app fetches posts directly from the Hacker News API and filters them based on:
- **Text length** - Finds posts with substantial content
- **Low engagement** - Posts with fewer votes and comments
- **Recency** - Focuses on posts from the last week (adjustable)

Posts are ranked by their Passion Score, which measures the ratio between author effort (text length) and community engagement (votes + comments). Higher scores indicate more overlooked content.

## Features

- 🔍 Real-time search across Ask HN, Show HN, and New posts
- 📊 Passion Score algorithm to identify overlooked content  
- 🎛️ Adjustable filters for date range, text length, and engagement thresholds
- 📖 Pagination for browsing through all discovered posts
- ⚡ Pure client-side app – no backend or database needed
- 🎨 Clean, HN-inspired interface

## Try It Out

Visit the live site: https://pj4533.com/hn-overlooked/

Or run it locally by opening `index.html` in your browser. That's it – no build process, no dependencies.

## Why This Exists

Sometimes the best content on Hacker News gets buried. Maybe it was posted at 3 AM, or during major news events, or just didn't catch the algorithm's attention. This tool gives those thoughtful, detailed posts a second chance to be discovered.
