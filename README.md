# IT23546752-ITPM-Assignment-1

# IT23546752 – Playwright Test Automation

## About

This project tests the SwiftTranslator website (https://www.swifttranslator.com/) using test cases from an Excel file.

## What You Need

- Node.js 16 or higher
- Internet connection

## Setup

1. **Clone the project**
```bash
git clone https://github.com/Sandusarani-Senadeera/IT23546752-ITPM-Assignment-1.git

```

2. **Install dependencies**
```bash
npm install
```

3. **Install browsers**
```bash
npx playwright install
```

## Run Tests

```bash
npm test
```

## View Results

```bash
npm run report
```

## Test Data

Tests are in `test-data/IT23546752.xlsx` with these columns:
- TCID
- Test Case Name
- Input
- Expected
- Type

## Project Files

```
IT23546752/
├── e2e/
│   └── swifttranslator.excel.spec.js
├── test-data/
│   └── IT23546752.xlsx
├── playwright.config.js
├── package.json
└── README.md
```
