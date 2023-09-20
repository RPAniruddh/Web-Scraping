# Web Scraper Readme

## Overview

This is a simple web scraper tool written in TypeScript. It allows you to extract links and text content from a given URL.

## Dependencies

- axios
- cheerio
- fs
- fast-csv

## Usage

1. Install dependencies:

```bash
npm install
```

2. Run the scraper:

```bash
node index.js <URL>
```

Replace `<URL>` with the target website you want to scrape.

## Functions

### `scrapeWebsite(url: string): Promise<ScrapedData>`

This function takes a URL as input and returns an object containing extracted links and text content.

### `storeScrapedDataAsJSON(data: ScrapedData, filename: string): Promise<void>`

This function saves the scraped data as a JSON file.

### `storeScrapedDataAsCSV(data: ScrapedData, filename: string): Promise<void>`

This function saves the scraped data as a CSV file.

## Example

```bash
node index.js https://example.com
```

This will scrape `https://example.com`, extract links and text content, and save the data as both JSON and CSV files.

## Note

- Ensure that you have Node.js and npm installed on your system.
- Make sure to provide a valid URL as a command-line argument.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- [axios](https://axios-http.com/)
- [cheerio](https://cheerio.js.org/)
- [fast-csv](https://c2fo.github.io/fast-csv/docs/introduction/getting-started)
- [Node.js](https://nodejs.org/)

## Author

[Your Name](https://github.com/yourusername)

---

Feel free to customize this readme file further based on your specific project details and requirements.
