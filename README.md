# Otherworldly Artifacts Gallery

This is a web app that allows users to browse a gallery of otherworldly artifacts. The app provides a user-friendly interface to display a list of artifacts, including an image, and additional details about each artifact in a modal dialog when selected.

## Features
- Displays a list of artifacts with basic details and images.
- Clicking on an artifact opens a modal dialog with full details.
- A close button in the modal allows the user to dismiss it.
- User-friendly design with a clean and modern color scheme.

## Requirements
To complete the project, the app includes:
- A list of artifacts displaying key attributes and images.
- A modal dialog that presents all attributes of the selected artifact.
- A close button within the modal dialog.
- Proper formatting for each displayed data attribute.
- Data loaded via Fetch API from a remote JSON data source.

### Technology Stack
- **HTML** for structure.
- **CSS** for styling and layout.
- **JavaScript** for functionality and event handling.
- **Fetch API** to retrieve data from a remote server.

## Installation and Setup
1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/artifacts-gallery.git
    ```
2. Navigate into the project folder:
    ```bash
    cd artifacts-gallery
    ```
3. Open `index.html` in your preferred browser.

## Usage
1. Upon loading the app, you will see a list of artifacts displayed as cards.
2. Click on any artifact card to view more detailed information in a modal.
3. Close the modal by clicking the close button (`×`) or by clicking outside the modal.

## Data Source
This project uses an API to fetch artifact data, including names, descriptions, images, origins, and power levels.
- **API Endpoint**: [https://artifacts-api.up.railway.app/artifacts](https://artifacts-api.up.railway.app/artifacts)

## Folder Structure
