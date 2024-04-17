# Playwright Framework

This repository contains a Playwright framework setup for automated testing. The framework is structured as follows:

## Project Folder Structure

Project Folder<br>
├─ .github<br>
│ &nbsp; &nbsp; &nbsp; &nbsp;└── main.yml<br>
├── node_modules <br>
├─ playwrite-report<br>
│ &nbsp; &nbsp; &nbsp; &nbsp;└── data<br>
│ &nbsp; &nbsp; &nbsp; &nbsp;└── index.html<br>
├─ src<br>
│ &nbsp; &nbsp; &nbsp; &nbsp;├── api<br>
│ &nbsp; &nbsp; &nbsp; &nbsp;├── config<br>
│ &nbsp; &nbsp; &nbsp; &nbsp;├── logging<br>
│ &nbsp; &nbsp; &nbsp; &nbsp;├── pages<br>
│ &nbsp; &nbsp; &nbsp; &nbsp;├── reporting<br>
│ &nbsp; &nbsp; &nbsp; &nbsp;├── testdata<br>
│ &nbsp; &nbsp; &nbsp; &nbsp;├── tests<br>
│ &nbsp; &nbsp; &nbsp; &nbsp;└── utils<br>
├─ test-results<br>
│ .gitignore<br>
│ package-lock.json<br>
│ package.json<br>
│ playwright.config.ts<br>
│ readme.md<br>

## Description

- `.gitignore`: Specifies intentionally untracked files to ignore in Git.
- `package-lock.json` and `package.json`: Node.js package files specifying project dependencies.
- `playwright.config.ts`: Configuration file for Playwright settings.
- `readme.md`: Document outlining project requirements.

### `.github`

- `.github/main.yml`: GitHub Actions workflow file for continuous integration.

### `node_modules`

- Directory containing Node.js modules installed by npm.

### `src`

- Source code directory containing project files.

#### `api`

- Directory for API-related scripts.

#### `config`

- Directory containing environment configuration files and authentication data.

#### `logging`

- Directory for log files generated during test execution.

#### `pages`

- Page object files representing different pages of the application under test.

#### `testdata`

- Directory containing test data files in various formats, such as JSON and CSV.

#### `tests`

- Directory for test scripts written in TypeScript.

#### `utils`

- Directory for utility scripts used in testing, such as encryption and logging utilities.

### `test-results`

- Directory for storing test execution results, including screenshots, trace files, and videos.

## Usage

- Clone the repository and install dependencies using `npm install`.
- Run tests using `npm test`.
- View test reports in the `playwright-report` directory.
- Explore source code files for detailed implementation.

## Contributing

Contributions are welcome! Please follow the established coding style and guidelines. If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.


