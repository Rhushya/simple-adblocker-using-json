# simple-adblocker-using-json
This is a simple adblocker for chrome where it block google ads  and can be used or extended to other website or links for blocking ads 

# Ad Blocker Extension

This extension blocks requests to certain advertising domains using the Declarative Net Request API in Google Chrome.

## Getting Started

Follow these steps to deploy the extension using Google Developer mode:

### 1. Clone the Repository

Clone this repository to your local machine:

[![Clone in VSCode](https://img.shields.io/badge/Clone%20in-VSCode-blue.svg)](vscode://clone?url=https%3A%2F%2Fgithub.com%2FRhushya%2Fsimple-adblocker-using-json.git)



### 2. Load the Extension in Chrome

1. Open Google Chrome and navigate to `chrome://extensions/`.
2. Enable Developer mode by toggling the switch in the upper-right corner.
3. Click on the "Load unpacked" button.
4. Select the directory where you cloned the repository.

### 3. Verify Extension Deployment

Once the extension is loaded, you should see it listed among your installed extensions in Chrome. Make sure it's enabled.

### 4. Testing

To test the extension, visit web pages that include ads from domains such as `doubleclick.net` or `googleadservices.com`. The extension should block requests to these domains.

## File Structure

- **rules.json**: Contains the rules for blocking ads.
- **manifest.json**: Manifest file that defines the extension's metadata and permissions.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
