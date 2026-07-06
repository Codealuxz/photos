# Photos

My photography portfolio, live at **[photo.codealuxz.fr](https://photo.codealuxz.fr)**.

A static gallery in **pure HTML/CSS/JS**, with a small Python script that generates the thumbnails.

## How it works

- `photos.json` lists all the pictures and their metadata
- `generate_thumbnails.py` creates optimized thumbnails from the originals in `photos/`
- The front end loads `photos.json` and renders the gallery, no framework involved

## Add new photos

1. Drop the originals into `photos/`
2. Run the thumbnail generator:

```bash
python generate_thumbnails.py
```

3. The gallery picks them up automatically

## Stack

- HTML / CSS / JavaScript (vanilla)
- Python (Pillow) for thumbnail generation
