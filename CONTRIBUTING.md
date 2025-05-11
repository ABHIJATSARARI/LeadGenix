# Contributing to LeadGenix

Thank you for your interest in contributing to LeadGenix! This document provides guidelines and instructions to help you get started.

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
  - [Reporting Bugs](#reporting-bugs)
  - [Suggesting Features](#suggesting-features)
  - [Pull Requests](#pull-requests)
- [Development Setup](#development-setup)
- [Style Guides](#style-guides)
- [Community](#community)

## Code of Conduct

By participating in this project, you are expected to uphold our Code of Conduct. Please report unacceptable behavior to [team@leadgenix.tech](mailto:team@leadgenix.tech).

## How Can I Contribute?

### Reporting Bugs

Before submitting a bug report:

- Check the issue tracker to avoid duplicate reports
- Collect information about the bug (steps to reproduce, screenshots, error messages)

When submitting a bug report, please use our bug report template and include:

- A clear, descriptive title
- Detailed steps to reproduce the issue
- Expected vs. actual behavior
- Screenshots or videos (if applicable)
- Your environment (OS, browser, device)

### Suggesting Features

Feature suggestions are tracked as GitHub issues. When suggesting a feature:

- Use a clear and descriptive title
- Provide a detailed description of the suggested feature
- Explain why this feature would be useful to LeadGenix users
- Include mockups or examples if possible

### Pull Requests

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Run tests to ensure your code works as expected
5. Commit your changes (`git commit -m 'Add some amazing feature'`)
6. Push to your branch (`git push origin feature/amazing-feature`)
7. Open a Pull Request

## Development Setup

To set up the project locally:

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/leadgenix.git

# Navigate to the project directory
cd leadgenix

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env
# Edit .env with your configuration

# Start development server
npm run dev
```

## Style Guides

### Git Commit Messages

- Use the present tense ("Add feature" not "Added feature")
- Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
- Limit the first line to 72 characters or less
- Reference issues and pull requests liberally after the first line

### JavaScript Style Guide

We use ESLint for JavaScript code quality. Run `npm run lint` to check your code.

### Documentation Style Guide

- Use Markdown for documentation
- Reference code with backticks (`)
- Include code examples when relevant

## Community

Join our community:

- [Twitter](https://twitter.com/leadgenix)
- [LinkedIn](https://linkedin.com/company/leadgenix)
- [Discord](https://discord.gg/leadgenix)

Thank you for contributing to LeadGenix!