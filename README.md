## Contribution Guidelines

Please follow the [Commit Guidelines](./commit-guidelines.md) when making
changes.

For detailed instructions on importing the general ruleset, refer to the
[Ruleset Import Guide](./ruleset-import-guide.md).

---

## Project Setup

This repository maintains common configuration files to ensure consistent coding
standards across all contributors. These configurations cover code linting,
formatting, and editor settings. They serve as the rules and configurations to
be followed when starting a new project. It is important to refer to the most
up-to-date rules and configurations stored in this repository.

### 1. Start a New Project

When starting a new project, you need to apply the common configurations from
this repository. Follow these steps to set up your project:

```bash
# Create a new project directory
mkdir my-new-project
cd my-new-project

# Initialize the project (you can use npm or yarn)
npm init -y
```

### 2. Install Dependencies

```bash
# Install ESLint and Prettier
npm install eslint prettier --save-dev
```

### 3. Add ESLint and Prettier Configurations

To integrate ESLint and Prettier into your project, follow these steps:

a. Add ESLint Configuration

You can access the .eslintrc.json file from the repository. Simply copy it from
the repository and place it in your project root directory:

```bash
# Copy the .eslintrc.json file from the repository to your project
curl -o .eslintrc.json https://raw.githubusercontent.com/looyti/installation/refs/heads/main/.eslintrc
```

Alternatively, you can manually copy the content of the .eslintrc.json file from
the repository into your project.

b. Add Prettier Configuration

You can access the .prettierrc file from the repository as well. To include it
in your project, run:

```bash
# Copy the .prettierrc file from the repository to your project
curl -o .prettierrc https://raw.githubusercontent.com/looyti/installation/refs/heads/main/.prettierrc
```

Alternatively, you can manually copy the content of the .prettierrc file from
the repository into your project.

### 4. Configure VSCode Settings

For an optimal development environment, configure VSCode to automatically format
and lint your code. You can access the .vscode/settings.json file from the
repository:

```bash
# Copy the .vscode/settings.json file from the repository to your project
curl -o .vscode/settings.json https://raw.githubusercontent.com/looyti/installation/refs/heads/main/.vscode/settings.json
```

Alternatively, you can manually copy the content of the .vscode/settings.json
file from the repository into your project.

This file ensures that the appropriate formatting and linting settings are
applied within VSCode.

## Run Prettier and ESLint

```bash
# Format the code using Prettier
npx prettier --write .

# Run ESLint to check the code and fix issues
npx eslint . --fix
```

## Check for Latest Rules in This Repository

This repository contains the most up-to-date ESLint, Prettier, and VSCode
configurations used in the project. When starting a new project or contributing
to an existing one, always refer to the configurations here to ensure the code
follows the same standards. This will help maintain a consistent codebase
throughout the project.

## Project Structure

When starting a new project, the structure should look like this:

```bash
/root
    /src
    /node_modules
    .eslintrc.json
    .prettierrc
    .vscode/
        settings.json
    package.json
```

## Conclusion

Using ESLint, Prettier, and VSCode settings ensures that all code is
consistently written, making collaboration easier and preventing formatting
issues. Always check the latest rules and configurations from this repository
before starting or contributing to the project, as it helps maintain a clean and
sustainable codebase.

This version refers to accessing the .eslintrc.json, .prettierrc, and
.vscode/settings.json files directly from the repository, ensuring contributors
follow the most up-to-date configurations.
