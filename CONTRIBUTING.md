# Contributing to Event Manager

Thank you for your interest in contributing to Event Manager! We welcome contributions to improve the system's features, performance, and overall design.

Please follow these guidelines to make sure the process is smooth and efficient for everyone.

---

## How to Contribute

### 1. Reporting Bugs

If you find a bug:
1. Search the repository's issues to see if it has already been reported.
2. If it hasn't, open a new issue.
3. Provide a clear title and description, steps to reproduce the bug, expected behavior, and screenshots if applicable.

### 2. Suggesting Enhancements

If you have an idea for a feature:
1. Open a new issue and select the enhancement template (if available).
2. Clearly explain the feature and why it would be useful.
3. Discuss the implementation options before writing code.

### 3. Submitting Pull Requests (PRs)

To propose changes to the codebase:
1. **Fork** the repository and clone your fork locally.
2. Create a new branch named after the feature or issue you are working on (e.g., `feature/custom-branding` or `bugfix/invalid-qr-scan`).
3. Make your changes. Ensure code formatting is consistent with project configuration (ESLint rules).
4. Write clear commit messages.
5. Push your branch to GitHub and submit a Pull Request to the main branch of the original repository.
6. Provide a detailed summary of your changes in the PR description, including references to any related issues.

---

## Development Environment Setup

Ensure you have Node.js and npm installed. To start developing:
1. Configure your local environment by copying standard Firebase, EmailJS, and FreeImage credentials to a `.env.local` file.
2. Run `npm install` to install dependencies.
3. Start the Next.js development server:
   ```bash
   npm run dev
   ```
4. Verify code quality by running the linter:
   ```bash
   npm run lint
   ```

Thank you for your support!
