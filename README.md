# Ultimate Token Checker <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-filetype-py" viewBox="0 0 16 16">
  <path fill-rule="evenodd" d="M14 4.5V14a2 2 0 0 1-2 2H7v-1h5a1 1 0 0 0 1-1V4.5h-2A1.5 1.5 0 0 1 9.5 3V1H4a1 1 0 0 0-1 1v9H2V2a2 2 0 0 1 2-2h5.5zM0 11.85h1.6q.434 0 .732.179.302.175.46.477t.158.677-.16.677q-.158.299-.464.474a1.45 1.45 0 0 1-.732.173H.79v1.342H0zm2.06 1.714a.8.8 0 0 0 .085-.381q0-.34-.185-.521-.185-.182-.513-.182H.788v1.406h.66a.8.8 0 0 0 .374-.082.57.57 0 0 0 .238-.24m2.963.75v1.535H4.23v-1.52L2.89 11.85h.876l.853 1.696h.032l.856-1.696h.855z"/>
</svg>

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
