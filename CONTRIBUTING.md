# Contributing to num2words-BD-INR

Thank you for considering contributing to num2words-BD-INR! This document provides guidelines and instructions for contributing to this project.

## Code of Conduct

By participating in this project, you are expected to uphold our Code of Conduct:
- Be respectful and inclusive
- Use welcoming and inclusive language
- Be collaborative and constructive
- Focus on what is best for the community
- Show empathy towards other community members

## How Can I Contribute?

### Reporting Bugs

This section guides you through submitting a bug report. Following these guidelines helps maintainers and the community understand your report, reproduce the behavior, and find related reports.

- **Use a clear and descriptive title** for the issue to identify the problem.
- **Describe the exact steps which reproduce the problem** in as many details as possible.
- **Provide specific examples** to demonstrate the steps.
- **Describe the behavior you observed after following the steps** and point out what exactly is the problem with that behavior.
- **Explain which behavior you expected to see instead and why.**
- **Include screenshots or animated GIFs** if possible.
- **Include details about your configuration and environment**.

### Suggesting Enhancements

This section guides you through submitting an enhancement suggestion, including completely new features and minor improvements to existing functionality.

- **Use a clear and descriptive title** for the issue to identify the suggestion.
- **Provide a step-by-step description of the suggested enhancement** in as many details as possible.
- **Provide specific examples to demonstrate the steps**.
- **Describe the current behavior** and **explain which behavior you expected to see instead** and why.
- **Explain why this enhancement would be useful** to most users.

### Pull Requests

- Fill in the required template
- Follow the Python style guides
- Document new code based on the Documentation Styleguide
- Include tests for your changes
- End all files with a newline
- Avoid platform-dependent code

## Development Process

### Setting Up Development Environment

1. Fork the repository
2. Clone your fork to your local machine
3. Set up a Python virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
4. Install dependencies:
    pip install -r requirements.txt
    pip install -e 
5. Running Tests:
    pytest

### Code Style
This project follows PEP 8 style guidelines. Please ensure your code adheres to these standards.
- You can check your code style by running: flake8 num2words_bd_inr tests

### Documentation
Please document your code using docstrings following the Google docstring format.

### Release Process
The project maintainers will handle the release process, including:

- Updating the version number
- Creating a release on GitHub
- Publishing to PyPI

### Thank You!
Your contributions to open source, large or small, make projects like this possible. Thank you for taking the time to contribute.