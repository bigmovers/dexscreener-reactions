# DexScreener Emoji Reactions Spammer

This script allows you to spam any emoji on a token page on [DexScreener.com](https://dexscreener.com) with unique fingerprints, ensuring it remains undetected. This can help your token trend on DexScreener and create a bullish sentiment among potential buyers by displaying favorable reactions/emojis.



https://github.com/bigmovers/dexscreener-reactions/assets/165174061/8d07e7cb-bd0a-46eb-92c8-8688966a4a07



**TELEGRAM** for contact & **POC**(Proof of Concept) & **VOUCHES**: [@benorizz0](https://t.me/benorizz0)

Support in running the tool is included in the price.

Watch out for other scammers on GitHub - they either sell my outdated program which has been closed or simply selling blank files.


**Other tools**
- [Volume Maker](https://github.com/bigmovers/solana-volume-bot)
- [Pump.Fun Bundler(25 buys)](https://github.com/bigmovers/pumpfun-bundler)
- [Buyers/Holders Maker](https://github.com/bigmovers/solana-maker)
- [Sniper for New Pairs with Filters](https://github.com/bigmovers/solana-sniper-bot)
- Non-JITO Bundler (3 buys)
- LP Manager
- Telegram Cloner

  
## Features

- Spam any emoji on a DexScreener token page.
- Utilizes unique fingerprints to remain undetected.
- Helps in trending your token and creating a positive sentiment.

## Prerequisites

- Python 3.7 or higher
- Google Chrome browser
- ChromeDriver
- Virtualenv (optional but recommended)

## Installation

1. **Get the project from https://t.me/benorizz0:**

2. **Create a virtual environment (optional but recommended):**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required packages:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Download ChromeDriver:**

    Ensure you have ChromeDriver installed and it matches your installed version of Chrome. Download it from [here](https://sites.google.com/a/chromium.org/chromedriver/downloads) and place it in a directory included in your system's PATH.

## Configuration

1. **Edit `config.py`:**

    Open the `config.py` file and configure the following variables:

    ```python
    DEXSCREENER_URL = "https://dexscreener.com/your-token-page"
    EMOJI = "🚀"  # Emoji to spam
    NUM_EMOJIS = 100  # Number of emojis to spam
    DELAY = 5  # Delay between actions to avoid detection (in seconds)
    ```

## Usage

1. **Run the script:**

    ```bash
    python spam_emoji.py
    ```

    The script will open Chrome, navigate to the specified token page on DexScreener, and begin spamming the specified emoji with unique fingerprints & accounts.

## Disclaimer

This script is intended for educational purposes only. Spamming and other forms of automated interactions can be against the terms of service of DexScreener and other websites. Use this script responsibly and at your own risk.

## Contributing

If you'd like to contribute, please fork the repository and use a feature branch. Pull requests are welcome.


## Contact

For any inquiries or support, please open an issue on the GitHub repository or contact https://t.me/benoriz0.

