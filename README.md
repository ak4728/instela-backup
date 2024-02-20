# User Entries Fetcher

This HTML file allows you to fetch user entries from Instela and export them to an Excel file. 

## Usage

1. Open the HTML file (`index.html`) in a web browser.
2. Enter the link to the Instela user profile in the input field. The link should look like "https://tr.instela.com/user/username--userid".
3. Click the "Fetch Entries" button to retrieve all entries for the user. Note that fetching a large number of entries may take some time.
4. Once the process completes, an Excel file named `UserEntries.xlsx` will be generated for download.

## Features

- Supports fetching entries from Instela user profiles.
- Converts fetched entries into an Excel file for easy analysis.

## Dependencies

- [xlsx.full.min.js](https://cdnjs.cloudflare.com/ajax/libs/xlsx/0.17.0/xlsx.full.min.js): JavaScript library for creating Excel files.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
