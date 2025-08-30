# Contributing to GitHub Automation

Thank you for your interest in contributing to the GitHub Automation project! This document provides guidelines and information for contributors.

## Getting Started

### Prerequisites
- Git installed on your system
- GitHub account
- Basic knowledge of Git and GitHub workflows

### Setting up the repository
1. Fork the repository
2. Clone your fork locally:
   ```bash
   git clone https://github.com/YOUR_USERNAME/github-automation.git
   cd github-automation
   ```
3. Add the upstream remote:
   ```bash
   git remote add upstream https://github.com/indrango/github-automation.git
   ```

## Making Changes

### Creating a feature branch
1. Ensure you're on the main branch and it's up to date:
   ```bash
   git checkout main
   git pull upstream main
   ```
2. Create a new branch for your feature:
   ```bash
   git checkout -b feature/your-feature-name
   ```

### Making your changes
1. Make the necessary changes to the code
2. Test your changes thoroughly
3. Commit your changes with clear, descriptive commit messages:
   ```bash
   git add .
   git commit -m "feat: add new automation feature"
   ```

### Pushing your changes
1. Push your feature branch to your fork:
   ```bash
   git push origin feature/your-feature-name
   ```

## Creating a Pull Request

1. Go to your fork on GitHub
2. Click on "Compare & pull request" for your feature branch
3. Fill in the PR template with:
   - Clear description of changes
   - Any related issues
   - Screenshots if applicable
4. Submit the PR

## Code Style Guidelines

- Follow existing code formatting
- Write clear, readable code
- Add comments for complex logic
- Update documentation as needed

## Review Process

- All PRs require at least one review
- Address any feedback or requested changes
- Maintainers will merge approved PRs

## Questions or Need Help?

If you have questions or need help, please:
- Open an issue on GitHub
- Check existing issues and discussions
- Reach out to the maintainers

Thank you for contributing! 🚀
