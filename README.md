# Facebook Ads Campaign Analysis Extension

A Chrome extension that enhances Facebook Ads Manager with LLM-powered analysis and insights.

## Features

- Integration with Facebook Ads Manager
- Side panel with campaign analytics
- Popup interface for quick access to controls
- Background script for data processing
- Secure communication between content scripts and background processes

## Installation

### Development Mode

1. Clone this repository:
   ```
   git clone https://github.com/matheuspinhati/facebook-ads-extension.git
   cd facebook-ads-extension
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Build the extension:
   ```
   npm run build
   ```

4. Load the extension in Chrome:
   - Open Chrome and navigate to `chrome://extensions/`
   - Enable "Developer mode" in the top-right corner
   - Click "Load unpacked"
   - Select the `dist` folder in the project directory

## Development

### Available Scripts

- `npm run build`: Builds the extension for production
- `npm run dev`: Builds the extension and watches for changes
- `npm run test`: Runs the test suite

### Project Structure

- `public/`: Static files copied to the build folder
- `src/`: Source code
  - `background/`: Background scripts
  - `contentScript/`: Content scripts injected into Facebook pages
  - `popup/`: Extension popup interface
  - `sidepanel/`: Side panel interface for detailed analytics
  - `utils/`: Shared utilities and helpers

## License

MIT