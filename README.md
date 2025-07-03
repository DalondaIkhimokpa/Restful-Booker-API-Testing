# Restful Booker API Tests

Automated API tests for Restful Booker platform using Postman and Newman.

## Setup

1. Install Node.js
2. Clone this repository
3. Install dependencies:

```bash
npm install
```

## Running Tests

Basic run:
```bash
npm test
```

Run with HTML report:
```bash
npm run test-with-report
```

Reports will be generated in `reports/` folder.

## Collection Details

## Project Structure
restful-booker-tests/
├── collections/
│   ├── restful-booker.postman_collection.json
├── environments/
│   ├── restful-booker.postman_environment.json
├── data/
│   ├── test-data.json
├── reports/
├── screenshots/
├── LICENSE
├── README.md
├── package.json
└── .gitignore

- **Base URL**: `https://restful-booker.herokuapp.com`
- **Authentication**: Token-based or Basic Auth
- **Coverage**: All CRUD operations + edge cases