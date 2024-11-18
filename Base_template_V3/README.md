# Chrome Extension v3 Starter

![Chrome Extension Logo](https://raw.githubusercontent.com/SimGus/chrome-addon-v3-starter/master/logo/logo-128.png)

This repo contains a basic, working example of a Chrome extension using **manifest v3**. It's perfect for getting started with building your own extension or understanding how to upgrade an older extension to v3.

## What’s Inside?
- **Manifest v3**: The newest version for Chrome extensions.
- **Popup**: A simple popup to interact with the extension.
- **Service Worker**: Background logic running in the extension.

## Installation Guide

1. **Clone the repo** using the following command:
   ```bash
   git clone https://github.com/varungupta04/Extension
2. Navigate to the folder to work with the template
   cd Extension/Base_template_V3
   
## Browser Compatibility
- Works on any **Chromium-based browsers** like Chrome, Chromium, Brave, Edge, Vivaldi, and Opera.
- **Doesn’t work** on Firefox or Safari because they use different formats.

## FAQs

### How do I remove the popup?
If you don’t need the popup, just delete the `popup` folder and remove `default_popup` from the `manifest.json` file.

### How to debug?
To debug your service worker:
1. Go to **chrome://extensions**.
2. Find your extension and click on **service worker**.
3. Paste your code into the console and see any errors.

### Uninstalling the extension
- Go to **chrome://extensions**.
- Find the extension and click **Delete**.

### Can I push my changes to my repo?
1. Create a GitHub account and set up Git.
2. Initialize the repo with `git init`.
3. Push your changes with `git push`.

## External Resources
- [Manifest v3 Overview](https://developer.chrome.com/docs/extensions/mv3/intro/mv3-overview/)
- [Migrating from v2 to v3](https://developer.chrome.com/docs/extensions/mv3/intro/mv3-migration/)
