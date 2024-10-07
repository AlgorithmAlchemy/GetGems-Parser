# NFT Parser for GetGems.io

This is a Python-based project that parses user data from [GetGems.io](https://getgems.io/) and stores the results in a SQLite database.

## Features
- Collects NFT data for users from GetGems.io.
- Stores data into SQLite database.
- Uses Selenium WebDriver with Firefox for browsing.
- Parses wallet names from a text file and processes each wallet.

## Requirements

- Python 3.10+
- Selenium
- Firefox browser
- GeckoDriver
- SQLite3 (comes pre-installed with Python)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/nft-getgems-parser.git
cd nft-getgems-parser
```

Install the required Python packages
```bash
pip install selenium
```
 Add a text file wallet.txt with wallet names in the data folder
