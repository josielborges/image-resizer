# Multiple Image Resizer

A simple and intuitive web application to load, adjust, and save images with control over resizing and positioning.

## About the Application

This tool allows you to select single/multiple images simultaneously and adjust each one individually within a globally defined container size and shape. It's ideal for preparing images for avatars, thumbnails, or other uses where a specific size and aspect ratio are required for a set of images.

## Features

* **Multiple Image Selection:** Load several images at once using the file input.
* **Individual Container Views:** Each loaded image appears in its own editing block with a dedicated preview area.
* **Global Dimension and Format Settings:** Define the width, height, and format (rectangular or circular) that will be applied to all image containers.
* **Individual Zoom and Positioning:** For each image, adjust the zoom level and drag it within its container to choose the exact cropping area.
* **Save Image Individually:** Download the resized and cropped image of each item separately.
* **Copy Image Individually:** Copy the resized and cropped image of each item to the system clipboard (requires browser support).
* **Save All Images (ZIP):** Download all adjusted images in a single ZIP file.
* **Consistent Visual Identity:** Maintains the original visual identity provided in the base code.

## How to Use

1.  **Load Images:** Click the "Selecionar imagens" (Select images) button in the control panel and choose the images you want to resize. You can select multiple images.
2.  **Adjust Global Settings:** In the "Configurações Globais" (Global Settings) panel, set the "Unidade" (Unit - Pixels or Centimeters), "Largura" (Width), "Altura" (Height), "Prefixo do arquivo" (File prefix - for names when saving), and "Formato" (Format - Rectangular or Circular). Click "Aplicar Dimensões" (Apply Dimensions) to apply the settings to all image containers.
3.  **Adjust Individually:** For each image in the grid, use the zoom slider or the mouse wheel over the image to adjust the zoom. Click and drag the image to position it within the container (frame).
4.  **Save or Copy:** Use the "Salvar" (Save) or "Copiar" (Copy) buttons in each image item to get the image individually.
5.  **Save All:** Click the "Salvar Todas (.zip)" (Save All (.zip)) button in the control panel to download a ZIP file containing all adjusted images.

## Libraries Used

* [JSZip](https://stuk.github.io/jszip/) for generating the ZIP file on the client side.
* [FileSaver.js](https://github.com/eligrey/FileSaver.js/) to facilitate saving generated files in the browser.

Both libraries are loaded via CDN (Content Delivery Network) directly within the HTML file.

## Tools links

[Single image resizer](https://josielborges.github.io/image-resizer/single-image.html)

[Multiple image resizer](https://josielborges.github.io/image-resizer/multiple-images.html)