# What If You Read Instead?

A minimal web calculator that shows how many books you could read if you swapped your daily doom scrolling time for reading.

Enter your daily scroll time, and the tool tells you how many books you'd finish per day, per week, and per year — with a visual progress bar for partial books.

## Features

- **Instant calculation** — results update live as you type
- **Minutes or hours** — toggle between input units
- **Advanced mode** — enter your own reading speed (words per minute) for a tailored result
- **Shareable URLs** — the URL updates automatically as you type, so you can copy and share a pre-filled link
- **Mobile friendly** — touch-optimized with responsive layout
- **Zero dependencies** — single HTML file, no frameworks, no build step
- **No tracking** — runs entirely in the browser, no data collected

## How it works

The calculation is based on:

- **Average reading speed:** 238 words per minute
- **Average book length:** 200 pages × 300 words per page = 60,000 words
- **Time to read one book:** ~252 minutes (~4.2 hours)

These are rough estimates. The advanced mode lets users override the reading speed for a more personal result.

## Shareable URLs

The URL updates automatically as you type. Supported query parameters:

| Parameter | Description | Example |
|-----------|-------------|---------|
| `minutes` | Daily scroll time in minutes | `?minutes=45` |
| `hours` | Daily scroll time in hours | `?hours=2` |
| `wpm` | Custom reading speed (advanced mode) | `?minutes=45&wpm=300` |

Copy the URL from your browser's address bar at any point to share a pre-filled result.

## Usage

Open `index.html` in any browser. That's it.

To host it yourself, drop the file on any static hosting service (GitHub Pages, Netlify, Vercel, or just open it locally).

## Deployment on GitHub Pages

1. Clone or fork this repo
2. Make sure the main file is named `index.html`
3. Go to **Settings → Pages** in your repo
4. Set source to **Deploy from a branch** → `main` / `/ (root)`
5. Your site will be live at `https://yourusername.github.io/doom-scroll-calculator/`

## License

MIT — see [LICENSE](LICENSE) for details.
