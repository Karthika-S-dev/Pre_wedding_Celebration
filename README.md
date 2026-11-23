# Karthika & Ram Narayan — Pre-wedding celebration

A mobile-first static invitation for the private celebration on 1 December 2026.

## Preview
Open `index.html` in a browser. Keep the four JPEG files in this folder beside it.

## Publish with the existing GitHub Pages site
Upload the entire `prewedding-celebration` folder into the root of the `Karthika-Ram-Wedding` repository. This keeps the original wedding invitation at the root and makes this one available at:

`https://karthika-s-dev.github.io/Karthika-Ram-Wedding/prewedding-celebration/`

The social preview image is set to that hosted `cover.jpeg` path. If you publish it somewhere else, update the `og:image` URL in `index.html`.

## Editable details
At the bottom of `index.html`, edit the `CONFIG` object to change names, date/time, venue, maps URL, music video, or photo filenames. Replace the corresponding JPEG files in this folder to change the photos. The WhatsApp share preview uses the title, description, and cover image metadata in the `<head>`.

Music opens after a tap because mobile browsers block automatic audio. The player uses the previously shared YouTube Music track and provides a direct YouTube Music link as a fallback.
