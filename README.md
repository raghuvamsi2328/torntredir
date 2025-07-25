# Magnet Link Redirector

A simple web application that redirects magnet links based on the user's operating system.

## Features

- **Smart OS Detection**: Automatically detects iOS, macOS, and other platforms
- **Universal Web Player**: All users are redirected to instant.io web torrent player
- **Flexible Input**: Accepts both info hashes and full magnet links
- **Tracker Integration**: Automatically adds popular tracker servers
- **URL Hash Support**: Works with hash-based URLs for easy sharing

## Usage

### Basic Usage
```
https://yourusername.github.io/torntredir/#[INFO_HASH]
```

### Examples
```
# With info hash only
https://yourusername.github.io/torntredir/#1234567890abcdef1234567890abcdef12345678

# With full magnet link
https://yourusername.github.io/torntredir/#magnet:?xt=urn:btih:1234567890abcdef1234567890abcdef12345678
```

## How It Works

1. The application reads the hash value from the URL
2. Detects the user's operating system
3. Formats the magnet link with additional trackers
4. Redirects to instant.io web torrent player for all platforms

## Files

- `index.html` - Main redirector page
- `test.html` - Test page with sample links and debug information

## Testing

Open `test.html` in your browser to test various scenarios and see debug information about OS detection.

## Deployment

This project is designed to work with GitHub Pages. Simply:

1. Push to a GitHub repository
2. Enable GitHub Pages in repository settings
3. Access via `https://yourusername.github.io/repositoryname/`

## Browser Support

Works in all modern browsers. Tested on:
- Safari (iOS/macOS)
- Chrome (all platforms)
- Firefox (all platforms)
- Edge (Windows)

## License

MIT License - feel free to use and modify as needed.
