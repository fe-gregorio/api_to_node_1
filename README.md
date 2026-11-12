# Color Direction Tool

A creative tool for developing color art direction for campaigns, videos, and animations using real visual references.

This is a prototype for an API assignment, with the longer-term goal of turning the workflow into a reusable node in a creative AI canvas toolkit.

## The idea

Search for an image on **Adobe Stock**, select a visual reference, extract its prominent colors, and use **The Color API** to explore related palettes. The output helps creative teams move from an image reference to color directions that can be reused across a project.

## APIs and libraries

| Tool | Purpose | Access |
| --- | --- | --- |
| [Adobe Stock API](https://developer.adobe.com/stock/docs/getting-started/) | Search for reference images and retrieve previews and metadata | Adobe developer access and API credentials; licensing requires additional authorization |
| [The Color API](https://www.thecolorapi.com/docs) | Generate color harmonies and return HEX/RGB values and color names | No API key required |
| [Pillow](https://pillow.readthedocs.io/en/stable/) | Python library to inspect an image and sample its colors | Installed locally; **not** a third API |