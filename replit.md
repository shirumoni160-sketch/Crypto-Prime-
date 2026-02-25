# Crypto Prime Signals

A static HTML website for a premium crypto trading signals platform.

## Project Structure

- `index.html` - Main (and only) page of the site

## Running the Project

The site is served using Python's built-in HTTP server:

```
python3 -m http.server 5000 --bind 0.0.0.0
```

Runs on port 5000.

## Deployment

Configured as a static site deployment with `publicDir: "."`.
