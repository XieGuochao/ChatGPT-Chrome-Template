# ChatGPT-Chrome-Template

ChatGPT Chrome Extension Template is a quick-start template for building a Chrome Extension that uses ChatGPT. It is based on the [ChatGPT JS Toolkit](https://github.com/XieGuochao/ChatGPT-JS-Toolkit).

## Usage

### Description

This template illustrates how to use [ChatGPT JS Toolkit](https://github.com/XieGuochao/ChatGPT-JS-Toolkit) in Chrome Extension. The demo application has the following functionalities:

- Store and manage the credential information.
- Query available models.
- Trigger event on text selection.
- Start a new chat with the selected text and query ChatGPT for completion.

### Customization

Here's the directory structure so that one could easily extend and build their own applications:

- `/scripts`: The scripts loaded on specific websites.
  - `authentication.js`: Validate credential by querying the available models.
  - `selection-action.js`: Handle the text selection event and query ChatGPT.
- `/src`: The `index` and `options` pages.
  - `index.html`, `index.js` and `index.css`: The index page when clicking on the extension icon.
  - `options.html`, `options.js` and `options.css`: The options page for extension configuartions.
- `chatgpt.js`: The [ChatGPT JS Toolkit](https://github.com/XieGuochao/ChatGPT-JS-Toolkit).
- `manifest.json`: Manage the scripts and pages. For more information, please refer to the [Documentation of Chrome Extension Manifest v3](https://developer.chrome.com/docs/extensions/mv3/intro/).
- `utils.js`: Functions used by both scripts and popup pages.

### Update `chatgpt.js`

This template is guaranteed to sync with [ChatGPT JS Toolkit](https://github.com/XieGuochao/ChatGPT-JS-Toolkit) for the latest [chatgpt.js](./chatgpt.js). If you would like to update manually, simply download the latest one from [ChatGPT JS Toolkit](https://github.com/XieGuochao/ChatGPT-JS-Toolkit).

## License

[MIT](LICENSE)
