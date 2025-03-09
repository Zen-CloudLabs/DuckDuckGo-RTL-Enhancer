# DuckDuckGo RTL Enhancer

A simple userscript that automatically applies right-to-left text direction to DuckDuckGo search results containing Persian, Arabic, or other RTL language content.

## Features

- Automatically detects search results with RTL language content
- Applies RTL text direction for better readability
- Adds Vazirmatn font for improved RTL text display
- Works with dynamically loaded search results

## Installation

1. Install a userscript manager extension:
   - [Tampermonkey](https://www.tampermonkey.net/) (Chrome, Edge, Firefox)
   - [Violentmonkey](https://violentmonkey.github.io/) (Chrome, Firefox)
   - [Greasemonkey](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/) (Firefox)

2. Install this script from:
   - [GitHub](https://raw.githubusercontent.com/Zen-CloudLabs/DuckDuckGo-RTL-Enhancer/refs/heads/main/duckduckgo-rtl-enhancer.js)
   - [Greasy Fork](https://update.greasyfork.org/scripts/529245/DuckDuckGo-RTL-Enhancer.user.js)

## How It Works

The script analyzes search result text and applies RTL direction when more than 40% of the characters are from RTL languages. It also sets Vazirmatn as the font for better RTL text rendering.

## Contributing

Feel free to submit issues or pull requests on GitHub.

## License

MIT License

