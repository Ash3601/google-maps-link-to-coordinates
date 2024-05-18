# Google Maps Coordinates Extractor (Client-Side Only)

This simple HTML/CSS/JavaScript tool extracts latitude and longitude coordinates directly from expanded Google Maps URLs. It's designed for use in the browser and does not require a server-side component for basic functionality.

## Features

* **Direct Coordinate Extraction:**  Parses coordinates from Google Maps URLs that contain the `@latitude,longitude` format.
* **Query Parameter Extraction:** Handles URLs with coordinates in the `ll` query parameter (e.g., `?ll=latitude,longitude`).
* **Copy to Clipboard:** Easily copy the extracted coordinates with a single click.
* **Responsive Design:** Works well on desktop and mobile browsers.

## Usage

1. **Paste Expanded Google Maps URL:** Enter a **fully expanded** Google Maps URL (not a shortened URL) into the input field. 
    * The URL should contain coordinates either directly (e.g., `https://www.google.com/maps/@lat,lng`) or as query parameters (e.g., `https://www.google.com/maps/place/...&ll=lat,lng`).
2. **Click "Get Coordinates":** The tool will attempt to extract the coordinates from the URL.
3. **Copy Coordinates:** If the coordinates are found, click the "Copy" button next to them.

## Limitations

* **Expanded URLs Only:** This tool only works with fully expanded Google Maps URLs. It cannot handle shortened URLs or place links that require geocoding.
* **Limited URL Formats:** It supports a limited range of URL formats. It might not work with all Google Maps URLs.

## Contributing

This project is a basic client-side tool. However, contributions to improve functionality or error handling are welcome! Feel free to open issues or submit pull requests.
