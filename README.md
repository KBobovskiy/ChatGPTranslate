![ChatGPTranslate](src/icons/icon128.png)

# ChatGPTranslate

## Description
ChatGPTranslate is a Chrome extension that allows users to highlight text on any webpage, click an icon to translate the text using OpenAI, and get an explanation of the translated text. It provides a seamless way to understand and interpret foreign language content directly from your browser.

<img width="428" alt="Screenshot 2024-06-15 at 6 28 57 PM" src="https://github.com/johnlewissims/ChatGPTranslate/assets/43911794/c36c62d7-a7e7-4f0e-8773-b38f6d604c87">

## Features
- Highlight text and click an icon to translate it.
- Get an explanation of the translated text.
- Hear the pronunciation of the text.
- Optionally receive a word-by-word breakdown of the text.
- Dynamically loads a popup with translation, explanation, and breakdown.
- Settings page for entering and saving OpenAI API Key.
- Toggle settings to always display explanations or show them via links.

## Installation and Setup

### Step 1: Clone the Repository
Clone this repository to your local machine using:
```bash
git clone https://github.com/johnlewissims/ChatGPTranslate.git
```

### Step 2: Install Dependencies
Navigate to the project directory and install the necessary dependencies using:
```bash
cd ChatGPTranslate
npm install
```

### Step 3: Build the Project
Build the project to generate the dist folder:
```bash
npm run build
```

### Step 4: Load the Extension in Chrome
- Open Chrome and go to chrome://extensions/.
- Enable "Developer mode" by toggling the switch in the top right corner.
- Click the "Load unpacked" button and select the directory where you cloned the repository.

### Step 5: Set Your OpenAI API Key
- Click on the extension icon in the Chrome toolbar.
- If you haven't set an API key, you'll see an instruction message.
- Click the link to go to the settings page.
- Enter your OpenAI API Key and save it. You can obtain your API key from the OpenAI API Keys page.
