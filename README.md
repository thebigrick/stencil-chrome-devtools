# BigCommerce Stencil Context Analyzer

## Table of contents

- [Overview](#overview)
- [Getting started](#getting-strted)
- [Features](#features)
- [Usage](#usage)
  - [In Action](#in-action)
- [Development for contribution or customization](#development-for-contribution-or-customization)
  - [Prerequisites](#prerequisites)
  - [Building the Extension](#building-the-extension)
  - [Running in Development Mode](#running-in-development-mode)
- [Contributing](#contributing)
- [License](#license)

## Overview

BigCommerce Stencil Context Analyzer is a Chrome extension designed to aid developers working with BigCommerce Stencil themes.
This extension provides a contextual analysis tool, allowing developers to easily inspect and debug the context in local development environments.

## Getting started

- Add the extension to your Chrome browser from the Chrome Web Store at this link: [BigCommerce Stencil Context Analyzer](https://chromewebstore.google.com/detail/bigcommerce-debug-extensi/anodmbnkfihdenokbndlbfppoojmfcgp) .
- Start a local development environment for a BigCommerce Stencil theme (**must be on localhost:3000**).
- Open the Chrome DevTools and navigate to the **BigCommerce Stencil** tab to view the context data.
  - Use the search bar to find specific context variables and explore the context data as needed.

## Features

- Context inspection for BigCommerce Stencil themes.
- Display detailed context data directly within the Chrome DevTools.
- Easy navigation and search functionality to find specific context variables.

### In Action

![in action](https://github.com/phoenix128/bigcommerce-stencil-chrome/blob/main/doc-files/action.gif?raw=true)

## Usage

1. Download the extension from the chrome store
2. Open your BigCommerce local development environment in Chrome.
3. Open the Chrome DevTools by pressing `F12` or `Ctrl+Shift+I`.
4. Navigate to the **BigCommerce Stencil** tab.
5. Use the search bar to find specific context variables.
6. Explore the context data as needed for debugging and development purposes.

## Development for contribution or customization

If you wish to contribute to this project, follow the instructions below to get started.

### Prerequisites

- Node.js
- npm

### Building the Extension

1. Install the dependencies:
    ```sh
    npm install
    ```

2. Build the project:
    ```sh
    npm run build
    ```

3. Reload the extension in Chrome:
    - Go to `chrome://extensions/`
    - Set development mode
    - Click on "Load unpacked" and select the directory containing the code from this repo
    - Click on the **Reload** button for the BigCommerce Stencil Context Analyzer extension.

### Running in Development Mode

To run the extension in development mode with live reloading:

1. Start the development server:
    ```sh
    npm start
    ```

2. Start a local stencil theme development on port 3000
3. Open Chrome and navigate to http://localhost:4000/panel.html

## Contributing

Contributions are welcome! Please submit any bugs, issues, or feature requests through the project's GitHub issue tracker.

## License

Distributed under the MIT License. See LICENSE.txt for more information.


