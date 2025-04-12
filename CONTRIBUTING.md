# Contributing to AstroMatch

Thank you for your interest in contributing to AstroMatch! This document provides guidelines and instructions for contributing to this project.

## Code of Conduct

By participating in this project, you agree to maintain a respectful and inclusive environment for everyone involved.

## How to Contribute

### Reporting Bugs

If you find a bug in the application, please create an issue with the following information:
- Clear title describing the issue
- Steps to reproduce the bug
- Expected behavior
- Actual behavior
- Screenshots if applicable
- Device information (model, OS version)
- Flutter and Dart version

### Suggesting Features

For feature suggestions, create an issue with:
- Clear title describing the feature
- Detailed description of the feature
- Why this feature would be beneficial
- Any implementation ideas you may have

### Development Workflow

1. Fork the repository
2. Create a new branch with a descriptive name (`feature/add-profile-verification`)
3. Make your changes
4. Write or update tests as needed
5. Ensure all tests pass
6. Update documentation if necessary
7. Submit a pull request

### Pull Request Process

1. Ensure your code follows the project's style guidelines
2. Update the README.md or documentation with details of changes if applicable
3. The PR should work on iOS and Android
4. Include screenshots for UI changes
5. Link any related issues in the PR description

## Development Setup

### Prerequisites

- Flutter SDK (latest stable version)
- Android Studio / VS Code
- Git

### Setup Instructions

1. Clone your forked repository
   ```
   git clone https://github.com/your-username/astromatch-updated.git
   ```

2. Navigate to the project directory
   ```
   cd astromatch-updated
   ```

3. Install dependencies
   ```
   flutter pub get
   ```

4. Set up Firebase (follow instructions in project documentation)

5. Run the app
   ```
   flutter run
   ```

## Coding Guidelines

- Follow Dart's [style guide](https://dart.dev/guides/language/effective-dart/style)
- Write meaningful commit messages
- Comment your code where necessary
- Write tests for new features
- Ensure code is properly formatted (`flutter format .`)
- Run static analysis before submitting (`flutter analyze`)

## Specialized Contributions

### Astrological Calculations

If you're contributing to the astrological calculation algorithms:
- Ensure accuracy of implementations
- Include sources or references for algorithms
- Add validation tests with known results

### AI Integration

For AI-related contributions:
- Follow best practices for API usage
- Ensure privacy considerations are addressed
- Document prompt engineering approaches

## Getting Help

If you need assistance with your contribution, you can:
- Comment on the relevant issue
- Reach out to project maintainers
- Ask questions in pull requests

Thank you for contributing to AstroMatch!
