# WebCyphr

WebCyphr-a web extension that safeguards your browsing by detecting potential threats and phishing websites while offering a unique password generator for enhanced security.

<p align="center">
  <img src="icon.png", width="400", height="400", title="webCyphr"/>
</p>
  <div align="center">
  <img alt="GitHub code size in bytes" src="https://img.shields.io/github/languages/code-size/RubberPirate/WebCyphr">
  <img alt="GitHub license" src="https://img.shields.io/github/license/RubberPirate/WebCyphr">
  <a href="https://github.com/RubberPirate/WebCyphr/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/RubberPirate/WebCyphr"></a>
  <img alt="GitHub commit activity" src="https://img.shields.io/github/commit-activity/m/RubberPirate/WebCyphr">
  <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/RubberPirate/WebCyphr">
</div>
<p align="center">
  <a href="#features">Features</a> •
  <a href="#installation">Installation</a> •
  <a href="#usage">Usage</a> •
  <a href="#required-tools">Required Tools</a>
  <br>
  <br>

<div align="center">


https://github.com/user-attachments/assets/90abfad7-5e19-42b7-8fad-37ae72c954a0


</div>

# 🔒 Features of WebCyphr Browser Extension
  
- 🛡️ Real-Time Threat Monitoring: Actively scans and blocks harmful or phishing websites while browsing.
- 🚫 Website Blacklisting: Prevents access to a predefined list of malicious and phishing URLs.
- 🔍 Secure Link Verifier: Allows manual input of URLs to check for potential threats using Google Safe Browsing API.
- 🔑 Strong Password Generator: Generates customizable strong passwords with options for length, uppercase, lowercase, numbers, and special characters.
- ⚡ Interactive Warning Pages: Displays an aesthetic, user-friendly, animated warning page when visiting blocked sites.
- 💡 User Bypass Instructions: Provides subtle guidance on how to disable real-time scanning, ensuring informed user decisions.
- 🎨 Mouse-Interactive Animated Background: Includes a visually engaging particle animation for warning pages, responsive to cursor movements.
- 🌐 Always-On Protection: Continuous monitoring and blocking enabled by default, ensuring safety across all sessions.
- 🛠️ Customizable Tools: Accessible tools for secure browsing directly from the extension popup menu.
- 🧩 Modern UI Design: Clean, dark-themed user interface for an intuitive user experience.


# Installation

1. Clone the repo using
```sh
git clone https://github.com/rubberpirate/WebCyphr
```

2. Generate a Google Safe Browsing API Key from [Google Cloud Console](https://console.cloud.google.com) and use it in popup.js
```sh
"https://safebrowsing.googleapis.com/v4/threatMatches:find?key=<API-KEY-HERE>"
```

3. Then turn on the Developer Mode in your Browser and load unpacked inside `WebCyphr/Extensions/WebCyphr-main`

4. You can use the same method to install WebScanner also which can be used for Easy to acess Context-Menu scan

5. And here you go, You have your Extensions ready 

# Usage

# Edit/Add Sites to Blacklist

1. Clone the repo using
```sh
git clone https://github.com/rubberpirate/WebCyphr
```

2. Generate a Google Safe Browsing API Key from [Google Cloud Console](https://console.cloud.google.com) and use it in popup.js
```sh
"https://safebrowsing.googleapis.com/v4/threatMatches:find?key=<API-KEY-HERE>"
```

3. Then turn on the Developer Mode in your Browser and load unpacked inside `WebCyphr/Extensions/WebCyphr-main`

4. You can use the same method to install WebScanner also which can be used for Easy to acess Context-Menu scan

5. And here you go, You have your Extensions ready 
