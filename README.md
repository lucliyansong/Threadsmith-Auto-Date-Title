# Threadsmith Auto Date Title

A modified fork of [Threadsmith](https://github.com/jonlai211/Threadsmith) that adds structured date-based naming for ChatGPT conversations.

ChatGPT conversations can be renamed using the format:

`YYYY-MM-DD｜Category｜Title`

Example:

`2026-09-23｜Learning｜Complex Analysis`

## About this fork

This project is based on the original **Threadsmith** project created by **Jonathan Lai**.

Original project:  
https://github.com/jonlai211/Threadsmith

This fork focuses on adding a consistent date, category, and title structure to ChatGPT conversation names for easier organization and searching.

## Changes in this fork

- Added date prefixes to generated ChatGPT conversation titles
- Added the format `YYYY-MM-DD｜Category｜Title`
- Added structured category-based conversation naming
- Improved organization of ChatGPT conversation history
- Retains the original Threadsmith title-generation and review workflow

## Installation

1. Download this repository or the ZIP package
2. Extract the ZIP file
3. Open `chrome://extensions`
4. Enable **Developer mode**
5. Click **Load unpacked**
6. Select the `Threadsmith-Auto-Date-Title` folder
7. Open `https://chatgpt.com`
8. Configure your AI provider and API key

## Features

- Automatic ChatGPT conversation renaming
- Date-based naming
- Category-based naming
- Review titles before applying changes
- Edit generated titles before applying
- Undo applied renames
- Supports Chinese and English titles
- Supports OpenAI-compatible AI providers
- Stores settings locally in the browser

## Providers

The extension supports OpenAI-compatible providers such as:

- DeepSeek
- OpenAI
- OpenRouter
- Custom OpenAI-compatible endpoints

Your own API key is used and stored locally by the extension.

## Privacy

The extension does not operate its own backend.

Conversation text used for title generation is sent only to the AI provider configured by the user.

API keys and extension settings are stored locally in the browser.

See [PRIVACY.md](PRIVACY.md) for more information.

## Credits

This repository is a modified fork of **Threadsmith** by **Jonathan Lai**.

Original repository:  
https://github.com/jonlai211/Threadsmith

Thanks to Jonathan Lai for creating and open-sourcing the original project.

## License

The original Threadsmith project is licensed under the MIT License.

Original project copyright:

Copyright (c) 2026 Jonathan Lai

Modifications in this fork:

Copyright (c) 2026 lucliyansong

See [LICENSE](LICENSE) for the complete MIT License text.
