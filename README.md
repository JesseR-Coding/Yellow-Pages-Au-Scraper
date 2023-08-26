# Yellow Pages Australia - Web Scraper (ONLY WORKING YP AUSTRALIA SCRAPER)

The Yellow Pages Web Scraper is a Python script designed to extract business data from the Yellow Pages Australia website. This tool utilizes web scraping techniques to gather valuable business information, which can then be used for various purposes such as analysis, research, or data enrichment.

`PURCHASE HERE:` [https://yellowpagesauscraping.sellpass.io/products/Yellow-Pages-Australia-Scraper](https://yellowpagesauscraping.sellpass.io/products/Yellow-Pages-Australia-Scraper)

`Contact Me On Discord For Support:` litez.eth

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Output](#output)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone or download this repository to your local machine.
2. Make sure you have Python 3.x installed.
3. Install the Chrome driver that matches your current Chrome version: [https://chromedriver.chromium.org/downloads](https://chromedriver.chromium.org/downloads)
5. Install the required dependencies using the following command:

   ```bash
   pip install -r requirements.txt

## Usage

1. After cloning the repository, navigate to the 'Scraper.py' file.
2. Run the script using the following command:

   ```bash
   python Scraper.py

3. When prompted for the URL, input the Yellow Pages link in the following format:

   ```bash
   https://www.yellowpages.com.au/find/hairdressers/australia/page-
   
`Note: Modify the URL to match your desired search and location.`

4. For the 'elements' input, ensure that you don't enter a value greater than 1000. The website restricts the view beyond this limit. To get around this issue you can break up the scraping into batches and target different states that don't have more than 1000 results.

## Output

The scraped data will be saved in a CSV file named `final.csv`. The CSV file will include the following columns:

- Yellow Pages Link
- Business Name
- Business Email Address
- Business Website (if available)

Feel free to enhance or modify the scraper to extract additional data as needed.

`Note: The scraper will create a "links.csv" file first which is part of the scraping process, this CSV file will automatically delete when the scraping is finished.`

## Contributing

Contributions are welcome! If you find any issues or want to add new features to the scraper, please open an issue or submit a pull request in this repository.

## License

This project is licensed under the [MIT License](LICENSE).


Created By [https://github.com/JesseR-Coding/Yellow-Pages-Au-Scraper](https://github.com/JesseR-Coding/Yellow-Pages-Au-Scraper)
---

Happy Scraping! 
