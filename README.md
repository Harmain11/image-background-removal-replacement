# Image Background Removal and Replacement

## Overview
This notebook demonstrates how to remove and replace image backgrounds using machine learning with the `rembg` library. It includes a simple Streamlit-based web app for interactive background editing by either uploading images or entering image URLs.

## Features
- Remove image backgrounds using ML with `rembg`.
- Replace backgrounds with user-provided or URL-based images.
- Interactive Streamlit app for image upload, processing, and viewing.
- Adjustable background removal threshold slider.
- Saves original, masked, and merged images locally.

## Tech Stack
- Python
- Jupyter Notebook / Google Colab
- Streamlit
- Libraries: `rembg`, `PIL` (Pillow), `requests`, `pyngrok`

## How to Use
1. Clone the repository.
2. Open the notebook `image-background-removal-replacement.ipynb` in Jupyter or Google Colab.
3. Install dependencies with pip (`rembg`, `streamlit`, `pyngrok`).
4. Run cells to prepare images and launch the Streamlit app.
5. Use the app to either upload local images or input image URLs.
6. Adjust background removal threshold and view the results.
7. The processed images are saved in `original` and `masked` folders.

## Status
This notebook is organized and documented for clean GitHub presentation and easy user interaction.