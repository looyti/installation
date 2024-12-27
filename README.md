## Installation

This repository aims to maintain consistent coding standards across all contributors. To ensure uniformity, we use a set of common configuration files for code linting, formatting, and editor settings.

Follow the steps below to set up your development environment and ensure that you're following the same standards as the rest of the team.

### 1. Clone the Repository

Start by cloning the repository to your local machine:

```bash
git clone <repository-url>
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Setup ESLint

```bash
npm install eslint --save-dev
```

### 4. Setup Prettier

```bash
npm install prettier --save-dev
```

Make sure to run Prettier to format the code automatically:

```bash
npx prettier --write .
```

### 5. VSCode Settings

For a seamless development experience, we recommend using VSCode with specific settings. The .vscode/settings.json file provides editor preferences such as code formatting on save and ESLint integration.

You can include this configuration to ensure everyone is using the same settings: 1. Open VSCode 2. Install ESLint and Prettier extensions for VSCode. 3. Add the .vscode/settings.json file to your project to enforce these settings.

```bash
{
    "editor.formatOnSave": true,
    "eslint.autoFixOnSave": true,
    "eslint.validate": ["javascript", "javascriptreact", "typescript", "typescriptreact"],
    "prettier.requireConfig": true
}
```

This ensures that code is formatted and linted automatically when saving files in VSCode.

## Project Structure

The project is structured as follows:

```bash
/root
    /src
    /node_modules
    .eslintrc.js
    .prettierrc
    .vscode/
        settings.json
    package.json
```

By following these steps and using these configurations, everyone working on this project will maintain the same coding style and standards.

## Conclusion

Using ESLint, Prettier, and VSCode settings ensures that all code is written consistently, making collaboration easier and avoiding formatting issues. Make sure you follow the guidelines and run the necessary tools to keep the project clean and maintainable.
