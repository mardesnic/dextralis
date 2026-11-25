# des-dextralis

The Dextralis page: logo and contact details. Plain HTML, no build.

Demo: https://dextralis.hr/

## Features

- One page: the Dextralis logo, email and GitHub
- Light and dark mode (the logo follows the text colour)
- Works at phone width

## Development

No build step. Serve the folder and open it:

```bash
python3 -m http.server 8080
```

`logo/` holds the logo versions (mark, wordmark, horizontal, vertical).
`CNAME` keeps the `dextralis.hr` domain on GitHub Pages.
