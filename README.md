# Expenzo

> A lightweight, privacy-friendly expense tracker that runs entirely in your browser.

Expenzo helps you record everyday expenses, organize them by category, monitor payment status, and understand spending patterns through clear summaries and charts. Your data stays in your browser by default, with JSON export and import available for backups and migration.

**Live Demo:** [Open Expenzo](https://nosibbiswas22.github.io/expenzo/)

## Features

- Add, edit, search, and remove expense entries
- Organize expenses with built-in and custom categories
- Track estimated amounts, quantities, dates, and paid or unpaid status
- View expense totals by category and filter summaries by month
- Explore yearly trends with charts powered by Chart.js
- Export expense data to JSON and import it later
- Clear stored expense data when needed
- Responsive interface designed for desktop and mobile browsers
- No account, backend, or build step required

## Built With

- HTML5
- CSS3
- Vanilla JavaScript
- [Chart.js](https://www.chartjs.org/) for visual summaries
- [jsPDF](https://github.com/parallax/jsPDF) and AutoTable for PDF-related reporting support
- Browser `localStorage` for client-side persistence

## Getting Started

### Requirements

- A modern web browser
- An optional local static web server for development

### Run Locally

1. Clone the repository:

	```bash
	git clone https://github.com/nosibbiswas22/expenzo.git
	cd expenzo
	```

2. Open `index.html` in a modern browser, or serve the project directory with a static server. For example, with Python:

	```bash
	python -m http.server 8000
	```

3. Visit [http://localhost:8000](http://localhost:8000).

Expenzo loads its third-party libraries from public CDNs, so an internet connection is required when opening the app for the first time unless those assets are replaced with local copies.

## Usage

1. Use **Add** to create an expense entry with an item, quantity, category, and amount.
2. Use **List** to review, edit, or delete saved entries.
3. Use **Summary** to filter totals by month, update payment status, and view charts.
4. Use **Settings** to manage categories and export or import your JSON data.

## Data and Privacy

Expenzo stores expense entries and categories in your browser's local storage. The project does not include a server or user account system. Clearing browser site data can remove your saved entries, so use the export feature to keep a backup.

## Project Structure

```text
.
├── index.html              # Application shell and external library links
├── app.css                 # Application styles
├── app.js                  # Navigation and application initialization
└── components/             # Views, storage utilities, and shared UI behavior
```

## Contributing

Contributions are welcome. To propose a change:

1. Fork the repository.
2. Create a feature branch: `git checkout -b feature/your-change`.
3. Make and test your changes in a modern browser.
4. Open a pull request with a clear description of the change.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

## Author

Created by [Nosib Biswas](https://nosibbiswas22.github.io/nosibbiswas/).