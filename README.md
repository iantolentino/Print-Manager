# Drag then Print

A simple web application that allows users to **upload or drag‑and‑drop multiple images**, adjust various print parameters, and then print each image on its own page with optional text overlays and transformations.

## Features

1. **Multiple Image Support**  
   - Select or drag‑and‑drop multiple images at once.  
   - Each image is displayed in its own paper preview.

2. **Text Overlays**  
   - Add a title/description and a deadline/date to each preview.  
   - Overlays appear at the bottom‑left corner of each page in the final printout.

3. **Transformation & Orientation**  
   - **Scale** images from 50% to 200%.  
   - **Rotate** images in 90° increments.  
   - **Center** images or let them fill naturally.  
   - **Toggle orientation** between portrait (210mm × 297mm) and landscape (280mm × 190mm).

4. **Image Effects**  
   - **Black & White** mode applies a grayscale filter.  
   - **Toggle Border** around each paper preview.

5. **Print Multiple Pages**  
   - Each image prints on its own page.  
   - Page breaks are automatically inserted for each preview.

## How It Works

1. **Select Images**  
   - Click **Choose Files** to browse and select multiple images, **or** drag them anywhere onto the window to auto‑upload.

2. **Preview & Adjust**  
   - Each image appears in its own paper preview.  
   - Use the **slider** to resize.  
   - Click **Center Image**, **Landscape**, **Portrait**, **Rotate Image**, **Black & White**, or **Toggle Border** to adjust how each preview appears.

3. **Add Text/Deadline**  
   - Type your text and deadline in the input fields, then click **Apply Text**.  
   - Text overlays appear in the bottom‑left corner of each preview.

4. **Print**  
   - Click **Print** to open your browser’s print dialog.  
   - **Tip**: Set print margins to “None” or “Minimum” for best results.  
   - Each preview prints on its own page.

## Usage

1. **Open the HTML File**  
   - Double‑click the `index.html` (or whichever filename you use) to open it in your preferred browser.  

2. **Add Images**  
   - Drag images onto the window **or** click the file input to select multiple images.  

3. **Customize**  
   - Type text/deadline, choose orientation (Landscape or Portrait), rotate if needed, and apply any filters.  

4. **Print**  
   - Click **Print**. In the print dialog, ensure margins are set appropriately (often “None” or “Minimal”) and pick the correct paper size.  

## Tips & Troubleshooting

- **Images Cut Off in Print**  
  - Make sure margins are set to None/Minimal in your print dialog.  
  - Try reducing the scale slider (e.g., 90%) if the image is still too large.  
- **Landscape vs. Portrait**  
  - Landscape previews have a wider, shorter dimension (280mm × 190mm). If the image seems off‑center, use **Center Image** mode.  
- **Drag & Drop**  
  - Drag files anywhere on the page. If it’s not working, check the console for errors or confirm you’re dropping valid image files.

## Customization

- **Default Deadline**  
  - If no deadline is entered, the script automatically inserts the current date/time.  
- **Orientation & Position**  
  - Adjust the `updateTransform()` function for custom transformations.  
- **Border & Padding**  
  - Toggling the border also adjusts padding to ensure images remain fully visible.

## Contributing

1. **Fork** the repository (if hosting on GitHub).  
2. Create a **new branch** for your feature or bug fix.  
3. **Commit** your changes, then open a **pull request**.

## License

This project is released under the [MIT License](https://opensource.org/licenses/MIT). You are free to use, modify, and distribute this code in your own projects.

**Enjoy using “Drag then Print” for your multi-image printing needs!** If you have any questions or run into any issues, feel free to reach out.
