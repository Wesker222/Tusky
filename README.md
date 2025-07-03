# Tusky Automation

Automate full interaction with the **Tusky Testnet Vaults** web application using Python and Puppeteer (Pyppeteer).

## Overview

This project provides a Python automation script to streamline and fully automate user workflows on the Tusky Testnet vaults platform: 

- Connect Sui wallet or Google account  
- Create a secure 12-word password  
- Backup the recovery phrase  
- Create a vault  
- Upload files securely  
- Provide feedback on the platform  

Tusky Testnet Vaults enable token-gated access and secure decentralized file storage on the Sui blockchain.

## Features

- Headless or headed browser automation with Python Puppeteer (Pyppeteer)  
- Automates wallet or Google account connection flow (manual steps may be required for wallet popups)  
- Automatically creates vaults with password and backup phrase handling  
- Supports file uploads through the web interface  
- Automates feedback submission on the platform  

## Getting Started

### Prerequisites

- Python 3.8 or higher  
- Pyppeteer (`pip install pyppeteer`)  
- Access to Tusky Testnet: [https://testnet.app.tusky.io/vaults](https://testnet.app.tusky.io/vaults)  
- Sui wallet or Google account credentials (for manual login steps if needed)  

### Installation

Clone the repository:

```bash
git clone https://github.com/Wesker222/Tusky.git
cd Tusky
```

Install dependencies:

```bash
pip install -r requirements.txt
```

*(If `requirements.txt` is not present, install Pyppeteer directly)*

```bash
pip install pyppeteer
```

### Usage

Edit the automation script to configure your password phrase, file path for upload, and any other parameters.

Run the script:

```bash
python automate_tusky_testnet.py
```

The script will:

1. Open the Tusky Testnet vaults web app  
2. Connect your Sui wallet or Google account (may require manual interaction)  
3. Create a 12-word password and backup phrase  
4. Create a vault  
5. Upload a file to the vault  
6. Submit feedback on the platform  

## Notes

- Wallet connection popups (e.g., Sui wallet extensions) may require manual approval or additional automation tooling.  
- Adjust CSS selectors in the script if the Tusky UI changes.  
- Ensure your file path for upload is correct and accessible by the script.  

## About Tusky Testnet Vaults

Tusky Testnet Vaults provide token-gated access to decentralized vaults on the Sui blockchain, enabling secure file storage and sharing with blockchain-backed access control.

Explore the platform here: [https://testnet.app.tusky.io/vaults](https://testnet.app.tusky.io/vaults)

## Contributing

Contributions, bug reports, and feature requests are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.

