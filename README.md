# Quora SMS Scraper
This Python script automates the process of scraping Quora for answers matching specific keywords within a given timeframe. It utilizes browser automation through Selenium to interact with the Quora website, extract relevant information, and output the results in JSON format.

# Features:
Automated Login: Logs into Quora using provided credentials.
Keyword Search: Searches Quora for questions containing specified keywords.
Dynamic Web Scraping: Extracts answer links and associated metadata from the search results.
Output Generation: Outputs the scraped data to a JSON file.
Logging: Logs errors and messages for debugging purposes.

# Usage:
Ensure Python and necessary dependencies (such as Selenium) are installed.
Configure Quora credentials in the config.ini file.
Prepare a file containing keywords to search for.
Run the script with appropriate command-line arguments:
-k/--keywords: Path to the file containing keywords.
-o/--output: Output file path for storing the scraped data.
-t/--bytime: Specify the timeframe for the search (e.g., hour, day, week, month, year).

# Python3 quora.py -k keyword.txt -t 5hour -o output.json

# Additional Notes:
Customize the script as needed for specific use cases or integration with other systems.
Make sure to handle potential changes in website structure or policies that may affect the scraping process.
Use responsibly and adhere to Quora's terms of service and guidelines.

# Credits:
Credit goes to Mr. Sudo 0 for the initial version of this script.

# Disclaimer:
This script is provided as-is and may not guarantee 100% accuracy or reliability. Use it responsibly and verify its results in real-world scenarios. Ensure compliance with Quora's terms of service and data usage policies.

