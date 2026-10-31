# Encyclopedia of the Farm

An offline, high-fidelity archive and mirror of **Encyclopedia of the Farm** (La Granja Ibiza / Slowness).

## Overview

This repository preserves the complete editorial structure, botanical entries, environmental soundscapes, and cinematic video loops of the Encyclopedia of the Farm:

- **12 Botanical Entries**: Avocado, Chili, Carrot, Eggplant, Greens, Herbs, Longbean, Lavender, Pepper, Strawberry, Tomatoes, Watermelon.
- **200 Video Loops**: All authentic Vimeo MP4 video loops preserved locally.
- **Soundscapes**: Environmental field recordings and audio modules.
- **Responsive Layout**: Powered by ZURB Foundation and original custom stylesheets.

## Running Locally

### Option 1: Using Go (Native)
```bash
go run server.go
```
Then visit [http://localhost:8080](http://localhost:8080).

### Option 2: Using Python
```bash
python3 -m http.server 8080
```
Then visit [http://localhost:8080](http://localhost:8080).

### Option 3: Static Hosting / GitHub Pages
This repository is pre-configured for direct static hosting. To enable GitHub Pages:
1. Go to repository **Settings** -> **Pages**.
2. Under **Build and deployment**, select source: **Deploy from a branch**.
3. Select branch: `main`, folder: `/ (root)`.
4. Click **Save**.

## License & Attribution
Content and assets originally produced by Slowness & Studio Airport. Preserved for educational and archival research purposes.
