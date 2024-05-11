# ChatAi Basic Android
## Features

- Simple and clean user interface
- Send messages to ChatGPT and receive responses in real-time
- Manage API keys for authenticating with ChatGPT API
- Settings for customizing API call parameters (e.g., response length, temperature)

## Getting Started

### Prerequisites

- Android Studio
- Android SDK (minimum API level 21 - Lollipop)
- A valid API key from OpenAI for accessing the ChatGPT API

### Installation

1. Clone the repository
2. Add your OpenAI API key in `OpenAIApi.kt`
3. Build and run the app on an emulator or a physical device.

## Usage

1. Launch the app on your device.
2. Enter your message in the input field and press the send button.
3. The app will send your message to ChatGPT and display the response in the chat window.

## Customization

You can customize the ChatGPT API call parameters by accessing the settings page within the app. Some of the customizable parameters include:

- `max_tokens`: Limit the length of the response.
- `temperature`: Control the randomness of the response (lower values make the response more focused and deterministic, while higher values make it more creative and diverse).

