# Contributing to Samriddhi Portal

First off, thank you for considering contributing to Samriddhi Portal! It's people like you that make this project better for everyone.

## Table of Contents
- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
- [Getting Started](#getting-started)
- [Pull Request Process](#pull-request-process)
- [Style Guidelines](#style-guidelines)
- [Commit Message Guidelines](#commit-message-guidelines)

## Code of Conduct

### Our Pledge
In the interest of fostering an open and welcoming environment, we pledge to make participation in our project a harassment-free experience for everyone.

### Our Standards
- Be respectful and inclusive
- Accept constructive criticism gracefully
- Focus on what is best for the community
- Show empathy towards other community members

## How Can I Contribute?

### Reporting Bugs
Before creating bug reports, please check existing issues to avoid duplicates. When creating a bug report, include:

- A clear and descriptive title
- Steps to reproduce the issue
- Expected behavior
- Actual behavior
- Screenshots (if applicable)
- Your environment details (OS, browser, etc.)

### Suggesting Enhancements
Enhancement suggestions are tracked as GitHub issues. When creating an enhancement suggestion, include:

- A clear and descriptive title
- Detailed description of the proposed enhancement
- Explain why this enhancement would be useful
- List any alternatives you've considered

### Pull Requests
- Fill in the pull request template
- Follow the style guidelines
- Include appropriate test cases
- Update documentation as needed
- Ensure all tests pass

## Getting Started

### Setting Up Your Development Environment

1. **Fork the repository**
   ```bash
   # Click the "Fork" button on GitHub
   ```

2. **Clone your fork**
   ```bash
   git clone https://github.com/YOUR-USERNAME/Initial-project-upload---Samriddhi-Portal.git
   cd Initial-project-upload---Samriddhi-Portal
   ```

3. **Add upstream remote**
   ```bash
   git remote add upstream https://github.com/datta007-ai/Initial-project-upload---Samriddhi-Portal.git
   ```

4. **Create a new branch**
   ```bash
   git checkout -b feature/your-feature-name
   # or
   git checkout -b fix/your-bug-fix
   ```

### Keeping Your Fork Up to Date
```bash
# Fetch upstream changes
git fetch upstream

# Checkout your main branch
git checkout main

# Merge upstream changes
git merge upstream/main

# Push to your fork
git push origin main
```

## Pull Request Process

1. **Update your branch** with the latest changes from upstream/main
   ```bash
   git fetch upstream
   git rebase upstream/main
   ```

2. **Make your changes** in your feature branch

3. **Test your changes** thoroughly

4. **Commit your changes** with a clear commit message
   ```bash
   git add .
   git commit -m "Add feature: brief description"
   ```

5. **Push to your fork**
   ```bash
   git push origin feature/your-feature-name
   ```

6. **Create a Pull Request** on GitHub
   - Go to the original repository
   - Click "New Pull Request"
   - Select your branch
   - Fill in the PR template with details about your changes
   - Link any related issues

7. **Wait for review**
   - Address any feedback from maintainers
   - Make requested changes if needed
   - Push additional commits to your branch (they'll automatically appear in the PR)

## Style Guidelines

### General Code Style
- Write clear, readable code
- Add comments for complex logic
- Keep functions small and focused
- Use meaningful variable and function names
- Follow the existing code style in the project

### Documentation
- Update README.md if you change functionality
- Add inline comments for complex code
- Document all public APIs
- Keep documentation up to date with code changes

## Commit Message Guidelines

### Format
```
type(scope): subject

body (optional)

footer (optional)
```

### Types
- **feat**: A new feature
- **fix**: A bug fix
- **docs**: Documentation only changes
- **style**: Changes that don't affect code meaning (formatting, etc.)
- **refactor**: Code change that neither fixes a bug nor adds a feature
- **test**: Adding or updating tests
- **chore**: Changes to build process or auxiliary tools

### Examples
```
feat(auth): Add user authentication system

fix(api): Resolve null pointer exception in data handler

docs(readme): Update installation instructions

test(utils): Add unit tests for helper functions
```

### Best Practices
- Use present tense ("add feature" not "added feature")
- Use imperative mood ("move cursor to..." not "moves cursor to...")
- Keep the subject line under 50 characters
- Capitalize the subject line
- Don't end the subject line with a period
- Use the body to explain what and why, not how

## Questions?

If you have questions about contributing, feel free to:
- Open an issue with the label "question"
- Reach out to the maintainers
- Check existing documentation

Thank you for contributing! 🎉
