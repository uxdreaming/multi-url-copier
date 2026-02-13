# Links Capture

Chrome extension to capture multiple URLs from a page without navigating to them. Two modes: grab all links at once, or manually pick the ones you need.

## Features

- **Bulk capture**: Copy every URL on a page with one shortcut
- **Manual selection**: Click on specific links to build your list
- **Smart filtering**: Only captures valid `http`/`https` URLs, auto-deduplicates
- **Toast notifications**: See captured URLs in real-time
- **Zero UI**: No popup, no toolbar — just keyboard shortcuts

## Installation

1. Clone this repository
2. Go to `chrome://extensions/`
3. Enable **Developer mode**
4. Click **Load unpacked** and select the folder

## Usage

| Shortcut | Action |
|----------|--------|
| `Alt+Shift+U` | Copy ALL links on the current page |
| `Alt+U` | Toggle manual selection mode |
| `Click` | Capture a link (in selection mode) |
| `Alt+U` | Copy captured links and exit selection |
| `Esc` | Cancel without copying |

### Bulk capture

Press `Alt+Shift+U` to instantly copy all URLs from the page to clipboard, one per line.

### Manual selection

1. Press `Alt+U` — page dims slightly, cursor becomes crosshair
2. Click on links to add them to your list (toast shows each capture)
3. Press `Alt+U` again to copy all selected URLs and exit

## Permissions

| Permission | Why |
|------------|-----|
| `clipboardWrite` | Copy URLs to clipboard |
| `<all_urls>` | Run on any page |

## License

MIT
