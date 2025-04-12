# Print Manager

Print Manager is a versatile web application designed to help users create, customize, and print compositions with ease. Whether you're planning a project with specific timeframes or designing a visual layout, Print Manager provides an intuitive interface and powerful tools to bring your ideas to life. Built with HTML, CSS, and JavaScript, it runs directly in your browser, making it accessible and easy to use.

## Features

- **Image Handling**: Upload multiple images and manipulate them with scaling and rotation options.
- **Text Boxes**: Add customizable, draggable text boxes with editable content.
- **Line Drawing**: Draw lines with snapping to horizontal or vertical orientations for precision.
- **Timeframe Management**: Automatically calculate project durations based on start and deadline dates, splitting them into Carpentry (70%) and Finishing (30%) phases.
- **Customization**: Adjust image scale, toggle black-and-white mode, rotate images, modify preview height, and toggle borders.
- **Print Optimization**: Preview and print compositions with adjustable settings, ensuring a polished output.

## Installation

Print Manager is a web-based application that requires no complex installation. To get started:

1. Download or clone the project files to your local machine.
2. Open the `index.html` file in a modern web browser (e.g., Chrome, Firefox, Edge).
3. Begin using the application immediately—no additional dependencies or setup required.

**Browser Compatibility**: Print Manager is optimized for modern browsers. For the best experience, use the latest version of your preferred browser.

## Usage

Print Manager offers a straightforward interface with a side panel for controls and a preview area for your composition. Below are instructions for common tasks:

### Uploading an Image
1. In the side panel, click the "Choose Files" button or drag and drop images into the browser window.
2. Select one or more image files from your computer.
3. The images will appear in the preview area, each on its own page.

### Adding a Text Box
1. Click the "Add Text Box" button in the side panel.
2. In the modal that appears, enter your desired text (supports multiple lines).
3. Click "Done" to add the text box to the most recently uploaded image's preview.
4. Drag the text box to reposition it or use arrow keys for precise movement.

### Drawing a Line
1. Click the "Add Line" button in the side panel.
2. Click and drag within the preview area to draw a line (snaps to horizontal or vertical if near those angles).
3. Release to finalize the line, then drag it to reposition as needed.

### Managing Timeframes
1. The "Start Time" field defaults to today’s date.
2. Enter a date in the "Deadline" field (e.g., `YYYY-MM-DD`).
3. Click "Add Timeframe" to calculate and display the duration, including:
   - Total days
   - Carpentry phase (70% of total)
   - Finishing phase (30% of total)
4. The timeframe details appear in the top-right corner of each preview.

### Customizing the Composition
- **Scale Image**: Use the "Resize Image" slider (50% to 200%) to adjust the image size.
- **Rotate Image**: Click "Rotate Image" to rotate the image 90 degrees clockwise.
- **Black & White**: Click "Black & White" to toggle grayscale mode.
- **Toggle Border**: Click "Toggle Border" to show or hide the preview border.
- **Adjust Height**: Click "Adjust Height" and enter a new height in millimeters (e.g., `200`) to resize the preview.

### Printing
1. Customize your composition using the tools above.
2. Click the "Print" button to open your browser’s print dialog.
3. Adjust print settings (e.g., paper size, orientation) and print your composition.

## Customization

Print Manager is built with HTML, CSS, and JavaScript, making it highly customizable. Here are some ways to tailor it to your needs:

- **Default Settings**: Edit the JavaScript (e.g., `currentScale`, `rotation`) to change initial values.
- **Styles**: Modify the CSS in the `<style>` section to adjust colors, fonts, or layout.
- **Features**: Extend functionality by adding new buttons or modifying existing logic in the `<script>` section.

For example, to change the default preview height, update the `--preview-height` variable in the JavaScript `adjustHeight` function.

## Contributing

We welcome contributions to Print Manager! To contribute:

1. Fork the repository on GitHub.
2. Create a new branch for your feature or bug fix (e.g., `git checkout -b feature/new-tool`).
3. Make your changes and commit them with clear, descriptive messages.
4. Push your changes to your fork (e.g., `git push origin feature/new-tool`).
5. Submit a pull request to the main repository for review.

Please ensure your code follows the existing style and includes comments where necessary.
