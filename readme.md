# Cookie Editor Extension

The Cookie Editor is a browser extension designed for developers, testers, and privacy-conscious users to easily view, edit, and manage cookies for any website. This extension is available as an unpacked extension, meaning you can install it directly from the source code.

## Features

- **View Cookies**: Browse and search cookies set by any website in a user-friendly interface.
- **Edit Cookies**: Modify cookie values, expiry dates, and other attributes directly within the extension.
- **Add New Cookies**: Create new cookies with custom values and settings for any domain.
- **Delete Cookies**: Remove specific cookies or clear all cookies for a domain at once.
- **Export/Import Cookies**: Export cookies to a JSON file for backup or sharing, and import cookies from JSON files.
- **Bulk Actions**: Select multiple cookies to edit or delete them in bulk.
- **Responsive Design**: Fully functional on different screen sizes, including mobile devices.

## Installation

Since this extension is not available on the Chrome Web Store or Firefox Add-ons, you'll need to install it manually as an unpacked extension.

### Chrome

1. **Download or Clone the Repository:**
   - Download the repository as a ZIP file and extract it, or clone it using Git:
     ```bash
     git clone https://github.com/shaileshsaravanan/cookie-editor-extension.git
     ```

2. **Load Unpacked Extension:**
   - Open Chrome and go to `chrome://extensions/`.
   - Enable "Developer mode" in the top right corner.
   - Click "Load unpacked" and select the folder containing the extension's files.

3. **Access the Extension:**
   - The Cookie Editor extension should now appear in your browser's toolbar. Click the icon to start using the extension.

### Firefox

1. **Download or Clone the Repository:**
   - Download the repository as a ZIP file and extract it, or clone it using Git:
     ```bash
     git clone https://github.com/yourusername/cookie-editor-extension.git
     ```

2. **Load Temporary Add-on:**
   - Open Firefox and go to `about:debugging#/runtime/this-firefox`.
   - Click on "Load Temporary Add-on..." and select the `manifest.json` file inside the extension's folder.

3. **Access the Extension:**
   - The Cookie Editor extension icon should now appear in your browser's toolbar.

**Note:** In Firefox, the extension will be removed when you close the browser. To keep it permanently, you need to load it each time or consider submitting it to the Firefox Add-ons site.

## Usage

1. Click on the Cookie Editor icon in your browser's toolbar.
2. Select the website whose cookies you want to manage.
3. Use the provided tabs and controls to view, edit, delete, or export cookies.
4. To import cookies, click the "Import" button and upload your JSON file.


## Contributing

We welcome contributions from the community! Here's how you can contribute:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Submit a pull request with a detailed description of your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

*Disclaimer: This extension is designed for developers and advanced users. Modifying cookies can affect website functionality and security. Use with caution.*
