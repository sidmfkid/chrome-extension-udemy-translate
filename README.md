<p align="center">
  <img src="https://github.com/ChenYCL/chrome-extension-udemy-translate/raw/v2.0.0/example/ball-logo.png" alt="Udemy Translate" height="128" width="128" />
</p>

<h4 align="center">
  Udemy Translate
</h4>

[![Build Status](https://img.shields.io/badge/README-English-yellow.svg)](README.md)
![GitHub All Releases](https://img.shields.io/github/downloads/ChenYCL/chrome-extension-udemy-translate/total)
![GitHub package.json version (branch)](https://img.shields.io/github/package-json/v/ChenYCL/chrome-extension-udemy-translate/v2.1.7)
[![MIT Licence](https://badges.frapsoft.com/os/mit/mit.svg?v=103)](https://opensource.org/licenses/mit-license.php)

## About This Extension

This is a powerful Chrome extension that can translate subtitles from any website into different languages in real-time. It's no longer limited to specific video platforms but supports user-defined subtitle translation for any website.

## Key Features

- Supports subtitle translation for any website
- Uses OpenAI API for high-quality translation
- Supports locally deployed Ollama AI models
- Users can customize target websites and DOM selectors
- Real-time translation without page refresh
- Supports multi-language translation
- Customizable subtitle style and position
- [ ] Support for third-party professional translation interfaces, as OpenAI and Ollama translation quality is not controllable

## Installation Methods

First method: Install from the Chrome Web Store (link to be updated)

Second method: Download from WeChat Official Account or download the source code to build

- Step 1:

Follow the WeChat Official Account: 影音下午茶 and reply 'Tool Download'

Open your Google Chrome or new version of Edge browser

![Step 1](https://github.com/ChenYCL/chrome-extension-udemy-translate/raw/master/example/step1.png)

- Step 2:
Enable Developer Mode
![Step 2](https://github.com/ChenYCL/chrome-extension-udemy-translate/raw/master/example/step2.png)

Results:

![Show](https://github.com/ChenYCL/chrome-extension-udemy-translate/raw/master/example/show.png)

![Show](https://github.com/ChenYCL/chrome-extension-udemy-translate/raw/master/example/netflix.png)

![Show](https://github.com/ChenYCL/chrome-extension-udemy-translate/raw/master/example/lynda.png)

![Show](https://github.com/ChenYCL/chrome-extension-udemy-translate/raw/master/example/hulu.jpg)

## Version

v3.0.0

## Features

- [x] Basic translation
- [x] Netflix video support
- [x] Lynda video support
- [x] LinkedIn video support
- [x] HBO Now video support
- [x] HBO Max video support
- [x] Hulu video support
- [x] Amazon video support
- [x] Paramount+ video support
- [x] Disney+ video support
- [x] simplilearn.com support
- [x] Yandex translation API integration
- [x] Azure Cognitive Services
- [x] OpenAI
- [x] Ollama
- [x] Subtitle styling options

## Usage
- After installing the extension, click the extension icon to open the configuration panel
- Choose the translation API (OpenAI or Ollama)
- Enter the necessary API keys or configuration information
- Add the domain of the website you want to translate subtitles for and the corresponding DOM selector
- Save the settings and refresh the target webpage

## API Configuration

- OpenAI Configuration
1. Select OpenAI in the configuration panel
2. Enter your OpenAI API key
3. Choose an appropriate model (e.g., gpt-3.5-turbo)
4. Configure the proxy URL

- Ollama Local Configuration
Install Ollama: Visit the Ollama website to download and install
Pull the required model:
```bash
ollama pull llama2
```

## Ollama Configuration
- Select Ollama in the extension configuration panel
- Enter the Ollama service URL (default is http://localhost:11434)
- Select the model name you pulled (e.g., llama2)

## Custom Website Configuration
1. In the configuration panel, add the domain of the website you want to translate subtitles for
2. Specify the correct DOM selector for that website to locate subtitle elements
3. Save the settings and refresh the target webpage to take effect

## Notes
- Ensure you have sufficient API usage quota
- Ollama local deployment requires higher hardware configuration, please choose an appropriate model based on your device performance
- First-time use may require some time to load and initialize the model

## Cooperation Promotion
Contact via WeChat Official Account

## Welcome to Follow the WeChat Official Account
There are related plugin usage tutorials. Follow and reply 'Translation Tool' to get it. Follow and reply '工具下载' to get the latest version. Regular sharing of audiovisual information worth watching.

<img src="https://raw.githubusercontent.com/ChenYCL/chrome-extension-udemy-translate/master/example/qrcode.BMP" alt="" height="148" width="148" />

## Donation Channel ☕️

### Alipay
<img src="https://github.com/ChenYCL/chrome-extension-udemy-translate/raw/v2.0.0/example/alipay.JPG" alt="" height="148" width="148" />

### WeChat
<img src="https://github.com/ChenYCL/chrome-extension-udemy-translate/raw/v2.0.0/example/wechat.JPG" alt="" height="148" width="148" />

## Communication
[Telegram Group](https://t.me/joinchat/Gs1RFzD5MpIwJ7S-)

<img src="https://i.loli.net/2021/01/12/Vti5GPdqxjN3ETL.jpg" alt="" height="148" width="148" />

## Code Contribution
Contributions are welcome! Just send a PR for fixes and documentation updates, and open an issue for new features beforehand. Make sure tests pass and coverage remains high. Thank you!
