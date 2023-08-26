# Yellow Pages Web Scraper

The Yellow Pages Web Scraper is a Python script designed to extract business data from the Yellow Pages Australia website. This tool utilizes web scraping techniques to gather valuable business information, which can then be used for various purposes such as analysis, research, or data enrichment.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Output](#output)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone or download this repository to your local machine.
2. Make sure you have Python 3.x installed.
3. Install the Chrome driver that matches your current Chrome version: [I'm an inline-style link](https://chromedriver.chromium.org/downloads)
5. Install the required dependencies using the following command:

   ```bash
   pip install -r requirements.txt

## Usage

1. Open a terminal and navigate to the directory where you cloned/downloaded the repository.
2. Edit the `config.json` file to specify your preferences for scraping (see Configuration section below).
3. Run the scraper using the following command:
   ```bash
   python yellow_pages_scraper.py
4. The scraped data will be saved to the specified output file in CSV format.

## Configuration

In the `config.json` file, you can customize various aspects of the scraping process:

- `search_query`: The search term used to find relevant businesses on Yellow Pages.
- `location`: The location/city for which you want to retrieve business data.
- `max_results`: The maximum number of results to scrape.
- `output_file`: The name of the CSV file where the scraped data will be saved.

Adjust these settings according to your requirements before running the scraper.

## Output

The scraped data will be saved in a CSV file specified in the `output_file` configuration. The CSV file will include the following columns:

- Business Name
- Business Address
- Business Website (if available)
- (Can be Modified to Accept other entries

Feel free to enhance or modify the scraper to extract additional data as needed.

## Contributing

Contributions are welcome! If you find any issues or want to add new features to the scraper, please open an issue or submit a pull request in this repository.

## License

This project is licensed under the [MIT License](LICENSE).

## Credit

Created By Jesse Radevski | [I'm an inline-style link](https://github.com/JesseRadevski)
---

Happy Scraping!
