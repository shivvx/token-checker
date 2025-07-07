# Ultimate Token Checker 🔐

A powerful and fast Discord token checker tool designed for educational and development purposes. This tool validates Discord tokens, checks Nitro status, billing information, and locked status, all while supporting proxy usage and multithreading for high performance.

---

## Features

- Validates Discord tokens for authenticity
- Detects Nitro subscription status
- Checks if tokens have billing information attached
- Identifies locked and unlocked tokens
- Supports proxy usage for anonymity and bypassing rate limits
- Multithreaded for faster token checking
- Outputs categorized results into separate files for easy management
- Colorful and user-friendly command-line interface

---

## Installation

1. Clone this repository or download the source code.
2. Ensure you have Python 3.x installed.
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Prepare your `Tokens.txt` file with one token per line.
5. (Optional) Prepare a `proxys.txt` file with proxies if you want to use proxy support.

---

## Usage

Run the tool using:

```bash
python main.py
```

You will be prompted to enable proxy usage (type `y` or `n`).

The tool will then check all tokens in `Tokens.txt` and output results into the `output/` directory:

- `Working.txt` - Valid tokens
- `NotWorking.txt` - Invalid tokens
- `Nitro.txt` - Tokens with Nitro subscription
- `Billing.txt` - Tokens with billing information
- `Locked.txt` - Locked tokens
- `NotLocked.txt` - Unlocked tokens

---

## Output Example

The terminal will display colorful logs indicating the status of each token checked, including username, Nitro status, billing, and locked status.

---

## Credits

Developed by [Shivamx-Dev](https://github.com/Shivamx-Dev)

---

## License

This project is licensed under the GNU General Public License v3.0 (GPL-3.0). See the LICENSE file for details.

---

## Disclaimer

This tool is intended for educational and development purposes only. Use responsibly and respect Discord's Terms of Service.
